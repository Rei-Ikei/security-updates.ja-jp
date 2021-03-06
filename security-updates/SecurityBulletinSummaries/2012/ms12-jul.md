---
TOCTitle: 'MS12-JUL'
Title: 2012 年 7 月のセキュリティ情報
ms:assetid: 'ms12-jul'
ms:contentKeyID: 61229699
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-jul(v=Security.10)'
--- 

2012 年 7 月のセキュリティ情報
==============================

公開日: 2012年7月11日 | 最終更新日: 2012年12月18日

**バージョン:** 5.1

[![](../../images/Dn627279.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627279.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2012 年 7 月公開のセキュリティ情報の一覧です。

2012 年 7 月のセキュリティ情報の公開により、2012 年 7 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2012 年 7 月 11 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 7 月 11 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。7 月のセキュリティ情報 Webcast に今すぐご登録ください (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

概要
----

 
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェアおよびダウンロード先」を参照してください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >セキュリティ情報タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動の必要性</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254824">MS12-043</a></td>
<td style="border:1px solid black;">XML コアサービスの脆弱性により、リモートでコードが実行される (2722479) <br />
<br />
このセキュリティ更新プログラムは一般に公開された Microsoft XML コア サービスに存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者は、該当の Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせて攻撃者の Web サイトに誘導することにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft 開発者用ツール、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377">MS12-044</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2719177) <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 2 件の Internet Explorer に存在する脆弱性を解決します。これらの脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者が現在のユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254441">MS12-045</a></td>
<td style="border:1px solid black;">Microsoft Data Access Components の脆弱性により、リモートでコードが実行される (2698365) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252510">MS12-046</a></td>
<td style="border:1px solid black;">MicrosoftVisual Basic for Applications の脆弱性により、リモートでコードが実行される (2707960) <br />
<br />
このセキュリティ更新プログラムは、Microsoft Visual Basic for Applications に存在する一般に公開された 1 件の脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じディレクトリにある正当な Microsoft Office ファイル (.docx ファイルなど) を開いた場合、リモートでコードが実行される可能性があります。また、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを完全に制御する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
マイクロソフト開発者用ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380">MS12-047</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2718523) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239507">MS12-048</a></td>
<td style="border:1px solid black;">Windows シェルの脆弱性により、リモートでコードが実行される (2691442) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された名前のファイルまたはディレクトリを開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251035">MS12-049</a></td>
<td style="border:1px solid black;">TLS の脆弱性により、情報漏えいが起こる (2655992) <br />
<br />
このセキュリティ更新プログラムは、一般に公開された 1 件の TLS の脆弱性を解決します。この脆弱性で、攻撃者が影響を受けるシステムから提供される暗号化された Web トラフィックを傍受した場合、情報漏えいが起こる可能性があります。CBC モードを使用しないすべての暗号は影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611">MS12-050</a></td>
<td style="border:1px solid black;">SharePoint の脆弱性により、特権が昇格される (2695502) <br />
<br />
このセキュリティ更新プログラムは Microsoft SharePoint および Windows SharePoint サービスに存在する 1 件の公開された脆弱性および 5 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性により、標的となる SharePoint サイトにユーザーを誘導する、特別に細工された URL をユーザーがクリックした場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255000">MS12-051</a></td>
<td style="border:1px solid black;">Microsoft Office for Mac の脆弱性により、特権が昇格される (2721015) <br />
<br />
このセキュリティ更新プログラムは、Microsoft Office for Mac に存在する一般に公開された 1 件の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるコンピューターに悪意のある実行可能ファイルを配置し、別のユーザーが後でログインして悪意のある実行可能ファイルを実行した場合、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >サービス拒否の悪用可能性の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254824">MS12-043</a></td>
<td style="border:1px solid black;">MSXML の初期化されていないメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1889">CVE-2012-1889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しています。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377">MS12-044</a></td>
<td style="border:1px solid black;">キャッシュされたオブジェクトのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1522">CVE-2012-1522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377">MS12-044</a></td>
<td style="border:1px solid black;">属性削除のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1524">CVE-2012-1524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254441">MS12-045</a></td>
<td style="border:1px solid black;">ADO キャッシュサイズ ヒープ オーバーフローの RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1891">CVE-2012-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252510">MS12-046</a></td>
<td style="border:1px solid black;">Visual Basic for Applications の安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1854">CVE-2012-1854</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しています。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380">MS12-047</a></td>
<td style="border:1px solid black;">キーボードのレイアウトの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1890">CVE-2012-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380">MS12-047</a></td>
<td style="border:1px solid black;">Win32k の誤った型処理の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1893">CVE-2012-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239507">MS12-048</a></td>
<td style="border:1px solid black;">コマンド インジェクションの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0175">CVE-2012-0175</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251035">MS12-049</a></td>
<td style="border:1px solid black;">TLS プロトコルの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1870">CVE-2012-1870</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611">MS12-050</a></td>
<td style="border:1px solid black;">HTML のサニタイズの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611">MS12-050</a></td>
<td style="border:1px solid black;">XSS scriptresx.ashx の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1859">CVE-2012-1859</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611">MS12-050</a></td>
<td style="border:1px solid black;">SharePoint スクリプトのユーザー名の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1861">CVE-2012-1861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611">MS12-050</a></td>
<td style="border:1px solid black;">SharePoint の反映したリスト パラメーターの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1863">CVE-2012-1863</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255000">MS12-051</a></td>
<td style="border:1px solid black;">Office for Mac の不適切なフォルダー アクセス許可による脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1894">CVE-2012-1894</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=496e93ac-fcce-458f-839b-25ff1ab22fde)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a4bc78fb-3927-4059-ae1c-35c369e39203)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=405ce29a-7c97-44de-aed9-4c90cbdaaf1b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8324496f-aca4-4a86-833d-c22341e71cd3)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d27bd5e9-a3a6-411e-bc50-2b03d64fb50c)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=64f8d1a4-4a9d-4ee0-8a66-d157d516afb5)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=94029b68-5b7b-4d0e-b175-cfc2b0eba91a)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=36fc4c85-fa93-4c6b-b93a-94460e9ba23b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5f268365-9c18-4fc7-b11e-b1f19c4a5a2a)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b7321c17-0e8e-4217-8da6-4c270dbfc802)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3b56ba48-b74c-4681-8e17-715dc5d45e2c)  
(KB2721693)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=465ef3d0-df59-4f73-a06d-49a81286c01f)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d53bd571-ad30-41c7-8c5f-f217097770f5)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1f058336-4a6a-47d0-ad6f-276dc381d1db)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b13e2388-01f3-46bf-97b4-612e2778477a)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2b24d755-f96f-47d6-b286-2bfd4e278dcc)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d1955b23-5931-4891-9c11-401efcb6c05c)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5f261883-daec-4af3-8bc1-46da9c164de7)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5b6d6227-8695-4ecb-86e1-bb264f954898)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a0bd0591-62f8-40d1-93fa-7f0afc4fc09c)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eab0f4c6-3f2e-435d-aef7-d9230295ab15)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=68eb373e-2c1e-40db-8ad0-0a369a96255b)  
(KB2721693)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e46047d5-9a2d-48c4-b1c8-3db884c25b5c)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=60c57c8b-6d56-42de-ab1e-e4e3258c7818)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=563399b3-cb19-40e9-ba9d-0079032c8cee)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/ja-jp/download/details.aspx?id=30233)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b6a75978-0c11-49fb-8aa7-c47efb3bf4e8)  
(KB2719177)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0c43c093-296e-4e12-b995-4f9e3f00cbe0)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3c957f8a-8f32-4a12-ade9-10a7e2984e88)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2e9a4aeb-3f34-483c-ba3a-3141164e9e8a)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/ja-jp/download/details.aspx?id=30204)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8470af29-68e2-4fd2-bc30-3c9188e65c59)  
(KB2719177)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4d9b91c9-a412-4344-b934-0d2fbd9526fd)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7300636f-aefd-46bf-a7ba-780d6f939b4f)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fe8467e2-8b37-4ec2-ba9f-324918f1f045)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c62ec513-887c-4a42-a3cc-3e92631526ed)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4009dd66-b6d0-4c14-acde-f52d75d8f9d1)  
(KB2719177)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a8ed6a19-c128-46e5-ae38-5fa9f843ba0d)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b609981c-fda8-4085-ae8d-5b760ad4e73f)  
(KB2719177)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=043464e4-9572-419b-a03a-ca11bf918052)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=00638d5e-6156-4c1b-a131-3d1fff514bdb)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=76f640b8-5aab-4880-9d74-22e2a5086342)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca890b4d-124f-4293-b8d0-69f6302b5189)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e886c5f4-7f38-4c90-905b-a682e6a8ffd0)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(緊急)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(警告)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(警告)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Server Core インストール オプション
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-044](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[MS12-045](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[MS12-047](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[MS12-048](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[MS12-049](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS12-043 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="5">
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-046](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[MS12-051](http://go.microsoft.com/fwlink/?linkid=255000)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c4c925b8-df99-4d4f-b939-878d77d64514)  
(KB2687627)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d49c4893-d867-4d16-90f5-354eb4757d90)<sup>[1]</sup>
(KB2687626)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>
(KB2596744)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>
(KB2596744)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-046](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[MS12-051](http://go.microsoft.com/fwlink/?linkid=255000)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=877700ed-3d03-4d46-a77b-5063d8f7d2e3)  
(KB2721015)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-046](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[MS12-051](http://go.microsoft.com/fwlink/?linkid=255000)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)(緊急)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)(緊急)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
(重要)  
[Microsoft InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
(重要)  
[Microsoft InfoPath 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
(重要)  
[Microsoft InfoPath 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS12-043 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS12-046 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

<sup>[1]</sup>Microsoft Office 用のこれらの更新プログラムはすべてのサポートされている Microsoft Office スイートおよびこの脆弱性の影響を受ける共有 Office コンポーネントを含むその他の Microsoft Office ソフトウェアに適用されます。これらの例としては、サポートされているバージョンの Microsoft Visio および Microsoft Project などがあります。

MS12-050 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (xlsrvwfe) (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 3 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 (coreserver) (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 3 (xlsrvwfe) (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (xlsrvwfe) (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 3 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 (coreserver) (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>
(KB2596663)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (xlsrvwfe) (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>
(KB2596942)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 (wosrv)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
(重要)  
[Microsoft SharePoint Server 2010 (coreserverloc)](http://www.microsoft.com/ja-jp/download/details.aspx?id=30302)  
(KB2553194)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
(重要)  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserverloc)](http://www.microsoft.com/ja-jp/download/details.aspx?id=30302)  
(KB2553194)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows SharePoint Services および Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7a54f510-0782-44c4-848a-8ef90d332e61)<sup>[2]</sup>
(KB2760604)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=61b9f234-3d9c-41d4-854d-30ca5e6fd2a6)  
(KB2596911)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24265175-635f-4846-afcc-f692d4710707)  
(KB2596911)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS12-043 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS12-050 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

<sup>[1]</sup> サポートされているエディションの Microsoft Office SharePoint Server 2007 の場合、お客様はこのセキュリティ情報で説明している脆弱性に対する保護を行うために、Microsoft Office SharePoint 2007 用のセキュリティ更新プログラム パッケージ (KB2596663 および KB2596942) に加え、Microsoft Windows SharePoint Services 3.0 (KB2596911) のセキュリティ更新プログラムもインストールする必要があります。

<sup>[2]</sup>この更新プログラムは、マイクロソフトダウンロードセンターからのみ入手可能です。

#### Microsoft Office Web Apps

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-050](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
</table>

<p></p>

 
MS12-050 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Expression Web
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-046](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-043](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[MS12-046](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ea7c5762-586f-4e38-ad63-43eb05e79f4d)<sup>[1]</sup>
(KB2688865)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>
(重要)
</td>
</tr>
</table>

<p></p>

 
MS12-043 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS12-046 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

<sup>[1]</sup>この更新プログラムのパッケージは、サポートされているバージョンの Microsoft Visual Basic for Applications ランタイム (Vbe6.dll) に適用され、マイクロソフト ダウンロード センターからのみご利用可能です。

<sup>[2]</sup>サポートされているバージョンの VBA SDK は、Microsoft Visual Basic for Applications SDK 6.3、Microsoft Visual Basic for Applications SDK 6.4 および Microsoft Visual Basic for Applications SDK 6.5 です。

<sup>[3]</sup>このセキュリティ情報で説明している脆弱性を解決する独立系ソフトウェア ベンダー (ISV) 向けの更新されたバージョンの Visual Basic for Applications SDK は、Summit Software Company からご利用できます。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「security\_patch」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が System Center Configuration Manager を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](http://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。System Center Configuration Manager の詳細については、[System Center Configuration Manager](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d%20-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199/ja) :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

-   MS12-043 で説明している問題についてマイクロソフトに協力してくださった [Google Security Team](http://www.google.com/)
-   MS12-043 で説明している問題を報告してくださった [Qihoo 360 Security Center](http://www.360.cn/)
-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-044 で説明している問題を報告してくださった spa-s3c.blogspot.com の Jose A. Vazquez 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-044 で説明している問題を報告してくださった Omair 氏
-   [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS12-045 で説明している問題を報告してくださった匿名のリサーチャー
-   MS12-046 で説明している問題を報告してくださった [Huawei Security Labs](http://www.huawei.com) の Bai Haowen 氏
-   MS12-047 で説明している問題を報告してくださった [Core Security Technologies](http://www.coresecurity.com/) の Nicolas Economou 氏
-   MS12-047 で説明している問題を報告してくださった [Qihoo 360 Security Center](http://www.360.cn/)
-   [Secunia Research](http://secunia.com/) と協力して、MS12-047 で説明している問題を報告してくださった Neusoft Corporation の Lufeng Li 氏
-   MS12-048 で説明している問題を報告してくださった [IBM Security Systems - Application Security](http://blog.watchfire.com/) の Adi Cohen 氏
-   MS12-050 で説明している問題を報告してくださった [IBM Security Systems - Application Security](http://blog.watchfire.com/) の Adi Cohen 氏
-   MS12-050 で説明している問題を報告してくださった [Salesforce.com の Product Security Team](https://trust.salesforce.com/) の Yang Yang 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617.aspx)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/07/11): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2012/07/12):脆弱性の深刻度が「警告」であるため、Exploitability Index (悪用可能性指標) から CVE-2012-1860 を削除しました。Exploitability Index には、セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
-   V2.0 (2012/08/22):MS12-043 について、Microsoft XML コア サービス 5.0 のダウンロード リンクを追加しました。
-   V3.0 (2012/10/10):MS12-043 について、Windows 8 および Windows Server 2012 のサポートされているエディションにインストールされた場合、Microsoft XML Core Services 4.0 を影響を受けるソフトウェアに追加しました。詳細については、MS12-043 セキュリティ情報を参照してください。
-   V4.0 (2012/11/14):MS12-046 では、KB2598361 更新プログラムが、Microsoft Office 2003 Service Pack 3 用の KB2687626 更新プログラムに置き換えられました。詳細については、セキュリティ情報 MS12-046 を参照してください。
-   V5.0 (2012/12/12):MS12-043 では、KB2687324 更新プログラムは、Microsoft Office 2003 Service Pack 3 上にインストールされる Microsoft XML コア サービス 5.0 用の KB2687627 更新プログラムに置き換えられ、KB2596679 更新プログラムは、影響を受けるすべてのエディションの Microsoft Groove 2007、Microsoft Groove Server 2007、および Microsoft Office SharePoint Server 2007 と共にインストールされる Microsoft XML コア サービス 5.0 用の KB2687497 更新プログラムに置き換えられました。詳細については、MS12-043 セキュリティ情報を参照してください。
-   V5.1 (2012/12/18):MS12-050 について、セキュリティ情報の概要ページを更新し、Microsoft Windows SharePoint Services 2.0 用の更新プログラムが利用可能となったことをお知らせしました。この更新プログラムはマイクロソフト ダウンロード センターからのみ入手可能です。

*Built at 2014-04-18T01:50:00Z-07:00*
