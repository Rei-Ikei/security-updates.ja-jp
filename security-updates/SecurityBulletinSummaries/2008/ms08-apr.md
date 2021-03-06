---
TOCTitle: 'MS08-APR'
Title: 2008 年 4 月のセキュリティ情報
ms:assetid: 'ms08-apr'
ms:contentKeyID: 61229646
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-apr(v=Security.10)'
---

 

2008 年 4 月のセキュリティ情報
==============================

公開日: 2008年4月9日 | 最終更新日: 2009年2月19日

**バージョン:** 1.0

注: 今月よりお客様のフィードバックを反映し、「影響を受けるソフトウェア」のフォーマットおよび「MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム」の内容を変更しました。

絵でみるセキュリティ情報
------------------------

 
[MS08-018 : Project の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-018e.mspx)

[MS08-019 : Visio の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-019e.mspx)

[MS08-020 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-020e.mspx)

[MS08-021 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-021e.mspx)

[MS08-022 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-022e.mspx)

[MS08-023 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-023e.mspx)

[MS08-024 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-024e.mspx)

[MS08-025 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-025e.mspx)

このセキュリティ情報は 2008 年 4 月に公開したセキュリティ情報の一覧です。

2008 年 4 月のセキュリティ情報の公開により、2008 年 4 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 4 月 9 日 午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[4 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 4 月 9 日 の午後 (日本時間) に配信予定です。 詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

これはマイクロソフトが 2008 年 4 月に公開を予定しているセキュリティ情報の事前通知です。今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (5)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-018                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-018 Microsoft Project の脆弱性により、リモートでコードが実行される (950183)](http://technet.microsoft.com/security/bulletin/ms08-018)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **概要**                     | この深刻度が「緊急」のセキュリティ更新プログラムは、特別に細工された Project ファイルをユーザーが表示した場合、リモートでコードが実行される可能性がある Microsoft Project に存在する非公開で報告された脆弱性を解決します。攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。この更新プログラムは、再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **影響を受けるソフトウェア** | **Microsoft Office.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-021                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-021 GDI の脆弱性により、リモートでコードが実行される (948590)](http://technet.microsoft.com/security/bulletin/ms08-021)                                                                                                                                                                                                                                                                                                                                                                      |
| **概要**                     | この深刻度セキュリティ更新プログラムは、非公開で報告された 2 件の GDI に存在する脆弱性を解決します。これらの脆弱性で、特別な細工がされた EMF または WMF 画像ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは、コンピュータを再起動する必要があります。                                                                                                                                                                                                                                                                                            |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-022                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-022 VBScript および JScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (944338)](http://technet.microsoft.com/security/bulletin/ms08-022)                                                                                                                                                                                                                          |
| **概要**                     | このセキュリティ更新プログラムは、Windows の VBScript および JScript スクリプト エンジンに存在する 非公開で報告された脆弱性を解決します。攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                 |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                  |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは、コンピュータを再起動する必要があります。                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                           |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-023                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-023 ActiveX Kill Bit 用のセキュリティ更新プログラム (948881)](http://technet.microsoft.com/security/bulletin/ms08-023)                                                                                                                                                                                                                                                                                                                                                                    |
| **概要**                     | このセキュリティ更新プログラムは 1 件の非公開で報告されたマイクロソフト製品の脆弱性を解決します。この更新プログラムには Yahoo! Music Jukebox 製品用の Kill Bit も含まれています。この脆弱性により、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、リモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは、再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                               |
| **影響を受けるソフトウェア** | **Microsoft Windows, Internet Explorer.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                          |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-024                                                                                                                                                                                                                                                                                                                                                    |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-024 Internet Explorer 用の累積的なセキュリティ更新プログラム (947864)](http://technet.microsoft.com/security/bulletin/ms08-024)                                                                                                                                                                                                                                                       |
| **概要**                     | このセキュリティ更新プログラムは 1 件の非公開で報告された脆弱性を解決します。この脆弱性により、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、リモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                               |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは、コンピュータを再起動する必要があります。                                                                                                                                                                                     |
| **影響を受けるソフトウェア** | **Microsoft Windows, Internet Explorer.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                      |

重要 (3)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-019                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-019 Microsoft Visio の脆弱性により、リモートでコードが実行される (949032)](http://technet.microsoft.com/security/bulletin/ms08-019)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **概要**                     | このセキュリティ更新プログラムは、特別に細工された Visio ファイルをユーザーが表示した場合、リモートでコードが実行される可能性がある Microsoft Office Visio に存在する非公開で報告された脆弱性を解決します。攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。この更新プログラムは、再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **影響を受けるソフトウェア** | **Microsoft Office.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-020                                                                                                                                                                                                                                                          |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-020 DNS クライアントの脆弱性により、なりすましが行われる (945553)](http://technet.microsoft.com/security/bulletin/ms08-020)                                                                                                                                                                 |
| **概要**                     | この更新プログラムは非公開で報告された脆弱性を解決します。Windows DNS クライアントになりすましの脆弱性が存在し、攻撃者は特別に細工した応答をDNS リクエストに送信し、これにより「なりすまし攻撃」が行われる、または正規の場所からインターネット トラフィックがリダイレクトされる可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                     |
| **脆弱性の影響**             | なりすまし                                                                                                                                                                                                                                                                                        |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは、コンピュータを再起動する必要があります。                                                                                           |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                               |

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-025                                                                                                                                                                                                                                                                                                          |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS08-025 Windows カーネルの脆弱性により、特権が昇格される (941693)](http://technet.microsoft.com/security/bulletin/ms08-025)                                                                                                                                                                                                                     |
| **概要**                     | この深刻度「重要」のセキュリティ更新プログラムは、非公開で報告された Windows カーネルの脆弱性を解決します。ローカルの攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                     |
| **脆弱性の影響**             | 特権の昇格                                                                                                                                                                                                                                                                                                                                        |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは、コンピュータを再起動する必要があります。                                                                                                                                           |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                               |

影響を受けるソフトウェア
------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場合、脆弱性の深刻度も記載されています。

**注** **:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

#### オペレーティング システムとコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2&amp;displaylang=ja">Microsoft Windows 2000 Service Pack 4</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e&amp;displaylang=ja">VBScript 5.1 および JScript 5.1</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e&amp;displaylang=ja">VBScript 5.6 および JScript 5.6</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc&amp;displaylang=ja">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(緊 急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f&amp;displaylang=ja">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b051ae04-fe81-440d-9136-d6b239ca954e&amp;displaylang=ja">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e&amp;displaylang=ja">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=41326ade-96b6-47ce-9291-d4e3039471c4&amp;displaylang=ja">Microsoft Windows 2000 Service Pack 4</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224&amp;displaylang=ja">Microsoft Windows 2000 Service Pack 4</a><br />
( 重要)</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a&amp;displaylang=ja">Windows XP Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0124698-3b94-4474-9473-22a2f39a4a56&amp;displaylang=ja">VBScript 5.6 および JScript 5.6</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10&amp;displaylang=ja">Windows XP Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=36c641ad-953f-4b09-ba1c-9c383295e180&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=e771efe8-8881-4f23-b5b0-15651a390ba9&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48&amp;displaylang=ja">Windows XP Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178&amp;displaylang=ja">Windows XP Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652&amp;displaylang=ja">VBScript 5.6 および JScript 5.6</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=01400970-df68-4daf-aa39-2fc4f969974c&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=85beacc0-8ca2-4ded-9c24-23348d05c735&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9364bf81-6505-4788-958d-a4bd29dc98ad&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a&amp;displaylang=ja">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2</a><br />
(重要)</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3&amp;displaylang=ja">VBScript 5.6 および JScript 5.6</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(注意)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=214bd8f5-6eb2-414c-b013-c516a306d692&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d3b855a6-4648-4771-826d-11a151828eac&amp;displaylang=ja">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e3dde449-e062-4ce0-a9f4-433bff23e224&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=12cefefc-8553-4dca-9850-c653371de61e&amp;displaylang=ja">VBScript 5.6 および JScript 5.6</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(注意)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fd123394-a5d6-4b55-be74-2938f52ce922&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=320fd100-35e1-4345-9399-796393235cbc&amp;displaylang=ja">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium based Systems</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium based Systems</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21&amp;displaylang=ja">VBScript 5.6 および JScript 5.6</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(注意)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2&amp;displaylang=ja">Microsoft Internet Explorer 6</a><br />
(緊急)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d&amp;displaylang=ja">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium based Systems</a><br />
(重要)</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista および Windows Vista Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5&amp;displaylang=ja">Windows Vista および Windows Vista Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d7f14001-7f42-4ca0-9193-cdf061179b59&amp;displaylang=ja">Windows Vista および Windows Vista Service Pack 1</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d4e24966-6530-463a-9ee2-f6a9d000f998&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87&amp;displaylang=ja">Windows Vista</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9640cd8b-d749-4ddd-8af9-b298cebed969&amp;displaylang=ja">Windows Vista および Windows Vista Service Pack 1</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6&amp;displaylang=ja">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</a><br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d33462b6-7391-482d-babe-fb4cd0beaa21&amp;displaylang=ja">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=295cf8f2-265e-4570-b708-21033337fe05&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=73f3a234-3973-4467-be7e-69efa7ee978c&amp;displaylang=ja">Windows Vista x64 Edition</a><br />
(重要)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04&amp;displaylang=ja">Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1</a><br />
(重要)</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 for 32-bit Systems</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=006d5c47-53e6-4ee1-932c-497611804938&amp;displaylang=ja">Windows Server 2008 for 32-bit Systems</a><br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=95691924-2813-4a86-9e11-99d853f8e606&amp;displaylang=ja">Windows Server 2008 for 32-bit Systems</a><br />
(注意)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b&amp;displaylang=ja">Windows Internet Explorer 7</a>\*<br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4497333c-9418-4b91-83dc-0155735421c0&amp;displaylang=ja">Windows Server 2008 for 32-bit Systems</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008 for x64-based Systems</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8909f144-655b-4f07-916f-fd967f1efb2b&amp;displaylang=ja">Windows Server 2008 for x64-based Systems</a><br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=920ae29b-19d0-4089-ac79-f2da824a2256&amp;displaylang=ja">Windows Server 2008 for x64-based Systems</a><br />
(注意)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=93e9f52a-c7d0-4033-9c12-740665a219af&amp;displaylang=ja">Windows Internet Explorer 7</a>\*<br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda&amp;displaylang=ja">Windows Server 2008 for x64-based Systems</a><br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 for Itanium-based Systems</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7&amp;displaylang=ja">Windows Server 2008 for Itanium-based Systems</a><br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f&amp;displaylang=ja">Windows Server 2008 for Itanium-based Systems</a><br />
(注意)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05&amp;displaylang=ja">Windows Internet Explorer 7</a><br />
(緊急)</td>
<td style="border:1px solid black;">-</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce&amp;displaylang=ja">Windows Server 2008 for Itanium-based Systems</a><br />
(重要)</td>
</tr>
</tbody>
</table>

<p></p>

 

\* **Windows Server 2008 Server Core インストールは影響を受けません。**これらの更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 をインストールした場合、これらの脆弱性の影響を受けるファイルがシステムに存在していたとしても、サポートされているエディションの Windows Server 2008 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

#### Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリ ティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-018"><strong>MS08-018</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2000 Service Release 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fbe46241-b9da-40c6-803d-42eb6234be77&amp;displaylang=ja">Project 2000 Service Release 1</a><br />
(KB949043)<br />
(緊急)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Project 2002 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=07a90718-6597-426d-9dca-a336d60c01b8&amp;displaylang=ja">Project 2002 Service Pack 1</a><br />
(KB949005)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4&amp;displaylang=ja">Project 2003 Service Pack 2</a><br />
(KB948962)<br />
(重要)</td>
</tr>
</tbody>
</table>

<p></p>

 

 
<p></p>

<table style="border:1px solid black;">
<caption>Microsoft Visio</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリ ティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-019"><strong>MS08-019</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Visio 2002 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964&amp;displaylang=ja">Visio 2002 Service Pack 2</a><br />
(KB947896)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Visio 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631&amp;displaylang=ja">Visio 2003 Service Pack 2</a><br />
(KB947650)<br />
(重要 )</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Visio 2003 Service Pack 3</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631&amp;displaylang=ja">Visio 2003 Service Pack 3</a><br />
(KB947650)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Visio 2007</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e&amp;displaylang=ja">Visio 2007</a><br />
(KB947590)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Visio 2007 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e&amp;displaylang=ja">Visio 2007 Service Pack 1</a><br />
(KB947590)<br />
(重要)</td>
</tr>
</tbody>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet Security センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [Security At Home](http://www.microsoft.com/japan/athome/security) をご覧ください。この情報は「最新のセキュ リティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security\_patch」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の 関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに 役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer** **および** **Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**注意:** 2007 年 10 月 9 日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルは更新されていません。この日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルに新しいセキュリティ更新プログラムは追加されていません。また、新しいバージョンの Enterprise Scan Tool はリリースされません。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、およ び SQL Server 2000 用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新 プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用の お客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供さ れた更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコン ピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開する予定です。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   [Microsoft Knowledge Base Article 894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): 2008 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)か らダウンロードすることができます。「security update」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS08-018 に説明されている問題について報告してくださった韓国の [National Cyber Security Center](http://www.ncsc.go.kr/kn-cert/)
-   MS08-019 に説明されている問題について報告してくださった匿名の発見者
-   MS08-019 に説明されている問題について報告してくださった匿名の発見者
-   MS08-020 に説明されている問題について報告してくださった [Trusteer](http://www.trusteer.com/) の Amit Klein 氏
-   MS08-020 に説明されている問題について報告してくださった [Scanit](http://www.scanit.be/) の Alla Berzroutchko 氏
-   MS08-020 に説明されている問題について報告してくださった [Nominet UK](http://www.nominet.org.uk/) の Roy Arends 氏
-   MS08-021 に説明されている問題について報告してくださった [iDefense Labs](http://labs.idefense.com/) の Jun Mao 氏
-   MS08-021 に説明されている問題について報告してくださった [Zero Day Initiative](http://www.zerodayinitiative.com/) の Sebastian Apelt 氏
-   MS08-021 に説明されている問題について報告してくださった [SkyRecon](http://www.skyrecon.com/) の Thomas Garnier 氏
-   MS08-021 に説明されている問題について報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS08-022 に説明されている問題について報告してくださった [Symantec](http://www.symantec.com/) の Peter Ferrie 氏
-   MS08-023 に説明されている問題について報告してくださった [iDefense VCP](http://labs.idefense.com/vcp/) の 匿名のリサーチャー
-   MS08-024 に説明されている問題について報告してくださった [Secunia](http://secunia.com/) の Carsten Eiram 氏
-   MS08-025 に説明されている問題について報告してくださった Thomas Garnier 氏

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報 の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または 書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連 会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一 切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   2008/04/09: このセキュリティ情報ページを公開しました。
-   2008/04/10: マイクロソフト セキュリティ情報 MS08-018 の「概要」を更新しました。
-   2008/04/17: 「影響を受けるソフトウェア」の「Office スイートおよびソフトウェア」内の表を明確にしました。
-   2009/02/19: Windows Server 2008 for 32-bit Systems および Windows Server 2008 for x64-based Systems の Server Core が影響を受けないことについての注釈を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
