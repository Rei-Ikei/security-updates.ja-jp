---
TOCTitle: 'MS14-FEB'
Title: 2014 年 2 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-feb'
ms:contentKeyID: 61597943
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-feb(v=Security.10)'
---

2014 年 2 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2014 年 2 月 12 日 | 最終更新日:2014 年 10 月 1 日

**バージョン:** 1.3

このセキュリティ情報の概要は 2014 年 2 月公開のセキュリティ情報の一覧です。

2014 年 2 月のセキュリティ情報の公開により、2014 年 2 月 11 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2014 年 2 月 12 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[2 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572879&culture=en-us) (英語)。

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
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度および脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2909921)<br />
<br />
このセキュリティ更新プログラムは、Internet Explorer に存在する 1 件の一般に公開された脆弱性および 23 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391023">MS14-011</a></td>
<td style="border:1px solid black;">VBScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (2928390)<br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows の VBScript スクリプト エンジンに存在する非公開で報告された脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web サイトを訪問すると、リモートでコードが実行される可能性があります。しかし、いかなるケースでも、攻撃者はユーザーに Web サイトを見るよう強制することはできません。その代わり、攻撃者はユーザーに何らかの操作を実行するように仕向けます。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトへ誘導しようとします。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386447">MS14-007</a></td>
<td style="border:1px solid black;">Direct2D の脆弱性により、リモートでコードが実行される (2912390)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者は、特別に細工されたコンテンツを強制的にユーザーに表示させることはできません。その代わり、ユーザーに操作を行わせることが攻撃者にとっての必要条件となります。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトにユーザーを誘導します。または、電子メールで送信した添付ファイルを開かせようとします。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390218">MS14-008</a></td>
<td style="border:1px solid black;">Microsoft Forefront Protection for Exchange の脆弱性により、リモートでコードが実行される (2927022)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Forefront に存在する 1 件の脆弱性を解決します。この脆弱性により、特別に細工された電子メール メッセージがスキャンされると、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft セキュリティ ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、特権が昇格される (2916607)<br />
<br />
このセキュリティ更新プログラムは Microsoft .NET Framework に存在する 2 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性により、ユーザーが特別に細工された Web サイト、または特別に細工された Web コンテンツが含まれている Web サイトを訪問した場合、特権が昇格される可能性があります。しかし、すべての場合、攻撃者がこのような Web サイトにユーザーを強制的に訪問させる方法はないと考えられます。その代わり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャー メッセージ内のリンクをクリックさせることにより、ユーザーを侵害された Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391022">MS14-005</a></td>
<td style="border:1px solid black;">Microsoft XML コア サービスの脆弱性により、情報漏えいが起こる (2916036)<br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows に搭載され、一般に公開された Microsoft XML コア サービスに存在する 1 件の脆弱性を解決します。この脆弱性で、ユーザーが Internet Explorer を使用して、特別に細工された Web ページを表示した際に情報漏えいが起こる可能性があります。攻撃者は、特別に細工されたコンテンツを強制的にユーザーに表示させることはできません。その代わり、ユーザーに操作を行わせることが攻撃者にとっての必要条件となります。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトにユーザーを誘導します。または、電子メールで送信した添付ファイルを開かせようとします。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386450">MS14-006</a></td>
<td style="border:1px solid black;">IPv6 の脆弱性により、サービス拒否が起こる (2904659)<br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるシステムに特別に細工した IPv6 パケットを大量に送信した場合、サービス拒否が起きる可能性があります。この脆弱性が悪用されるには、標的となるコンピューターと同じサブネットに属していることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391022">MS14-005</a></td>
<td style="border:1px solid black;">MSXML の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0266">CVE-2014-0266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする標的型攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386450">MS14-006</a></td>
<td style="border:1px solid black;">TCP/IP version 6 (IPv6) のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0254">CVE-2014-0254</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386447">MS14-007</a></td>
<td style="border:1px solid black;">Microsoft Graphics コンポーネントのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0263">CVE-2014-0263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390218">MS14-008</a></td>
<td style="border:1px solid black;">RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0294">CVE-2014-0294</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">POST 要求の DoS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0253">CVE-2014-0253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">型トラバーサルの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0257">CVE-2014-0257</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">VSAVB7RT ASLR の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0295">CVE-2014-0295</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0267">CVE-2014-0267</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0268">CVE-2014-0268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0269">CVE-2014-0269</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0270">CVE-2014-0270</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0271">CVE-2014-0271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0272">CVE-2014-0272</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0273">CVE-2014-0273</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0274">CVE-2014-0274</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0275">CVE-2014-0275</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0276">CVE-2014-0276</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0277">CVE-2014-0277</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0278">CVE-2014-0278</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0279">CVE-2014-0279</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0280">CVE-2014-0280</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0281">CVE-2014-0281</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0283">CVE-2014-0283</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0284">CVE-2014-0284</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0285">CVE-2014-0285</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0286">CVE-2014-0286</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0287">CVE-2014-0287</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0288">CVE-2014-0288</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0289">CVE-2014-0289</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0290">CVE-2014-0290</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer のクロス ドメインの情報の漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0293">CVE-2014-0293</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391023">MS14-011</a></td>
<td style="border:1px solid black;">VBScript のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0271">CVE-2014-0271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
なし

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
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(緊急)  
Internet Explorer 7   
(2909921)  
(緊急)  
Internet Explorer 8   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(緊急)  
VBScript 5.8   
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 Service Pack 3:  
(2904878)  
(重要)  
(Media Center Edition 2005 Service Pack 3 および Tablet PC Edition 2005 Service Pack 3 のみ)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2901111)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898856)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2916036)  
(重要)

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
(2909921)  
(緊急)  
Internet Explorer 7   
(2909921)  
(緊急)  
Internet Explorer 8   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(緊急)  
VBScript 5.7   
(2909212)  
(緊急)  
VBScript 5.8   
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901111)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898856)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2916036)  
(重要)

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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 6   
(2909921)  
(警告)  
Internet Explorer 7  
(2909921)  
(警告)  
Internet Explorer 8  
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(警告)  
VBScript 5.7   
(2909212)  
(警告)  
VBScript 5.8   
(2909210)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2901115)  
(重要)  
Microsoft .NET Framework 1.1 Service Pack 1  
(2898860)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2901111)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898856)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2916036)  
(注意)

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
(2909921)  
(警告)  
Internet Explorer 7  
(2909921)  
(警告)  
Internet Explorer 8  
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(警告)  
VBScript 5.7   
(2909212)  
(警告)  
VBScript 5.8   
(2909210)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901111)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898856)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2916036)  
(注意)

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
(2909921)  
(警告)  
Internet Explorer 7  
(2909921)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(警告)  
VBScript 5.7   
(2909212)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901111)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898856)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2916036)  
(注意)

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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
なし

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(緊急)  
Internet Explorer 8  
(2909921)  
(緊急)  
Internet Explorer 9   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(緊急)  
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901113)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898858)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2911502)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2916036)  
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
(2909921)  
(緊急)  
Internet Explorer 8  
(2909921)  
(緊急)  
Internet Explorer 9   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(緊急)  
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901113)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898858)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2911502)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2916036)  
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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(警告)  
Internet Explorer 8  
(2909921)  
(重要)  
Internet Explorer 9   
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(警告)  
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901113)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898858)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2911502)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(警告)  
Internet Explorer 8  
(2909921)  
(重要)  
Internet Explorer 9   
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(警告)  
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901113)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898858)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2911502)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2901113)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2898858)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2911502)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2916036)  
(注意)

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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(緊急)  
Internet Explorer 9   
(2909921)  
(緊急)  
Internet Explorer 10   
(2909921)  
(緊急)  
Internet Explorer 11   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(緊急)  
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)  
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2916036)  
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
(2909921)  
(緊急)  
Internet Explorer 9   
(2909921)  
(緊急)  
Internet Explorer 10   
(2909921)  
(緊急)  
Internet Explorer 11   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(緊急)  
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)  
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2916036)  
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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(重要)  
Internet Explorer 9   
(2909921)  
(重要)  
Internet Explorer 10   
(2909921)  
(重要)  
Internet Explorer 11   
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)  
Internet Explorer 9 を実行しているシステムの VBScript 5.8  
(2909921)<sup>[1]</sup>
(警告)  
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)  
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2916036)  
(注意)

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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(重要)  
Microsoft .NET Framework 3.5  
(2898866)  
(重要)  
Microsoft .NET Framework 4.5  
(2901119)  
(重要)  
Microsoft .NET Framework 4.5  
(2898865)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2916036)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2904659)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(重要)  
Microsoft .NET Framework 3.5  
(2898866)  
(重要)  
Microsoft .NET Framework 4.5  
(2901119)  
(重要)  
Microsoft .NET Framework 4.5  
(2898865)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2916036)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2904659)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(重要)  
Microsoft .NET Framework 3.5  
(2898868)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2916036)  
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
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(重要)  
Microsoft .NET Framework 3.5  
(2898868)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2916036)  
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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(重要)  
Microsoft .NET Framework 3.5  
(2898866)  
(重要)  
Microsoft .NET Framework 4.5  
(2901119)  
(重要)  
Microsoft .NET Framework 4.5  
(2898865)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2904659)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(重要)  
Microsoft .NET Framework 3.5  
(2898868)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 10 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2901119)  
(重要)  
Microsoft .NET Framework 4.5  
(2898865)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2916036)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2904659)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11 を実行しているシステムの VBScript 5.8  
(2909210)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2912390)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1  
(2901128)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2916036)  
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
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[注意](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)

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
VBScript 5.7   
(2909212)  
(深刻度なし)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2916036)  
(注意)

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
VBScript 5.7   
(2909212)  
(深刻度なし)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2916036)  
(注意)

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
VBScript 5.8   
(2909210)  
(深刻度なし)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(重要)  
Microsoft .NET Framework 4  
(2901110)  
(重要)  
Microsoft .NET Framework 4  
(2898855)  
(重要)  
Microsoft .NET Framework 4.5  
(2901118)  
(重要)  
Microsoft .NET Framework 4.5  
(2898864)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2916036)  
(注意)

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
VBScript 5.8   
(2909210)  
(深刻度なし)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(重要)  
Microsoft .NET Framework 3.5  
(2898866)  
(重要)  
Microsoft .NET Framework 4.5  
(2901119)  
(重要)  
Microsoft .NET Framework 4.5  
(2898865)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2904659)  
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
VBScript 5.8   
(2909210)  
(深刻度なし)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(重要)  
Microsoft .NET Framework 3.5  
(2898868)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(重要)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2916036)  
(注意)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
MS14-011 に関する注意事項

<sup>[1]</sup> Internet Explorer 9 を実行しているシステムでは、この脆弱性は [MS14-010](http://go.microsoft.com/fwlink/?linkid=390977) の Internet Explorer 9 用の累積的な更新プログラム 2909921 によって解決されます。

 

### Microsoft セキュリティ ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Forefront Protection 2010 for Exchange Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID

</td>
<td style="border:1px solid black;">
[MS14-008](http://go.microsoft.com/fwlink/?linkid=390218)

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
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Protection 2010 for Exchange Server

</td>
<td style="border:1px solid black;">
Microsoft Forefront Protection 2010 for Exchange Server  
(2927022)  
(緊急)

</td>
</tr>
</table>
 
 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

-   Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。
-   Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

MS14-005

-   MSXML の情報漏えいの脆弱性 (CVE-2014-0266) についてマイクロソフトに協力してくださった [FireEye, Inc.](http://www2.fireeye.com/)

MS14-007

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Microsoft Graphics コンポーネントのメモリ破損の脆弱性 (CVE-2014-0263) を報告してくださった [Omair](http://krash.in/) 氏

MS14-009

-   型トラバーサルの脆弱性 (CVE-2014-0257) を報告してくださった、[Context Information Security](http://www.contextis.com/) の James Forshaw 氏

MS14-010

-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0267) についてマイクロソフトに協力してくださった [KeenTeam](http://www.k33nteam.org/) (@K33nTeam) の Liang Chen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0267) についてマイクロソフトに協力してくださった [VulnHunt](http://www.vulnhunt.com/) の Code Audit Labs
-   Internet Explorer の特権の昇格の脆弱性 (CVE-2014-0268) を報告してくださった [Context Information Security](http://www.contextis.com/) の James Forshaw 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0269) を報告してくださった Simon Zuckerbraun 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0270) を報告してくださった、Yenteasy - Security Research の Jose A. Vazquez 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0270) を報告してくださった Yenteasy - Security Research の Jose A. Vazquez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0272) を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0273) を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0274) を報告してくださった Arthur Gerkis 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0274) を報告してくださった lokihardt@ASRT 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0275) を報告してくださった Simon Zuckerbraun 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0276) を報告してくださった、[Security-Assessment.com](http://www.security-assessment.com/) の Scott Bell 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0277) を報告してくださった、[Security-Assessment.com](http://www.security-assessment.com/) の Scott Bell 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0278) を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0278) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0279) を報告してくださった、[Security-Assessment.com](http://www.security-assessment.com/) の Scott Bell 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0279) を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0280) を報告してくださった、[Security-Assessment.com](http://www.security-assessment.com/) の Scott Bell 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0281) を報告してくださった cons0ul 氏と suto 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0283) を報告してくださった Sachin Shinde 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0284) を報告してくださった Sachin Shinde 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0285) を報告してくださった Simon Zuckerbraun 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0285) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0286) を報告してくださった Simon Zuckerbraun 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0287) を報告してくださった [Corelan](http://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0288) を報告してくださった Arthur Gerkis 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0289) を報告してくださった lokihardt@ASRT 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0290) を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0290) を報告してくださった [Qihoo](http://www.360.cn/) の Zhibin Hu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0290) を報告してくださった [Trend Micro](http://www.trendmicro.com/) の Yuki Chen 氏
-   Internet Explorer のクロス ドメインの情報の漏えいの脆弱性 (CVE-2014-0293) を報告してくださった [Dieyu dieu deus deva divine dio theos dievas dewa ilu Diyin Ayóo Átʼéii atua tiānzhŭ Yahweh Zeus Odin El](http://dieyu.org/)

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

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)
-   Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/02/12):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2014/02/14):MS14-008 について、Exploitability Index (悪用可能性指標) の中で、CVE-2014-0294 の旧バージョンのソフトウェア リリースに関する悪用可能性の評価を更新しました。
-   V1.2 (2014/02/17):MS14-011 について、Exploitability Index (悪用可能性指標) の中で、CVE-2014-0271 の最新ソフトウェア リリースに関する悪用可能性の評価を更新しました。
-   V1.3 (2014/10/01):MS14-009 について、「影響を受けるソフトウェア」の表で、Windows Server 2008 R2 for x64-based Systems Service Pack 1 にインストールされている Microsoft .NET Framework 4 に対し Server Core の記載を追加しました (2898855)。今回の更新は情報のみの変更です。Server Core インストール上で影響を受けるソフトウェアを実行し、更新プログラム 2898855 を既に適用している場合は、特に措置を講じる必要はありません。Server Core インストール上で影響を受けるソフトウェアを実行し、この更新プログラムをまだインストールしていない場合は、MS14-009 で説明している脆弱性から保護するために更新プログラムをインストールする必要があります。ダウンロード リンクについては、このセキュリティ情報を参照してください。

*Page generated 2014-09-23 14:39Z-07:00.*
