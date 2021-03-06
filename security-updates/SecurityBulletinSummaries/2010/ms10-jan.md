---
TOCTitle: 'MS10-JAN'
Title: 2010 年 1 月のセキュリティ情報
ms:assetid: 'ms10-jan'
ms:contentKeyID: 61229674
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-jan(v=Security.10)'
--- 

2010 年 1 月のセキュリティ情報
==============================

公開日: 2010年1月13日 | 最終更新日: 2010年1月22日

**バージョン:** 1.0

[![](../../images/Dn627253.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627253.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-001 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-001e.mspx)

[MS10-002 : Intnernet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-002e.mspx)

このセキュリティ情報は 2010 年 1 月に公開したセキュリティ情報の一覧です。

2010 年 1 月 22 日に定例外で公開した[セキュリティ情報 MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) に関する情報を追加しました。

2010 年 1 月 13 日のセキュリティ情報の公開により、2010 年 1 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 1 月 13 日 の午後 (日本時間) に配信しました。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこの定例外の緊急セキュリティ情報 MS10-002 についての概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 1 月 22 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 1 月 13 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行いました。[1 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427677&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはこの定例外の緊急セキュリティ情報 MS10-002 に関するお客様からの質問を解決するため、2010 年 1 月 21 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[1 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032440627&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

 
 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報番号</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-001">MS10-001</a></td>
<td style="border:1px solid black;"><strong>Embedded OpenType フォント エンジンの脆弱性により、リモートでコードが実行される (972270)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、ユーザーが Internet Explorer、PowerPoint、Microsoft Word などの Embedded OpenType (EOT) フォントをレンダリングできるクライアント アプリケーションで、特別な細工がされた EOT フォントでレンダリングされたコンテンツを表示した場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-002">MS10-002</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (978207)</strong><br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する 7 つの非公開で報告された脆弱性と 1 つの公開された脆弱性を解決します。より深刻な脆弱性では、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報番号                                                | 脆弱性タイトル                                                                            | CVE ID                                                                           | Exploitability Index の評価                                                                     | 注意事項                                                                                                                                                                                          |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-001](http://technet.microsoft.com/security/bulletin/ms10-001) | LZCOMP 圧縮解除処理中の Microtype Express Compressed フォントに関する整数処理問題の脆弱性 | [CVE-2010-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0018) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性 | この悪用可能性指標は Microsoft Windows 2000 のコンピューターを対象とします。Windows XP またはそれ以降のオペレーティング システムのコンピューターでの悪用の見込みはありません。                    |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | XSS フィルターのスクリプト処理の脆弱性                                                    | [CVE-2009-4074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-4074) | なし                                                                                            | この脆弱性によりコードが実行されることはありません。                                                                                                                                              |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | URL の検証の脆弱性                                                                        | [CVE-2010-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | (なし)                                                                                                                                                                                            |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | 初期化されていないメモリ破損の脆弱性                                                      | [CVE-2010-0244](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0244) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | (なし)                                                                                                                                                                                            |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | 初期化されていないメモリ破損の脆弱性                                                      | [CVE-2010-0245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0245) | なし                                                                                            | [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) を適用済みのお客様はこの脆弱性から保護されています。この脆弱性は、MS09-072 の更新プログラムによる変更によりブロックされます。 |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | 初期化されていないメモリ破損の脆弱性                                                      | [CVE-2010-0246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0246) | なし                                                                                            | [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) を適用済みのお客様はこの脆弱性から保護されています。この脆弱性は、MS09-072 の更新プログラムによる変更によりブロックされます。 |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | 初期化されていないメモリ破損の脆弱性                                                      | [CVE-2010-0247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0247) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | (なし)                                                                                                                                                                                            |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | HTML オブジェクトのメモリ破損の脆弱性                                                     | [CVE-2010-0248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0248) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性 | (なし)                                                                                                                                                                                            |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | HTML オブジェクトのメモリ破損の脆弱性                                                     | [CVE-2010-0249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0249) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                             |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
**この表はどのように使用しますか?**
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=47f85cbd-282e-4c92-9809-68bba49e0a12)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4 上にインストールされた Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=51e99e4f-1670-4b12-a9fe-e0ccf50cdabc)  
(緊急)  
[Microsoft Windows 2000 Service Pack 4 上にインストールされた Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a38aa9d0-c3fe-4d41-8805-7d5370263c1b)  
(緊急)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=793a6b3f-7660-40be-b7d5-7b0eec55e1cd)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3 用の Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=207eecad-6e84-48e6-ae18-6794a3618ee0)  
(緊急)  
[Windows XP Service Pack 2 および Windows XP Service Pack 3 用の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3510c7d8-7e8f-479e-b6f9-5745a845664d)  
(緊急)  
[Windows XP Service Pack 2 および Windows XP Service Pack 3 用の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7c2948fb-f486-4801-bc21-bbf40d5a78c2)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=31609ce9-656a-4f7d-a501-709a31ca34c3)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2 用の Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=eb2d8055-4d50-4f83-82b8-055c7b8f5422)  
(緊急)  
[Windows XP Professional x64 Edition Service Pack 2 用の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cc5aea0b-e553-4f7f-a2cc-cba41bb87ae7)  
(緊急)  
[Windows XP Professional x64 Edition Service Pack 2 用の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=41b83fad-948b-4a9c-80ed-9c5a60bd35b4)  
(緊急)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e1d6e338-dea9-458e-b35d-796e069d74d7)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2 用の Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fea91227-44ad-4549-8732-497a8ceff870)  
(警告)  
[Windows Server 2003 Service Pack 2 用の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14726445-3ff4-463c-9fc1-c9b758079aca)  
(緊急)  
[Windows Server 2003 Service Pack 2 用の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7d480c87-2ca9-4505-a59d-a6d73d001fa5)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ddbcf231-9fde-4dc2-ad04-a01b69d1a980)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2 用の Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=633e63f4-605b-43c4-8a4b-2730312a1c72)  
(警告)  
[Windows Server 2003 x64 Edition Service Pack 2 用の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c8742230-16d8-4b2f-bd3e-8834c759856b)  
(緊急)  
[Windows Server 2003 x64 Edition Service Pack 2 用の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3e2e740b-8417-4758-8468-15221249ec71)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c71a13cf-7e2f-4b02-8684-1a4e4b46ddda)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems 用の Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b9308d50-ca66-43ff-9dc5-d05c90baa764)  
(警告)  
[Windows Server 2003 with SP2 for Itanium-based Systems 用の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5622f223-df9c-4a6a-bdf0-feebaf9920fd)  
(緊急)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1、および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1、および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6387228c-eedc-4511-b3c6-8922606f4c84)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1、および Windows Vista Service Pack 2 の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=92495551-dedd-43d4-bb3a-51028bc5c6d6)  
(緊急)  
[Windows Vista、Windows Vista Service Pack 1、および Windows Vista Service Pack 2 の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e2cbd7d-f64f-49e5-a159-1965ebfe2a92)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1、および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1、および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7b4f5089-13b1-421b-a00b-22632bba4229)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1、および Windows Vista x64 Edition Service Pack 2 の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3cb139b3-59f4-44ef-9911-4dd4e3b83e7d)  
(緊急)  
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1、および Windows Vista x64 Edition Service Pack 2 の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b7a7e8e7-f4c5-459d-ab6c-05a192e1e3f9)  
(緊急)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e175c436-37e0-497f-8b7f-6cacaa25ad7c)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2 の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8c4c91ec-1b2b-4176-bd77-45245b590329)\*\*  
(緊急)  
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2 の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f5ce8582-af63-4870-bee3-0abeeefa1458)\*\*  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b10a177-fd45-406f-8edc-b8d4b84881b7)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7 in Windows Server 2008 for x64-based Systems and Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4f9975b8-3f91-4116-9200-ef55ece75854)\*\*  
(緊急)  
[Internet Explorer 8 in Windows Server 2008 for x64-based Systems and Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=be11981c-d286-4e3c-94bf-d4e67a975d5a)\*\*  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e8bc9a24-a794-4827-a6bb-785c6b2189f4)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2 の Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9395547f-b620-4cbd-9ff5-11b76cd73859)  
(緊急)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=75491ad0-40a6-4efb-9574-d82210f6d0da)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=278443c1-15dc-436b-893b-ffea6d29d16d)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8a53f0e9-0616-440e-90f2-a12524e1bee4)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a584cd0f-2e05-4e36-8858-0ffead637162)  
(緊急)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=308166e4-571b-4d6c-bd9f-3ed4afa4eafe)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d3386793-a594-4bc5-8308-28b561d43087)\*\*  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1d0da42b-9755-4fd2-afd1-0d023d187133)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems の Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9d137bab-8312-4240-af74-c65ba652fde0)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*\*Server Core インストールは影響を受けません。**この更新プログラムで解決されている脆弱性は、Server Core インストールオプションを使用してインストールされたサポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 は、影響を受けません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](http://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトはセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [961747](http://support.microsoft.com/kb/961747) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について、すべての Windows のコンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報):
    Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS10-001 で説明している問題について報告してくださった [Google Inc.](http://www.google.com/) の Tavis Ormandy 氏
-   MS10-002 で説明している問題について報告してくださった [David Lindsay "thornmaker"](http://p42.us/) 氏および [Eduardo A. Vela Nava "sirdarckcat"](http://www.sirdarckcat.net/)氏
-   MS10-002 で説明している問題について報告してくださった Lostmon Lords 氏
-   MS10-002 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Brett Moore 氏
-   MS10-002 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している [team509](http://www.team509.com/) の Wushi 氏
-   MS10-002 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している eshu.co.uk の Sam Thomas 氏
-   MS10-002 で説明している問題について報告してくださった Fortinet の [Fortinet’s FortiGuard Labs](http://www.fortiguardcenter.com/) の Haifei Li 氏
-   MS10-002 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Peter Vreugdenhil 氏
-   MS10-002 で説明している問題について報告してくださった [BugSec](http://www.bugsec.com/) の Meron Sellem 氏

MS10-002 で説明している問題の詳細を連絡し、顧客の保護に協力して下さった下記の企業に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   [Google Inc.](http://www.google.com/) および [MANDIANT](http://www.mandiant.com/)
-   [Adobe](http://www.adobe.com/)
-   [McAfee](http://www.mcafee.com/)
-   フランス政府 CSIRT [CERTA](http://www.certa.ssi.gouv.fr/)

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/01/13: このセキュリティ情報ページを公開しました。
-   2010/01/21: 2010 年 1 月 22 日公開予定の緊急リリースに関するお知らせを追加しました。
-   2010/01/22: マイクロソフト セキュリティ情報 **MS10-002: Internet Explorer 用の累積的なセキュリティ更新プログラム (978207)** を追加しました。またこの定例外のセキュリティ情報用の Web キャストのリンクを追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
