---
TOCTitle: ISA Server での Web 公開に関するトラブル シューティング
Title: ISA Server での Web 公開に関するトラブル シューティング
ms:assetid: 'e43e2222-e4fb-4e37-a5b9-61a983d28674'
ms:contentKeyID: 19869587
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc751292(v=TechNet.10)'
---

ISA Server での Web 公開に関するトラブル シューティング
=======================================================

最終更新日: 2003年7月7日

**Microsoft ISA Server 2000 Feature Pack 1 バージョン 1**

以下は、ISA Server での Web 公開に関する一般的な問題です。該当する問題に基づいて構成を修正した後、Web 公開をテストして、問題が解決されたかどうかを確認してください。

##### トピック

[](#eeaa)[問題の一般的な発生原因を調べる](#eeaa)

[](#edaa)[Web リスナに関する問題](#edaa)

[](#ecaa)[ISA Server の Web 公開に関する問題](#ecaa)
[](#ebaa)[IIS に関する問題](#ebaa)

[](#eaaa)[SSL 証明書に関する問題](#eaaa)

### 問題の一般的な発生原因を調べる

以下の事項を確認してください。

1.  **Web サイトに直接アクセスできますか。**ISA Server コンピュータを経由せずに、Web サイトにアクセスできるかどうかを確認します。アクセスできない場合、問題は ISA Server コンピュータではなく、Web サーバーと IIS に関連しています。

    これをテストする最も簡単な方法は、ISA Server コンピュータで Internet Explorer (IE) を開き、\[ツール\] メニューの \[インターネットオプション\] をクリックします。\[接続\] タブで、\[LAN の設定\] をクリックし、\[プロキシサーバーを使用する\] オプションが選択されていないことを確認します。次に、ISA Server コンピュータの IE から Web サイトにアクセスします。

2.  3.  **インターネット上での Web サイト名が、ISA Server コンピュータの外部ネットワークアダプタの IP アドレスに解決されますか。**そうでない場合は、DNS の問題です。DNS サーバーの管理者に連絡し、Web サイト名が ISA の外部ネットワークアダプタに解決されるようにインターネット DNS を設定してください。インターネットサービスプロバイダが DNS ゾーンをホストしている場合は、連絡してこの問題を解決してもらう必要があります。テストには nslookup ユーティリティを使用し、サイト名がどのように解決されるかを調べます。nslookup の詳細については、MSDN または Windows のヘルプを参照してください。

4.  5.  **Web サイトに接続したとき、エラー 403 ページが表示されますか。**これは、ISA Server コンピュータの外部 IP への接続に成功していることを示します。したがって、ISA Server の Web 公開または IIS に問題があります。

6.  7.  **Web サイトに接続したとき、"サーバーへの接続に失敗しました" というメッセージが表示されますか。**いずれかの ISA Server Web リスナに問題があると思われます。

8.  9.  **Web サイトに接続したとき、500 内部サーバーエラーページが表示されますか。**Web サーバー上の SSL 証明書に問題がある可能性があります。

10. 

[](#mainsection)[ページのトップへ](#mainsection)

### Web リスナに関する問題

以下の事項を確認してください。

1.  **ISA Server コンピュータ上で w3svc サービスが実行されていませんか。**これは、Web サーバーを公開するために IIS が使用するサービスです。ポート 80 で競合が発生するので、このサービスを ISA Server コンピュータ上で実行しないでください。ISA Server コンピュータ上に配置された

    Web サイトを公開する場合は、ポート 80 以外のポートでリッスンするように ISA Server を構成する必要があります。詳細については、「ISA サーバー上の Web サーバーの公開」を参照してください。

2.  3.  **ISA Server で着信方向の Web トラフィックが許可されていますか。**確認には、netstat ユーティリティを使用して、外部ネットワークアダプタがポート 80 でリッスンしているかどうかを調べます。

    netstat を使用するには、ISA Server コンピュータのコマンドプロンプトに「netstat -an」と入力します。Web リスナが正しく構成されている場合は、次のように出力されます。
        ```

    この netstat 出力の 192.168.0.1:80 は、ISA Server コンピュータの外部 IP アドレスがポート 80 でリッスンしていることを示しています。使用している ISA Server コンピュータの外部 IP アドレスがポート 80 でリッスンしていることを確認してください。ISA Server コンピュータ上の Web サイトを公開する場合は、netstat 出力で表示される、ポート 80 以外のポートでリッスンするように ISA Server を構成する必要があります。

    これ以外の場合は、Web リスナが正しく構成されていません。Web リスナの構成方法については、シナリオドキュメントの Web リスナに関する手順を参照してください。

4.  

[](#mainsection)[ページのトップへ](#mainsection)

### ISA Server の Web 公開に関する問題

以下の事項を確認してください。

1.  インターネット上での Web サイト名が、ISA Server コンピュータの外部ネットワークアダプタの IP アドレスに解決されますか。DNS サーバーの管理者に連絡し、Web サイト名が ISA Server の外部ネットワークアダプタに解決されるようにインターネット DNS を設定してください。

2.  3.  Web 公開ルールで使用されている宛先セットの値は、ユーザーがブラウザに入力する値と同じですか。www.adatum.com など、外部ユーザーが Web サイトへアクセスするときに指定するパブリック名と同じになるように、宛先セットを設定してください。Web サーバーの完全修飾ドメイン名でなければなりません。

4.  5.  Web 公開ルールの \[動作\] タブで、内部サーバーが IP アドレスまたは完全修飾ドメイン名 (FQDN) によって指定されていますか。IP アドレスまたは FQDN ベースの名前のみを使用してください。この名前は Web サイトの内部名です。宛先セットとは関係ありません。

6.  7.  宛先セット名が、ホストしている Web サーバーの FQDN と同じになっていませんか。この場合、ISA Server は、Web サーバーではなく、ISA Server 自体の外部ネットワークアダプタに要求を送信してしまいます。これを回避するには、Web 公開ルールの \[動作\] タブで、FQDN ではなく内部 Web サイトの IP アドレスを使用します。

8.  9.  SSL ブリッジの設定は Web 公開のセットアップにしていますか。実際の設定と、シナリオドキュメントで説明されている設定を比較してください。

10. 11. Web 公開宛先セットに対する要求またはすべての宛先セットに対する要求を、上流サーバーへリダイレクトするルーティングルールがありますか。その場合は、Web 公開宛先セット用の新しいルーティングルールを作成し、\[動作\] オプションの \[指定された宛先から直接要求を取得する\] を選択します。ルーティングルールは順番に処理されるので、上流サーバーへリダイレクトするルールよりこの新しいルールを優先させる必要があります。

12. 13. ISA Server コンピュータと Web サーバーの両方で認証を要求していませんか。ISA Server コンピュータでのみ認証を行ってください。

14. 15. ISA Server を経由せずに外部クライアントへ Web 応答を返せるようになっていませんか。Web サーバーは、他のルートを経由してではなく、ISA Server を経由してのみ応答を返せるようになっていなければなりません。応答は、ISA Server 経由でないと、要求を発行したクライアントが応答元を確認できず、受け入れられません。応答が ISA Server を経由するかどうかをテストするには、Web サーバーで、任意の外部 Web サイト名を使ってtracertコマンドラインユーティリティを実行し、ISA Server がホップの 1 つとして表示されることを確認します。コマンドプロンプトで、「tracert &lt;サイト名&gt;」 (たとえば、「tracert www.adatum.com」) と入力します。

16. 

[](#mainsection)[ページのトップへ](#mainsection)

### IIS に関する問題

以下の事項を確認してください。

1.  **IIS がホストヘッダーを使用するように構成されていますか。**これは、新しい IIS Web サイトを作成するときに構成する設定です。IIS の既定ではホストヘッダーが使用されず、ISA Server による Web 公開に適しています。特定のホストヘッダーを使用するように IIS を構成している場合は、次のいずれかの操作を行ってください。

    -   特定のホストヘッダーを使用しないように IIS を変更します。

    -   
    -   IIS で必要とされるホストヘッダーを、ISA Server で使用するホストヘッダーに変更します。

    -   
    -   Web 公開シナリオのドキュメントで説明しているように、Web 公開ルールオプション \[公開サーバーに送信されたオリジナルのホストヘッダーを、上で指定したサーバーに送信する\] を選択します。

    -   

2.  

ホストヘッダー要件の変更については、IIS のマニュアルを参照してください。

IIS の一般的なトラブル シューティングに関する情報については、Windows 2000 ヘルプを参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

### SSL 証明書に関する問題

以下の事項を確認してください。

1.  内部 Web サーバーで証明書の有効性に関する問題が発生していませんか。

    -   内部 Web サーバー上の証明書が要求日に有効でない。

    -   
    -   内部 Web サーバーの証明機関が信頼されていない。

    -   
    -   Web 公開ルールの \[動作\] タブで指定されているサーバー名または IP アドレスが証明書の名前と一致していない。

    -   

    最初の 2 つの問題は証明書の有効性に関連しており、解決するには、証明書が最新のものであること、および信頼された証明機関から発行されたものであることを確認します。3 番目の問題は、次のいずれかの方法で解決できます。

    -   サーバー上の名前と一致する新しい証明書を取得します。

    -   
    -   Web 公開ルールの \[動作\] タブで、証明書の名前に合わせてサーバー名を変更し、その名前が内部 Web サーバーにマップされるようにローカル DNS サーバーを構成します。

    -   
    -   Web 公開ルールの \[動作\] タブで、証明書の名前に合わせてサーバー名を変更します。ISA Server コンピュータの WINNT\\system32\\drivers\\etc\\hosts ファイルで、証明書および \[動作\] タブの名前と内部 Web サーバーの IP アドレスのマッピングを追加します。

    -   

2.  

例として示した企業、組織、製品、ドメイン名、電子メールアドレス、ロゴ、人、場所およびイベントはすべて架空の存在です。実在の企業、組織、製品、ドメイン名、電子メールアドレス、ロゴ、人、場所、またはイベントとの関連性を意図したり、暗示することはありません。

[](#mainsection)[ページのトップへ](#mainsection)