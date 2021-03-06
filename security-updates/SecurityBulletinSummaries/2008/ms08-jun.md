---
TOCTitle: 'MS08-JUN'
Title: 2008 年 6 月のセキュリティ情報
ms:assetid: 'ms08-jun'
ms:contentKeyID: 61229652
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-jun(v=Security.10)'
---

 

2008 年 6 月のセキュリティ情報
==============================

公開日: 2008年6月11日 | 最終更新日: 2009年4月2日

**バージョン:** 1.0

絵でみるセキュリティ情報
------------------------

 
[MS08-030 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-030e.mspx)

[MS08-031 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-031e.mspx)

[MS08-032 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-032e.mspx)

[MS08-033 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-033e.mspx)

[MS08-034 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-034e.mspx)

[MS08-035 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-035e.mspx)

[MS08-036 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-036e.mspx)

このセキュリティ情報は 2008 年 6 月に公開したセキュリティ情報の一覧です。

2008 年 6 月のセキュリティ情報の公開により、2008 年 6 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 6 月 11 日 午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[6 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357221&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 6 月 11 日 の午後 (日本時間) に配信予定です。 詳細は、 「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

緊急 (3)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-030                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Bluetooth スタックの脆弱性により、リモートでコードが実行される (951376)**](http://technet.microsoft.com/security/bulletin/ms08-030)                                                                                                                                                                                                                                                     |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告されたリモートでコードが実行される可能性のある Windows の Bluetooth スタックの脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピュータを完全に制御する可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                              |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                               |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                        |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                           |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-031                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Internet Explorer 用の累積的なセキュリティ更新プログラム (950759)**](http://technet.microsoft.com/security/bulletin/ms08-031)                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された 1 件の脆弱性および公開された 1 件の脆弱性を解決します。非公開で報告された脆弱性については、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、リモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。公開された脆弱性については、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、情報が漏えいする可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                                                                                                                                                                          |
| **影響を受けるソフトウェア** | **Microsoft Windows, Internet Explorer.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-033                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**DirectX の脆弱性により、リモートでコードが実行される (951698)**](http://technet.microsoft.com/security/bulletin/ms08-033)                                                                                                                                                                                                                                                                                                                                 |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された 2 件の脆弱性を解決します。これらの脆弱性で、特別な細工がメディア ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                                          |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                             |

重要 (3)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-034                                                                                                                                                                                                                                                                                                                                                       |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**WINS の脆弱性により、特権が昇格される (948745)**](http://technet.microsoft.com/security/bulletin/ms08-034)                                                                                                                                                                                                                                                                                  |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された Windows Internet Name Service (WINS) に存在する特権が昇格する脆弱性を解決します。攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                  |
| **脆弱性の影響**             | 特権の昇格                                                                                                                                                                                                                                                                                                                                                                                     |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                            |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                               |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-035                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Active Directory の脆弱性により、サービス拒否が起こる (953235)**](http://technet.microsoft.com/security/bulletin/ms08-035)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows 2000 Server, Windows Server 2003, および Windows Server 2008 上の Active Directory、Windows XP Professional および Windows Server 2003 にインストールされた Active Directory Application Mode (ADAM)、Windows Server 2008 にインストールされた Active Directory Lightweight Directory Service (AD LDS) に存在する脆弱性を解決します。この脆弱性により、サービス拒否の状態が起こる可能性があります。Windows XP Professional、Windows Server 2003 および Windows Server 2008 でこの脆弱性が悪用されるには、有効なログオンの資格情報を所有することが攻撃者にとっての必要条件となります。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピュータが応答を停止する、または自動的に再起動する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **脆弱性の影響**             | サービス拒否                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-036                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Pragmatic General Multicast (PGM) の脆弱性により、サービス拒否が起こる (950762)**](http://technet.microsoft.com/security/bulletin/ms08-036)                                                                                                                                                                                                                                                                                                                            |
| **概要**                     | このセキュリティ更新プログラムは、特別に細工された PGM パケットを受信するとサービス拒否の状態が起こる非公開で報告された 2 件の Pragmatic General Multicast (PGM) プロトコルの脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピュータが応答を停止する、または自動的に再起動する可能性があります。サービス拒否の脆弱性は、コンピュータが応答を停止する影響がありますが、攻撃者がコードを実行したり、特権が昇格されることはない点に注意してください。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                             |
| **脆弱性の影響**             | サービス拒否                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                          |

警告 (1)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-032                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (950760)**](http://technet.microsoft.com/security/bulletin/ms08-032)                                                                                                                                                                                                                                                                                                                                                                                      |
| **概要**                     | このセキュリティ更新プログラムは、一般に報告された 1 件の Microsoft Speech API に存在する脆弱性を解決します。この脆弱性により、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、リモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。このセキュリティ更新プログラムは、BackWeb 製のソフトウエア製品の Kill Bit も含んでいます。 |
| **最大深刻度**               | [警告](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                                                                                                   |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                      |

影響を受けるソフトウェア
------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新 プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場 合、脆弱性の深刻度も記載されています。

**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

#### Windows オペレーティング システムとサーバー

 
<p></p>

<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>警告</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=88990b23-d37f-4d02-a5a3-2ee389ade53c&amp;displaylang=ja">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(重要)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c47cf8a-8100-4d43-855a-f225a3492b19&amp;displaylang=ja">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=65640123-a9e4-455c-a51a-9df28bd2d412&amp;displaylang=ja">DirectX 7.0</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c6a28d45-13cf-48c4-8f89-3417d552e90b&amp;displaylang=ja">DirectX 8.1</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4dc47e04-5e95-4636-a814-3f912d961461&amp;displaylang=ja">DirectX 9.0, DirectX 9.0a, DirectX 9.0b または DirectX 9.0c</a><br />
(緊急)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=cedfd988-232c-4cba-ac65-beb54b8946e0&amp;displaylang=ja">Microsoft Windows 2000 Service Pack 4</a><br />
(警告)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows 2000 Server Service Pack 4</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=aa8aa79f-c2cc-440c-9e5c-089143e6f814&amp;displaylang=ja">Microsoft Windows 2000 Server Service Pack 4</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=53438880-9ea9-4975-9b85-2a1d3d232793&amp;displaylang=ja">Active Directory</a><br />
(KB949014)<br />
(重要)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
</tr>
</tbody>
</table>

<p></p>


 
<p></p>

<table style="border:1px solid black;">
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>警告</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2 および Windows XP Service Pack 3</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=980bb421-950f-4825-8039-44cc961a47b8&amp;displaylang=ja">Windows XP Service Pack 2 および Windows XP Service Pack 3</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=cc325017-3a48-4475-90e4-0c79a002fce3&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=fbc31bde-0bf5-490c-96a8-071310d9464a&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7aaa6427-1e22-4566-960c-836a3b9e5f36&amp;displaylang=ja">DirectX 9.0, DirectX 9.0a, DirectX 9.0b または DirectX 9.0c</a><br />
(緊急)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=36b14a81-5979-4e38-9ba3-ed83dfc17adf&amp;displaylang=ja">Windows XP Service Pack 2 および Windows XP Service Pack 3</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2d8957c2-e473-4dca-8d68-19fdaea36e26&amp;displaylang=ja">Windows XP Service Pack 2 および Windows XP Service Pack 3</a><br />
(警告)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional Service Pack 2 および Windows XP Professional Service Pack 3</td>
<td style="border:1px solid black;">(Windows XP Service Pack 2 および Windows XP Service Pack 3 の行をご覧ください。)</td>
<td style="border:1px solid black;">(Windows XP Service Pack 2 および Windows XP Service Pack 3 の行をご覧ください。)</td>
<td style="border:1px solid black;">(Windows XP Service Pack 2 および Windows XP Service Pack 3 の行をご覧ください。)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7d6aec31-cfb4-470c-983e-78c6a3ebabfe&amp;displaylang=ja">ADAM</a><br />
(KB949269)<br />
(警告)</td>
<td style="border:1px solid black;">(Windows XP Service Pack 2 および Windows XP Service Pack 3 の行をご覧ください。)</td>
<td style="border:1px solid black;">(Windows XP Service Pack 2 および Windows XP Service Pack 3 の行をご覧ください。)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=81ab56ca-933f-4974-a393-290a54c30a78&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c8783cfe-9da5-4842-ab3a-1e2be4fafc47&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=19c0ccdc-95c9-4151-96b6-4f49b594ebe0&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e8e7e9d-828d-442c-acac-8d91e80dfb36&amp;displaylang=ja">DirectX 9.0, DirectX 9.0a, DirectX 9.0b または DirectX 9.0c</a><br />
(緊急)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ef2e0b48-1bde-4ccc-8f40-2918c2568b2b&amp;displaylang=ja">ADAM</a><br />
(KB949269)<br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9e9d24ee-8183-428c-8067-168a8d85eaa1&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=62874096-7d17-4116-9795-4756e2fb6dae&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(警告)</td>
</tr>
</tbody>
</table>

<p></p>

 

 
<p></p>

<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>警告</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=286aada6-a358-41f1-b81a-8de39b9f908a&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(警告)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a1ae9ad2-8329-4c96-b950-7534b3287eaa&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2274ecb2-2802-47e2-84fd-6621fcb17758&amp;displaylang=ja">DirectX 9.0, DirectX 9.0a, DirectX 9.0b または DirectX 9.0c</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=08fc90d5-23aa-4327-8aef-16bc5170769d&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a4aed117-3c76-4d80-b50e-8e07e2ef2f7d&amp;displaylang=ja">Active Directory</a><br />
(KB949014)<br />
(警告)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=0a983ffb-4f5a-4b78-9bf5-813dcc5df8d3&amp;displaylang=ja">ADAM</a><br />
(KB949269)<br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1e8e2faf-009f-403b-a5fe-a47cf014db3a&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=dadead99-09cb-4f2b-850d-e98a627cb9f8&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(注意)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6604569a-3db0-47e7-bd30-7dfba8145386&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(警告)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=fb0c70b4-ce9f-43d6-875a-3cfd0d3a2681&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5ba63bb7-ed6d-4c59-88b3-456eda07e190&amp;displaylang=ja">DirectX 9.0, DirectX 9.0a, DirectX 9.0b または DirectX 9.0c</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=71675ae8-d60a-4834-b358-2d8e761e62fc&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8298a6e4-d3e2-48ea-ac29-aa4dc5a8ec77&amp;displaylang=ja">Active Directory</a><br />
(KB949014)<br />
(警告)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=334252db-4a7a-4161-bb71-2a20c0b5bd93&amp;displaylang=ja">ADAM</a><br />
(KB949269)<br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=78bf92d8-63c4-4596-8425-8fcfea7f5582&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=84f9b533-b0cb-46d1-b4a8-5c9469abbd22&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(注意)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0262beb8-1eb5-4c2d-a50a-0c6c6e0c1f61&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(警告)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=28d2913c-1c6b-4671-9892-de08698cd5a6&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=be71c002-2f64-49e9-9f4b-ba99c4f3caf6&amp;displaylang=ja">DirectX 9.0, DirectX 9.0a, DirectX 9.0b または DirectX 9.0c</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=87affdc9-d9fe-413c-af30-f3d3b671ec72&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems and Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f6bf4b85-b91d-4378-a356-cd11f12cbbfd&amp;displaylang=ja">Active Directory</a><br />
(KB949014)<br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5b7e94fa-22ed-4f7c-b452-647b2e620113&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems and Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ac35ce19-d761-4529-9f55-1e1b5b2447ad&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems and Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(注意)</td>
</tr>
</tbody>
</table>

<p></p>

 

 
<p></p>

<table style="border:1px solid black;">
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>警告</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista および Windows Vista Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6524debe-be50-44d1-8543-af0bfaf086ad&amp;displaylang=ja">Windows Vista および Windows Vista Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6d68b39d-157f-4c3d-ac76-bc5a9386db59&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4d4b305b-57f8-448d-92fa-3dcdd1f42ed7&amp;displaylang=ja">DirectX 10.0</a><br />
(緊急)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ef2d2a4b-4831-41be-b5d0-8df5b01fd205&amp;displaylang=ja">Windows Vista および Windows Vista Service Pack 1</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4af6575e-b061-45a6-b3d8-ecb32d76b2d3&amp;displaylang=ja">Windows Vista および Windows Vista Service Pack 1</a><br />
(警告)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6adee8b9-3455-4f3b-8bdd-2585c8ff83b8&amp;displaylang=ja">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4cf92235-861e-4b74-bee3-8e977c8688d9&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b040cfad-2290-44f4-8f5a-5d1ed98a7265&amp;displaylang=ja">DirectX 10.0</a><br />
(緊急)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0839fcf4-85ca-445e-896b-f634b10b6700&amp;displaylang=ja">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=67576acb-9cb6-4c76-9a72-dc5e5556b658&amp;displaylang=ja">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</a><br />
(警告)</td>
</tr>
</tbody>
</table>

<p></p>

 

 
<p></p>

<table style="border:1px solid black;">
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-030"><strong>MS08-030</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-031"><strong>MS08-031</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-033"><strong>MS08-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-034"><strong>MS08-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-035"><strong>MS08-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-036"><strong>MS08-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-032"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>警告</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 for 32-bit Systems</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a8922e7e-9264-4e09-b8ad-c5420fed8690&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(警告)<strong>\*\*</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0c495f8-2a35-4638-a635-1e55dd15e062&amp;displaylang=ja">DirectX 10.0</a><br />
(緊急)<strong>\*\*</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2981156e-2e2f-469e-91be-da127d50f3fc&amp;displaylang=ja">Active Directory</a><br />
(KB949014)<br />
(警告)<strong>\*</strong><br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=2981156e-2e2f-469e-91be-da127d50f3fc&amp;displaylang=ja">AD LDS</a><br />
(KB949014)<br />
(警告)<strong>\*</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0466a6e7-fdca-4647-af62-449e5f20d1e4&amp;displaylang=ja">Windows Server 2008 for 32-bit Systems</a><br />
(警告)<strong>\*\*</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8a507fba-8c93-4952-91e4-98e9e7affbd2&amp;displaylang=ja">Windows Server 2008 for 32-bit Systems</a><br />
(注意)<strong>\*\*\*</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008 for x64-based Systems</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=05b0e838-24d7-4387-b069-2604bbcc43b9&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(警告)<strong>\*\*</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0b70fc2e-4e80-4ae8-8682-41ea04c24e4e&amp;displaylang=ja">DirectX 10.0</a><br />
(緊急)<strong>\*\*</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b5cfe6f4-c5ba-4be9-a6b8-9381c40c85aa&amp;displaylang=ja">Active Directory</a><br />
(KB949014)<br />
(警告)<strong>\*</strong><br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=b5cfe6f4-c5ba-4be9-a6b8-9381c40c85aa&amp;displaylang=ja">AD LDS</a><br />
(KB949014)<br />
(警告)<strong>\*</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=304898e6-21a7-476f-b9ed-7ac0d88a91e2&amp;displaylang=ja">Windows Server 2008 for x64-based Systems</a><br />
(警告)<strong>\*\*</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1a11499d-a008-407f-9084-a5189fa27015&amp;displaylang=ja">Windows Server 2008 for x64-based Systems</a><br />
(注意)<strong>\*\*\*</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 for Itanium-based Systems</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=640e1865-ebcc-4d69-a770-fd360020da1e&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=80ec83e0-cfb8-4a5e-9254-6679a7225b83&amp;displaylang=ja">DirectX 10.0</a><br />
(緊急)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8907783b-e3fe-40b2-9fc8-4937e7d58b7e&amp;displaylang=ja">Windows Server 2008 for Itanium-based Systems</a><br />
(警告)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=59b1689c-e723-4d87-973e-4beac107a6f7&amp;displaylang=ja">Windows Server 2008 for Itanium-based Systems</a><br />
(注意)</td>
</tr>
</tbody>
</table>

<p></p>

 

**\*Windows Server 2008 Server Core は、この脆弱性の影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度が適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 の特定のエディションには適用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**\*\*Windows Server 2008 Server Core は、この脆弱性の影響を受けません。** Windows Server 2008 のサポートされているエディションは、Server Core インストール オプションが使用されてインストールされている場合、この脆弱性の影響を受けません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 の特定のエディションには適用できないことに注意してください。詳細は、[Server コアのインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**\*\*\*Windows Server 2008 Server Core は、この脆弱性の影響を受けません。**この更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 をインストールした場合、これらの脆弱性の影響を受けるファイルがシステムに存在していたとしても、サポートされているエディションの Windows Server 2008 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションに関する詳細情報は、[Server Core](http://msdn.microsoft.com/library/ms723891(vs.85).aspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ 更新プログラムを管理してください。詳細情報は、 [TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では 、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュ リティ更新プログラムを入手する」をクリックすることによってもご 覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つ けることができます。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer** **および** **Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ 確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、 Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、および SQL Server 2000 用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   [Microsoft Knowledge Base Article 894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): 2008 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)か らダウンロードすることができます。「security update」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれ ます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリース の ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについ てそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS08-031 に説明されている問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Sebastian Apelt 氏、Peter Vreugdenhil 氏および匿名のリサーチャー
-   MS08-033 に説明されている問題について報告してくださった [IBM Internet Security Systems X-Force](http://xforce.iss.net/)のリサーチャーである Mark Dowd 氏
-   MS08-033 に説明されている問題について報告してくださった [Tipping Point](http://www.tippingpoint.com/) に協力している匿名のリサーチャーおよび [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS08-035 に説明されている問題について報告してくださった [Securify](http://www.securify.com/) の Alex Matthews 氏および John Guzik 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、 [マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフト では、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。（Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2008/06/11: このセキュリティ情報ページを公開しました。
-   2008/06/12: MS08-030、MS08-031、MS08-032、MS08-033、および MS08-036 に関する Windows XP Service Pack 2 および Windows XP Service Pack 3 のエントリを明確にするため、「影響を受けるソフトウェア」の Windows XP の表を更新しました。
-   2008/07/17: MS08-033 の影響を受けるソフトウェアとして DirectX 9.0a を追加しました。
-   2009/04/02: MS08-032 を更新し、Windows Server 2008 の Server Core インストールはこのセキュリティ情報で説明している脆弱性による影響は受けませんが、更新プログラムは提供されることを説明しました。今回の更新は情報のみの変更です。Server Core インストールを使用して Windows Server 2008 をインストールされたお客様はこの更新プログラムをインストールする必要はありません。

*Built at 2014-04-18T01:50:00Z-07:00*
