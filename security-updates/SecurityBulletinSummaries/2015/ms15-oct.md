---
TOCTitle: 'MS15-OCT'
Title: 2015 年 10 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-oct'
ms:contentKeyID: 70457352
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-oct(v=Security.10)'
---

2015 年 10 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日:2015 年 10 月 14 日 | 最終更新日: 2016 年 6 月 23 日

**バージョン:** 2.2

このセキュリティ情報の概要は 2015 年 10 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムと共に、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「**関連情報**」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「**影響を受けるソフトウェア**」を参照してください。

<p> </p>  <table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度<br />
と脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>既知の<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3096441)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3096441">3096441</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3093983">3093983</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625091">MS15-107</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3096448)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、情報漏えいが起こる可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=623633">MS15-108</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する JScript と VBScript 用のセキュリティ更新プログラム (3089659)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の VBScript および JScript スクリプト エンジンに存在する脆弱性を解決します。この中で比較的深刻な脆弱性が悪用されると、Internet Explorer を通じて脆弱性を悪用するように特別に細工された Web サイトを攻撃者がホストして (または侵害された Web サイトや、ユーザーが提供するコンテンツまたは広告を受け入れるかホストする Web サイトを利用して)、その Web サイトを表示するようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。攻撃者は「初期化しても安全」と判断された ActiveX コントロールを、IE レンダリング エンジンを使用するアプリケーションや Microsoft Office ドキュメントに埋め込み、ユーザーを特別に細工された Web サイトに誘導する可能性もあります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625078">MS15-109</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Windows Shell 用のセキュリティ更新プログラム (3096443)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性により、ユーザーが Windows で特別な細工がされたツール バー オブジェクトを開くか、攻撃者が特別な細工がされたコンテンツをオンラインで表示するようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3096440)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625080">MS15-111</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する Windows カーネル用のセキュリティ更新プログラム (3096447)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で比較的深刻なものでは、攻撃者が影響を受けるコンピューターにログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>脆弱性のタイトル</strong></td>
<td style="border:1px solid black;"><strong>CVE の識別番号</strong></td>
<td style="border:1px solid black;"><strong>最新のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>過去のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否<br />
悪用可能性評価</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">スクリプト エンジンのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2482">CVE-2015-2482</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6042">CVE-2015-6042</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6044">CVE-2015-6044</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6045">CVE-2015-6045</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6046">CVE-2015-6046</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6047">CVE-2015-6047</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6048">CVE-2015-6048</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6049">CVE-2015-6049</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6050">CVE-2015-6050</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6051">CVE-2015-6051</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">VBScript および JScript ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6052">CVE-2015-6052</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6053">CVE-2015-6053</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">スクリプト エンジンのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6055">CVE-2015-6055</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">スクリプト エンジンのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6056">CVE-2015-6056</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">スクリプト エンジンの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6059">CVE-2015-6059</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625089">MS15-106</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6184">CVE-2015-6184</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625091">MS15-107</a></td>
<td style="border:1px solid black;">Microsoft Edge の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6057">CVE-2015-6057</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625091">MS15-107</a></td>
<td style="border:1px solid black;">Microsoft Edge の XSS フィルター バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6058">CVE-2015-6058</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/f">MS15-108</a></td>
<td style="border:1px solid black;">スクリプト エンジンのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2482">CVE-2015-2482</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=623633">MS15-108</a></td>
<td style="border:1px solid black;">VBScript および Jscript ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6052">CVE-2015-6052</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=623633">MS15-108</a></td>
<td style="border:1px solid black;">スクリプト エンジンのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6055">CVE-2015-6055</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=623633">MS15-108</a></td>
<td style="border:1px solid black;">スクリプト エンジンの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6059">CVE-2015-6059</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625078">MS15-109</a></td>
<td style="border:1px solid black;">ツール バーの解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2515">CVE-2015-2515</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625078">MS15-109</a></td>
<td style="border:1px solid black;">Microsoft タブレット入力バンドの解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2548">CVE-2015-2548</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2555">CVE-2015-2555</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft SharePoint の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2556">CVE-2015-2556</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2557">CVE-2015-2557</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2558">CVE-2015-2558</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft Office Web Apps XSS のなりすましの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6037">CVE-2015-6037</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625092">MS15-110</a></td>
<td style="border:1px solid black;">Microsoft SharePoint のセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6039">CVE-2015-6039</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625080">MS15-111</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2549">CVE-2015-2549</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625080">MS15-111</a></td>
<td style="border:1px solid black;">Windows の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2550">CVE-2015-2550</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625080">MS15-111</a></td>
<td style="border:1px solid black;">トラスト ブートのセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2552">CVE-2015-2552</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625080">MS15-111</a></td>
<td style="border:1px solid black;">Windows マウント ポイントの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2553">CVE-2015-2553</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=625080">MS15-111</a></td>
<td style="border:1px solid black;">Windows オブジェクト参照の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2554">CVE-2015-2554</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントを基に、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(緊急)  
Internet Explorer 8  
(3093983)  
(緊急)  
Internet Explorer 9  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3080446)  
(緊急)  
Windows Vista Service Pack 2  
(3093513)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(緊急)  
Internet Explorer 8  
(3093983)  
(緊急)  
Internet Explorer 9  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3080446)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3093513)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(警告)  
Internet Explorer 8  
(3093983)  
(警告)  
Internet Explorer 9  
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(警告)  
Internet Explorer 8  
(3093983)  
(警告)  
Internet Explorer 9  
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(緊急)  
Internet Explorer 9  
(3093983)  
(緊急)  
Internet Explorer 10  
(3093983)  
(緊急)  
Internet Explorer 11  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3080446)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3093513)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(緊急)  
Internet Explorer 9  
(3093983)  
(緊急)  
Internet Explorer 10  
(3093983)  
(緊急)  
Internet Explorer 11  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3080446)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3093513)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3093983)  
(警告)  
Internet Explorer 9  
(3093983)  
(警告)  
Internet Explorer 10  
(3093983)  
(警告)  
Internet Explorer 11  
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105210)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3097617)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3097617)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3097617)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105210)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3097617)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based System  
(3097617)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based System  
(3097617)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-106**](http://go.microsoft.com/fwlink/?linkid=625089)

</td>
<td style="border:1px solid black;">
[**MS15-107**](http://go.microsoft.com/fwlink/?linkid=625091)

</td>
<td style="border:1px solid black;">
[**MS15-108**](http://go.microsoft.com/fwlink/?linkid=623633)

</td>
<td style="border:1px solid black;">
[**MS15-109**](http://go.microsoft.com/fwlink/?linkid=625078)

</td>
<td style="border:1px solid black;">
[**MS15-111**](http://go.microsoft.com/fwlink/?linkid=625080)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3094996)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.8 および VBScript 5.8  
(3094995)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

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
Windows Server 2012  
(Server Core インストール)  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3088195)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

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
Windows Server 2012 R2  
(Server Core インストール)  
(3080446)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3088195)  
(重要)

</td>
</tr>
</table>
 
### Microsoft Office スイートおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
Microsoft Excel 2007 Service Pack 3  
(3085615)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(3085542)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3085609)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 ビット版)  
(3085514)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3085609)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 ビット版)  
(3085514)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3085583)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3085583)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3085583)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 ビット版)  
(2920693)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 ビット版)  
(2920693)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3097266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3097264)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3085619)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(3085618)  
(重要)

</td>
</tr>
</table>
 
**MS15-110 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft Office Services および Web Apps

 
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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3054994)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3054994)  
(重要)

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3085596)  
(重要)

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services  
(3085568)  
(重要)

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web App 2010 Service Pack 2  
(3085520)  
(重要)  
Microsoft Excel Web App 2010 Service Pack 2  
(3085595)  
(重要)

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3085571)  
(重要)

</td>
</tr>
</table>
 
**MS15-110 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)  
(2596670)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)  
(2596670)  
(重要)

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2  
(2553405)  
(重要)

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
[**MS15-110**](http://go.microsoft.com/fwlink/?linkid=625092)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3085567)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3085582)  
(重要)

</td>
</tr>
</table>
 
**MS15-110 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールの詳細については、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/dn903755.aspx)を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート: [インターナショナル サポート](http://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation およびその関連会社は、本文書に含まれている情報の使用および使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社およびこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/10/14): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2015/10/15): このセキュリティ情報の概要ページを更新し、Exploitability Index (悪用可能性指標) の CVE-2015-6046 のタイトルを修正しました。これは情報のみの変更です。
-   V1.2 (2015/10/16): このセキュリティ情報の概要ページを更新し、CVE-2015-6046 の悪用可能性評価を修正しました。これは情報のみの変更です。
-   V2.0 (2015/10/30): このセキュリティ情報の概要ページを更新し、MS15-106 に追加された脆弱性 CVE-2015-6045 を解決する Windows 10 用の新たな累積的な更新プログラム 3105210 をリリースし、この脆弱性を Exploitability Index (悪用可能性指標) に追記したことをお知らせしました。Windows 10 システムを実行しているお客様のみ、この新たな更新プログラムをインストールしてください。それ以前のオペレーティング システムは、影響を受けないか 2015 年 10 月 14 日の最初の公開時に修正を受信しています。詳細およびダウンロード リンクについては、サポート技術情報 3105210 を参照してください。
-   V2.1 (2016/01/28): MS15-106 に関して、このセキュリティ情報の概要ページを更新し、CVE-2015-6184 を追加しました。これは情報のみの変更です。
-   V2.2 (2016/06/23): 概要の表の MS15-106 に既知の問題を追加しました。この更新プログラムをインストールした後、Internet Explorer 11 の iFrame で localStorage の更新時にストレージ イベントが発生しません。この既知の問題に関する詳細情報と解決策については、[サポート技術情報 3168674](https://support.microsoft.com/ja-jp/kb/3168674) を参照してください。以前 MS15-106 について、累積的な更新プログラム 3093983 をインストール後、Internet Explorer 11 が メモリと CPU サイクルを大量に消費する問題の解決を含む既知の問題を追加しました。この既知の問題に関する詳細情報と解決策については、[サポート技術情報 3119070](https://support.microsoft.com/ja-jp/kb/3119070) を参照してください。

*Page generated 2016-06-22 16:23-07:00.*
