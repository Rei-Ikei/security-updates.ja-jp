---
TOCTitle: 'MS12-MAY'
Title: 2012 年 5 月のセキュリティ情報
ms:assetid: 'ms12-may'
ms:contentKeyID: 61229702
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-may(v=Security.10)'
--- 

2012 年 5 月のセキュリティ情報
==============================

公開日: 2012年5月9日 | 最終更新日: 2012年5月24日

**バージョン:** 2.1

[](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627282.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627282.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)[](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2012 年 5 月公開のセキュリティ情報の一覧です。

2012 年 5 月のセキュリティ情報の公開により、2012 年 5 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「 [マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance) 」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2012 年 5 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 5 月 9 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。 [5 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499667) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、 [Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248419">MS12-029</a></td>
<td style="border:1px solid black;">Microsoft Word の脆弱性により、リモートでコードが実行される (2680352) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された RTF ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">Microsoft Office、Windows、.NET Framework、Silverlight 用のセキュリティ更新プログラムの組み合わせ (2681578) <br />
<br />
このセキュリティ更新プログラムは Microsoft Office、Microsoft Windows、Microsoft .NET Framework、Microsoft Silverlight に存在する 3 件の公開された脆弱性および 7 件の非公開で報告された脆弱性を解決します。最も深刻な場合、ユーザーが特別な細工がされた文書を開いた場合や、TrueType フォント ファイルが埋め込まれた悪意のある Web ページを表示した場合に、この脆弱性によりリモートでコードが実行される可能性があります。攻撃者は、悪意のある Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせて攻撃者の Web サイトに誘導することにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework、Microsoft Silverlight、<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970">MS12-035</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、リモートでコードが実行される (2693777) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された .NET Framework に存在する 2 件の脆弱性を解決します。これらの脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) を実行する Web ブラウザーを使用して、特別に細工された Web ページを表示した場合、クライアント システムで、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、 リモートでコードが実行される (2663830) <br />
<br />
このセキュリティ更新プログラムは Microsoft Office に存在する 1 件の一般に公開された脆弱性および 5 件の非公開で報告された脆弱性を解決します。これらの脆弱性で、特別に細工された Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248385">MS12-031</a></td>
<td style="border:1px solid black;">Microsoft Visio Viewer 2010 の脆弱性により、リモートでコードが実行される (2597981) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された Visio ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964">MS12-032</a></td>
<td style="border:1px solid black;">TCP/IP の脆弱性により、特権が昇格される (2688338) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性でより深刻なものが悪用された場合、攻撃者がユーザーのシステムにログオンして特別な細工が施されたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=247902">MS12-033</a></td>
<td style="border:1px solid black;">Windows Partition Manager の脆弱性により、特権が昇格される (2690533) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248419">MS12-029</a></td>
<td style="border:1px solid black;">RTF 不一致の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0183">CVE-2012-0183</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">Excel ファイル形式のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0141">CVE-2012-0141</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">OBJECTLINK レコードの Excel ファイル形式のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0142">CVE-2012-0142</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">さまざまな変更されたバイトを使用するときの Excel メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0143">CVE-2012-0143</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Microsoft Office 2003 のみが影響を受けます。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">Excel SXLI レコードのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0184">CVE-2012-0184</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">Excel MergeCells レコードのヒープ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0185">CVE-2012-0185</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499">MS12-030</a></td>
<td style="border:1px solid black;">Excel Series レコードの解析の種類の不一致の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1847">CVE-2012-1847</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248385">MS12-031</a></td>
<td style="border:1px solid black;">VSD ファイル形式のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0018">CVE-2012-0018</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは Visio Viewer 2010 および Visio Viewer 2010 Service Pack 1 (Visio Viewer の唯一サポートされているバージョンです) に影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964">MS12-032</a></td>
<td style="border:1px solid black;">Windows ファイアウォールのバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0174">CVE-2012-0174</a></td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964">MS12-032</a></td>
<td style="border:1px solid black;">TCP/IP のダブル フリーの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0179">CVE-2012-0179</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=247902">MS12-033</a></td>
<td style="border:1px solid black;">Plug and Play (PnP) Configuration Manager の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0178">CVE-2012-0178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">.NET Framework のバッファー割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0162">CVE-2012-0162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">GDI+ レコードの種類の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0165">CVE-2012-0165</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">GDI+ ヒープ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0167">CVE-2012-0167</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">Silverlight ダブルフリーの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0176">CVE-2012-0176</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">Windows およびメッセージの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0180">CVE-2012-0180</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">キーボード レイアウト ファイルの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0181">CVE-2012-0181</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038">MS12-034</a></td>
<td style="border:1px solid black;">スクロール バーの計算方法の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1848">CVE-2012-1848</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970">MS12-035</a></td>
<td style="border:1px solid black;">.NET Framework のシリアル化の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0160">CVE-2012-0160</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970">MS12-035</a></td>
<td style="border:1px solid black;">.NET Framework のシリアル化の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0161">CVE-2012-0161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
</tbody>
</table>

<p></p>

  
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
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
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
なし
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
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b2ea7a8d-a537-441c-8e80-2ba4ac37e320)  
(KB2660649)  
(Tablet PC Edition 2005 Service Pack 3 のみ)  
(重要)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9a4db1b4-15b2-4fae-83c4-a86331425c9e)  
(KB2659262)  
(重要)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8d341077-8fcd-4666-a27e-2141a04a321e)  
(KB2676562)  
(緊急)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=954e8ae9-9247-496a-bbde-76981c49e3b3)  
(KB2686509)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3:](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b0803633-7fda-4862-a908-3450180cdaaa)  
(KB2604042)  
(Media Center Edition 2005 Service Pack 3 および Tablet PC Edition 2005 Service Pack 3 のみ)  
(緊急)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6ebaccbc-512b-4f2f-bf2a-8958f012e13f)  
(KB2659262)  
(重要)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e0357165-4400-40a6-a7a4-7b762a1793ba)  
(KB2676562)  
(緊急)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f3b1568f-d7ad-4e6e-b45b-53b16b303d9d)  
(KB2686509)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
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
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
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
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bc7bfb79-8eaf-4c22-b1c9-e774c55eb06d)  
(KB2659262)  
(重要)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6287b994-041f-45b7-a230-d689bf1901a8)  
(KB2676562)  
(緊急)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=167e8c49-f9f6-488b-86ad-4056d3d20213)  
(KB2686509)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b0df42a4-7444-4da6-a9b2-35a56bdc64a4)  
(KB2604078)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bf7c9aea-dc18-499f-b456-2c29e9a74a15)  
(KB2659262)  
(重要)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f9f49cd0-24db-4438-afde-aa7113ec2035)  
(KB2676562)  
(緊急)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4614161c-ae05-43ad-8dd3-85975ec2bc4c)  
(KB2686509)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
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
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6414b607-6fb1-4527-b218-c3cb5adfd4d1)  
(KB2659262)  
(重要)  
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2563425d-4f6e-4f33-b775-a8d421b0e254)  
(KB2676562)  
(緊急)  
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=67f659ee-0d28-40f3-ae2f-f8fceeac8bff)  
(KB2686509)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
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
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e11d8738-379a-4dfe-b21c-495041d9523a)  
(KB2658846)  
(重要)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d8068e95-ac4d-45e8-84b7-b12d633c70b5)  
(KB2659262)  
(重要)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=02c857c6-5dfa-46fb-adef-35eac2bf5f41)  
(KB2660649)  
(重要)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=292d1f3b-a065-4d7d-9046-f35ab7f0591b)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1dc6e10-34eb-45ea-92b3-9983c00f6cb5)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d9d5e290-dc57-4587-b31d-706b541924ec)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=838f588b-2a0d-4dae-b54d-782e6985fd83)  
(KB2658846)  
(重要)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3bde7f59-163c-4491-abc9-a822daa8142f)  
(KB2659262)  
(重要)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9f97c5a4-62ee-4e4f-8811-a43545d76327)  
(KB2660649)  
(重要)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8f90c09c-a2cb-4adb-ace7-a8bc38d78ba6)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d65565d4-d865-438a-bfb7-d71af9dd884e)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=827b9f15-b67d-4dd4-a39b-7c148bae5041)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=360adbed-a451-44ed-8675-ca5624ef1cf3)  
(KB2658846)  
(重要)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705)  
(KB2659262)  
(重要)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=278c378b-6ee4-4f80-b9c3-ede885f4bbda)<sup>[3]</sup>
(KB2660649)  
(重要)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d5a6d617-8ef6-42fa-a325-c15fa7ece7aa)  
(KB2658846)  
(重要)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2)  
(KB2659262)  
(重要)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=98c4ac87-eec2-4e02-b0e1-00626bcb0ffd)<sup>[3]</sup>
(KB2660649)  
(重要)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(緊急)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c65df271-8b7d-46d3-81b3-87c0ad05e8d0)  
(KB2659262)  
(重要)  
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=11da5031-1733-43ea-9204-294eb483c858)  
(KB2676562)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c5f7ee25-2fc1-44c7-b3e6-e2c969ecf1bc)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c081b058-b95e-4467-a2fc-fb1a68345c8f)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7)  
(KB2658846)  
(重要)  
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a)  
(KB2659262)  
(重要)  
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e)  
(KB2660649)  
(重要)  
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7)  
(KB2658846)  
(重要)  
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a)  
(KB2659262)  
(重要)  
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e)  
(KB2660649)  
(重要)  
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9)  
(KB2658846)  
(重要)  
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18)  
(KB2659262)  
(重要)  
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b)  
(KB2660649)  
(重要)  
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9)  
(KB2658846)  
(重要)  
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18)  
(KB2659262)  
(重要)  
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b)  
(KB2660649)  
(重要)  
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93)  
(KB2658846)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e)\[4\]  
(KB2660649)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93)  
(KB2658846)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e)\[4\]  
(KB2660649)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(緊急)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc)  
(KB2658846)  
(重要)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92)  
(KB2659262)  
(重要)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293)  
(KB2676562)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc)  
(KB2658846)  
(重要)  
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92)  
(KB2659262)  
(重要)  
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293)  
(KB2676562)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-035](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[MS12-032](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[MS12-033](http://go.microsoft.com/fwlink/?linkid=247902)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705)  
(KB2659262)  
(重要)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a)  
(KB2676562)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2)  
(KB2659262)  
(重要)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0)  
(KB2676562)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356)  
(KB2690533)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(重要)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(深刻度なし<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(重要)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)  
(KB2656405)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS12-034 に関する注意******

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「.NET Framework のインストール」を参照してください。

<sup>[2]</sup> このセキュリティ情報で説明している脆弱性に対する攻撃方法は確認されていないため、このソフトウェアに対するセキュリティ更新に深刻度は適用されません。しかし多層防御策として、マイクロソフトはこれらのソフトウェアをご使用のお客様に、このセキュリティ更新プログラムの適用を推奨します。

<sup>[3]</sup>この更新プログラムは、オプションのデスクトップエクスペリエンス機能がインストールされ、有効にされている Windows Server 2008 システムにのみ適用されます。詳細については、MS12-034 の更新プログラムに関するよく寄せられる質問 (FAQ) を参照してください。

\[4\]この更新プログラムは、オプションのインクと手書きサービス機能のインク サポート コンポーネントがインストールされ、有効にされているWindows Server 2008 R2 システムにのみ適用されます。詳細については、MS12-034 の更新プログラムに関するよく寄せられる質問 (FAQ) を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS12-035 に関する注意******

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「.NET Framework のインストール」を参照してください。

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
[MS12-029](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-030](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[MS12-031](http://go.microsoft.com/fwlink/?linkid=248385)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9819899d-7f7f-4ddd-9fc8-816a57d2979e)  
(KB2598332)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0abbf09c-8828-4524-8b38-e34faefa2ae4)  
(KB2598253)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=162901b1-4c1d-476f-99e9-218780897f92)  
(KB2597086)  
(重要)
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
[Microsoft Word 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee)<sup>[1]</sup>
(KB2596917)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729)  
(KB2596672)  
(重要)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0)  
(KB2596792)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e)<sup>[1]</sup>
(KB2597161)  
(重要)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac)  
(KB2597969)  
(重要)
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
[Microsoft Word 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee)<sup>[1]</sup>
(KB2596917)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729)  
(KB2596672)  
(重要)  
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0)  
(KB2596792)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e)<sup>[1]</sup>
(KB2597161)  
(重要)  
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac)  
(KB2597969)  
(重要)
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
[Microsoft Office 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71)  
(KB2589337)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84)  
(KB2597166)  
(重要)  
[Microsoft Office 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4)  
(KB2553371)  
(重要)
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
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71)  
(KB2589337)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84)  
(KB2597166)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4)  
(KB2553371)  
(重要)
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
[Microsoft Office 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be)  
(KB2589337)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400)  
(KB2597166)  
(重要)  
[Microsoft Office 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4)  
(KB2553371)  
(重要)
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
[Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be)  
(KB2589337)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400)  
(KB2597166)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4)  
(KB2553371)  
(重要)
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
[MS12-029](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-030](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[MS12-031](http://go.microsoft.com/fwlink/?linkid=248385)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59)  
(KB2665346)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59)  
(KB2665346)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f)  
(KB2665351)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f)  
(KB2665351)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-029](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[MS12-030](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[MS12-031](http://go.microsoft.com/fwlink/?linkid=248385)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9dedfb18-a651-49f7-b1fc-78f7b6cb234a)<sup>[2]</sup>
(KB2596842)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010
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
[Microsoft Visio Viewer 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f)  
(KB2597981)  
(重要)  
[Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f)  
(KB2597981)  
(重要)  
[Microsoft Visio Viewer 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2)  
(KB2597981)  
(重要)  
[Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2)  
(KB2597981)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c)  
(KB2596880)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82)  
(KB2597162)  
(重要)
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
[Microsoft Office 互換機能パック Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c)  
(KB2596880)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 互換機能パック Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82)  
(KB2597162)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS12-029 に関する注意

<sup>[1]</sup> Microsoft Word 2007 について、セキュリティ更新プログラム パッケージ KB2596917 に加えて、お客様はこのセキュリティ情報で説明している脆弱性から保護するために、Microsoft Office 互換機能パック (KB2596880) のセキュリティ更新プログラムもインストールする必要があります。

MS12-030 に関する注意

<sup>[1]</sup>Microsoft Excel 2007 について、セキュリティ更新プログラム パッケージ KB2597161 に加えて、お客様はこのセキュリティ情報で説明している脆弱性からの保護を行うために、Microsoft Office 互換機能パック (KB2597162) のセキュリティ更新プログラムもインストールする必要があります。

<sup>[2]</sup>この更新プログラムをインストールする前に、Microsoft Excel Viewer がサポートされているサービス パックのレベル (Excel Viewer 2007 Service Pack 2 または Excel Viewer 2007 Service Pack 3) に更新する必要があります。サポートされている Office ビューアーの詳細については、サポート技術情報 979860 を参照してください。

MS12-034 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight 4
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b)  
(KB2690729)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b)  
(KB2690729)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b)  
(KB2690729)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Silverlight 5
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-034](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63)  
(KB2636927)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63)  
(KB2636927)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63)  
(KB2636927)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
MS12-034 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様はセーフティとセキュリティ センターを参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「更新プログラムを自動的にチェックする」を参照してください。

さらに、セキュリティ更新プログラムは、Microsoft Update カタログからダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、Microsoft Update Catalog FAQ (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、Microsoft Baseline Security Analyzer を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、ソフトウェアの更新管理を参照してください。Configuration Manager の詳細については、System Center Configuration Manager を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management (英語情報) を参照してください。SMS の詳細については、Systems Management Server を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、Deploying Software Updates Using the SMS Software Distribution Feature (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、サポート技術情報 913086 を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、IT プロフェッショナル セキュリティ コミュニティにアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS12-029 で説明している問題を報告してくださった匿名のリサーチャー
-   MS12-030 で説明している 2 つの問題を報告してくださった [Omair](http://krash.in/) 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-030 で説明している問題を報告してくださった Omair 氏
-   Sean Larsson and Jun Mao, working with [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-030 で説明している 2 つの問題を報告してくださった Sean Larsson 氏および Jun Mao 氏
-   [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS12-030 で説明している問題を報告してくださった匿名のリサーチャー
-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-031 で説明している問題を報告してくださった Luigi Auriemma 氏
-   MS12-032 で説明している問題を報告してくださった [INFIGO IS](http://www.infigo.hr/) の Bojan Zdrnja 氏
-   MS12-032 で説明している問題についてマイクロソフトに協力してくださった [Genesys Telecommunications](http://www.genesyslab.com/) の Anatoliy Glagolev 氏
-   [Tipping Point](http://www.tippingpoint.com/)の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して MS12-034 で説明している問題を報告してくださった Alin Rad Pop 氏
-   [Tipping Point](http://www.tippingpoint.com/)の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して MS12-034 で説明している問題を報告してくださった Vitaliy Toropov 氏
-   MS12-034 で説明している問題を報告してくださった [Omair](http://krash.in/) 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、MS12-034 で説明している問題を報告してくださった匿名のリサーチャー
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、MS12-034 で説明している問題を報告してくださった匿名のリサーチャー
-   MS12-034 で説明している問題を報告してくださった [MWR InfoSecurity](http://www.mwrinfosecurity.com/) の Alex Plaskett 氏
-   MS12-034 で説明している問題を報告してくださった [Azimuth Security](http://www.azimuthsecurity.com/) の Tarjei Mandt 氏
-   MS12-034 で説明している問題を報告してくださった [Core Security Technologies](http://www.coresecurity.com/) の Nicolas Economou 氏
-   MS12-034 で説明している問題を報告してくださった Symantec の Geoff McDonald 氏
-   MS12-034 で説明している問題を報告してくださった h4ckmp 氏
-   MS12-035 で説明している 2 つの問題を報告してくださった [Context Information Security](http://www.contextis.co.uk/) の James Forshaw 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617.aspx)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/05/09):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2012/05/11):このセキュリティ情報の概要ページを更新し、Exploitability Index の CVE-2012-1847 のタイトルを更新しました。
-   V2.0 (2012/05/15):MS12-035 では、Microsoft .NET Framework 1.1 Service Pack 1 を実行しているすべてのサポートされているシステム (Windows Server 2003 Service Pack 2 にインストールされた場合を除く) 用のセキュリティ更新プログラムの番号を KB2656353 に修正しました。セキュリティ更新プログラムのファイルに関しては、変更はありません。この更新プログラムを正常に適用されたお客様は、その他の対策を行う必要はありません。
-   V2.1 (2012/05/24):このセキュリティ情報ページを更新し、MS12-034 に関して、Windows Server 2008 および Windows Server 2008 R2 用のセキュリティ更新プログラム KB2660649 に関する補足情報を追加しました。セキュリティ更新プログラムのファイルへの変更はありません。この更新プログラムを正常に適用されたお客様は、その他の対策を行う必要はありません。

*Built at 2014-04-18T01:50:00Z-07:00*
