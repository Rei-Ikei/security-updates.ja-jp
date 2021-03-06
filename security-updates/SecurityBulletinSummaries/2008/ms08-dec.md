---
TOCTitle: 'MS08-DEC'
Title: 2008 年 12 月のセキュリティ情報
ms:assetid: 'ms08-dec'
ms:contentKeyID: 61229648
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-dec(v=Security.10)'
---

 

2008 年 12 月のセキュリティ情報
===============================

公開日: 2008年12月10日 | 最終更新日: 2009年4月30日

**バージョン:** 1.0

絵でみるセキュリティ情報
------------------------

 
[MS08-078 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-078e.mspx)

[MS08-070 : Office と開発ツールの重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-070e.mspx)

[MS08-071 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-071e.mspx)

[MS08-072 : Word の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-072e.mspx)

[MS08-073 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-073e.mspx)

[MS08-074 : Excel の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-074e.mspx)

[MS08-075 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-075e.mspx)

[MS08-076 : Windows および Windows Media Player の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-076e.mspx)

[MS08-077 : SharePoint の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-077e.mspx)

このセキュリティ情報は 2008 年 12 月に公開したセキュリティ情報の一覧です。

2008 年 12 月 18 日に緊急リリースしました[マイクロソフト セキュリティ情報 MS08-078](http://technet.microsoft.com/security/bulletin/ms08-078) に関する情報を追加しました。

2008 年 12 月のセキュリティ情報の公開により、2008 年 12 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2008 年 12 月 10 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 12 月 10 日 午前 11 ：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[12 月のセキュリティ 情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトは MS08-078 の定例外の緊急セキュリティ情報に関するお客様からの質問を解決するため、2008 年 12 月 17 日 午後 1：00 (太平洋標準時刻、米国およびカナダ) と 2008 年 12 月 18 日 午前 11：00 (太平洋標準時刻、米国およびカナダ) の 2 回 Webcast を行う予定です。[12 月 17 日の Webcast (英語)](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us)、[12 月 18 日の Webcast (英語)](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us) に登録する。詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

 
 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID 番号</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;"><strong>GDI の脆弱性により、リモートでコードが実行される (956802)</strong><br />
<br />
この深刻度セキュリティ更新プログラムは、非公開で報告された 2 件の GDI に存在する脆弱性を解決します。これらの脆弱性のいずれかが悪用された場合、ユーザーが特別な細工がされた WMF 画像ファイルを開くと、リモートでコードが実行される可能性があります。これらの脆弱性を攻撃者が悪用した場合、影響を受けるコンピュータが完全に制御される可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;"><strong>Windows Search の脆弱性により、リモートでコードが実行される (959349)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Windows Search に存在する脆弱性を解決します。これらの脆弱性で、特別な細工がされた保存された検索ファイルがWindows エクスプローラーで開かれ、保存された場合、またはユーザーが特別な細工がされた 検索 URL をクリックした場合、リモートでコードが実行される可能性があります。これらの脆弱性を攻撃者が悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (958215)</strong><br />
<br />
この累積的な更新プログラムは非公開で報告された 4 つの脆弱性を解決します。これらの脆弱性により、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、リモートでコードが実行される可 能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-078">MS08-078</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用のセキュリティ更新プログラム (960714)</strong><br />
<br />
このセキュリティ更新プログラムは一般に公開された 1 件の脆弱性を解決します。この脆弱性では、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;"><strong>Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349)</strong><br />
<br />
このセキュリティ更新プログラムは 5 件の非公開で報告された脆弱性および 1 件の一般に公開された Microsoft Visual Basic 6.0 ランタイム拡張ファイル の ActiveX コントロールの脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工されたコンテンツが含まれる Web サイトを閲覧した場合、リモートでコードが実行される可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft 開発者用ツールおよびソフトウェア, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word の脆弱性により、リモートでコードが実行される (957173)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 8 件の Microsoft Office Word および Microsoft Office Outlookの脆弱性を解決します。この脆弱性では、ユーザーが特別に細工された Word またはリッチ テキスト形式 (RTF) ファイルを表示した場合、リモートでコードが実行される可能性があります。これらの脆弱性を攻撃者が悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel の脆弱性により、リモートでコードが実行される (959070)</strong><br />
<br />
このセキュリティ更新プログラムは、特別な細工がされた Excel ファイルをユーザーが表示した場合、リモートでコードが実行される可能性がある Microsoft Office Excel に存在する非公開で報告されたいくつかの脆弱性を解決します。これらの脆弱性を攻撃者が悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-077">MS08-077</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office SharePoint Server の脆弱性により、特権が昇格される (957175)</strong><br />
<br />
この更新プログラムは非公開で報告された脆弱性を解決します。攻撃者が SharePoint サイト上の管理 URL をブラウズすることにより認証を無視した場合、この脆弱性により特権が昇格される可能性があります。特権が昇格される攻撃が行われると、サービス拒否または情報の漏えいが引き起こされる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;"><strong>Windows Media コンポーネントの脆弱性により、リモートでコードが実行される (959807)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Windows Media コンポーネントに存在する脆弱性を解決します。これらの中で最も深刻な脆弱性により、リモートでコードが実行される可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細情報は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報番号                                                | セキュリティ情報タイトル                                                                                             | CVE ID                                                                           | Exploitability Index の評価                                                                                                                | 注意事項                                                                                                                                                                                                                         |  
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS08-070](http://technet.microsoft.com/security/bulletin/ms08-070) | Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349) | [CVE-2008-3704](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | 安定して動作する攻撃コードが一般に公開されています。                                                                                                                                                                             |  
| [MS08-070](http://technet.microsoft.com/security/bulletin/ms08-070) | Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349) | [CVE-2008-4252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-070](http://technet.microsoft.com/security/bulletin/ms08-070) | Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349) | [CVE-2008-4256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-070](http://technet.microsoft.com/security/bulletin/ms08-070) | Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349) | [CVE-2008-4253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-070](http://technet.microsoft.com/security/bulletin/ms08-070) | Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349) | [CVE-2008-4254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-070](http://technet.microsoft.com/security/bulletin/ms08-070) | Visual Basic 6.0 ランタイム拡張ファイル (ActiveX コントロール) の脆弱性により、リモートでコードが実行される (932349) | [CVE-2008-4255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | Windows 2000 が最も高いリスクにさらされます。Windows XP SP2、Windows Server 2003 SP1、および以降のオペレーティングシステムは、ヒープ保護機能が改善されているため、攻撃コードの影響を受けないと思われます。                       |  
| [MS08-071](http://technet.microsoft.com/security/bulletin/ms08-071) | GDI の脆弱性により、リモートでコードが実行される (956802)                                                            | [CVE-2008-3465](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-071](http://technet.microsoft.com/security/bulletin/ms08-071) | GDI の脆弱性により、リモートでコードが実行される (956802)                                                            | [CVE-2008-2249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                            | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4024](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4025](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4837](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-072](http://technet.microsoft.com/security/bulletin/ms08-072) | Microsoft Word の脆弱性により、リモートでコードが実行される (957173)                                                 | [CVE-2008-4031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                            | (なし)                                                                                                                                                                                                                           |  
| [MS08-073](http://technet.microsoft.com/security/bulletin/ms08-073) | Internet Explorer 用の累積的なセキュリティ更新プログラム (958215)                                                    | [CVE-2008-4258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-073](http://technet.microsoft.com/security/bulletin/ms08-073) | Internet Explorer 用の累積的なセキュリティ更新プログラム (958215)                                                    | [CVE-2008-4259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-073](http://technet.microsoft.com/security/bulletin/ms08-073) | Internet Explorer 用の累積的なセキュリティ更新プログラム (958215)                                                    | [CVE-2008-4261](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-073](http://technet.microsoft.com/security/bulletin/ms08-073) | Internet Explorer 用の累積的なセキュリティ更新プログラム (958215)                                                    | [CVE-2008-4260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-074](http://technet.microsoft.com/security/bulletin/ms08-074) | Microsoft Office Excel の脆弱性により、リモートでコードが実行される (959070)                                         | [CVE-2008-4265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-074](http://technet.microsoft.com/security/bulletin/ms08-074) | Microsoft Office Excel の脆弱性により、リモートでコードが実行される (959070)                                         | [CVE-2008-4266](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-074](http://technet.microsoft.com/security/bulletin/ms08-074) | Microsoft Office Excel の脆弱性により、リモートでコードが実行される (959070)                                         | [CVE-2008-4264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-075](http://technet.microsoft.com/security/bulletin/ms08-075) | Windows Search の脆弱性により、リモートでコードが実行される (959349)                                                 | [CVE-2008-4269](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-075](http://technet.microsoft.com/security/bulletin/ms08-075) | Windows Search の脆弱性により、リモートでコードが実行される (959349)                                                 | [CVE-2008-4268](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | (なし)                                                                                                                                                                                                                           |  
| [MS08-076](http://technet.microsoft.com/security/bulletin/ms08-076) | Windows Media コンポーネントの脆弱性により、リモートでコードが実行される (959807)                                    | [CVE-2008-3009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | 動作に一貫性のある攻撃コ―ドが作られる可能性があります。しかしながら、実質的な攻撃のシナリオが制限されているため、被害を伴う攻撃につながらないと思われます。                                                                      |  
| [MS08-076](http://technet.microsoft.com/security/bulletin/ms08-076) | Windows Media コンポーネントの脆弱性により、リモートでコードが実行される (959807)                                    | [CVE-2008-3010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | 動作に一貫性のある攻撃コ―ドが作られる可能性があります。しかしながら、実質的な攻撃のシナリオが制限されているため、被害を伴う攻撃につながらないと思われます。                                                                      |  
| [MS08-077](http://technet.microsoft.com/security/bulletin/ms08-077) | Microsoft Office SharePoint Server の脆弱性により、特権が昇格される (957175)                                         | [CVE-2008-4032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)                                                | 動作に一貫性のある攻撃コ―ドが作られる可能性があります。しかしながら、この脆弱性が悪用された攻撃の結果は情報漏洩にとどまり、リモートでコードが実行される事はないと思われます。                                                    |  
| [MS08-078](http://technet.microsoft.com/security/bulletin/ms08-078) | Internet Explorer 用のセキュリティ更新プログラム (960714)                                                            | [CVE-2008-4844](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844) | [1 - 安定した悪用コードの可能性 (セキュリティ情報公開時に公開されていました。)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 現在発生している攻撃において、動作に一貫性のある攻撃コ―ドを確認しました。しかし、Windows Vista および Windows Server 2008 の既定のインストール環境は、Internet Explorer が保護モードで実行されるため、悪用が困難になっています。 |
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=3b775fb1-1077-455d-af4a-4ccb5237974f&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=c242ba42-556b-4c87-bf33-9d99166ff096&displaylang=ja)  
(緊急)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c0583745-7e57-4265-9429-c3415cb8465f&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d3e18732-47f1-40ce-999c-d1fd283bf138&displaylang=ja)  
(緊急)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=124c14b6-9323-4f6f-902b-727aa56444bc&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc&displaylang=ja)  
(Microsoft Windows 2000 Service Pack 4 のみ)  
(KB954600)  
(重要)  
[Windows Media Format ランタイム 7.1 および Windows Media Format ランタイム 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media サービス 4.1](http://www.microsoft.com/downloads/details.aspx?familyid=58b7d241-cef6-48fa-aa52-017695f71db1&displaylang=ja)  
(Microsoft Windows 2000 Service Pack 4 のみ)  
(KB952068)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=af9a6cb0-725d-490c-9858-16ec40e98560&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0190a289-164e-41a7-8c01-fa1aaed3f531&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=99241309-e644-4088-a8f3-38837fab4037&displaylang=ja)  
(KB954600)  
(重要)  
[Windows Media Format ランタイム 9.0, Windows Media Format ランタイム 9.5, および Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=504f816c-f554-4b93-ac28-b085574d9bac&displaylang=ja)  
(Windows XP Service Pack 2 のみ)  
(KB952069)  
(重要)  
[Windows Media Format ランタイム 9.0, Windows Media Format ランタイム 9.5, および Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c&displaylang=ja)  
(Windows XP Service Pack 3 のみ)  
(KB952069)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8&displaylang=ja)  
(KB954600)  
(重要)  
[Windows Media Format ランタイム 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media Format ランタイム 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b&displaylang=ja)  
(KB952069)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=2315ce20-2f46-42c2-bb40-045f003409d7&displaylang=ja)  
(KB954600)  
(重要)  
[Windows Media Format ランタイム 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=d8958248-c889-499e-a6a9-3b394cdb27ea&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media サービス 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e&displaylang=ja)  
(KB952068)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=015df302-d79f-43a1-b5c5-32ac04de0510&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2ae17caf-6204-470e-8480-380d3d505657&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f&displaylang=ja)  
(KB954600)  
(重要)  
[Windows Media Format ランタイム 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=2278022e-a716-46c0-bedf-d626933bd815&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media Format ランタイム 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media サービス 9 シリーズ](http://www.microsoft.com/downloads/details.aspx?familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f&displaylang=ja)  
(KB952068)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f&displaylang=ja)  
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
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cddf9cf6-bdeb-4429-823a-879387a428d7&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0dcc5373-0435-42d5-864d-298e5bb122d9&displaylang=ja)  
(KB958623)  
(重要)  
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323&displaylang=ja)  
(KB958624)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3f62030a-9ce2-4c92-b948-143a6881921e&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999&displaylang=ja)  
(KB952069)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2112c5c8-7c9f-4491-b127-b1093085e105&displaylang=ja)  
(KB958623)  
(重要)  
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab&displaylang=ja)  
(KB958624)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25&displaylang=ja)  
(KB952069)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16&displaylang=ja)\*\*\*  
(KB958623)  
(重要)  
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295&displaylang=ja)\*\*\*  
(KB958624)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5552e564-dd1c-4e2a-9a42-6317522c884d&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media サービス 2008](http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df&displaylang=ja)\*  
(KB952068)  
(重要)
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
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295&displaylang=ja)\*\*\*  
(KB958624)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=e1deab57-ada2-4b12-9157-5615e7b0071d&displaylang=ja)\*\*\*  
(KB958623)  
(重要)  
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316&displaylang=ja)\*\*\*  
(KB958624)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=405b28db-47d7-4d6b-90e6-834c0a409323&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Format ランタイム 11](http://www.microsoft.com/downloads/details.aspx?familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3&displaylang=ja)  
(KB952069)  
(重要)  
[Windows Media サービス 2008](http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72&displaylang=ja)\*  
(KB952068)  
(重要)
</td>
</tr>
<tr class="alternateRow">
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
対象外
</td>
<td style="border:1px solid black;">
[Windows Media サービス 2008](http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72&displaylang=ja)\*  
(KB952068)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343&displaylang=ja)  
(KB958623)  
(重要)  
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9&displaylang=ja)  
(KB958624)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**MS08-078 に関する注意:**

MS08-078 で解決しているこの脆弱性は Windows Internet Explorer 8 Beta 2 のリリース後に報告されました。Windows Internet Explorer 8 Beta 2 を実行している場合は、この更新プログラムをダウンロードし、ご使用のシステムに適用することを推奨します。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から利用可能です。セキュリティ更新プログラムはマイクロソフト ダウンロード センターからダウンロードすることができます。「security update」 のキーワード探索で容易に見つけられます。

**Windows Server 2008 に関する注意:**

**\*Windows Server 2008 Server Core インストールは影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**\*\*Windows Server 2008 Server Core インストールは影響を受けません。** これらの更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 をインストールした場合、サポートされているエディションの Windows Server 2008 に影響を与えません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**\*\*\*Windows Server 2008 Server Core インストールは影響を受けません。**これらの更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 をインストールした場合、これらの脆弱性の影響を受けるファイルがシステムに存在していたとしても、サポートされているエディションの Windows Server 2008 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="5">
Microsoft Office スイート,システム, およびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a&displaylang=ja)  
(KB956328)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c&displaylang=ja)  
(KB958435)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876&displaylang=ja)  
(KB956329)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a&displaylang=ja)  
(KB958372)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2&displaylang=ja)  
(KB956357)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66&displaylang=ja)  
(KB958436)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37&displaylang=ja)  
(KB956358)  
(重要)  
[Microsoft Office Outlook 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37&displaylang=ja)  
(KB956358)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007](http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf&displaylang=ja)  
(KB958437)\*\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37&displaylang=ja)  
(KB956358)  
(重要)  
[Microsoft Office Outlook 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37&displaylang=ja)  
(KB956358)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf&displaylang=ja)  
(KB958437)\*\*\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office FrontPage
</td>
<td style="border:1px solid black;">
[Microsoft Office FrontPage 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea&displaylang=ja)\*  
(KB957797)  
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
Microsoft Office Project
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=89a44042-a629-40f3-800a-0bb45fc36591&displaylang=ja)  
(KB949045)  
(緊急)  
[Microsoft Office Project 2007](http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6&displaylang=ja)  
(KB949046)  
(緊急)  
[Microsoft Office Project 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6&displaylang=ja)  
(KB949046)  
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
<th colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820&displaylang=ja)\*\*  
(KB960402)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820&displaylang=ja)\*\*  
(KB960402)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62&displaylang=ja)\*\*  
(KB960401)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62&displaylang=ja)\*\*  
(KB960401)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7&displaylang=ja)\*\*  
(KB960403)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7&displaylang=ja)\*\*  
(KB960403)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
その他の Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](http://www.microsoft.com/downloads/details.aspx?familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af&displaylang=ja)  
\*\*\*(KB959487)  
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
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e&displaylang=ja)  
(KB958434)  
(重要)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e&displaylang=ja)  
(KB958434)  
(重要)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443&displaylang=ja)  
(KB958442)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3 および Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c&displaylang=ja)  
(KB956366)  
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
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック](http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970&displaylang=ja)  
(KB956828)  
(重要)  
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970&displaylang=ja)  
(KB956828)  
(重要)
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f&displaylang=ja)  
(KB958439)  
(重要)  
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f&displaylang=ja)  
(KB958439)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
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
[Microsoft Office SharePoint Server 2007 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e&displaylang=ja)  
(KB956716)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e&displaylang=ja)  
(KB956716)  
(重要)  
[Microsoft Office SharePoint Server 2007 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86&displaylang=ja)  
(KB956716)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86&displaylang=ja)  
(KB956716)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS08-070 のセキュリティ情報に関する注意:**  
更新プログラムのファイルに関する詳細情報は、上記の**「Microsoft 開発者用ツールおよびソフトウェア」**の欄も併せてご覧ください。このセキュリティ情報は Microsoft Office と Microsoft 開発者用およびソフトウェアの両方を対象としています。

**MS08-077 のセキュリティ情報に関する注意:**    
更新プログラムのファイルに関する詳細情報は、上記の**「Microsoft サーバー ソフトウェア」**の欄も併せてご覧ください。このセキュリティ情報は Microsoft Office スイートおよびソフトウェアと Microsoft サーバー ソフトウェアの両方を対象としています。

**MS08-070 のセキュリティ情報の Microsoft Office FrontPage に関する注意:**  
\*この更新プログラムは、簡体字中国語 (中国)、Pan-Chinese (香港)、繁体字中国語 (台湾) および韓国語版の FrontPage 2002 Service Pack 3 のみに適用します。

**MS08-072 および MS08-074 のセキュリティ情報内の Microsoft Office for Mac に関する注意:**  
\*\*対応する更新プログラムは MS08-072 および MS08-074 のセキュリティ情報で同じです。同じファイルに脆弱性が存在するため、これらの更新プログラムは両方のセキュリティ情報で同じです。

**MS08-072 のセキュリティ情報内の Works 8 に関する注意:**  
\*\*\*このセキュリティ更新プログラムを入手するには、お客様が Microsoft Works 8.0 を実行している場合、まず Works 8.5 に更新する必要があります。詳細は、[Microsoft Works のアップデート](http://www.microsoft.com/products/works/international/update_1020.mspx)で説明しています。これには、Microsoft Works 8.0、Works Suite 2004 および Works Suite 2005 をご使用のお客様すべてが含まれます。Works Suite 2006 を実行している場合、すでに Works 8.5 が含まれています。

**MS08-074 の Microsoft Office Excel 2007 および Microsoft Office Excel 2007 Service Pack 1 についての注意:**  
\*\*\*\*MS08-074 で説明している脆弱性に対する保護を行うために、Microsoft Office Excel 2007 および Microsoft Office Excel 2007 Service Pack 1 に関しては、セキュリティ更新プログラム パッケージ KB958437 に加えて [Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)用のセキュリティ更新プログラム (KB958439) を併せてインストールする必要があります。 KB958437 および KB958439 の両方の更新プログラムを既に正常にインストールされたお客様は再インストールの必要はありません。

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
Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
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
Microsoft Visual Basic
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic 6.0 ランタイム Extended Files](http://www.microsoft.com/downloads/details.aspx?familyid=e27eebcb-095d-43ec-a19e-4a46e591715c&displaylang=ja)  
(KB926857)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6&displaylang=ja)  
(KB958392)  
(緊急)  
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed&displaylang=ja)  
(KB958393)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205&displaylang=en)  
(KB958369)  
(緊急)  
[Microsoft Visual FoxPro 9.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172&displaylang=en)  
(KB958370)  
(緊急)  
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a&displaylang=en)  
(KB958371)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
**MS08-070 のセキュリティ情報に関する注意:**  
更新プログラムのファイルに関する詳細情報は、上記の**「Microsoft Office スイートおよびソフトウェア」**の欄も併せてご覧ください。このセキュリティ情報は Microsoft Office スイートおよびソフトウェアと Microsoft 開発者用ツールおよびソフトウェアの両方を対象としています。

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
Search Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Search Server
</td>
<td style="border:1px solid black;">
[Microsoft Search Server 2008 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e&displaylang=ja)\*  
(KB956716)  
(重要)  
[Microsoft Search Server 2008 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86&displaylang=ja)\*\*  
(KB956716)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS08-077 のセキュリティ情報に関する注意:**  
\*Microsoft Search Server 2008 Express (32 ビット) を含みます。  
\*\*Microsoft Search Server 2008 Express (64 ビット) を含みます。
更新プログラムのファイルに関する詳細情報は、上記の**「Microsoft Office スイートおよびソフトウェア」**の欄も併せてご覧ください。このセキュリティ情報は Microsoft Office スイートおよびソフトウェアと Microsoft 開発者用ツールおよびソフトウェアの両方を対象としています。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): 2008 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

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

-   MS08-070 で説明しているいくつかの問題について報告してくださった[VenusTech](http://www.venustech.com.cn/) のADLab
-   MS08-070 で説明している問題について報告してくださった [Affiliated Computer Services](http://www.acs-inc.com/) の Jason Medeiros 氏
-   MS08-070 で説明している問題について報告してくださった [Secunia Research](http://secunia.com/) の Carsten Eiram 氏
-   MS08-070 で説明している問題について報告してくださった [McAfee Avert Labs](http://www.avertlabs.com/) に協力している Mark Dowd 氏
-   MS08-070 で説明している問題について報告してくださった [Insomnia Security](http://www.insomniasec.com/) の Brett Moore 氏
-   MS08-070 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している CHkr\_D591 氏
-   MS08-070 で説明している問題について報告してくださった [CERT/CC](http://www.cert.org/) に協力している Michal Bucko 氏
-   MS08-070 で説明している問題について報告してくださった [Symantec](http://www.symantec.com/) の Security Intelligence Analysis Team
-   MS08-071 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Jun Mao 氏
-   MS08-071 で説明している問題について報告してくださった [Bitblaze group at Carnegie Mellon University and UC Berkeley](http://bitblaze.cs.berkeley.edu/) の Juan Caballero 氏
-   MS08-072 で説明している問題について報告してくださった [Core Security Technologies](http://www.coresecurity.com) の Ricardo Narvaja 氏
-   MS08-072 で説明している問題について報告してくださった [Secunia Research](http://secunia.com/) の Dyon Balding 氏
-   MS08-072 で説明している問題について報告してくださった Yamata Li 氏
-   MS08-072 で説明しているいくつかの問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力している Wushi 氏
-   MS08-072 で説明している問題について報告してくださった [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) の Aaron Portnoy 氏
-   MS08-072 で説明している問題について報告してくださった Wushi 氏 および [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力している Ling 氏
-   MS08-072 で説明している問題について報告してくださった [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している [team509](http://www.team509.com/) のWushi 氏
-   MS08-073 で説明している問題について報告してくださった Carlo Di Dato (aka shinnai) 氏
-   MS08-073 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力している Brett Moore 氏
-   MS08-073 で説明している問題について報告してくださった [Casaba Security](http://www.casabasecurity.com/) の Chris Weber 氏
-   MS08-073 で説明している問題について報告してくださった [Verisign iDefense Labs](http://labs.idefense.com/) の Jun Mao 氏
-   MS08-074 で説明している問題について報告してくださった [Verisign iDefense Labs](http://labs.idefense.com/) の Joshua J. Drake 氏
-   MS08-074 で説明している問題について報告してくださった [signedness.org](http://www.signedness.org/) の Claes M Nyberg 氏
-   MS08-074 で説明している問題について報告してくださった [Secunia](http://secunia.com/) の Dyon Balding 氏
-   MS08-075 で説明している問題について報告してくださった [eEye Digital Security](http://www.eeye.com) の Andre Protas 氏
-   MS08-075 で説明している問題について報告してくださった Nate McFeters 氏
-   MS08-075 で説明している問題について報告してくださった匿名の発見者

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2008/12/10: このセキュリティ情報ページを公開しました。
-   2008/12/11: MS08-076 の影響を受けるソフトウェアを修正し、Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2 上の Windows Media Format ランタイム 9.5 および Windows Media Format ランタイム 11 を別のセキュリティ更新プログラムとして記載しました。また、セキュリティ情報 MS08-076 について、Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2 上の Windows Media Format ランタイム 11 x64 Edition に関する誤った記載を削除しました。
-   2008/12/17: このセキュリティ情報ページを更新し、2008 年 12 月 18 日に定例外でセキュリティ情報の緊急リリースする予定があることをお知らせしました。
-   2008/12/18: マイクロソフト セキュリティ情報 MS08-078: Internet Explorer のセキュリティ更新プログラム (960714) を追加しました。また、この定例外のセキュリティ情報に関する Webcast のリンクも追加しました。
-   2009/01/08: MS08-072 の影響を受けるソフトウェアから Microsoft Office Word Viewer 2003 を削除しました。
-   2009/01/14: MS08-076 を更新し、Windows XP Service Pack 2 (KB952069) および Windows XP Service Pack 3 (KB952069) 上の Windows Media Format ランタイム 9.5 用の新しい更新プログラムのパッケージの提供をお知らせしました。Windows Media コンポーネントのすべてのその他のサポート対象の影響を受けるバージョンを実行しており、オリジナル版のセキュリティ更新プログラム MS08-076 のパッケージを既に正常に適用されたお客様は今回新たな対応を行う必要はありません。 また、Microsoft Windows 2000 Service Pack 4 のすべてのエディション上の Windows Media Player 6.4 および Windows Media サービス 4.1 を影響を受けるソフトウェアとして記載しました。なお、本更新プログラム (Windows Media Player 6.4 は KB954600、Windows Media サービス 4.1 は KB952068) が提供されながら適用していないお客様は、適用する必要があることを説明しました。

    そして、MS08-072 を更新し、「影響を受けるソフトウェア」の一覧に Microsoft Office Word Viewer を追加しました。Microsoft Office Word Viewer をご利用のお客様で、セキュリティ更新プログラム (KB956366) のインストールが成功している場合、再インストールの必要はありません。

-   2009/01/29: MS08-074 の「影響を受けるソフトウェア」の表に補足説明を追加し、サポートされている Microsoft Office Excel 2007 のバージョン用のセキュリティ更新プログラム KB958437 および KB958439 に関する説明も追加しました。セキュリティ更新プログラムのバイナリまたは検出の変更はありません。 既に KB958437 および KB958439 の更新プログラムを正常にインストールされた Microsoft Office Excel 2007 または Microsoft Office Excel 2007 Service Pack 1 をご使用のお客様は再インストールの必要はありません。
-   2009/04/30: MS08-076 の影響を受けるソフトウェアに Windows Server 2008 for 32-bit Systems Service Pack 2 および Windows Server 2008 for x64-based Systems Service Pack 2 上の Windows Media サービス 2008 (KB952068) を追加しました。これは検出の変更のみで、バイナリへの変更はありません。KB952068 の更新プログラムを正常にインストールされたお客様は、この更新プログラムの再インストールの必要はありません。

*Built at 2014-04-18T01:50:00Z-07:00*
