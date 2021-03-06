---
TOCTitle: 'MS10-SEP'
Title: 2010 年 9 月のセキュリティ情報
ms:assetid: 'ms10-sep'
ms:contentKeyID: 61229681
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-sep(v=Security.10)'
--- 

2010 年 9 月のセキュリティ情報
==============================

公開日: 2010年9月15日 | 最終更新日: 2011年10月31日

**バージョン:** 6.1

[![](../../images/Dn627260.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627260.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2010 年 9 月公開のセキュリティ情報の一覧です。

2010 年 9 月のセキュリティ情報の公開により、2010 年 9 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/japan/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 9 月 15 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2010 年 9 月 15 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[9 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454433&eventcategory=4&culture=en-us&countrycode=us) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://technet.microsoft.com/japan/security/bulletin/summary) (英語情報) を参照してください。

このセキュリティ情報の概要のバージョン 3 に追加された定例外のセキュリティ情報 MS10-070 について、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2010 年 9 月 28 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[9 月 28 日午後 1:00 のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032464130&culture=en-us)(英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、Microsoft Security Bulletin Summaries and Webcasts (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061">MS10-061</a></td>
<td style="border:1px solid black;">印刷スプーラ― サービスの脆弱性により、リモートでコードが実行される (2347290)<br />
<br />
このセキュリティ更新プログラムは、印刷スプーラ― サービスに存在する、一般に公開された脆弱性を解決します。この脆弱性により、攻撃者が RPC 上に印刷スプーラ―のインターフェイスを持つ影響を受けるシステムに、特別に細工した印刷リクエストを送信した場合、リモートでコードが実行される可能性があります。既定で、プリンターは現在サポート中の Windows のオペレーティング システムで共有されていません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062">MS10-062</a></td>
<td style="border:1px solid black;">MPEG-4 コーデックの脆弱性により、リモートでコードが実行される (975558)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された MPEG-4 コーデックに存在する脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたメディア ファイルを開くか、または Web サイトや Web コンテンツを配信するアプリケーションから特別な細工がされたストリーミング コンテンツを受け取った場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063">MS10-063</a></td>
<td style="border:1px solid black;">Unicode スクリプト プロセッサの脆弱性により、リモートでコードが実行される (2320113)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Unicode スクリプト プロセッサの脆弱性を解決します。ユーザーが特別な細工がされた文書または Web ページを Embedded OpenTｙpe フォントをサポートするアプリケーションで表示した場合、この脆弱性によりリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-064">MS10-064</a></td>
<td style="border:1px solid black;">Microsoft Outlook の脆弱性により、リモートでコードが実行される (2315011)<br />
<br />
この更新プログラムは非公開で報告された脆弱性を解決します。この脆弱性で、ユーザーが、オンライン モードで Exchange サーバーに接続している影響を受けるバージョンの Microsoft Outlook を使用して特別な細工がされた電子メール メッセージを開いた場合、またはプレビュー表示した場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065">MS10-065</a></td>
<td style="border:1px solid black;">Microsoft インターネット インフォメーション サービス (IIS) の脆弱性により、リモートでコードが実行される (2267960)<br />
<br />
このセキュリティ更新プログラムは、インターネット インフォメーション サービス (IIS) に存在する 2 件の非公開で報告された脆弱性および 1 件の一般に公開された脆弱性を解決します。最も深刻な脆弱性で、クライアントが特別に細工された HTTP リクエストをサーバーに送信すると、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性の悪用に成功した場合、影響を受けるシステムを完全に制御する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066">MS10-066</a></td>
<td style="border:1px solid black;">リモート プロシージャー コールの脆弱性により、リモートでコードが実行される (982802)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows Vista、Windows Server2008、Windows 7、および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
この脆弱性で、攻撃者が特別に細工された RPC の応答を RPC リクエストを行っているクライアントに送信した場合、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、任意のコードを実行し、影響を受けるコンピューターを完全に制御する可能性があります。攻撃者による制御のもとで、ユーザーに悪意のあるサーバーへの RPC 接続を開始させることが攻撃者にとっての必要条件となります。攻撃者はユーザーの操作なしでこの脆弱性をリモートで悪用することはできないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067">MS10-067</a></td>
<td style="border:1px solid black;">ワードパッドのテキスト コンバーターの脆弱性により、リモートでコードが実行される (2259922)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows Vista、Windows Server2008、Windows 7、および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
この脆弱性は、ユーザーがワードパッドを使用して、特別に細工されたファイルを開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068">MS10-068</a></td>
<td style="border:1px solid black;">Local Security Authority Subsystem Service (LSASS) の脆弱性により、特権が昇格される (983539)<br />
<br />
このセキュリティ更新プログラムは Active Directory、Active Directory Application Mode (ADAM) および Active Directory Lightweight Directory Service (AD LDS) に存在する非公開で報告された脆弱性を解決します。この脆弱性により、認証された攻撃者が特別な細工がされた Lightweight Directory Access Protocol (LDAP) メッセージをリッスンしているLSASS サーバーに送信した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、標的となる Windows ドメイン内でメンバー アカウントを所有していることが攻撃者にとっての必要条件となります。しかし、Windows ドメインに参加しているワークステーションを所有することは攻撃者にとっての必要条件ではありません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-069">MS10-069</a></td>
<td style="border:1px solid black;">Windows クライアント/サーバー ランタイム サブシステムの脆弱性により、特権が昇格される (2121546)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows Vista、Windows Server2008、Windows 7、および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
この脆弱性で、攻撃者が中国語、日本語または韓国語のシステム ロケールで構成されている影響を受けるコンピューターにログオンした場合、特権が昇格される可能性があります。攻撃者によりこの脆弱性が悪用された場合、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントの作成が行われる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070">MS10-070</a></td>
<td style="border:1px solid black;">ASP.NET の脆弱性により、情報漏えいが起こる (2418042)<br />
<br />
このセキュリティ更新プログラムは ASP.NET に存在する一般に公開された脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、ビュー ステートなどのサーバーによって暗号化されたデータを読み取る可能性があります。この脆弱性はデータの改ざんにも使用される可能性があります。この脆弱性の悪用に成功した場合、サーバーによって暗号化されたデータが解読され、改ざんされる可能性があります。Microsoft .NET Framework 3.5 Service Pack 1 以前の Microsoft .NET Framework のバージョンはこの脆弱性のファイルのコンテンツの漏えいの影響は受けません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用可能性の評価 (高→低)、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
| セキュリティ情報 ID                                                       | 脆弱性のタイトル                                          | CVE の識別番号                                                                   | Exploitability Index の評価                                                                     | 注意事項                                                                   |  
|---------------------------------------------------------------------------|-----------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|  
| [MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062) | MPEG-4 コーデックの脆弱性                                 | [CVE-2010-0818](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0818) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | ヒープの緩和策により、Windows Vista でのコード実行の可能性は低くなります。 |  
| [MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068) | LSASS のヒープのオーバーフローの脆弱性                    | [CVE-2010-0820](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0820) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                     |  
| [MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)       | CSRSS のローカルの特権の昇格の脆弱性                      | [CVE-2010-1891](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1891) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                     |  
| [MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067) | WordPad Word 97 テキスト コンバータのメモリの破損の脆弱性 | [CVE-2010-2563](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2563) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                     |  
| [MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066) | RPC のメモリの破損の脆弱性                                | [CVE-2010-2567](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2567) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                     |  
| [MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061) | 印刷スプーラ サービスの偽装の脆弱性                       | [CVE-2010-2729](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2729) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は現在インターネット エコシステム上で悪用されています。          |  
| [MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070) | ASP.NET の脆弱性                                          | [CVE-2010-3332](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3332) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は現在インターネット エコシステム上で悪用されています。          |  
| [MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065) | ディレクトリ認証の回避の脆弱性                            | [CVE-2010-2731](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2731) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は一般に公開されていました。                                     |  
| [MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063) | Uniscribe フォント解析エンジンのメモリの破損の脆弱性      | [CVE-2010-2738](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2738) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                     |  
| [MS10-064](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-064) | Outlook のヒープ ベース バッファー オーバーフローの脆弱性 | [CVE-2010-2728](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2728) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                     |  
| [MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065) | リクエスト ヘッダーのバッファー オーバーフローの脆弱性    | [CVE-2010-2730](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2730) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                     |  
| [MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065) | IIS のパラメーター リクエストの反復のサービス拒否の脆弱性 | [CVE-2010-1899](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1899) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | これは、サービス拒否の脆弱性です。                                         |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
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
</tr>
<tr>
<th colspan="10">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急 ](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=93faba6b-0a85-4acc-b527-a012bbf56b13&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2084a01c-2a91-4650-8665-7053015f2083&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a1d47f30-c1fc-4b9d-8829-3bad1224006a&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=555864c3-9114-4988-8526-7bf545a27706&displaylang=ja)  
(KB2124261)  
(重要)  
IIS 認証:  
[インターネット インフォメーション サービス 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=ae55787e-4a5c-48d5-aedf-0abada514938&displaylang=ja)  
(KB2290570)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7ad0f2cf-03dc-49a0-a16e-17fed0c01cc6&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fc4369ec-864a-42ae-a850-b006872241fe&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[ADAM (Active Directory Application Mode)](http://www.microsoft.com/downloads/details.aspx?familyid=6554f98f-4dc5-4784-b92c-b0aae1fa22ca&displaylang=ja)  
(KB982000)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=20091358-7127-4ace-bf96-4319461ad305&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ja)  
(KB2418241)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ja)  
(KB2416468)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9f7f3737-056d-44bd-b644-51093b5b501b&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b27f310f-6ecc-4abb-8944-9fc24c66e077&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0b28bfac-783d-4c89-988b-4123c0343855&displaylang=ja)  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3349b12b-621e-48bc-9c57-489c7a56920d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7567986a-261d-4def-9fa5-c667994c7844&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[ADAM (Active Directory Application Mode)](http://www.microsoft.com/downloads/details.aspx?familyid=5bc00f9a-3028-4c9d-be06-f2b78fa444c4&displaylang=ja)  
(KB982000)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=107eb958-b60f-40ae-a785-5d5b4d13d8c6&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ja)  
(KB2418241)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ja)  
(KB2416468)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d79680b-c071-462f-9cea-551fbd42edf0&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0a942985-081f-455c-bf9d-4345392c91b0&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7ff7de2f-3e37-4aff-a8e4-5ed21b83575c&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=29e6cf4f-446b-461c-82f7-cfa8478cf739&displaylang=ja)  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8b3004b-07db-4638-a9b7-224ff829081c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3290e7ee-1e4a-464c-abfd-17fc4108601e&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=3fe6e78c-c60a-4903-9273-27b37e129f0a&displaylang=ja)  
(KB981550)  
(重要)  
[ADAM (Active Directory Application Mode)](http://www.microsoft.com/downloads/details.aspx?familyid=c42731f1-6393-42ed-b59f-5310c832fdc4&displaylang=ja)  
(KB982000)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fd46ba66-8ca1-4aa2-b91b-9e5861a173f7&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=71f0daad-e2df-421c-9818-58e1e40cdb65&displaylang=ja)  
(KB2416451)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ja)  
(KB2418241)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ja)  
(KB2416468)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=073b3305-4a81-4ef8-b6aa-e53b31a936b4&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8382c1f2-e16d-475c-a8a0-e378696808f1&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=750e4a79-11bf-4726-9eb4-5dd3d029a717&displaylang=ja)  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=612b2096-bd82-47ca-8b99-454c2f158d39&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b21570cc-4f90-4ed8-b901-a34584d44a63&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=22412eed-33cd-4dfc-8ef7-b74dcd7c5faf&displaylang=ja)  
(KB981550)  
(重要)  
[ADAM (Active Directory Application Mode)](http://www.microsoft.com/downloads/details.aspx?familyid=79fb639d-2cc1-4bea-9df6-c67ed95890e3&displaylang=ja)  
(KB982000)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ff5976e0-579c-4e6e-a225-c0d3913cdc85&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ja)  
(KB2418241)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ja)  
(KB2416468)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=ca35a520-c4da-41bb-abcc-d5bc534ff19a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=be7b3310-ffb7-4528-9c9e-aebe14d264d6&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f6841057-1745-44e9-a16a-c180dd941ddf&displaylang=ja)  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=1f04f151-330a-4b6c-826e-76def35daa73&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=c9c4427d-54c8-4f3c-9a94-818196cd5180&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=cab75c8a-0d12-4a91-82b2-9f9b70610f67&displaylang=ja)  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=e450ca08-1d75-4419-ad9f-c5e5efb55cd5&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46&displaylang=ja)  
(KB2418241)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780&displaylang=ja)  
(KB2416468)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=028977fd-0f39-42d4-9fee-0d90a2931cfd&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=84629c25-7827-40c1-86fb-7ffa247202a0&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ac1b0260-3802-45d4-985e-ac827d784e4f&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=75059175-9c59-45d5-81ce-09b964640e5f&displaylang=ja)  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2 のみ:  
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=853a71f3-fb0d-43af-a2b8-45bf8ca1a588&displaylang=ja)  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)  
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a&displaylang=ja)  
(KB2416469)  
(重要)  
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93&displaylang=ja)  
(KB2416474)  
(重要)  
Windows Vista Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2、Microsoft .NET Framework 3.5 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04&displaylang=ja)  
(KB2416470)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c68b9337-883d-4e98-ba0a-90b5cad46184&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=36e2a74b-e5c6-47d5-9cd9-b9171be63c7d&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ebfdcd6d-413e-4359-8863-e992327a607f&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=9864c590-10a7-4971-a717-924ed0d6cace&displaylang=ja)  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2 のみ:  
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=566f468b-22b6-400a-a656-ae64cfcb52df&displaylang=ja)  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)  
Windows Vista x64 Edition Service Pack 1 のみ  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a&displaylang=ja)  
(KB2416469)  
(重要)  
Windows Vista x64 Edition Service Pack 1 のみ  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93&displaylang=ja)  
(KB2416474)  
(重要)  
Windows Vista x64 Edition Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2、Microsoft .NET Framework 3.5 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04&displaylang=ja)  
(KB2416470)  
(重要)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e2e788de-8400-4bf6-b96b-a915154aa20a&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fdfc393e-a54d-44dd-ba45-c2a550ffd2a1&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b679fe0c-5498-4fc5-84c8-0cd24b625907&displaylang=ja)\*  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=d798dc8e-ae64-4a1d-abda-f58cf69779d8&displaylang=ja)\*  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=1452befe-b7b8-4131-b36f-dded2bd16d5e&displaylang=ja)\*  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)\*\*  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)\*\*  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)\*\*  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)\*\*<sup>[1]</sup>
(KB2416472)  
(重要)  
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a&displaylang=ja)\*\*  
(KB2416469)  
(重要)  
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93&displaylang=ja)\*\*  
(KB2416474)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2、Microsoft .NET Framework 3.5 および Microsoft .NET Framework 3.5 Service Pack](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04&displaylang=ja)1\*\*  
(KB2416470)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e08d4f49-5a13-4e1d-b0a7-27b314c2edb5&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b7af424-6286-4a80-827c-c4df4f92fe43&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e1b38b87-24f6-4aaa-afa9-40f4015d6694&displaylang=ja)\*  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e29f01dc-b00d-4c12-a13e-63aa0b09d919&displaylang=ja)\*  
(KB2124261)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=38eb875f-1869-401b-b7d3-9f18f4ba4f24&displaylang=ja)\*  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)\*\*  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)\*\*  
(KB2418240)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)\*\*  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)\*\*<sup>[1]</sup>
(KB2416472)  
(重要)  
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a&displaylang=ja)\*\*  
(KB2416469)  
(重要)  
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93&displaylang=ja)\*\*  
(KB2416474)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2、Microsoft .NET Framework 3.5 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04&displaylang=ja)\*\*  
(KB2416470)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae&displaylang=ja)\*\*  
(KB2418240)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=098537d5-bf6e-4e04-ad33-1cde697e062f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ceb856e8-f4a6-4229-bd26-b1a763d7d443&displaylang=ja)  
(KB981322)  
(緊急)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=d595c8d2-90b1-46e4-bb9f-60efd0bf3a02&displaylang=ja)  
(KB2124261)  
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
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282&displaylang=ja)  
(KB2416447)  
(重要)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a&displaylang=ja)  
(KB2416473)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)  
Windows Server 2008 for Itanium-based Systems のみ  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a&displaylang=ja)  
(KB2416469)  
(重要)  
Windows Server 2008 for Itanium-based Systems のみ  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93&displaylang=ja)  
(KB2416474)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2、Microsoft .NET Framework 3.5 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04&displaylang=ja)  
(KB2416470)  
(重要)
</td>
</tr>
<tr>
<th colspan="10">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=34619e9e-1f00-40e4-be6f-5bbf5e3c801b&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=5b2d42da-4dbc-4fbb-be22-09ca7dec5aa3&displaylang=ja)  
(KB2124261)  
(重要)  
IIS FastCGI:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=c843afd9-b6f2-48de-91cc-1c0d481c2be4&displaylang=ja)  
(KB2271195)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=454fc025-bfa2-4552-9522-3585f523ecb2&displaylang=ja)  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7&displaylang=ja)  
(KB2416471)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=dbb747a5-658d-44cf-bd49-425d1700157f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=66b64374-95e4-4b99-80e6-98dc63cd272b&displaylang=ja)  
(KB2124261)  
(重要)  
IIS FastCGI:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f0c0454-cbb6-47ed-9227-98aa45b8cbdb&displaylang=ja)  
(KB2271195)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=b15ad533-3cf1-4dcf-847c-05ebffb84e26&displaylang=ja)  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7&displaylang=ja)  
(KB2416471)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472) (重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472) (重要)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-061](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-061)
</td>
<td style="border:1px solid black;">
[MS10-062](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-062)
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-065](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-065)
</td>
<td style="border:1px solid black;">
[MS10-066](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-066)
</td>
<td style="border:1px solid black;">
[MS10-067](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-067)
</td>
<td style="border:1px solid black;">
[MS10-068](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-068)
</td>
<td style="border:1px solid black;">
[MS10-069](http://technet.microsoft.com/security/bulletin/ms10-069)
</td>
<td style="border:1px solid black;">
[MS10-070](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=11e20088-1be2-4166-9c97-234b7e9f1c4f&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=21458cce-f67e-4e95-a067-8311afefc261&displaylang=ja)\*  
(KB2124261)  
(重要)  
IIS FastCGI:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=9578b1de-f2c1-4b37-9d82-69e929cab6f3&displaylang=ja)\*  
(KB2271195)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=54f36389-8be4-4a0c-9640-dc32addac9d7&displaylang=ja)\*  
(KB981550)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7&displaylang=ja)\*  
(KB2416471)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)\*<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=d8c635f8-8978-44bf-b457-e07368f08ef4&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
IIS ASP:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=3b8f3fd1-1ef4-4e9f-9bce-0c68f10519d1&displaylang=ja)  
(KB2124261)  
(重要)  
IIS FastCGI:  
[インターネット インフォメーション サービス 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=21adf80d-267f-47cd-9c03-4b4854ba159f&displaylang=ja)  
(KB2271195)  
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
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7&displaylang=ja)  
(KB2416471)  
(重要)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6&displaylang=ja)<sup>[1]</sup>
(KB2416472)  
(重要)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。Server Core インストール オプションを使用してインストールしている場合、サポートされているエディションのWindows Server 2008 はこのアドバイザリで説明している脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS10-063 の注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS10-070 のセキュリティ情報に関する注意

<sup>[1]</sup>.NET Framework 4.0 Client Profile は影響を受けません。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework 4.0 Client Profile は、.NET Framework 4.0 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4.0 に影響を及ぼしますが、.NET Framework 4.0 Client Profile には影響しません。詳細については、 「[NET Framework のインストール](http://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

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
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-063](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-063)
</td>
<td style="border:1px solid black;">
[MS10-064](http://technet.microsoft.com/ja-jp/security/bulletin/ms10-064)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0b56f85f-d39b-410a-857a-799a5d714de7&displaylang=ja)  
(KB2288608)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d5e85841-9dea-4776-9e0e-3cd272066f37&displaylang=ja)  
(KB2293422)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=bb7783b1-b396-4254-b317-f2292b305cfc&displaylang=ja)  
(KB2288613)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ec8ed81e-05d0-4c20-b5fb-ebc72230a8bd&displaylang=ja)  
(KB2293428)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=44c5bccf-66dd-4796-9089-e6171d8c9785&displaylang=ja)  
(KB2288621)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6009d507-135c-4ce8-a830-925134f214dc&displaylang=ja)  
(KB2288953)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS10-063 の注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および適用ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および適用のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://go.microsoft.com/fwlink/?linkid=50120) の Web サイトを参照してください。

Systems Management Server

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、[System Center Configuration Manager 2007](http://technet.microsoft.com/ja-jp/library/bb735860.aspx) (英語情報) も参照してください。管理者が SMS 2003 を使用してセキュリティ更新プログラムを適用する方法については、[SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) (英語情報) を参照してください。また、SMS 2.0 ユーザーも、Security Update Inventory Tool (SUIT) を活用して、セキュリティ更新プログラムを適用できます。SMS の詳細については、[Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (英語情報) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、WSUS および SUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://www.microsoft.com/security/msrc/mapp/partners.mspx)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS10-061 で説明している問題を報告してくださった [Kaspersky Lab](http://www.kaspersky.com/) の Sergey Golovanov 氏、Alexander Gostev 氏、Maxim Golovkin 氏、および Alexey Monastyrsky 氏、と [Design and Test Lab](http://www.dnt-lab.com/) の Vitaly Kiktenko 氏および Alexander Saprykin 氏
-   MS10-061 で説明している問題を報告してくださった [Symantec](http://www.symantec.com/index.jsp) の Liam O Morchu 氏
-   MS10-062 で説明している問題を報告してくださった [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html) の Matthew Watchinski 氏
-   MS10-063 で説明している問題を報告してくださった の Carsten Book 氏
-   MS10-063 で説明している問題を報告してくださった Red Hat Security Response Team の Marc Schoenefeld 氏
-   MS10-063 の CVE-2010-2738 の Exploitability Index の変更に結びつく情報を報告してくださった [Secunia](http://secunia.com/) の Carsten H. Eiram 氏
-   MS 10-064 で説明している問題を報告してくださった [Secunia](http://secunia.com/) の Dyon Balding 氏
-   MS10-065 で説明している問題を報告してくださった Jinsik Shim 氏
-   MS10-065 で説明している問題を報告してくださった Rubicon West の Travis Raybold 氏
-   MS10-066 で説明している問題を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS10-067 で説明している問題を報告してくださった [iDefense Labs](http://labs.idefense.com/) の S0lute 氏
-   MS10-069 で説明している問題を報告してくださった [日本 IBM](http://www.ibm.com/jp/ja/)

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2010/09/15): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2010/09/23): このセキュリティ情報ページを更新し、Exploitability Index (悪用可能性指標) の表で、CVE-2010-2738 についての記載を最初に公開した時よりも高く、CVE-2010-2730 については低くしました。また CVE-2010-0818 についての「注意事項」を変更しました。
-   V3.0 (2010/09/29): マイクロソフトセキュリティ情報 MS10-070 ASP.NET の脆弱性により、情報漏えいが起こる (2418042) また、この定例外のセキュリティ情報に関する Webcast のリンク先も追加しました。
-   V4.0 (2010/09/30): マイクロソフトはこのセキュリティ情報ページを更新し、MS10-070 の更新プログラムが Windows Update および Microsoft Update などのすべての配布方法により、利用可能になったことをお知らせしました。また、MS10-070 の更新プログラム KB2418240、KB2418241、KB2416470 および KB2416474 の詳細を更新しました。
-   V4.1 (2010/11/04): MS10-070 の「影響を受けるソフトウェア」の一覧に、.NET Framework 4.0 Client Profile が影響を受けないことについて、説明を追加しました。
-   V5.0 (2010/12/15): マイクロソフトはこのセキュリティ情報ページを更新し、他の更新プロフラムおよび/または製品が正常にインストールされるのを妨げるセットアップの問題を修正する .NET Framework 4.0 用の新しい更新プログラム (KB2416472) が利用可能になったことをお知らせしました。システムを正常に更新済みのお客様は、措置を講じる必要はありません。
-   V6.0 (2011/02/24): このセキュリティ情報ページを更新し、Windows 7 for 32-bit Systems Service Pack 1、Windows 7 for x64-based Systems Service Pack 1、Windows Server 2008 R2 for x64-based Systems Service Pack 1 または Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 をインストールした後、Microsoft .NET Framework 4.0 をインストールしたお客様に Microsoft .NET Framework 4.0 (KB2416472) の MS10-070 の更新プログラム パッケージを提供するよう検出を変更したことをお知らせしました。
-   V6.1 (2011/10/31): MS10-070 を更新し、 Windows Server 2008 R2 for x64-based System 上の .NET Framework 4 の Server Core インストールの適用性を修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
