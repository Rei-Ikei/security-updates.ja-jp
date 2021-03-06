---
TOCTitle: 'MS14-MAY'
Title: 2014 年 5 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-may'
ms:contentKeyID: 62246604
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-may(v=Security.10)'
---

2014 年 5 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2014 年 5 月 2 日 | 最終更新日:2014 年 5 月 14 日

**バージョン:** 2.0

このセキュリティ情報の概要は 2014 年 5 月公開のセキュリティ情報の一覧です。

2014 年 5 月のセキュリティ情報の公開により、2014 年 5 月 9 日に公開した事前通知を、このセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2014 年 5 月 14 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[5 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572979&culture=en-us) (英語)。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>  <table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=397669"><strong>MS14-021</strong></a><br />
(2014 年 5 月 2 日に定例外としてリリース)</td>
<td style="border:1px solid black;"><strong>Internet Explorer 用のセキュリティ更新プログラム (2965111)<br />
<br />
</strong>このセキュリティ更新プログラムは Internet Explorer に存在する 1 件の一般に公開されている脆弱性を解決します。この脆弱性により、影響を受けるバージョンの Internet Explorer をユーザーが使用して、特別に細工された Web ページを表示した場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用のセキュリティ更新プログラム (2962482)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 2 件の Internet Explorer に存在する脆弱性を解決します。これらの脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server の脆弱性により、リモートでコードが実行される (2952166)</strong><br />
<br />
このセキュリティ更新プログラムは、Microsoft Office サーバー ソフトウェアとプロダクティビティ ソフトウェアに存在する複数の非公開で報告された脆弱性を解決します。これらの脆弱性の中で最も深刻なものにより、認証された攻撃者が特別に細工されたページ コンテンツを標的となる SharePoint Server に送信した場合にリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア、<br />
プロダクティビティ ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (2961037)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、特別な細工が施されたライブラリ ファイルと同じネットワーク ディレクトリにある Office ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396820"><strong>MS14-025</strong></a></td>
<td style="border:1px solid black;"><strong>グループ ポリシー基本設定の脆弱性により、特権が昇格される (2962486)</strong><br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。この脆弱性により、Active Directory グループ ポリシー基本設定がドメイン全体でのパスワード配布に使用された場合、特権が昇格される可能性があります。この手法で、攻撃者は、グループ ポリシー基本設定と共に保存されるパスワードを取得し、解読する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396825"><strong>MS14-026</strong></a></td>
<td style="border:1px solid black;"><strong>.NET Framework の脆弱性により、特権が昇格される (2958732)<br />
</strong><br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、認証された攻撃者が特別な細工を施したデータを、.NET Remoting を使用している、影響を受けるワークステーションやサーバーに送信した場合、特権が昇格される可能性があります。.NET Remoting は、アプリケーションによって広く使用されているわけではありません。.NET Remoting を使用するように特に設計されたカスタム アプリケーションのみで、システムがこの脆弱性にさらされます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396823"><strong>MS14-027</strong></a></td>
<td style="border:1px solid black;"><strong>Windows シェル ハンドラーの脆弱性により、特権が昇格される (2962488)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が ShellExecute を使用する特別に細工されたアプリケーションを実行した場合、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></td>
<td style="border:1px solid black;"><strong>iSCSI の脆弱性により、サービス拒否が起こる (2962485)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。この脆弱性により、攻撃者が標的となるネットワークを介して特別に細工した iSCSI パケットを大量に送信した場合に、サービス拒否が起こる可能性があります。この脆弱性は、iSCSI ターゲットの役割が有効になっているサーバーにのみ影響します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396835"><strong>MS14-024</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft コモン コントロールの脆弱性により、セキュリティ機能のバイパスが起こる (2961033)</strong><br />
<br />
このセキュリティ更新プログラムは、MSCOMCTL コモン コントロール ライブラリの実装に存在する 1 件の非公開で報告された脆弱性を解決します。この脆弱性により、COM コンポーネントのインスタンス化機能を持つ Web ブラウザー (Internet Explorer など) で、特別に細工された Web ページを閲覧すると、セキュリティ機能のバイパスが起こる可能性があります。Web 閲覧攻撃シナリオでは、この脆弱性を悪用することに成功した攻撃者は、広い範囲の脆弱性からユーザーを保護する Address Space Layout Randomization (ASLR) セキュリティ機能をバイパスする可能性があります。セキュリティ機能のバイパス自体では、任意のコードが実行されることはありません。しかし、攻撃者はこの ASLR バイパスの脆弱性を、リモートでコードが実行される脆弱性など別の脆弱性と組み合わせて使用し、ASLR バイパスを利用することで、任意のコードを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
 
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
<p> </p>  <table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>脆弱性のタイトル</strong></td>
<td style="border:1px solid black;"><strong>CVE の識別番号</strong></td>
<td style="border:1px solid black;"><strong>最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</strong></td>
<td style="border:1px solid black;"><strong>旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否の悪用可能性の評価</strong></td>
<td style="border:1px solid black;"><strong>注意事項</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=397669"><strong>MS14-021</strong></a><br />
(2014 年 5 月 2 日に定例外としてリリース)</td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1776">CVE-2014-1776</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<a href="https://technet.microsoft.com/ja-jp/library/security/2963983">マイクロソフト セキュリティ アドバイザリ 2963983</a> で、この脆弱性を最初に説明しました。<br />
<br />
マイクロソフトは、Internet Explorer でこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しています。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;">SharePoint ページ コンテンツの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0251">CVE-2014-0251</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;">SharePoint XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1754">CVE-2014-1754</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></td>
<td style="border:1px solid black;">Web Applications ページ コンテンツの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1813">CVE-2014-1813</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></td>
<td style="border:1px solid black;">Microsoft Office の中国語文章校正の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1756">CVE-2014-1756</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></td>
<td style="border:1px solid black;">トークン再使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1808">CVE-2014-1808</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396835"><strong>MS14-024</strong></a></td>
<td style="border:1px solid black;">MSCOMCTL ASLR の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1809">CVE-2014-1809</a></td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396820"><strong>MS14-025</strong></a></td>
<td style="border:1px solid black;">グループ ポリシー基本設定のパスワードの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1812">CVE-2014-1812</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396825"><strong>MS14-026</strong></a></td>
<td style="border:1px solid black;">TypeFilterLevel の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1806">CVE-2014-1806</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396823"><strong>MS14-027</strong></a></td>
<td style="border:1px solid black;">Windows シェルのファイルの関連付けの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1807">CVE-2014-1807</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></td>
<td style="border:1px solid black;">iSCSI ターゲットのリモートでサービス拒否が起こる脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0255">CVE-2014-0255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></td>
<td style="border:1px solid black;">iSCSI ターゲットのリモートでサービス拒否が起こる脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0256">CVE-2014-0256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0310">CVE-2014-0310</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1815">CVE-2014-1815</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトは、Internet Explorer でこの脆弱性を悪用しようとする限定的な攻撃を確認しています。</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
**これらの表はどのように使用しますか?**
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(緊急)  
Internet Explorer 7  
(2964358)  
(緊急)  
Internet Explorer 8  
(2964358)  
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
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(緊急)  
Internet Explorer 7  
(2964358)  
(緊急)  
Internet Explorer 8  
(2964358)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(警告)  
Internet Explorer 7  
(2964358)  
(警告)  
Internet Explorer 8  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
(警告)  
Internet Explorer 7   
(2953522)  
(警告)  
Internet Explorer 8   
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2931352)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2932079)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
(警告)  
Internet Explorer 7  
(2964358)  
(警告)  
Internet Explorer 8  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
(警告)  
Internet Explorer 7   
(2953522)  
(警告)  
Internet Explorer 8   
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2932079)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2926765)  
(重要)

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
Internet Explorer 6  
(2964358)  
(警告)  
Internet Explorer 7  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
(警告)  
Internet Explorer 7   
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2932079)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(緊急)  
Internet Explorer 8  
(2964358)  
(緊急)  
Internet Explorer 9  
(2964358)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(緊急)  
Internet Explorer 8  
(2953522)  
(緊急)  
Internet Explorer 9  
(2953522)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(緊急)  
Internet Explorer 8  
(2964358)  
(緊急)  
Internet Explorer 9  
(2964358)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(緊急)  
Internet Explorer 8  
(2953522)  
(緊急)  
Internet Explorer 9  
(2953522)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(警告)  
Internet Explorer 8  
(2964358)  
(警告)  
Internet Explorer 9  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(警告)  
Internet Explorer 8  
(2953522)  
(警告)  
Internet Explorer 9  
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(警告)  
Internet Explorer 8  
(2964358)  
(警告)  
Internet Explorer 9  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(警告)  
Internet Explorer 8  
(2953522)  
(警告)  
Internet Explorer 9  
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(緊急)  
Internet Explorer 9  
(2964358)  
(緊急)  
Internet Explorer 10  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964444)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(緊急)  
Internet Explorer 9  
(2953522)  
(緊急)  
Internet Explorer 10  
(2953522)  
(緊急)  
Internet Explorer 11  
(2953522)  
(緊急)  
Internet Explorer 11  
(2961851)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(緊急)  
Internet Explorer 9  
(2964358)  
(緊急)  
Internet Explorer 10  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964444)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(緊急)  
Internet Explorer 9  
(2953522)  
(緊急)  
Internet Explorer 10  
(2953522)  
(緊急)  
Internet Explorer 11  
(2953522)  
(緊急)  
Internet Explorer 11  
(2961851)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(警告)  
Internet Explorer 9  
(2964358)  
(警告)  
Internet Explorer 10  
(2964358)  
(警告)  
Internet Explorer 11  
(2964358)  
(警告)  
Internet Explorer 11  
(2964444)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(警告)  
Internet Explorer 9  
(2953522)  
(警告)  
Internet Explorer 10  
(2953522)  
(警告)  
Internet Explorer 11  
(2953522)  
(警告)  
Internet Explorer 11  
(2961851)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
iSCSI Software Target 3.3  
(2933826)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(重要)  
Microsoft .NET Framework 4.5  
(2931367)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(重要)  
Microsoft .NET Framework 4.5  
(2931367)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964444)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(緊急)  
Internet Explorer 11  
(2961851)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)  
リモート サーバー管理ツール  
(2961899)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2926765)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2962123)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964444)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(緊急)  
Internet Explorer 11  
(2961851)  
(緊急)

</td>
<td style="border:1px solid black;">
リモート サーバー管理ツール  
(2928120)  
(重要)  
リモート サーバー管理ツール  
(2961899)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2926765)  
(重要)  
Windows 8.1 for x64-based Systems  
(2962123)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2928120)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(重要)  
Microsoft .NET Framework 4.5  
(2931367)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2933826)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(警告)  
Internet Explorer 11  
(2964444)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(警告)  
Internet Explorer 11  
(2961851)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2928120)  
(重要)  
Windows Server 2012 R2  
(2961899)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2926765)  
(重要)  
Windows Server 2012 R2  
(2962123)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2933826)  
(重要)  
Windows Server 2012 R2  
(2962073)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2931367)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
(緊急)  
Internet Explorer 11  
(2964444)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
(緊急)  
Internet Explorer 11  
(2961851)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1  
(2931366)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2926765)  
(重要)  
Windows RT 8.1  
(2962123)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-021**](http://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](http://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](http://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](http://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](http://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](http://go.microsoft.com/fwlink/?linkid=309325)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
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
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
(重要)  
Microsoft .NET Framework 4  
(2931365)  
(重要)  
Microsoft .NET Framework 4.5  
(2931368)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931368)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
(重要)  
Microsoft .NET Framework 4.5  
(2931367)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931367)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2926765)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2933826)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

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
Microsoft .NET Framework 3.5  
(2931358)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2931366)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2926765)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2962123)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2933826)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2962073)  
(重要)

</td>
</tr>
</table>
 
 

### Office スイートおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3 (校正ツール)  
(2767772)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3 (mscomct2)  
(2596804)  
(重要)  
Microsoft Office 2007 Service Pack 3 (mscomctlocx)  
(2817330)  
(重要)  
Microsoft Office 2007 Service Pack 3 (msaddndr)  
(2880508)  
(重要)  
Microsoft Office 2007 Service Pack 3 (msstdfmt)  
(2880507)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版) (校正ツール)  
(2878284)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版) (mscomct2)  
(2589288)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 ビット版) (mscomctlocx)  
(2810073)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 ビット版) (msaddndr)  
(2880971)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版) (校正ツール)  
(2878284)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版) (mscomct2)  
(2589288)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版) (mscomctlocx)  
(2810073)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版) (msaddndr)  
(2880971)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版) (校正ツール)  
(2878284)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版) (mscomct2)  
(2589288)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 ビット版) (msaddndr)  
(2880971)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版) (校正ツール)  
(2878284)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版) (mscomct2)  
(2589288)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版) (msaddndr)  
(2880971)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 および Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版) (校正ツール)  
(2880463)  
(重要)  
Microsoft Office 2013 (32 ビット版) (mso)  
(2878316)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版) (mscomct2)  
(2760272)  
(重要)  
Microsoft Office 2013 (32 ビット版) (mscomctlocx)  
(2880502)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版) (校正ツール)  
(2880463)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 ビット版) (mso) (2878316)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版) (mscomct2)  
(2760272)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 ビット版) (mscomctlocx)  
(2880502)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版) (校正ツール)  
(2880463)  
(重要)  
Microsoft Office 2013 (64 ビット版) (mso)  
(2878316)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版) (mscomct2)  
(2760272)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版) (校正ツール)  
(2880463)  
(重要)  
Microsoft Office 2013 Service Pack 1 (64 ビット版) (mso)  
(2878316)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版) (mscomct2)  
(2760272)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-023**](http://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](http://go.microsoft.com/fwlink/?linkid=396835)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT (校正ツール)  
(2880463)  
(重要)  
Microsoft Office 2013 RT (mso)  
(2878316)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT (mscomct2)  
(2760272)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1 (校正ツール)  
(2880463)  
(重要)  
Microsoft Office 2013 RT Service Pack 1 (mso)  
(2878316)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1 (mscomct2)  
(2760272)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (32 ビット版)  
(2837616)  
(緊急)  
SharePoint Server 2007 Service Pack 3 (32 ビット版) (dlcapp)  
(2596902)  
(緊急)  
SharePoint Server 2007 Service Pack 3 (32 ビット版) (dlc)  
(2596763)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (64 ビット版)  
(2837616)  
(緊急)  
SharePoint Server 2007 Service Pack 3 (64 ビット版) (dlcapp)  
(2596902)  
(緊急)  
SharePoint Server 2007 Service Pack 3 (64 ビット版) (dlc)  
(2596763)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wss)  
(2837588)  
(緊急)  
Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)  
(2837598)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wss)  
(2837588)  
(緊急)  
Microsoft SharePoint Server 2010 Service Pack 2 (coreserver)  
(2837598)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 (sts)  
(2863856)  
(緊急)  
Microsoft SharePoint Foundation 2013 (wssloc)  
(2863863)  
(緊急)  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2863829)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1 (sts)  
(2863856)  
(緊急)  
Microsoft SharePoint Foundation 2013 Service Pack 1 (wssloc)  
(2863863)  
(緊急)  
Microsoft SharePoint Server 2013 Service Pack 1 (coreserver)  
(2863829)  
(緊急)

</td>
</tr>
</table>
 
**MS14-022 についての注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft Office Services および Web Apps

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 Service Pack 1  
(2863922)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 Service Pack 2  
(2863922)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013  
(2760236)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013 Service Pack 1  
(2760236)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2880536)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2880536)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2880453)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2880453)  
(緊急)

</td>
</tr>
</table>
 
**MS14-022 についての注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### プロダクティビティ ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SharePoint Server 2013 Client Components SDK**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SharePoint Server 2013 Client Components SDK (32 ビット版)

</td>
<td style="border:1px solid black;">
SharePoint Server 2013 Client Components SDK (32 ビット版)  
(2863854)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SharePoint Server 2013 Client Components SDK (64 ビット版)

</td>
<td style="border:1px solid black;">
SharePoint Server 2013 Client Components SDK (64 ビット版)  
(2863854)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Designer 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2007 Service Pack 3 (ewd)  
(2596861)  
(緊急)  
Microsoft SharePoint Designer 2007 Service Pack 3 (spd)  
(2596810)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Designer 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1 (32 ビット版)  
(2810069)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2 (32 ビット版)  
(2810069)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1 (64 ビット版)  
(2810069)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2 (64 ビット版)  
(2810069)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft SharePoint Designer 2013**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-022**](http://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 (32 ビット版) (spdcore)  
(2752096)  
(緊急)  
Microsoft SharePoint Designer 2013 (32 ビット版) (spd)  
(2863836)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1 (32 ビット版) (spdcore)  
(2752096)  
(緊急)  
Microsoft SharePoint Designer 2013 Service Pack 1 (32 ビット版) (spd)  
(2863836)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 (64 ビット版) (spdcore)  
(2752096)  
(緊急)  
Microsoft SharePoint Designer 2013 (64 ビット版) (spd)  
(2863836)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1 (64 ビット版) (spdcore)  
(2752096)  
(緊急)  
Microsoft SharePoint Designer 2013 Service Pack 1 (64 ビット版) (spd)  
(2863836)  
(緊急)

</td>
</tr>
</table>
 
**MS14-022 についての注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

**MS14-021**

-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1776) についてマイクロソフトに協力してくださった [FireEye, Inc.](http://www2.fireeye.com/)

     

**MS14-023**

-   Microsoft Office の中国語文章校正の脆弱性 (CVE-2014-1756) を報告してくださった [NSFOCUS Security Team](http://www.nsfocus.com/)
-   トークン再使用の脆弱性 (CVE-2014-1808) を報告してくださった [ANSSI](http://www.ssi.gouv.fr/) の Arnaud Maillet 氏

     

**MS14-026**

-   TypeFilterLevel の脆弱性 (CVE-2014-1806) を報告してくださった [Context Information Security](http://www.contextis.com/) の James Forshaw 氏

     

**MS14-028**

-   Beyond Security の [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) プロジェクトに協力して、iSCSI ターゲットのリモートでサービス拒否が起こる脆弱性 (CVE-2014-0255) を報告してくださった匿名のリサーチャー
-   Beyond Security の [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) プロジェクトに協力して、iSCSI ターゲットのリモートでサービス拒否が起こる脆弱性 (CVE-2014-0256) を報告してくださった匿名のリサーチャー

     

**MS14-029**

-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0310) を報告してくださった [Google Security Team](http://www.google.com/) の Fermin J. Serna 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0310) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1815) を報告してくださった [Google Security Team](http://www.google.com/) の Clément Lecigne 氏

     

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)

国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/05/02):このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2014/05/14):マイクロソフト セキュリティ情報 MS13-022 ～ MS13-029 と、5 月 14 日のセキュリティ情報 Webcast のリンクを追加しました。

*Page generated 2014-05-15 10:22Z-07:00.*
