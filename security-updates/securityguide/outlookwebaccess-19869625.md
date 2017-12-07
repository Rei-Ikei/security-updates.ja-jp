---
TOCTitle: Outlook Web Access サーバー公開のシナリオ
Title: Outlook Web Access サーバー公開のシナリオ
ms:assetid: '0dfd23ca-1fc3-4581-9c60-6fee28e901cc'
ms:contentKeyID: 19869625
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc767971(v=TechNet.10)'
---

Outlook Web Access サーバー公開のシナリオ
=========================================

最終更新日: 2003年7月4日

**Microsoft ISA Server 2000 Feature Pack 1 バージョン 1**

##### トピック

[](#edaa)[概要](#edaa)

[](#ecaa)[シナリオのセットアップ](#ecaa)

[](#ebaa)[付録 A: デジタル証明書のインストール](#ebaa)

[](#eaaa)[付録 B: インストールガイド一覧](#eaaa)

### 概要

Microsoft Internet Security and Acceleration (ISA) Server 2000 は、サーバーを安全に公開し、外部ユーザーが内部リソースにアクセスできるようにします。Web 公開ルールまたはサーバー公開ルールを構成することにより、どのサーバーを利用できるようにするかを決定できます。

Web 公開ルールは、インターネットインフォメーションサービス (IIS) サーバーなどの Web サーバー上で HTTP コンテンツを利用できるように構成されます。サーバー公開ルールは、他のすべての種類のコンテンツを利用できるように構成されます。

Outlook Web Access サーバーが広く使用されるようになり、多くの管理者は新しい種類の公開パラダイムに直面しています。Outlook Web Access はもう 1 つの Web 公開シナリオと見ることができます。また、Outlook Web Access サーバーを他の Exchange Server と同じように公開することもできます。

このマニュアルでは、Outlook Web Access サーバーを公開する別の方法について説明します。ここでは、それらの方法を簡単に紹介し、そのシナリオを構成する手順について説明します。このマニュアルでは以下のシナリオに重点を置きます。

-   サーバー公開。このシナリオでは、Web ブラウザは ISA Server (SSL トンネリング) を通じて、OWA サーバーと直接 SSL 接続を確立します。ブラウザの互換性を最大限確保するため、OWA は暗号化された SSL トラフィックに組み込まれた IIS 基本認証を使ってユーザーを認証します。

-   
-   Web 公開。このシナリオでは、Web ブラウザは ISA Server との SSL 接続を確立します。ISA を選択すると、ISA は暗号化された SSL トラフィックに組み込まれた基本認証を使って着信要求を認証します。応答として、ISA は OWA との新しい SSL 接続を確立し、要求を転送します。OWA は、暗号化された SSL トラフィックに組み込まれた IIS 基本認証を使ってメールボックスへのアクセス要求を認証します。

-   

ブリッジ構成を使用しており、ISA Server が OWA サーバーにアクセスしているクライアントの SSL エンドポイントであるときは、OWA のウィザードを使って、ISA Server Feature Pack 1 のマニュアルの説明に従ってサーバー公開を構成します。

#### サーバー公開と Web 公開

サーバー公開ルールまたは Web 公開ルールを使用すると、Outlook Web Access サーバーを公開できます。それぞれのネットワーク要件に応じて、どの方法が適しているかを判断してください。ここでは、この判断にかかわる機能をいくつか紹介します。

サーバー公開ルールの方が構成が簡単です。また、HTTPS プロトコルとの外部通信だけを制限するように構成できます。さらに、OWA サーバーを宛先とする外部 IP トラフィックは ISA Server コンピュータで最初に審査されます。これは、TCP SYN 攻撃などの誤った形式の IP トラフィックによる攻撃など、悪意のある攻撃から ISA Server が保護してくれる、ということです。

Web 公開では多少複雑な構成処理が必要となりますが、サーバー公開で提供されるセキュリティ機能の他に、Web 公開にはさらに別の拡張機能が含まれています。

-   “URLscan” などのコンテンツフィルタによって、アプリケーション層の脆弱性のスキャンが可能になります。

-   
-   宛先セットのパスを指定することにより、Web サイト内の特定の領域への外部アクセスを制限できます。

-   
-   外部ユーザー要求を OWA サーバーに転送する前に認証できます。これにより、悪意のある、誤った形式の認証セッションから内部 Web サーバーが保護されます。

-   
-   OWA サーバー宛ての外部 IP トラフィックは、ISA Server コンピュータで厳しく審査されます。正しく構成された HTTP 要求だけが、内部 OWA Web サーバーに渡されます。

-   
-   アイコンなどのパブリック OWA リソースは ISA Server によってキャッシュされるため、パフォーマンスが向上します。

[](#mainsection)[ページのトップへ](#mainsection)

### シナリオのセットアップ

ここでは、OWA サーバー公開のための 2 つの構成方法について説明します。サーバー公開と Web 公開です。最初に、このシナリオで使用されるネットワークトポロジについて説明します。次に、両方のシナリオに共通した構成手順を紹介します。最後に、Web 公開とサーバー公開の手順を詳細に説明します。

「Lab Architecture」と「OWA サーバーの構成」の説明は、サーバー公開と Web 公開のどちらのシナリオにも関係していることに注意してください。

#### Lab Architecture

ここでは、OWA 公開のシナリオで使用されるネットワークトポロジについて説明します。

前の 2 つの公開方法のどちらを構成する場合もその手順説明を示すために、このマニュアルでは以下のネットワーク構成を利用して、現実に即した展開シナリオを示します。内部サーバーはすべて Windows 2000 Service Pack 3 (SP3) を実行しています。OWA サーバーサイトはクライアントのブラウザから、mail.fabrikam.com/exchange で参照されます。

このマニュアルではプライベート IP アドレス指定方式を使用しますが、実際のアドレス指定方式と置き換えることができます。

この手順説明は、すべてのコンポーネントが新規に、既定の設定でインストールされていることを前提としています。ISA Server SP1 と ISA Server Feature Pack 1、および Exchange/OWA は、適切なサーバーに正しくインストールされています。インストール手順の詳細については、対応する製品のマニュアルを参照するか、このマニュアルの最後にある付録を参照してください。

#### OWA サーバーの構成

プライバシーの保護とブラウザの互換性を最大限実現するため、OWA は、SSL 通信で暗号化される基本認証をサポートするように構成します。構成手順は OWA サーバーで実行します。

**OWA サーバーを構成するには**

1.  「付録 A デジタル証明書のインストール」の説明にあるデジタル証明書を準備し、インストールします。

2.  3.  以下の手順を実行して、SSL で暗号化された基本認証をサポートするように IIS を構成します。

    1.  インターネットサービスマネージャ、または \[IIS\] スナップインを含むカスタム MMC を開き、サーバーノード、\[既定の Web サイト\] ノードの順に展開し、仮想パス /Exchange を選択して、\[プロパティ\] をクリックします。

    2.  3.  \[ディレクトリセキュリティ\] タブ、\[認証コントロールの編集\] の順にクリックします。

    4.  5.  \[認証済みアクセス\] セクションの \[基本認証\] を選択し、\[編集\] をクリックして、ユーザーの認証を行うドメインを選択します。\[統合 Windows 認証\] がオンの場合は、オフにします。統合認証をオフにする操作は、Internet Explorer ブラウザで、優先認証スキーマとして基本認証が強制的に選択されるようにするために必要です。

    6.  7.  \[OK\] をクリックします。基本認証方式はセキュリティで保護されないということを示すダイアログボックスが表示されます。この認証プロトコルを SSL を使って暗号化し、\[はい\] をクリックして安全に次の作業に進めるようにします。

    8.  9.  \[OK\] をクリックします。認証設定を既定サイト内の子ノードにどのように継承するかを指定するように指示するダイアログボックスが表示される場合があります。\[すべて選択\]、\[OK\] の順にクリックします。

    10. 11. \[セキュリティで保護された通信\] セクションの \[編集\] をクリックし、\[保護されたチャネルを必要とする (SSL)\] チェックボックスをオンにして、\[OK\] を 2 回クリックします。

    12. 13. 仮想パス /public および /exchweb について手順 2.b から繰り返します。

    14. 

4.  5.  着信したクライアント要求を ISA Server に返すルーティングを行うように、OWA サーバーを構成します。

6.  

Web 公開シナリオでは、ISA Server は、外部の発信元から受け取るすべてのパケットの発信元 IP アドレスを、ISA Server コンピュータの内部インターフェイスの IP アドレスに自動的に変更します。サーバー公開では、ISA Server は元の発信元 IP アドレスを、最初に外部クライアントによって定義されたままにします。レジストリアップデートを使用すると、サーバー公開でも、ISA Server が外部の発信元から受け取るすべてのパケットの発信元 IP アドレスを、ISA Server コンピュータの内部インターフェイスの IP アドレスに自動的に変更するように設定できます。レジストリアップデートについては、[311777](http://support.microsoft.com/kb/311777) 「\[ISA\] サーバー公開時に外部クライアントのソース IP アドレスに NAT を適用する方法」 を参照してください。

サーバー公開でレジストリアップデートを使って発信元 IP アドレスを説明のように処理しないときは、ISA Server の内部 NIC アドレス (例では 10.0.0.1) の IP アドレスを反映するように、OWA コンピュータのデフォルトゲートウェイを構成する必要があります。

#### 公開方法の選択

OWA サーバーをセットアップしたら、以下のいずれかの方法で ISA Server コンピュータを構成する必要があります。

-   サーバー公開ルールを使って OWA サーバーを公開するには、「サーバー公開ルールの構成」を参照してください。

-   
-   Web 公開ルールを使って OWA サーバーを公開するには、「Web 公開ルールの構成」を参照してください。

-   

#### サーバー公開ルールの構成

プライバシーの保護とブラウザの互換性を最大限実現するため、OWA は、SSL 通信で暗号化される基本認証をサポートするように構成します。この構成手順は、ISA Server コンピュータで実行します。

**サーバー公開ルールを構成するには**

1.  \[ISA の管理\] コンソールを開き、\[サーバーとアレイ\] ノードを展開します。

2.  3.  ISA Server コンピュータノードを展開します。次に、\[公開\] ノードを展開します。

4.  5.  \[サーバー公開ルール\] ノードを右クリックし、\[新規作成\] コマンド、\[ルール\] の順にクリックします。\[新しいサーバー公開ルールウィザード\] が表示されます。

6.  7.  “OWA サーバー公開ルール” のようなわかりやすいルール名を入力し、\[次へ\] をクリックします。

8.  9.  \[内部サーバーの IP アドレス\] ボックスに OWA コンピュータに対応する IP アドレス (例では10.0.0.3) を入力し、\[ISA Server の外部 IP アドレス\] ボックスには、ISA 外部インターフェイスに対応する IP アドレス (例では 20.0.0.1) を入力して、\[次へ\] をクリックします。

10. 11. \[プロトコル設定\] ページで、ドロップダウンメニューから \[HTTPS サーバー\] を選択し、\[次へ\] をクリックします。

12. 13. \[クライアントの種類\] ページで、既定の \[すべての要求\] をそのまま受け入れ、\[次へ\] をクリックします。

14. 15. \[完了\] をクリックしてウィザードを終了します。

16. 

**展開のテスト**

外部クライアントは、完全修飾ドメイン名を ISA Server コンピュータの外部 IP アドレスに解決できれば、OWA サーバーにアクセスできます。通常これは、Web サイト名を ISA Server の外部 IP アドレスにマップするパブリック DNS サーバーに、パブリックインターネットドメイン名を登録することで実現します。ラボ環境で展開をテストする場合は、Windows インストールディレクトリの中の \\system32\\drivers\\etc\\hosts にあるクライアントの "hosts" ファイルの中で、メモ帳を使って Web サイトホスト名解決情報を指定できます。この例では、hosts ファイルには、“20.0.0.1 mail.fabrikam.com” が含まれています。

外部クライアントから OWA サイトに接続するには、Web アドレス、https://mail.fabrikam.com/exhcnage を入力します。URL で https を指定するのを忘れないでください。

#### Web 公開ルールの構成

**Web 公開ルールを構成するには**

1.  ISA Server の内部名の解決を構成します。

    **注意** コンピュータ名の解決に独自の DNS サーバーを使用する場合は、この手順をスキップしてかまいません。

    hosts ファイルは Windows インストールディレクトリの下の \\system32\\drivers\\etc\\hosts にあり、各サーバーの完全修飾ファイル名と対応 IP アドレス間のマッピングを含んでいます。この例で、クライアントに表示される OWA URL アドレスは "20.0.0.1 mail.fabrikam.com" のように指定できます。

    ISA Server コンピュータで "hosts" ファイルを編集して、以下のホスト名で正しい名前解決ができるようにします。

    -   内部 OWA ホスト名 (例では、owa.adatum.com)

    -   
    -   外部クライアントが OWA サイトにアクセスするためにブラウザに入力する URL アドレス (例では、mail.fabrikam.com)

    -   
    -   内部ドメインコントローラのホスト名 (例では、dc.adatum.com)

    -   

    内部ネットワークで名前解決が正しく行われているかどうかを確認するには、ISA Server コンピュータで ping ユーティリティを使って、すべてのコンピュータの FQDN 名を解決します。

2.  3.  \[新しい OWA の公開ウィザード\] を実行します。

    \[新しい OWA の公開ウィザード\] は、着信要求を受け入れるリスナをインストールし、OWA 固有の宛先セットを定義し、Web 公開ルールを作成します。

    1.  \[ISA の管理\] コンソールを開き、\[サーバーとアレイ\] ノードを展開します。ISA Server コンピュータノードを展開します。次に、\[公開\] ノードを展開します。\[サーバー公開ルール\] ノードを右クリックし、\[新規作成\] コマンド、\[Outlook Web Access サーバーの公開\] の順にクリックします。

    2.  3.  ルールを説明する名前 (例では “OWA Rule”) を入力し、\[次へ\] をクリックします。

    4.  5.  手順 2 で指定したように OWA サーバーの完全修飾ホスト名を入力します (例では mail.fabrikam.com)。

    6.  7.  \[ISA Server から Outlook Web Access サーバーへ SSL 接続を使う\] オプションをクリックし、\[次へ\] をクリックします。

    8.  9.  外部クライアントが OWA Web サイトへのアクセスに使用する完全修飾ホスト名を入力します。例では、owa.adayum.com です。

    10. 11. \[SSL を有効にする\] オプションをクリックし、\[選択\] ボタンをクリックします。前の手順で指定した URL にマップする証明書を選択します。\[OK\]、\[次へ\] の順にクリックします。

    12. 13. 要約を再確認し、\[完了\] をクリックします。

    14. 15. \[変更を保存して、サービスを再起動する\] を選択して、\[OK\] をクリックします。

    16. 

4.  

**既存の Web 公開ルールの修正**

OWA サーバーを公開するときは、\[新しい OWA の公開ウィザード\] を使用することを強くお勧めします。しかし、既存の Web 公開ルールを修正して OWA サーバーを公開することも可能です。

**既存の Web 公開ルールを修正するには**

既存の Web 公開ルールを修正して OWA サーバーを公開するには、以下の手順を実行します。

1.  以下の宛先を含む宛先セットを作成します。

    -   &lt;宛先&gt;/exchange\*

    -   
    -   &lt;宛先&gt;/public\*

    -   
    -   &lt;宛先&gt;/exchweb

    -   

    この場合の &lt;宛先&gt; は、ISA Server コンピュータの外部 IP アドレスに解決される完全修飾ドメイン名を表します。

2.  3.  適用可能な Web 公開ルールを修正して、宛先セットに適用します。

4.  5.  ISA によって OWA ルールと認識されるルールを、ここで紹介する VBScript を使って修正します。これは、ISA がクライアントからの SSL 要求を HTTPS ではなく HTTP としてブリッジするように構成されている場合には重要です。ISA Server は Web 公開ルールを OWA ルールとして認識すると、クライアントに返されるリンクは HTTPS リンクとして返されます。それ以外の場合、リンクは HTTP リンクとして返され、クライアントはそれらのリンクを使って接続できません。
        ```

6.  7.  ISA Server コンピュータの外部 IP アドレスで Web 要求をリッスンする、着信方向の Web 要求のリスナがインストールされていることを確認します。

8.  

#### ISA 認証スクリーニングの構成

それぞれの着信要求を OWA サーバーコンピュータに到着する前に認証するように、ISA Server を構成することが可能です。この追加機能によって、結果的にログオンセッションを不完全に終わらせる攻撃となり得る悪意のある外部認証の企みから、内部 OWA サーバーを保護することができます。ISA 認証スクリーニングでは、要求が到着したときにユーザーが証明書を提示する必要があります。要求が認証されると、ISA Server コンピュータはユーザーが提示した証明書と共に、要求を OWA サーバーコンピュータに渡します。この処理では、ユーザーが自分のパスワードを再入力する必要はありません。この新しい動作は ISA Feature Pack によって実装され、“基本委任” と呼ばれます。

**ISA 認証スクリーニングの構成**

それぞれの着信方向の Web 要求を OWA サーバーに転送する前に認証するように ISA を構成するには、以下の手順を実行します。

1.  \[サーバーとアレイ\] アイコンを展開し、ISA Server ベースのサーバーを右クリックして \[プロパティ\] をクリックします。

2.  3.  \[着信方向の Web 要求\] タブ、\[IP アドレスごとにリスナを構成する\] の順にクリックします。

4.  5.  OWA リスナを選択し、\[編集\] をクリックします。

6.  7.  認証のセクションで、\[このドメインの基本認証\] "だけ" をオンにし、\[選択\] ボタンをクリックして適切なドメイン名を選択します。注 : ISA Server コンピュータと OWA サーバーコンピュータは、同じアカウントデータベースにアクセスできる必要があります。ISA Server コンピュータと OWA サーバーコンピュータを同じドメイン内に配置することをお勧めします。\[OK\] をクリックします。

8.  9.  \[OK\] をクリックして ISA 管理コンソールに戻ります。ダイアログボックスが表示されたら、\[変更を保存して、サービスを再起動する\] を選択して \[OK\] をクリックします。

10. 11. \[公開\] ノードを展開し、\[Web 公開ルール\] ノードをクリックします。

12. 13. 画面右側のウィンドウ領域で、前の手順で定義した OWA ルール (例では "OWA Rule") をダブルクリックします。

14. 15. \[動作\] タブ、\[基本認証の資格情報の委任を許可する\] オプションの順に選択します。

16. 17. \[適用先\] タブ、\[指定されたユーザーとグループ\] の順に選択します。\[追加\] をクリックして、OWA サーバーへのアクセス許可を持つユーザー/グループを選択します。\[OK\] をクリックして、ルールのプロパティのウィンドウを閉じます。

18. 

**展開のテスト**

外部クライアントは、完全修飾ドメイン名を ISA Server コンピュータの外部 IP アドレスに解決できれば、OWA サーバーにアクセスできます。通常これは、Web サイト名を ISA Server の外部 IP アドレスにマップするパブリック DNS サーバーに、パブリックインターネットドメイン名を登録することで実現します。ラボ環境で展開をテストする場合は、Windows インストールディレクトリの \\system32\\drivers\\etc\\hosts にあるクライアントの "hosts" ファイルの中で、メモ帳を使って Web サイト名の解決情報を指定できます。この例では、hosts ファイルには、“20.0.0.1 mail.fabrikam.com” が含まれています。

外部クライアントから OWA サイトに接続するには、Web アドレス、https://mail.fabrikam.com/exchange を入力します。URL で https を指定するのを忘れないでください。

[](#mainsection)[ページのトップへ](#mainsection)

### 付録 A: デジタル証明書のインストール

セキュリティで保護された通信を有効にするために、OWA は、デジタルサーバー証明書 (SSL サーバー証明書とも呼ばれます) を使用する、クライアントブラウザとの SSL 通信をサポートします。以下のセクションでは、SSL 接続の確立に使用するデジタル証明書を準備およびインストールする手順について説明します。この手順は、サーバー公開と Web 公開 OWA の両方のシナリオで使用します。

デジタル証明書を展開するには、以下の手順を実行します。

1.  証明書の要求ファイルを生成します。この手順は \[IIS 証明書の要求ウィザード\] を使って実行します。

2.  3.  証明書の要求ファイルを認証機関に送信して、デジタル署名をしてもらい、承認を受けます。

4.  

どの認証機関を選択して連絡するかはビジネス上の判断であり、このマニュアルの説明範囲を超えています。Internet Explorer に一覧表示される民間の認証機関のいずれかに連絡することも、Windows 2000 および Windows Server 2003 に含まれる Microsoft Certificate Server を使って自分の組織内で独自の認証機関を展開することも可能です。このマニュアルでは、Microsoft Certificate Server を使用する場合について説明します。Internet Explorer を使って民間の認証機関の一覧を取得するには、以下のように操作します。ブラウザのメインメニューで \[ツール\]、\[インターネットオプション\]、\[コンテンツ\] タブ、\[発行元\]、\[信頼されたルート証明機関\] の順にクリックします。

以下の手順では、OWA サーバーの \[サーバー証明書ウィザード\] を使って、Web 公開とサーバー公開の両方のシナリオで証明書を要求し、インストールします。IIS は通常は ISA Server コンピュータにはインストールされていないため、OWA サーバーコンピュータで ISA Server コンピュータの証明書を作成し、それをエクスポートして ISA Server コンピュータにインストールします。各手順については、このマニュアルで詳細に説明します。

**注意** 証明機関から有効な証明書を受け取ったら、要求ファイルの生成に使用したコンピュータにその証明書をインストールしなければなりません。その証明書を使用して、証明書の要求に使用したコンピュータとは別のコンピュータを識別するには、証明書のデータを、証明書のホストとなるコンピュータにエクスポートしてコピーし、そこで、ローカルコンピュータの証明書ストアに格納する証明書データをインポートする必要があります。

**公開シナリオ用の証明書の手順**

デジタル証明書を取得およびインストールする手順は、サーバー公開のシナリオと Web 公開のシナリオでは異なります。しかし、IIS は通常 ISA Server コンピュータにインストールされていないため、すべての証明書要求は OWA サーバーの \[サーバー証明書ウィザード\] によって発行されます。各シナリオで必要な手順については、このトピックで簡単に説明します。各ステップの詳しい手順は、このマニュアルで後から説明します。

**サーバー公開シナリオでの証明書の取得**

サーバー公開シナリオで証明書を取得するには、以下の手順を実行します。

1.  「証明書手順」の「1. ルート証明書のサポート」に従って、OWA サーバーとすべての外部クライアントコンピュータに、信頼されたルート証明書をインストールします。

2.  3.  「証明書手順」の「2. 証明書の要求ファイルを生成する」に従って、証明書の要求ファイルを生成します。

    -   「証明書の要求ファイルを生成する」の手順 11 では証明書の共通名を指定する必要がありますが、ここで、ユーザーが Web サイトを要求するときに入力するサイトの Web アドレス (FQDN ホスト名) を入力します。例では、owa.adayum.com です。

    -   

4.  5.  「証明書手順」の「3. 証明書の要求ファイルを処理する」に従って、証明書の要求ファイルを処理します。

6.  7.  「証明書手順」の「4. 証明書をインストールする」に従って、証明書をインストールします。

8.  

**Web 公開シナリオでの証明書の取得**

Web 公開シナリオで証明書を取得するには、以下の手順を実行します。

1.  「証明書手順」の「1. ルート証明書のサポート」に従って、ISA Server、OWA サーバーコンピュータおよびすべてのクライアントコンピュータに、信頼されたルート証明書をインストールします。

2.  3.  「証明書手順」の「2. 証明書の要求ファイルを生成する」に従って、ISA Server コンピュータの証明書の要求を生成します。

    -   「証明書の要求ファイルを生成する」の手順 11 では証明書の共通名を指定する必要がありますが、ここで、外部クライアントが OWA サイトにアクセスするときに Web ブラウザに入力する

        URL の完全修飾ホスト名を入力します。例では、owa.adayum.com です。

    -   

4.  5.  「証明書手順」の「3. 証明書の要求ファイルを処理する」に従って、証明書の要求ファイルを処理します。

6.  7.  「証明書手順」の「4. 証明書をインストールする」に従って、証明書をインストールします。証明書のインストールが完了するまでは、他の手順を実行しないでください。

8.  9.  「証明書手順」の「5. 証明書を OWA から ISA にエクスポートする」に従って、証明書をファイルにエクスポートし、ISA Server コンピュータにコピーします。

10. 11. 「証明書手順」の「6. ISA Server に証明書をインストールする」に従って、証明書を ISA Server コンピュータにインストールします。

12. 13. 「証明書手順」の「7. OWA サーバーコンピュータから証明書を削除する」に従って、証明書を OWA サーバーコンピュータから削除します。

14. 15. 「証明書手順」の「2. 証明書の要求ファイルを生成する」に従って、OWA サーバーコンピュータの証明書の要求ファイルを生成します。

    -   「証明書の要求ファイルを生成する」の手順 11 では証明書の共通名を指定する必要がありますが、ここで、OWA サーバーの完全修飾ホスト名を入力します。

        例では、owa.adayum.com です。

    -   

16. 17. 「証明書手順」の「3. 証明書の要求ファイルを処理する」に従って、証明書の要求ファイルを処理します。

18. 19. 「証明書手順」の「4. 証明書をインストールする」に従って、証明書をインストールします。

20. 

#### 1. ルート証明書のサポート

クライアントとサーバー間に SSL 接続を確立するには、サーバー証明書を検証するルート CA 証明書をインストールする必要があります。一般に、コンピュータの CA のデータベースに含まれる民間の CA から発行された証明書を使用する場合、ルート証明書は既にインストールされているため、この手順を実行する必要はありません。インストールされたルート証明書の一覧を表示するには、Internet Explorer のメニューで \[ツール\]、\[インターネットオプション\] の順に選択します。\[コンテンツ\] タブを選択し、\[証明書\] をクリックし、\[信頼されたルート証明機関\] タブを選択します。その組織で、証明書を発行する CA として Microsoft Certificate Server をインストールするときは、ルート証明書のインストールを実行する必要があります。

ルート証明書は、SSL を使用するサーバーにアクセスするすべてのクライアントにインストールしなければなりません。たとえば、サーバー証明書 1 が ISA Server コンピュータにインストールされ、サーバー証明書 2 が、ISA Server コンピュータの背後にある内部 Web サーバーコンピュータにインストールされているシナリオでは、以下のルート証明書のインストールが必要です。

-   外部クライアントは、ISA Server コンピュータのクライアントであるため、サーバー証明書 1 を検証するルート証明書を必要とします。

-   
-   ISA Server コンピュータは Web サーバーコンピュータのクライアントであるため、サーバー証明書 2 を検証するルート証明書を必要とします。

-   

一般に、ISA Server コンピュータおよびサーバー公開シナリオで公開されたサーバーにインストールされる証明書には、民間の認証機関から発行されたものを使用し、接続を確立しよ

うとするクライアントによって簡単に信頼されるようにすることをお勧めします。しかし、Web 公開シナリオでは、Web サーバー上の証明書は内部の Microsoft Certificate Server が発行できます。ISA Server コンピュータが内部 Web サーバーとの SSL 接続を確立しようとするとき、この証明書はこのサーバーから信頼されるだけで十分だからです。

**注意** Microsoft Certificate Server の詳細については、『Creating Certificate Hierarchies with MS Certificate Server Version 1.0 (英語情報)』 (http://go.microsoft.com/fwlink/?linkid=12107) を参照してください。

**Microsoft Certificate Server ルート証明書を取得するには**

**注意** 以下の手順では、Certificate Server と直接に接続されておらず、すべての情報交換はフロッピーディスクを使って行われることが前提となっています。

1.  Microsoft Certificate Server コンピュータで Internet Explorer を開き、\[アドレス\] ボックスに「http://localhost/certsrv」と入力します。

2.  3.  \[CA 証明書または証明書失効リストの取得\] を選択し、\[次へ\] をクリックします。

4.  5.  \[CA 証明書のパスのインストール\] リンクをクリックし、ファイルをフロッピーディスクに保存します。

6.  

**Microsoft Certificate Server ルート証明書をインストールするには**

1.  フロッピーディスクから目的のコンピュータにルート証明書をコピーします。

    サーバー公開の場合は、外部クライアントコンピュータと OWA サーバーが該当します。Web 公開では、外部クライアントコンピュータ、OWA サーバーコンピュータおよび ISA Server コンピュータが該当します。

2.  3.  それぞれのコンピュータで \[MMC の証明書\] スナップインを開きます。\[スタート\] ボタン、\[ファイル名を指定して実行\] の順にクリックし、「MMC」と入力します。

4.  5.  \[コンソール\]、\[スナップインの追加と削除\]、\[追加\] ボタンの順にクリックします。

6.  7.  \[証明書\] を選択し、\[追加\] をクリックして、\[コンピュータアカウント\] を選択し、\[次へ\] をクリックします。

8.  9.  \[ローカルコンピュータ\] を選択し、\[完了\]、\[閉じる\]、\[OK\] の順にクリックします。

10. 11. \[信頼されたルート証明機関\] フォルダをクリックします。

12. 13. \[すべてのタスク\] を右クリックし、\[インポート\] をクリックします。

14. 15. \[証明書のインポートウィザード\] で \[次へ\] をクリックします。

16. 17. ルート証明書ファイルが一覧に表示されていることを確認し、それを選択します。\[次へ\] をクリックします。

18. 19. \[次へ\] をクリックします。

20. 21. \[完了\] をクリックします。

22. 23. \[信頼されたルート証明機関\] に、ルート証明書が表示されていることを確認します。

24. 

#### 2. 証明書の要求ファイルを生成する

外部ユーザーに公開された OWA Web サイト FQDN アドレス (mail.fabrikam.com など) を検証するサーバー証明書を取得する必要があります。この操作は、要求ファイルを作成して行います。

**注意** 証明書要求は、英数字以外の文字が含まれている場合には失敗します。

以下の手順の要求ファイルの作成を開始してから、証明書のインストールを完了するまでは、以下のどの動作も実行しないでください。

-   コンピュータ名または Web サイトへのバインドを変更すること。

-   
-   Service Pack またはセキュリティ修正プログラムを適用すること。

-   
-   暗号化レベルを変更すること、つまり、High Encryption Pack を適用すること。

-   
-   保留中の証明書要求を削除すること。

-   
-   Web サイトのセキュリティで保護された通信のいずれかを変更すること。

-   

**証明書の要求ファイルを生成するには**

証明機関 (CA) に送信して処理する新しい証明書の要求を生成するには、以下の手順を実行します。

1.  インターネットサービスマネージャまたは \[IIS\] スナップインを含むカスタム MMC を開きます。

2.  3.  既定の Web サイトを選択します。\[プロパティ\] を右クリックして選択します。

4.  5.  \[ディレクトリセキュリティ\] タブをクリックします。

6.  7.  \[セキュリティで保護された通信\] セクションで、\[サーバー証明書\] をクリックします。これによって、新しい \[Web サイト証明ウィザード\] が開始します。

8.  9.  \[次へ\] をクリックします。

10. 11. \[証明書の新規作成\] オプションを選択し、\[次へ\] をクリックします。次の画面が表示されるまでに多少時間がかかる場合があります。

12. 13. \[証明書の要求を作成して後で送信する\] オプションを選択し、\[次へ\] をクリックします。

    **注意** \[オンライン証明機関に直ちに証明書の要求を送信する\] オプションは、IIS がエンタープライズ CA にアクセスできない限り、選択できません。エンタープライズにアクセスするには、Active Directory を含む Windows 2000 に、Certificate Server 2.0 がインストールされていることが必要です。

14. 15. サイトのわかりやすい名前、たとえば、MMC 内のサイトのわかりやすい名前や Web サイトの所有者の名前などを任意で選択します。

16. 17. 使用するキーのビット長と、SGC 証明書を使用するかどうかを選択し、\[次へ\] をクリックします。

    **注意** ビット長と SGC の詳細については、アドレス http://&lt;サーバー名&gt;/iishelp/iis/htm/core/iistesc.htm のサーバー上にある IIS のヘルプを参照してください。

    この URL を正しく入力するには、&lt;サーバー名&gt; を自分の IIS サーバーの名前に置き換える必要があるので注意してください。

18. 19. 自分の組織 (O) と組織単位 (OU) を入力します。たとえば、会社名が Fabrikam で、販売 (Sales) 部門の Web サーバーをセットアップする場合、\[組織\] に「Fabrikam」と入力し、\[組織単位 (OU)\] に「Sales」と入力します。完了したら、\[次へ\] をクリックします。

20. 21. サイトの共通名 (CN) を入力します。これは、認証する Web アドレスと一致していなければなりません。サーバー公開の場合、これはユーザーが Web サイトを要求するときに入力する名前です。Web 公開では、この名前に、OWA サーバーまたは OWA コンピュータの FQDN が含まれる場合もあります。完了したら、\[次へ\] をクリックします。

22. 23. 自分の国/地域、市区町村および都道府県を入力します。都道府県名または市区町村名は決して省略しないでください。完了したら、\[次へ\] をクリックします。

24. 25. これから作成しようとしている証明書の要求ファイルの名前を選択します。このファイルには、ここで作成したすべての情報と共に、サイトの公開キーが含まれます。必要ならファイル名を参照できます。ここまでの手順が完了すると、1 つの .txt ファイルが作成されます。このファイルの既定の名前は Certreq.txt です。この手順が完了したら、\[完了\] ボタンをクリックします。

26. 27. この時点で、入力したすべての情報が含まれた要約の画面が表示されます。この情報がすべて正しいことを確認し、\[完了\] をクリックします。

28. 

これで証明書の要求ファイルの作成が完了しました。

#### 3. 証明書の要求ファイルを処理する

証明書をインターネットで使用するには、要求ファイルを証明機関 (オンライン機関) に送信します。そこで証明書の応答ファイルが生成されます。このファイルには公開キーが含まれ、民間の証明機関によってデジタル署名されます。

Web 公開シナリオで内部の Outlook Web Access コンピュータに証明書を配置するなど内部での使用を目的とした場合、Microsoft Certificate Server を使って自分自身のプライベート証明機関をインストールすることができます。

**Microsoft Certificate Server を使用して証明書の要求を処理するには**

**注意** 以下の手順では、Certificate Server と直接に接続されておらず、すべての情報交換はフロッピーディスクを使って行われることが前提となっています。

1.  証明書の要求ファイルをフロッピーディスクにコピーし、そのディスクを Certificate Server に挿入し、既知の場所にそのファイルをコピーします。

2.  3.  Microsoft Certificate Server コンピュータで Internet Explorer を開き、「http://localhost/certsrv」と入力します。

4.  5.  \[証明書の要求\]、\[次へ\] の順にクリックします。

6.  7.  \[要求の詳細設定\]、\[次へ\] の順にクリックします。

8.  9.  第 2 のオプション、\[Base 64 エンコード PKCS \#10 ファイルを使用して証明書の要求を送信するか、または Base 64 エンコード PKCS \#7 ファイルを使用して更新の要求を送信します\] を選択し、\[次へ\] をクリックします。

10. 11. 証明書テンプレートの見出しの下の \[Web サーバー\] を選択します。

12. 13. メモ帳を使って、証明書の要求ファイルを開き、Ctrl + A キーと Ctrl + C キーを押して、ファイルの内容をすべてクリップボードにコピーします。

14. 15. ファイルの内容をブラウザページの \[保存された要求\] 編集ボックスに貼り付け、\[送信\] をクリックします。

16. 17. \[証明書のダウンロード\] リンクをクリックして、応答ファイルをフロッピーディスクに保存します。

18. 19. フロッピーディスクを Outlook Web Access コンピュータに挿入し、応答ファイルを既知の場所にコピーします。

20. 

#### 4. 証明書をインストールする

証明機関から応答ファイルを受け取ったら、そのファイルを OWA サーバーにインストールする必要があります。ISA Server コンピュータにエクスポートする証明書は、証明書を要求した OWA サーバーに最初にインストールしなければなりません。

**応答ファイルをインストールするには**

1.  インターネットサービスマネージャを開きます。

2.  3.  \[インターネットインフォメーションサービス\] を展開します。保留中の証明書の要求がある \[既定の Web サイト\] を選択します。

4.  5.  \[既定の Web サイト\] を右クリックし、\[プロパティ\] をクリックします。

6.  7.  \[ディレクトリセキュリティ\] タブをクリックします。

8.  9.  \[セキュリティで保護された通信\] セクションで、\[サーバー証明書\] をクリックします。

10. 11. \[Web サイト証明ウィザード\] で、\[次へ\] をクリックします。

12. 13. \[保留中の要求を処理し、証明書をインストールする\] を選択します。\[次へ\] をクリックします。

14. 15. 証明書の応答ファイルの場所を入力するか、そのファイルを参照して、\[次へ\] をクリックします。

16. 17. 要約の画面を読んで、処理している証明書が正しいことを確認し、\[次へ\] をクリックします。

18. 19. 確認画面が表示されます。この情報を読んだら、\[次へ\] をクリックします。

20. 21. メッセージボックスの警告の \[はい\]、\[完了\] の順にクリックします。

22. 

#### 5. 証明書を OWA から ISA にエクスポートする

以下の手順に従って、証明書を OWA サーバーコンピュータから ISA Server コンピュータにエクスポートします。

1.  \[スタート\] ボタン、\[ファイル名を指定して実行\] の順にクリックします。\[開く\] ボックスに「MMC」と入力し、\[OK\] をクリックします。

2.  3.  \[コンソール\]、\[スナップインの追加と削除\] の順にクリックします。\[追加\] ボタンをクリックします。

4.  5.  \[証明書\] を選択し、\[追加\] をクリックして、\[コンピュータアカウント\] を選択し、\[次へ\] をクリックします。

6.  7.  \[ローカルコンピュータ\] を選択し、\[完了\]、\[閉じる\]、\[OK\] の順にクリックします。

8.  9.  \[個人\] フォルダを展開し、\[証明書\] を展開します。Web サイトの名前が記入された証明書が、右側のウィンドウ領域の \[発行先\] 列に表示されます。

10. 11. 証明書を右クリックし、\[すべてのタスク\]、\[エクスポート\] の順にクリックします。

12. 13. \[エクスポート\] ウィンドウで \[次へ\] をクリックします。

14. 15. \[はい、秘密キーをエクスポートします\]、\[次へ\] の順にクリックします。

    **注意** \[秘密キーのエクスポート\] ウィンドウに \[はい\] をクリックするオプションが表示されない場合は、秘密キーが既に別のコンピュータにエクスポートされているか、秘密キーがこのコンピュータに初めから存在していません。この証明書は ISA Server で使用できません。ISA Server 用にこのサイトの新しい証明書を要求する必要があります。

16. 17. \[Personal Information Exchange\] を選択します。3 つすべてのチェックボックスで既定の設定をそのまま受け入れます。

18. 19. エクスポートファイルを保護するパスワードを割り当て、そのパスワードを確認します。

20. 21. ファイル名と場所を割り当てます。

22. 23. \[完了\] をクリックします。必ず作成したファイルを保護してください。このファイルがないと SSL プロトコルを使用できません。

24. 25. 作成したファイルを ISA Server コンピュータにコピーします。

26. 

#### 6. ISA Server に証明書をインストールする

ISA Server コンピュータに証明書をインストールするには、以下の手順を実行します。

1.  \[スタート\] ボタン、\[ファイル名を指定して実行\] の順にクリックします。\[開く\] ボックスに「MMC」と入力し、\[OK\] をクリックします。

2.  3.  \[コンソール\]、\[スナップインの追加と削除\] の順にクリックします。\[追加\] ボタンをクリックします。

4.  5.  \[証明書\] を選択し、\[追加\] をクリックして、\[コンピュータアカウント\] を選択し、\[次へ\] をクリックします。

6.  7.  \[ローカルコンピュータ\] を選択し、\[完了\]、\[閉じる\]、\[OK\] の順にクリックします。

8.  9.  \[個人\] フォルダをクリックします。

10. 11. \[すべてのタスク\] を右クリックし、\[インポート\] をクリックします。

12. 13. \[証明書のインポートウィザード\] で \[次へ\] をクリックします。

14. 15. ファイルが一覧に表示されていることを確認し、\[次へ\] をクリックします。

16. 17. このファイルのパスワードを入力します。

18. 19. \[エクスポート可能なキーとしてマークする\] チェックボックスをクリックしてオンにします。

20. 21. \[次へ\] をクリックします。

22. 23. \[完了\] をクリックします。

24. 25. \[個人\] フォルダの下に \[証明書\] というサブフォルダが表示されたら、\[証明書\] フォルダをクリックして、証明書に OWA Web サイトのアドレス (例では mail.fabrikam.com) の名前が表示されていることを確認します。

26. 

#### 7. OWA サーバーコンピュータから証明書を削除する

OWA サーバーコンピュータから証明書を削除するには、以下の手順を実行します。

1.  OWA サーバーコンピュータで、インターネットサービスマネージャを開きます。

2.  3.  サーバーノードを展開し、\[既定の Web サイト\] ノードを選択します。\[プロパティ\] をクリックします。

4.  5.  \[ディレクトリセキュリティ\] タブをクリックします。\[セキュリティで保護された通信\] セクションで、\[サーバー証明書\] をクリックします。これによって、新しい \[Web サイト証明ウィザード\] が開始します。

6.  7.  \[次へ\] をクリックします。

8.  9.  \[現在の証明書を削除する\] を選択し、\[次へ\] をクリックします。

10. 11. \[次へ\]、\[完了\] の順にクリックします。

12. 13. インターネットサービスマネージャを閉じます。

[](#mainsection)[ページのトップへ](#mainsection)

### 付録 B: インストールガイド一覧

-   [インストールと導入ガイド](http://technet.microsoft.com/ja-jp/cc750607.aspx)

-   
-   [313139](http://support.microsoft.com/kb/313139) 最新の Internet Security and Acceleration Server 2000 Service Pack の入手方法

-   
-   [262068](http://support.microsoft.com/kb/262068) \[XADM\] Exchange 2000 のセット アップ方法

-   
-   Outlook Web Access Setup and Deployment (英語)

-   

例として示した企業、組織、製品、ドメイン名、電子メールアドレス、ロゴ、人、場所およびイベントはすべて架空の存在です。実在の企業、組織、製品、ドメイン名、電子メールアドレス、ロゴ、人、場所、またはイベントとの関連性を意図したり、暗示することはありません。

[](#mainsection)[ページのトップへ](#mainsection)