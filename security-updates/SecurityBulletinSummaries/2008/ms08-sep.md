---
TOCTitle: 'MS08-SEP'
Title: 2008 年 9 月のセキュリティ情報
ms:assetid: 'ms08-sep'
ms:contentKeyID: 61229657
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-sep(v=Security.10)'
---

 

2008 年 9 月のセキュリティ情報
==============================

公開日: 2008年9月5日 | 最終更新日: 2008年12月10日

**バージョン:** 3.0

絵でみるセキュリティ情報
------------------------

 
[MS08-052 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-052e.mspx)

[MS08-053 : Windows Media エンコーダーの重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-053e.mspx)

[MS08-054 : Windows Media Player の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-054e.mspx)

[MS08-055 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-055e.mspx)

このセキュリティ情報は 2008 年 9 月に公開したセキュリティ情報の一覧です。

2008 年 9 月のセキュリティ情報の公開により2008 年 9 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx) でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 9 月 10 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[9 月のセキュリティ 情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us) 詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 9 月 10 日 の午後 (日本時間) に配信予定です。 詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

緊急 (4)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Windows Media Player の脆弱性により、リモートでコードが実行される (954154)](http://technet.microsoft.com/security/bulletin/ms08-054)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された Windows Media Player の脆弱性を解決します。この脆弱性が悪用されると、Windows Media サーバーから特別に細工されたオーディオ ファイルが配信された時に、リモートでコードが実行される可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピューターに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、「影響を受けるソフトウェアおよびダウンロード先」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-052                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [GDI+ の脆弱性により、リモートでコードが実行される (954593)](http://technet.microsoft.com/security/bulletin/ms08-052)                                                                                                                                                                                                                                                                                                                                                                               |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows GDI+ に存在する数件の脆弱性を解決します。これらの脆弱性のため、ユーザーが影響を受けるソフトウェアを使用して特別な細工がされた画像ファイルを表示すると、リモートでコードが実行される可能性があります。この脆弱性は、ユーザーが影響を受けるソフトウェアを使用して特別に細工された画像ファイルを開いた場合、または特別に細工されたコンテンツが含まれる Web サイトを参照した場合、リモートでコードが実行される可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピューターに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要です。                                                                                                                                                                                                                                                                                                                           |
| **影響を受けるソフトウェア** | **Microsoft Windows, Internet Explorer, .NET Framework, Office, SQL Server, Visual Studio.** 詳細情報は、「影響を受けるソフトウェアおよびダウンロード先」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                               |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-053                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Windows Media エンコーダー 9 の脆弱性により、リモートでコードが実行される (954156)](http://technet.microsoft.com/security/bulletin/ms08-053)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **概要**                     | この更新プログラムは非公開で報告された Windows Media エンコーダー 9 シリーズに存在する非公開で報告された脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピューターに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、「影響を受けるソフトウェアおよびダウンロード先」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-055                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Office の脆弱性により、リモートでコードが実行される (955047)](http://technet.microsoft.com/security/bulletin/ms08-055)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **概要**                     | この更新プログラムは非公開で報告された Microsoft Office に存在する脆弱性を解決します。この脆弱性で、特別な細工がされた OneNote URL をユーザーがクリックした場合にリモートでコードが実行される可能性があります。この脆弱性を悪用して、攻撃者は影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピューターに必要であるかについて検出できます。ほとんどの場合、このセキュリティ更新プログラムは再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **影響を受けるソフトウェア** | **Microsoft Office.** 詳細情報は、「影響を受けるソフトウェアおよびダウンロード先」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866)  
(KB938464)  
(緊急)  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d)  
(KB947739)  
(なし)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a)  
(KB947742)  
(なし)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7f1cd013-2c4b-4582-9114-cb840a96124a)  
(KB947746)  
(なし)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8)  
(KB947748)  
(なし)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25)  
(緊急)
</td>
</tr>
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5891180-5dd1-49ec-bcc6-3030a544202c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=18efea9e-b103-46de-90d9-5e295854cec3)  
(緊急)  
[Windows Media エンコーダー 9 シリーズ x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9)  
(緊急)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-05)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ac03f138-eca4-46e1-9782-e811820e547f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=93f1451b-5b62-47e5-8f0c-b720b957999a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c83011cd-90b8-494c-9cad-fa055e101992)  
(警告)  
[Windows Media エンコーダー 9 シリーズ x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-05)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=334352e7-d41f-494f-866d-f1f1745ffd17)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(緊急)  
[Windows Media エンコーダー 9 シリーズ x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53)  
(緊急)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-05)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
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
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3906512b-26db-473e-b522-3883ff34a21c)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media エンコーダー 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(警告)  
[Windows Media エンコーダー 9 シリーズ x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734)\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5159bdba-3825-4816-a2be-ab035332b9e2)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**\*Windows Server 2008 Server Core は、この脆弱性の影響を受けません。** これらの更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 をインストールした場合、これらの脆弱性の影響を受けるファイルがシステムに存在していたとしても、サポートされているエディションの Windows Server 2008 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

#### Microsoft Office スイートおよびソフトウェア

 
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
Microsoft Office スイート、システム、およびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://technet.microsoft.com/security/bulletin/ms08-055)
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 および Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(重要)  
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(重要)  
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System および 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(重要)  
[2007 Microsoft Office System Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(重要)
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(重要)  
[2007 Microsoft Office System Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
その他の Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://technet.microsoft.com/security/bulletin/ms08-055)
</td>
</tr>
<tr>
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405) \*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48)  
(KB954479)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer、Microsoft Word Viewer 2003、Microsoft Word Viewer 2003 ServicePack 3、Microsoft Office Excel Viewer 2003 および Microsoft Office Excel Viewer 2003 Service Pack3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer、Microsoft Word Viewer 2003、Microsoft Word Viewer 2003 ServicePack 3、Microsoft Office Excel Viewer 2003 および Microsoft Office Excel Viewer 2003 Service Pack3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478) \*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cd503f08-1831-45ff-bdf4-dd918ca40505)  
(KB956500)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer、Microsoft Office PowerPoint Viewer 2007 および Microsoft Office PowerPoint Viewer 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer、Microsoft Office PowerPoint Viewer 2007 および Microsoft Office PowerPoint Viewer 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326) \*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326) \*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web および Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft Expression Web および Microsoft Expression Web 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326) \*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007 および Microsoft Office Groove Server 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Server 2007 および Microsoft Office Groove Server 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326) \*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](http://download.microsoft.com/download/3/b/e/3be87647-5b77-42c7-90fa-dc7d92882230/works8_kb956483_ja-jp.msp)  
(KB956483)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Digital Image Suite 2006
</td>
<td style="border:1px solid black;">
[Microsoft Digital Image Suite 2006](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=04afd760-8173-4069-9e82-d3bf053d9eae)  
(KB955992)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Home Style+
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた [Microsoft Office Home Style+ Service Pack 1 および Microsoft Office Home Style+ Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f4304ae-cd18-4f37-9327-26bb3ccc7dce&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft はがきスタジオ 2006
</td>
<td style="border:1px solid black;">
[Microsoft はがきスタジオ 2006](http://www.microsoft.com/downloads/details.aspx?familyid=2815b980-86d1-486a-890a-2b8f135bbc73&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft はがきスタジオ Basic 平成 18 年版
</td>
<td style="border:1px solid black;">
[Microsoft はがきスタジオ Basic 平成 18 年版](http://www.microsoft.com/downloads/details.aspx?familyid=2815b980-86d1-486a-890a-2b8f135bbc73&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office OneNote 2007
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office OneNote 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(緊急)  
[Microsoft Office OneNote 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
\* この影響を受けるソフトウェアの更新は、Microsoft Office XP Service Pack 3 の更新と同じです。

\*\* これらの影響を受けるソフトウェアの更新は、Microsoft Office 2003 Service Pack 2 および Microsoft Office 2003 Service Pack 3 の更新と同じです。

\*\*\* これらの影響を受けるソフトウェアの更新は、2007 Microsoft Office System および 2007 Microsoft Office System Service Pack 1 の更新と同じです。

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
対象外  
QFE のセキュリティ更新プログラム:  
[SQL Server 2000 Reporting Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5f9e7f78-7439-414b-a9dc-a779b89427db)  
(KB954609)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(緊急)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(緊急)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(緊急)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(緊急)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7848a652-4025-44bb-9c98-37a078b56d01)  
(KB947736)  
(なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e)  
(KB947737)  
(なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a)  
(KB947738)  
(なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a8c80b29-6d00-4949-a005-5d706122919a)  
(KB952241)  
(なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 再頒布可能パッケージ
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=82833f27-081d-4b72-83ef-2836360a904d)  
(KB954765)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 再頒布可能パッケージ
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1)  
(KB954766)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた [Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=1f4371b9-b8be-4455-94d2-2304ee340543)  
(KB955368)  
(なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた [Microsoft Visual FoxPro 9.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=49b21e30-722d-446e-9020-aceb3870db69)  
(KB955369)  
(なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた [Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa)  
(KB955370)  
(なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable: GDI+
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable: GDI+](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(なし)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft セキュリティ ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Forefront セキュリティ
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた [Microsoft Forefront Client Security 1.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e)  
(KB957177)  
(重要)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx) をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx) では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update) からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx) をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、および SQL Server 2000 用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx) をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): 2008 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開された Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してくださ い。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません** 。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い [謝意](http://technet.microsoft.com/security/bulletin/policy) を表します。

-   MS08-052 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Greg MacManus 氏
-   MS08-052 で説明している問題について報告してくださった [Fortinet's FortiGuard Global Security Research Team](http://www.fortinet.com/) の Bing Liu 氏
-   MS08-052 で説明している問題について報告してくださった [NGSSoftware](http://www.ngssoftware.com/) の Peter Winter-Smith 氏および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Ivan Fratric 氏
-   MS08-052 で説明している問題について報告してくださった [Assurent Secure Technologies の Vulnerability Research Team](http://www.assurent.com/)
-   MS08-052 で説明している問題について報告してくださった [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー
-   MS08-053 で説明している問題について [Bach Khoa Internetwork Security Center (BKIS) Hanoi University of Technology (Vietnam)](http://security.bkis.vn/) と共に報告してくださった Nguyen Minh Duc 氏および Le Manh Tung 氏
-   MS08-055 で説明している問題について報告してくださった [Insomnia Security](http://www.insomniasec.com/) の Brett Moore 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx) までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2008/09/10: このセキュリティ情報ページを公開しました。
-   2008/09/13: このセキュリティ情報ページを更新し、Microsoft Office Project 2002 Service Pack 2、Microsoft Office 2003 のすべての Office Viewer ソフトウェアおよび 2007 Microsoft Office System のすべての Office Viewer ソフトウェアを「影響を受けるソフトウェア」に追加しました。
-   2008/09/18: このセキュリティ情報ページを更新し、準備中であった「はがきスタジオ」のセキュリティ更新プログラムが利用可能になったことをお知らせしました。また、「影響を受けるソフトウェア」の一覧にある Microsoft Office Project 2002 Service Pack 2 を Microsoft Office Project 2002 Service Pack 1 に変更しました。これは名称のみの変更です。バイナリまたは検出への変更はありません。
-   2008/10/30: MS08-052 の影響を受けるソフトウェアから Microsoft Visio 2003 Viewer、Microsoft Visio 2007 Viewer、および Microsoft Visio 2007 Viewer Service Pack 1 を削除しました。
-   2008/12/11: MS08-052 の影響を受けるソフトウェアに Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1、Microsoft Expression Web および Microsoft Expression Web 2、Microsoft Office Groove Server 2007 および Microsoft Office Groove Server 2007 Service Pack 1 を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
