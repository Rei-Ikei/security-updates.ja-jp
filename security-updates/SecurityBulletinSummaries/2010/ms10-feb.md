---
TOCTitle: 'MS10-FEB'
Title: 2010 年 2 月のセキュリティ情報
ms:assetid: 'ms10-feb'
ms:contentKeyID: 61229673
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-feb(v=Security.10)'
--- 

2010 年 2 月のセキュリティ情報
==============================

公開日: 2010年2月10日 | 最終更新日: 2010年2月11日

**バージョン:** 1.0

[![](../../images/Dn627252.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627252.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-003 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-003e.mspx)

[MS10-004 : PowerPoint の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-004e.mspx)

[MS10-005 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-005e.mspx)

[MS10-006 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-006e.mspx)

[MS10-007 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-007e.mspx)

[MS10-008 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-008e.mspx)

[MS10-009 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-009e.mspx)

[MS10-010 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-010e.mspx)

[MS10-011 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-011e.mspx)

[MS10-012 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-012e.mspx)

[MS10-013 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-013e.mspx)

[MS10-014 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-014e.mspx)

[MS10-015 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-015e.mspx)

このセキュリティ情報は 2010 年 2 月に公開したセキュリティ情報の一覧です。

2010 年 2 月 10 日のセキュリティ情報の公開により、2010 年 2 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 2 月 10 日 の午後 (日本時間) に配信する予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 2 月 10 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[2 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427679&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-006">MS10-006</a></td>
<td style="border:1px solid black;"><strong>SMB クライアントの脆弱性により、リモートでコードが実行される (978251)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。この脆弱性で、攻撃者が特別に細工された SMB の応答を起動済みのクライアントの SMB リクエストに送信した場合、リモートでコードが実行される可能性があります。これらの脆弱性が悪用されるには、攻撃者はユーザーに悪意のある SMB サーバーへ SMB 接続を開始させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-007">MS10-007</a></td>
<td style="border:1px solid black;"><strong>Windows Shell ハンドラー の脆弱性により、リモートでコードが実行される (975713)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、Web ブラウザーなどのアプリケーションが Windows Shell ハンドラーを介して ShellExecute API 機能に特別に細工されたデータを渡した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-008">MS10-008</a></td>
<td style="border:1px solid black;"><strong>ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (978262)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件のマイクロソフトのソフトウェアの脆弱性を解決します。 この脆弱性では、ユーザーが Internet Explorer で特別に細工された Web ページを訪問し、ActiveX コントロールをインスタンス化した場合、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 この更新プログラムには 4 つのサードパーティの ActiveX コントロール用の Kill Bit も含まれています。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-009">MS10-009</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP の脆弱性により、リモートでコードが実行される (974145)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性で最も深刻なものについて、特別に細工されたパケットが IPv6 が有効にされているコンピューターに送信された場合、リモートでコードが実行される可能性があります。攻撃者は、特別に細工した ICMPv6 パケットを作成し、IPv6 が有効にされているコンピューターにそのパケットを送信することにより、この脆弱性を悪用する可能性があります。この脆弱性が悪用される可能性があるのは、攻撃者がリンクに存在する場合のみです。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-013">MS10-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow の脆弱性により、リモートでコードが実行される (977935)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft DirectShow に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された AVI ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-003">MS10-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office (MSO) の脆弱性により、リモートでコードが実行される (978214)</strong><br />
<br />
このセキュリティ更新プログラムは、特別に細工された Office ファイルをユーザーが開いた場合、リモートでコードが実行される可能性がある Microsoft Office に存在する非公開で報告された脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-004">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint の脆弱性により、リモートでコードが実行される (975416)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 6 件の Microsoft Office PowerPoint に存在する脆弱性を解決します。これらの脆弱性は、特別に細工された PowerPoint ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-010">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Windows Server 2008 Hyper-V の脆弱性により、サービス拒否が起こる (977894)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows Server 2008 Hyper-V および Windows Server 2008 R2 Hyper-V の脆弱性を解決します。この脆弱性により、Hyper-V サーバーがホストしているゲスト仮想マシンの一台で、認証済みユーザーがマシン命令を特定のシーケンスで実行した場合、サービス拒否が起こる可能性があります。この脆弱性を悪用する場合、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-011">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Windows クライアント/サーバー ランタイム サブシステムの脆弱性により、特権が昇格される (978037)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Windows 2000、Windows XP および Windows Server 2003 の Microsoft Windows クライアント/サーバー ランタイム サブシステム (CSRSS) に存在する 1 件の非公開で報告された脆弱性を解決します。この脆弱性で、攻撃者がコンピューターにログオンし、攻撃者がログオフした後も引き続き実行されるよう設計された特別な細工がされたアプリケーションを起動した場合、特権が昇格される可能性があります。この脆弱性を悪用する場合、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-012">MS10-012</a></td>
<td style="border:1px solid black;"><strong>SMB サーバーの脆弱性により、リモートでコードが実行される (971468)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された複数の Microsoft Windows に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性では、攻撃者が特別な細工がされた SMB パケットを作成し、そのパケットを影響を受けるコンピューターに送信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-014">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Kerberos の脆弱性により、サービス拒否が起こる (977290)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。 特別な細工がされたチケット更新のリクエストが信頼されている非 Windows Kerberos 領域に存在する認証されたユーザーから Windows Kerberos ドメインに送信された場合、この脆弱性により、サービス拒否が起こる可能性があります。 サービス拒否は、ドメイン コントローラーを再起動するまで続きます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-015">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、特権が昇格される (977165)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性により、攻撃者がシステムにログオンして、次に特別に細工されたアプリケーションを実行した場合に、特権の昇格が起こる可能性があります。いずれかの脆弱性が悪用された場合、攻撃者が有効なログオン資格情報を取得し、ローカルでログオンする可能性があります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-005">MS10-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft ペイントの脆弱性により、リモートでコードが実行される (978706)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft ペイントに存在する 1 件の脆弱性を解決します。これらの脆弱性により、ユーザーが Microsoft ペイントを使用して、特別に細工された JPEG の画像ファイルを表示すると、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">警告</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報番号                                                | 脆弱性タイトル                                                                      | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                                   |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|  
| [MS10-006](http://technet.microsoft.com/security/bulletin/ms10-006) | SMB クライアントの競合状態の脆弱性                                                  | [CVE-2010-0017](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0017) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | リモートの攻撃方法によりサービス拒否が起こり、ローカルの攻撃方法により特権の昇格が起こる可能性があります。 |  
| [MS10-011](http://technet.microsoft.com/security/bulletin/ms10-011) | CSRSS のローカルの特権の昇格の脆弱性                                                | [CVE-2010-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0023) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 攻撃者および被害者は同じコンソールにログオンする必要があります。                                           |  
| [MS10-007](http://technet.microsoft.com/security/bulletin/ms10-007) | URL の検証の脆弱性                                                                  | [CVE-2010-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint の LinkedSlideAtom のヒープ オーバーフローの脆弱性                       | [CVE-2010-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0030) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint の OEPlaceholderAtom 'placementId' の無効な配列のインデックスの脆弱性    | [CVE-2010-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0031) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint の OEPlaceholderAtom の Use After Free の脆弱性                          | [CVE-2010-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0032) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint Viewer の TextBytesAtom レコードのスタック オーバーフローの脆弱性        | [CVE-2010-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0033) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 脆弱性は PowerPoint Viewer 2003 のみが影響を受けます。                                                     |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | Office PowerPoint Viewer の TextCharsAtom レコードのスタック オーバーフローの脆弱性 | [CVE-2010-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0034) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 脆弱性は PowerPoint Viewer 2003 のみが影響を受けます。                                                     |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB の NTLM 認証のエントロピ不足の脆弱性                                            | [CVE-2010-0231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0231) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-015](http://technet.microsoft.com/security/bulletin/ms10-015) | Windows カーネルの例外ハンドラーの脆弱性                                            | [CVE-2010-0232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0232) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-003](http://technet.microsoft.com/security/bulletin/ms10-003) | MSO.DLL のバッファー オーバーフロー                                                 | [CVE-2010-0243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0243) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-013](http://technet.microsoft.com/security/bulletin/ms10-013) | DirectShow のヒープ オーバーフローの脆弱性                                          | [CVE-2010-0250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0250) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-006](http://technet.microsoft.com/security/bulletin/ms10-006) | SMB クライアントのプール破損の脆弱性                                                | [CVE-2010-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0016) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB のパス名のオーバーフローの脆弱性                                                | [CVE-2010-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0020) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB のメモリの破損の脆弱性                                                          | [CVE-2010-0021](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0021) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-005](http://technet.microsoft.com/security/bulletin/ms10-005) | MS ペイントの整数のオーバーフローの脆弱性                                           | [CVE-2010-0028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0028) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 悪用が成功するには、著しいユーザーの操作が必要条件になります。                                             |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint のファイル パスの処理のバッファー オーバーフローの脆弱性                 | [CVE-2010-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0029) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-015](http://technet.microsoft.com/security/bulletin/ms10-015) | Windows カーネルのダブル フリーの脆弱性                                             | [CVE-2010-0233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0233) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                     |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | ICMPv6 のルーター アドバタイズの脆弱性                                              | [CVE-2010-0239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0239) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 悪用される場合、攻撃者が標的のホストに対して「オンリンク」であることが必要です。                           |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | ヘッダーの MDL 断片化の脆弱性                                                       | [CVE-2010-0240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0240) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 脆弱性は、サード パーティのネットワーク ドライバーが必要です。                                             |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | ICMPv6 のルート情報の脆弱性                                                         | [CVE-2010-0241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0241) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 悪用される場合、攻撃者が標的のホストに対して「オンリンク」であることが必要です。                           |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB の Null ポインターの脆弱性                                                      | [CVE-2010-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0022) | [**3** - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | (なし)                                                                                                     |  
| [MS10-010](http://technet.microsoft.com/security/bulletin/ms10-010) | Hyper-V のインストラクション セットの検証の脆弱性                                   | [CVE-2010-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0026) | [**3** - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | サービス拒否のみ起こる可能性があります。                                                                   |  
| [MS10-014](http://technet.microsoft.com/security/bulletin/ms10-014) | Kerberos の NULL ポインター逆参照の脆弱性                                           | [CVE-2010-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0035) | [**3** - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | サービス拒否のみ; 悪用は、既定以外の構成のドメイン コントローラーでのみ起きる可能性があります。            |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | TCP/IP の選択の確認の脆弱性                                                         | [CVE-2010-0242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0242) | [**3** - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | (なし)                                                                                                     |
  
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
<th colspan="12">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[AVI フィルター](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3)  
(KB977914)  
(緊急)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=16787c93-2c95-4c13-8492-be1db9d18146)  
(KB975560)  
(緊急)  
[DirectX 9.0 の Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b)<sup>[1]</sup>
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=267ce982-54a0-418f-ad52-e4963610f714)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e5861705-8f49-45cb-8a92-cf052ccf4134)  
(警告)
</td>
</tr>
<tr>
<th colspan="12">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f6c4472e-385c-4412-bda9-c2e615e50713)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[AVI フィルター](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb)  
(KB977914)  
(緊急)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f7adee3-e68e-41b3-b835-d84691774f31)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2b348f5-ec8d-4782-bb03-5de550adea77)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[AVI フィルター](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dedc3010-a989-45f7-b9d4-f7079db3e572)  
(KB977914)  
(緊急)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7543e819-cd36-4e89-9850-60f00c50999d)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1f83bf7a-e16c-404a-89bd-f65843938299)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155)  
(警告)
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[AVI フィルター](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204)  
(KB977914)  
(緊急)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=983c5484-6321-4765-97ec-8d42d42d1f70)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=defd8603-ed9b-42f9-a539-2b6a690e9575)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=90360537-9311-45e2-8047-9a971f90c3c3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[AVI フィルター](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f)  
(KB977914)  
(緊急)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=de0186f6-27a2-4226-b8eb-f2912710f072)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7d63c95e-311a-446f-8852-dffd217a89f6)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[AVI フィルター](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764)  
(KB977914)  
(重要)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b1a7533a-913f-4054-b579-489a257bae5f)  
(KB975560)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=87732f7a-9339-43bc-a4e8-3da849f35b70)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d549c927-add7-4d83-bfc7-15dc35663dfb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c3c21225-8534-4c7f-96b6-20a743dcea74)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ee603435-26af-4ab9-9f22-92734346dc0a)  
(警告)
</td>
</tr>
<tr>
<th colspan="12">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=71f03946-622c-4403-b94f-f6a3de18a8c3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=16494dac-553a-4de9-b751-0d6b51cb43f0)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=519815fd-707d-476f-9e29-7b03b7a17af5)  
(緊急)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=09e19263-18ba-495e-bcf7-719e957204a7)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bc451228-3de4-427c-b42f-91f204c708b8)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47)\*\*  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=75327470-0f14-4cdd-bcb7-64684c61c267)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fde218c3-90ab-4664-852d-25ca55835054)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=362fea40-649b-4471-aad7-db29edd0ac10)\*\*  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0b93047d-f2c6-403b-9200-c251898bc1e0)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7)  
(緊急)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=effa638b-cfc1-4777-8219-7b433ed5e717)  
(KB975560)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f90fc0c8-babe-4224-be07-614ea7ddf102)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cd6b234b-8e96-4128-a77a-645a0882996a)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="12">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4ec49aa2-81df-4e65-80da-6201394c4089)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=122fc003-0651-4ad2-a5c8-a21536defad8)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b3265576-04c1-48b1-8ce9-128843c58cf5)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a8a2519c-3b89-4987-9473-920adafc78cb)  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5)  
(重要)
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
<th colspan="12">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cda31c54-8b81-4185-a623-64480ad4b73c)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a9811baa-1500-4c73-940b-57f8c5456891)\*\*  
(KB975560)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3214b347-d901-4aac-85ce-676e4602de87)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9)\*  
(重要)
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
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=badd6cab-7738-4401-a68c-c15414388601)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68)  
(KB975560)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e)  
(重要)
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
</table>

<p></p>

 
**MS10-013 に関する注意**

<sup>[1]</sup>DirectX 9.0 用の更新プログラムは Microsoft Windows 2000 上の DirectX 9.0a、DirectX 9.0b および DirectX 9.0c にも適用することができます。

**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

**\*\*Server Core インストールは影響を受けません。**この更新プログラムで解決されている脆弱性は、Server Core インストールオプションを使用してインストールされたサポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 は、影響を受けません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

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
Microsoft Office スイートおよびソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-003**](http://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://technet.microsoft.com/security/bulletin/ms10-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=47553f45-fa10-40e5-8267-9d42ff560a62)  
(KB977896)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c)  
(KB973143)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96)  
(KB976881)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報番号**
</td>
<td style="border:1px solid black;">
[**MS10-003**](http://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://technet.microsoft.com/security/bulletin/ms10-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7c985595-00c5-44b8-81c3-59d9967220f8) <sup>[1]</sup>
(KB979674)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7c985595-00c5-44b8-81c3-59d9967220f8) <sup>[1]</sup>
(KB979674)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**Microsoft Office for Mac に関する注意**

<sup>[1]</sup> Microsoft Office 2004 for Mac の累積的なサービス モデルのため、これらの更新プログラムは同一のものです。

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

-   MS10-003 で説明している問題について報告してくださった [Core Security Technologies](http://www.coresecurity.com/) の Damian Frizza 氏
-   MS10-004 で説明している問題について報告してくださった [Secunia](http://secunia.com/) の Carsten Eiram 氏
-   MS10-004 で説明している 3 つの問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Sean Larsson 氏
-   MS10-004 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) の [ZeroDay Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった SkD 氏
-   MS10-004 で説明している問題について報告してくださった [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/)の Cody Pierce 氏
-   MS10-005 で説明している問題について [Secunia](http://secunia.com/) と協力して報告してくださった ICST-ERCIS (Engineering Research Center of Info Security, Institute of Computer Science & Technology, Peking University/China) の Tielei Wang 氏
-   MS10-006 で説明している問題について報告してくださった [stratsec](http://www.stratsec.net/) の Laurent Gaffié 氏
-   MS10-007 で説明している問題を [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった Brett Moore 氏
-   MS10-007 で説明している問題について報告してくださった [Lostmon Lords](http://lostmon.blogspot.com/)氏
-   MS10-008 で説明している問題について報告してくださった [NGS Software](http://www.ngssoftware.com/index.htm) の Shaun Colley 氏
-   MS10-009 で説明している問題について報告してくださった [Google Security Team](http://www.google.com/) の Sumit Gwalani、Drew Hintz および Neel Mehta 氏
-   MS10-010 で説明している問題について報告してくださった Jan Bottorff 氏
-   MS10-011 で説明している問題について報告してくださった [Hispasec](http://www.hispasec.com/) の Matthew 'j00ru' Jurczyk 氏および Gynvael Coldwind 氏
-   MS10-012 で説明している問題について報告してくださった [Codenomicon](http://www.codenomicon.com/) の Joshua Morin 氏
-   MS10-012 で説明している問題について報告してくださった [BSI](http://www.bsi.bund.de/) の Florian Rienhardt 氏
-   MS10-012 で説明している問題について報告してくださった Hernan Ochoa 氏
-   MS10-013 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS10-015 で説明している問題について報告してくださった [Google](http://www.google.com/) の Tavis Ormandy 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/02/10: このセキュリティ情報ページを公開しました。
-   2010/02/11: MS10-005 の再起動情報を修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
