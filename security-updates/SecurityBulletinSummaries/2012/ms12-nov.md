---
TOCTitle: 'MS12-NOV'
Title: 2012 年 11 月のセキュリティ情報
ms:assetid: 'ms12-nov'
ms:contentKeyID: 61229703
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-nov(v=Security.10)'
--- 

2012 年 11 月のセキュリティ情報
===============================

公開日: 2012年11月14日

**バージョン:** 1.0

[![](../../images/Dn627283.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627283.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2012 年 11 月公開のセキュリティ情報の一覧です。

2012 年 11 月のセキュリティ情報の公開により、2012 年 11 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「マイクロソフト セキュリティ情報の事前通知」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2012 年 11 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 11 月 14 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。11 月のセキュリティ情報 Webcast に今すぐご登録ください (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

#### 概要

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268299">MS12-071</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2761451)  <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 3 件の Internet Explorer に存在する脆弱性を解決します。これらの脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260820">MS12-072</a></td>
<td style="border:1px solid black;">Windows シェルの脆弱性により、リモートでコードが実行される (2727528)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性により、ユーザーが Windows エクスプローラーで特別に細工されたブリーフケースを参照した場合にリモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、現在のユーザーとして任意のコードを実行する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255026">MS12-074</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、リモートでコードが実行される (2745030)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された .NET Framework に存在する 5 件の脆弱性を解決します。これらの脆弱性が攻撃者に悪用された場合、標的となるシステムのユーザーに悪意のあるプロキシ自動構成ファイルを使用させて、現在実行中のアプリケーションにコードを挿入することでコードのリモート実行が可能になります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=270856">MS12-075</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2761226)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft Windows に存在する脆弱性を解決します。最も深刻な場合、ユーザーが特別な細工がされた文書を開いた場合や、TrueType フォント ファイルが埋め込まれた悪意のある Web ページを表示した場合に、この脆弱性によりリモートでコードが実行される可能性があります。通常、ユーザーに電子メール メッセージ内のリンクをクリックさせて攻撃者の Web サイトに誘導することにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260964">MS12-076</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2720184)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft Office に存在する脆弱性を解決します。ユーザーが Microsoft Excel の影響を受けるバージョンで特別に細工されたファイルを開くと、脆弱性によってリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=258247">MS12-073</a></td>
<td style="border:1px solid black;">Microsoft インターネット インフォメーション サービス (IIS) の脆弱性により、情報漏えいが起こる (2733829)  <br />
<br />
このセキュリティ更新プログラムは Microsoft インターネット インフォメーション サービス (IIS) に存在する 1 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。攻撃者が特別に細工したコマンドを FTP サーバーに送信した場合、より深刻な脆弱性により、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">警告</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、Microsoft Exploitability Index (悪用可能性指標) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
| セキュリティ情報 ID                                       | 脆弱性のタイトル                                      | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価               | 旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価       | サービス拒否の悪用可能性の評価 | 注意事項                       |  
|-----------------------------------------------------------|-------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------|--------------------------------|  
| [MS12-071](http://go.microsoft.com/fwlink/?linkid=268299) | CFormElement における解放後使用の脆弱性               | [CVE-2012-1538](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1538) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-071](http://go.microsoft.com/fwlink/?linkid=268299) | CTreePos における解放後使用の脆弱性                   | [CVE-2012-1539](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1539) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 一時的                         | (なし)                         |  
| [MS12-071](http://go.microsoft.com/fwlink/?linkid=268299) | CTreeNode における解放後使用の脆弱性                  | [CVE-2012-4775](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4775) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-072](http://go.microsoft.com/fwlink/?linkid=260820) | Windows ブリーフケースの整数アンダーフローの脆弱性    | [CVE-2012-1527](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1527) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-072](http://go.microsoft.com/fwlink/?linkid=260820) | Windows ブリーフケースの整数オーバーフローの脆弱性    | [CVE-2012-1528](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1528) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 一時的                         | (なし)                         |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | リフレクションをバイパスする脆弱性                    | [CVE-2012-1895](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1895) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | セキュリティ情報を漏えいさせるコード アクセスの脆弱性 | [CVE-2012-1896](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1896) | 影響なし                                                                              | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 対象外                         | これは情報漏えいの脆弱性です。 |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | .NET Framework の安全でないライブラリのロードの脆弱性 | [CVE-2012-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2519) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | Web プロキシ自動発見 (WPAD) の脆弱性                  | [CVE-2012-4776](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4776) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                         |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | WPF 反映最適化の脆弱性                                | [CVE-2012-4777](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4777) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-075](http://go.microsoft.com/fwlink/?linkid=270856) | Win32k の解放後使用の脆弱性                           | [CVE-2012-2530](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2530) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                         |  
| [MS12-075](http://go.microsoft.com/fwlink/?linkid=270856) | Win32k の解放後使用の脆弱性                           | [CVE-2012-2553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2553) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                         |  
| [MS12-075](http://go.microsoft.com/fwlink/?linkid=270856) | Windows フォントの解析の脆弱性                        | [CVE-2012-2897](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2897) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | 一時的                         | (なし)                         |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Excel SerAuxErrBar のヒープ オーバーフローの脆弱性    | [CVE-2012-1885](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1885) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Excel のメモリ破損の脆弱性                            | [CVE-2012-1886](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1886) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Excel SST の解放後の無効な長さの使用の脆弱性          | [CVE-2012-1887](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1887) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Excel のスタック オーバーフローの脆弱性               | [CVE-2012-2543](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2543) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                         |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fcc633d6-fe18-4220-9b68-ff1479e4dec5)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3:](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f5472e86-2b2f-42bd-abca-6adf84973efa)  
(KB2698035)  
(Media Center Edition 2005 Service Pack 3 および Tablet PC Edition 2005 Service Pack 3 のみ)  
(重要)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31f2c645-b171-4f11-884b-f5056ef57b4f)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a736c3f0-0326-4a0a-9c12-f61bafa537bb)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=828699ac-eb88-4ff8-9110-69c206f5ef54)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0383bdea-53d1-4799-b380-14da1595882a)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=efe0de22-8ca3-474e-acda-7203bf66d0a3)  
(KB2698032)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73f5dec6-ccda-426d-8d2c-a2db3e59734a)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=615a96fe-88a5-498b-ae20-bbfc43e3b652)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dc9cd62a-c42d-4c54-bc14-7abd34aeb865)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=36962e96-0eaa-45a9-b2d6-6bec3242c73e)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e4ec19ea-06f2-4164-8e39-84f1d7a47ae7)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=205f1cf3-5431-4740-96c2-eaf019edeeeb)   
(KB2761451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c19585e3-a358-40b0-80a3-8dbb25ba8557)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c4b3fb44-338d-48be-9981-53fa2cf3094a)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1785af2-a211-467e-a696-d53840581bca)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b91091d0-176f-4ff9-98d2-74768b747c3a)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7e7b681c-c580-4671-a515-e5b469002c93)   
(KB2761451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31f5ad28-ffe9-4370-b3fc-62eb9fc0c4dd)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7a58e874-f3fc-4db8-8de0-cbfc6ebbf349)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2db93767-f364-49c6-9a03-39604173771f)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0c499445-595f-459f-86cf-b821cbb5fa65)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0161baaa-5d7b-4442-a202-41c64a73c9a8)   
(KB2761451)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=258048b5-d992-4821-8836-72262a7b5bb7)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=52f652bd-edc4-4450-91b4-f19401d2201c)   
(KB2761451)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1c067cb2-71a5-4f8d-9b11-243c9e5318ce)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fab87b20-398f-4043-9cbe-ffcae8e19ff0)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)   
(KB2761451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)   
(KB2761451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)   
(KB2761451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)   
(KB2761451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)   
(KB2761451)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)   
(KB2761451)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 8 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d7c93ade-f7e3-4b6f-b93d-894ca313282f)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b120a7a2-0eff-41d6-981e-60e5ecd55869)<sup>[2]</sup>
(KB2756872)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
[Windows 8 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24ce3f78-fb25-4f51-8bb0-8cebf19d8843)  
(KB2761226)  
(緊急)
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
対象外
</td>
<td style="border:1px solid black;">
[Windows 8 for 64-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7c4a17b7-bb7f-456c-9cb3-3a355e192734)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c7a417e6-72e5-4087-bb89-fb8e7f57894c)<sup>[2]</sup>
(KB2756872)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
[Windows 8 for 64-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=72c49d94-757c-4da4-a895-96d0830bc667)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ad6189ae-9341-409b-a53e-486fef094fd0)  
(KB2727528)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)  
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2737084)  
(重要)  
Microsoft .NET Framework 4.5<sup>[2]</sup><sup>[3]</sup>
(KB2756872)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2761226)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-071](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[MS12-072](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[MS12-074](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[MS12-075](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[MS12-073](http://go.microsoft.com/fwlink/?linkid=266541)
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
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)
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
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc) (Server Core インストール)  
(KB2761226)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)
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
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883) (Server Core インストール)  
(KB2761226)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup><sup>[2]</sup>
(KB2716513)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30) (Server Core インストール)  
(KB2761226)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30) (Server Core インストール)  
(KB2761226)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(警告)  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(緊急)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(重要)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa) (Server Core インストール)  
(KB2761226)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS12-073 に関する注意

<sup>[1]</sup>このオペレーティング システムの既定のFTP サービスではありません。

<sup>[2]</sup>この更新プログラムは、マイクロソフト ダウンロード センターからのみ入手可能です。

MS12-074 に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「.NET Framework のインストール」を参照してください。

<sup>[2]</sup> Windows 8、Windows Server 2012 およびWindows RT 上で Microsoft .NET Framework 4.5 を実行しているお客様は、この問題の影響は受けません。2012 年 10 月 11 日にリリースされた「Windows 8 Client と Windows Server 2012 の一般公開用の累積的な更新プログラム」(KB2756872) には、追加の多層防御の変更が含まれています。この更新プログラムをまだインストールされていないお客様は、多層防御策としてインストールすることを推奨します。詳細については、マイクロソフト サポート技術情報 2745030 の「関連情報」を参照してください。ダウンロード先および詳細については、サポート技術情報 2756872 を参照してください。この更新プログラムには、セキュリティ以外の内容が含まれています。

<sup>[3]</sup>Windows RT セキュリティ更新プログラムは [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) からのみの提供となります。

MS12-075 に関する注意

<sup>[1]</sup>この更新プログラムは、Windows Update を通じてのみ入手可能です。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-076](http://go.microsoft.com/fwlink/?linkid=260964)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5bb12b2b-a8e2-4324-afee-e4d26dbc658f)  
(KB2687481)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a1074d-bf4f-4b96-b394-1edc581748d0)  
(KB2597126)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5db02eae-966e-41a9-8b64-ddda5f8b2e2a)  
(KB2597126)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-076](http://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d3d801a2-d57f-4b4c-970a-c296bc716521)  
(KB2764048)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0f4e073f-4fec-440d-a9bf-1e01ee9e92ad)  
(KB2764047)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-076](http://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a0917aeb-1e94-4142-bc20-5f1998ac249c)<sup>[2]</sup>
(KB2687313)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 互換機能パック Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS12-076 に関する注意

<sup>[1]</sup>Microsoft Excel 2007について、セキュリティ更新プログラム パッケージ KB2687307 に加えて、お客様はこのセキュリティ情報で説明している脆弱性からの保護を行うために、Microsoft Office 互換機能パック (KB2687311) のセキュリティ更新プログラムもインストールする必要があります。

<sup>[2]</sup>この更新プログラムをインストールする前に、Microsoft Excel Viewer がサポートされているサービス パックのレベル (Excel Viewer 2007 Service Pack 2 または Excel Viewer 2007 Service Pack 3) に更新する必要があります。サポートされている Office ビューアーの詳細については、[サポート技術情報 979860](http://support.microsoft.com/kb/979860/ja) を参照してください。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[TechNet セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様はセーフティとセキュリティ センターを参照してください。この情報には「セキュリティ更新プログラム」リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、Microsoft Update および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索で容易に見つけられます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「更新プログラムを自動的にチェックする」を参照してください。

さらに、セキュリティ更新プログラムは、Microsoft Update カタログからダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (たとえば「MS12-001」など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、Microsoft Update Catalog FAQ (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、Microsoft Baseline Security Analyzer を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、Microsoft Windows Server Update Services (WSUS) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。System Center Configuration Manager の詳細については、System Center テクニカル リソースを参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management (英語情報) を参照してください。SMS の詳細については、Systems Management Server を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、Deploying Software Updates Using the SMS Software Distribution Feature (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199/ja):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、Microsoft Active Protections Program (MAPP) パートナーに記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、サポート技術情報 913086 を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、IT プロフェッショナル セキュリティ コミュニティにアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-071 で説明している問題を報告してくださった spa-s3c.blogspot.com の Jose A. Vazquez 氏
-   MS12-071 で説明されている問題を報告してくださった [Trend Micro](http://www.trendmicro.com/) の Cheng-da Tsai (Orange) 氏、Sung-ting Tsai 氏、および Ming-chieh Pan (Nanika) 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-072 で説明されている問題を報告してくださった Tal Zeltzer 氏
-   MS12-073 で説明されている問題を報告してくださった ProDX の Justin Royce 氏
-   MS12-074 で説明されている問題を報告してくださった Context Information Security の James Forshaw 氏
-   MS12-075 で説明している問題を報告してくださった [Google Inc](http://www.google.com) の Matthew Jurczyk 氏
-   MS12-075 で説明されている問題を報告してくださった [Documill](http://www.documill.com) の Eetu Luodemaa 氏と Joni Vähämäki 氏
-   [iDefense VCP](http://labs.idefense.com) に協力して、MS12-076 で説明されている問題を報告してくださった Sean Larsson 氏
-   [iDefense VCP](http://labs.idefense.com) に協力して、MS12-076 で説明されている問題を報告してくださった匿名のリサーチャー
-   [HP TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS12-076 で説明されている問題を報告してくださった匿名のリサーチャー

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617.aspx)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/11/14):このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
