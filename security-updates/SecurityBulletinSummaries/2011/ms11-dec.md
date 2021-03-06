---
TOCTitle: 'MS11-DEC'
Title: 2011 年 12 月のセキュリティ情報
ms:assetid: 'ms11-dec'
ms:contentKeyID: 61229684
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-dec(v=Security.10)'
--- 

2011 年 12 月のセキュリティ情報
===============================

公開日: 2011年12月14日 | 最終更新日: 2012年2月24日

**バージョン:** 2.1

[![](../../images/Dn627263.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627263.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 12 月公開のセキュリティ情報の一覧です。

2011 年 12 月 30 日に緊急リリースしたセキュリティ情報 MS11-100 に関する情報を追加しました。
2011 年 12 月のセキュリティ情報の公開により、2011 年 12 月 30 日に公開した定例外の事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「マイクロソフト セキュリティ情報の事前通知」を参照してください。

マイクロソフトはこの定例外のセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 12 月 30 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。 [12 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、 [Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 12 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「今月のワンポイント セキュリティ情報」をご覧ください。マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 12 月 14 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。 [12 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、 [Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2639417) <br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。ユーザーが特別な細工がされた文書を開いた場合や、TrueType フォント ファイルが埋め込まれた悪意のある Web ページを表示した場合に、この脆弱性によりリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;">ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (2618451) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft のソフトウエアに存在する 1 件の脆弱性を解決します。この脆弱性は、ユーザーが Internet Explorer で特定のバイナリの動作を使用する、特別な細工がされた Web ページを表示した場合、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この更新プログラムには 4 つのサードパーティの ActiveX コントロール用の Kill Bit も含まれています。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;">Windows Media の脆弱性により、 リモートでコードが実行される (2648048) <br />
<br />
このセキュリティ更新プログラムは、Window Media Player と Windows Media Center について非公開で報告された脆弱性を解決するものです。この脆弱性により、特別に細工された Microsoft Digital Video Recording (.dvr-ms) ファイルをユーザーが開いた際に、リモートでコードが実行される可能性があります。すべての場合において、ユーザーに強制的にファイルを開かせることはできません。攻撃を成功させるためには、ユーザーを誘導してファイルを開かせる必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;">Microsoft Office IME (中国語版) の脆弱性により、特権が昇格される ( 2652016) <br />
<br />
この更新プログラムは非公開で報告された Microsoft Office IME (中国語版) に存在する 1 件の脆弱性を解決します。ログオンしているユーザーが、影響を受けるバージョンの簡体字中国語版 Microsoft Pinyin (MSPY) Input Method Editor (IME) がインストールされているシステムで特定のアクションを実行すると、この脆弱性により、特権が昇格される場合があります。攻撃者によりこの脆弱性が悪用された場合、カーネルモード内の任意のコードが実行される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全な管理者権限を持つ新たなアカウントを作成する可能性があります この脆弱性で影響を受けるのは、Microsoft Pinyin IME 2010 の実装のみです。その他のバージョンの簡体字中国語版 IME およびその他の実装の IME は影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、 リモートでコードが実行される (2590602) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別な細工がされた Word ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Microsoft Publisher の脆弱性により、 リモートでコードが実行される (2607702) <br />
<br />
このセキュリティ更新プログラムは Microsoft Office に存在する 1 件の一般に公開された脆弱性および 3 件の非公開で報告された脆弱性を解決します。この最も深刻な脆弱性は、特別に細工された Publisher ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。攻撃者がこれらの脆弱性のいずれかを悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;">OLE の脆弱性により、リモートでコードが実行される (2624667) <br />
<br />
このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 の非公開で報告された脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP、Windows Server 2003 について、深刻度は「重要」です。Windows Vista、Windows Server 2008、Windows 7 および Windows Server 2008 R2 はこの脆弱性の影響を受けません。<br />
<br />
この脆弱性により、ユーザーが特別に細工された OLE オブジェクトを開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;">Microsoft PowerPoint の脆弱性により、リモートでコードが実行される (2639142) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性により、特別に細工された PowerPoint ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかを攻撃者が悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;">Active Directory の脆弱性により、リモートでコードが実行される (2640045) <br />
<br />
このセキュリティ更新プログラムは Active Directory、Active Directory Application Mode (ADAM) および Active Directory Lightweight Directory Service (AD LDS) に存在する非公開で報告された脆弱性を解決します。これらの脆弱性により、攻撃者が Active Directory ドメインにログオンし、特別に細工されたアプリケーションを実行した場合、リモートでコードが実行される可能性があります。この脆弱性が悪用されるには、まず、Active Directory ドメインにログオンするための資格情報を取得することが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2640241) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。Office のファイル検証 (OFV) をインストールおよび構成して、疑わしいファイルの表示を防ぐことにより、CVE-2011-3403 で説明している脆弱性を悪用するための攻撃手法をブロックします。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;">Windows クライアント/サーバー ランタイム サブシステムの脆弱性により、 特権が昇格される (2620712) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるコンピューターにログオンし、デバイス イベント メッセージを整合性レベルの高いプロセスに送信するため特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、特権が昇格される (2633171) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。これらの脆弱性により、攻撃者が影響を受けるシステムにログオンし、この脆弱性を悪用することを目的として特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーが、この脆弱性を悪用することはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ 更新プログラム (2618444) <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 3 件の Internet Explorer に存在する脆弱性を解決します。このうち最も深刻な脆弱性では、特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じディレクトリにある正当な HyperText Markup Language (HTML) ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">.NET Frameworkの脆弱性 により、 特権が 昇格される (2638420) <br />
<br />
このセキュリティ更新プログラムは、Microsoft .NET Framework における、1 件の公式に公開された脆弱性と、3 件の非公式に報告された脆弱性を解決します。これらの脆弱性で最も深刻なのは、非認証の攻撃者が特別に細工された Web の要求を標的のサイトに送った場合に特権の昇格が許可されるということにあります。この脆弱性の悪用に成功した攻撃者は、任意のコマンドの実行を含む、ASP.NET サイトに実際に存在するアカウントを使用したあらゆるアクションを行うことができます。この脆弱性を悪用するためには、攻撃者は実際に存在するユーザー名で、ASP.NET サイトに登録できるようになる必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
| セキュリティ情報 ID                                       | 脆弱性のタイトル                                                     | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価               | 旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価       | サービス拒否の悪用可能性の評価 | 注意事項                                                                                                                    |  
|-----------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------|  
| [MS11-087](http://go.microsoft.com/fwlink/?linkid=233008) | TrueType フォントの解析の脆弱性                                      | [CVE-2011-3402](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | この脆弱性は一般に公開されていました。                                                                                      |  
| [MS11-088](http://go.microsoft.com/fwlink/?linkid=227070) | Pinyin IME 昇格の脆弱性                                              | [CVE-2011-2010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2010) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | (なし)                                                                                                                      |  
| [MS11-089](http://go.microsoft.com/fwlink/?linkid=225739) | Word の解放後使用の脆弱性                                            | [CVE-2011-1983](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1983) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-090](http://go.microsoft.com/fwlink/?linkid=232507) | Microsoft Time でリモートでコードが実行される脆弱性                  | [CVE-2011-3397](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3397) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-091](http://go.microsoft.com/fwlink/?linkid=235287) | Publisher の境界外の配列のインデックスの脆弱性                       | [CVE-2011-3410](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3410) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-091](http://go.microsoft.com/fwlink/?linkid=235287) | Publisher の無効なポインターの脆弱性                                 | [CVE-2011-3411](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3411) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-091](http://go.microsoft.com/fwlink/?linkid=235287) | Publisher のメモリの破損の脆弱性                                     | [CVE-2011-3412](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3412) | 影響なし                                                                              | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | 対象外                         | (なし)                                                                                                                      |  
| [MS11-092](http://go.microsoft.com/fwlink/?linkid=232517) | Windows Media Player DVR-MS のメモリ破損の脆弱性                     | [CVE-2011-3401](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3401) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-093](http://go.microsoft.com/fwlink/?linkid=232516) | OLE プロパティの脆弱性                                               | [CVE-2011-3400](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3400) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-094](http://go.microsoft.com/fwlink/?linkid=232493) | PowerPoint の安全でないライブラリのロードの脆弱性                    | [CVE-2011-3396](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3396) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | Microsoft PowerPoint 2010 が影響を受けるのは、最新のサービスパックがインストールされていない場合のみです。                  |  
| [MS11-094](http://go.microsoft.com/fwlink/?linkid=232493) | OfficeArt の図形の RCE の脆弱性                                      | [CVE-2011-3413](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3413) | 影響なし                                                                              | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | 対象外                         | (なし)                                                                                                                      |  
| [MS11-095](http://go.microsoft.com/fwlink/?linkid=232666) | Active Directory のバッファー オーバーフローの脆弱性                 | [CVE-2011-3406](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3406) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | Active Directory、AD LDS、または ADAM を実行しているコンピューターのみが影響を受けます。                                    |  
| [MS11-096](http://go.microsoft.com/fwlink/?linkid=232696) | レコードのメモリ破損の脆弱性                                         | [CVE-2011-3403](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3403) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-097](http://go.microsoft.com/fwlink/?linkid=232663) | CSRSS のローカルの特権の昇格の脆弱性                                 | [CVE-2011-3408](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3408) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                      |  
| [MS11-098](http://go.microsoft.com/fwlink/?linkid=232424) | Windows カーネルの例外ハンドラーの脆弱性                             | [CVE-2011-2018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2018) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                                                                                                                      |  
| [MS11-099](http://go.microsoft.com/fwlink/?linkid=232505) | XSS フィルターの情報漏えいの脆弱性                                   | [CVE-2011-1992](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1992) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 対象外                         | これは情報漏えいの脆弱性です。                                                                                              |  
| [MS11-099](http://go.microsoft.com/fwlink/?linkid=232505) | Internet Explorer の安全でないライブラリのロードの脆弱性             | [CVE-2011-2019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2019) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | (なし)                                                                                                                      |  
| [MS11-100](http://go.microsoft.com/fwlink/?linkid=232432) | ハッシュテーブルの衝突がサービス拒否を引き起こす可能性のある脆弱性 - | [CVE-2011-3414](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3414) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 一時的                         | これは、サービス拒否の脆弱性であり、一般に公開されていました。サービス拒否の脆弱性は、悪用可能性指標「3」の評価になります。 |  
| [MS11-100](http://go.microsoft.com/fwlink/?linkid=232432) | ASP.Net フォームの認証バイパスの脆弱性 -                             | [CVE-2011-3416](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3416) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | 特権の昇格 - アカウントの引き継ぎ                                                                                           |  
| [MS11-100](http://go.microsoft.com/fwlink/?linkid=232432) | ASP.Net フォームの認証のチケットをキャッシュする脆弱性 -             | [CVE-2011-3417](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3417) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | 対象外                         | 特権の昇格 - アカウントの引き継ぎ                                                                                           |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント
  
表 1:

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-087](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](http://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b01bb041-005c-48c4-a606-66aa264ba0fa)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=21b4b999-2dbf-4921-80bd-cc7ab2cd1190)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d85091b5-69bb-4d0f-839a-a65cd94e2887)  
(KB2619339)  
(緊急)  
[Windows XP Media Center Edition 2005 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=03bc6446-7cf3-47c4-8ed1-a53a4d53a429)  
(KB2619340)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73531165-f299-4b62-b738-52fca410eaae)  
重要
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3b816964-d3c3-4f05-94c3-f54a6f54ca73)  
(KB2626416)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=edb594a4-14d2-4ffe-8d1c-2c283689fe8c)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0a872cd2-5f4d-400c-a1c4-a2d194746fb6)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=126e8092-980d-471a-867d-d5939671b7df)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7d1d1e9a-603c-4895-a69f-b61186a75ad5)  
(KB2619339)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a98bb7cf-9939-4927-8d21-ccb3845e7cb7)  
重要
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=986f0087-c674-4060-8710-af3496adbfdd)  
(KB2626416)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9e1273e2-7775-40b4-b939-ab530677cd4a)  
重要
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-087](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](http://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e84e6964-1580-41ef-9d3e-4d0c3ad4cb69)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dfb948c5-8aee-4bcd-babf-3564b78712dd)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6b555040-1117-4b06-a48c-02f0e1b686d8)  
重要
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=01caf06f-777d-4ea8-95ca-e11d60a973ad)  
(KB2621146)  
重要  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6f7c7ccd-22a3-4fbc-bf21-bd0e42ab1da5)  
(KB2626416)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a14057e5-e2c2-4dde-8d26-542a9f162e98)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9d9f3667-3fd6-4948-83db-282783599f41)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2d37a8cb-2316-4db4-980c-11b6dcbdc696)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eb17782c-f754-42ab-905b-6f141df008c3)  
重要
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1ba50cf-fc6b-4668-b71c-e9f75a8ac638)  
(KB2621146)  
重要  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1b610eb3-456c-4125-94b7-1ead4face8e3)  
(KB2626416)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7f595fd6-bdfd-4075-97e5-70efb7d49dff)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1ecf72cd-6732-4cf3-aa22-8caf15ea633e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7726ddbe-0578-44fb-a40f-49b804a45989)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4cdde8a9-6d44-41fa-82c0-a25404cdfbb5)  
重要
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=74099261-60ad-4c68-906c-60e131818955)  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=147ec6d3-3401-4aa3-a409-55346bcc7bd7)  
重要
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-087](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](http://go.microsoft.com/fwlink/?linkid=232663)
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
なし
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7f69ec9d-43ad-4106-90ef-c191e7ec43af)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1dd069a2-fb1a-4f31-88cc-bc031c3e2c80)  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e9130fad-de8c-4be0-aea1-62cbaa310b76)  
(KB2619339)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=470da512-2c8b-4ba9-b7bb-b9e6c45cd33f)  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fa6e6d91-4aca-49a6-a6e8-c33ec413097e)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ae1f1f86-6f13-4e1e-9f93-4f70b6c9927e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=60fd5bf6-e820-44f6-8081-b98c0103acc1)  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b7c4bf05-eb2d-48ac-a6df-8afd88e811d8)  
(KB2619339)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8daf9a49-60cb-4813-ac7a-e9a4bf296889)  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c9794756-803d-48ba-86db-350fb577f01b)  
重要
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-087](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](http://go.microsoft.com/fwlink/?linkid=232663)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c4ba344d-dd0d-4cfb-81d9-d364d7f37e25)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f485d4c3-a4af-4ae6-9404-e79afcbb4f6e)\*\*  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6f9ddcdb-a471-4e00-a697-92a24e4ea8d4)\*  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6f934885-b134-400c-a452-50fd4eeedd5e)\*  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=058963f6-9654-41d0-86d2-f25a0c2ad416)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=28598ef6-13fb-44fd-8c76-599af7b0a01d)\*\*  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5253477b-422f-404a-941e-8b69da5a2670)\*  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7ade3832-bc20-4fce-8eac-8a3d072d2f1c)\*  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=42cd1c33-11a7-4a29-ae85-f7272a626f91)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5915e19c-b576-453b-b621-5737774f5955)  
(深刻度なし<sup>[1]</sup>)
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
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4bd7a02b-c6d8-4eb5-a46d-e494a1233dc8)  
重要
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-087](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](http://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0526727a-f2fb-4846-9b04-f1899f52f1f6)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d112623c-86ce-434a-8fe1-ec3e3e632763)  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b6e44069-dec5-48f6-8fc4-8ab375a10b4e)  
(KB2619339)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d2e87199-6469-4bc0-a721-f43e817e4344)  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0666bdf5-9eed-44c9-84ee-b45f9b3e14b3)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cfd42c42-1595-419a-bf04-b23b64663629)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=81114ecd-0c73-4ca6-8a66-09c6c636a5db)  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f7997ab8-27e0-4714-845a-d237f4326587)  
(KB2619339)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ba8d7aa9-8299-49a3-b0c0-b8b5eab48434)  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=620f94f9-1f61-45a0-a22e-e7510b56b9b8)  
重要
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-087](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[MS11-090](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[MS11-092](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[MS11-093](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[MS11-095](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[MS11-097](http://go.microsoft.com/fwlink/?linkid=232663)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d64a31ca-cccd-488a-98fd-c059b9e9e1ea)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bc018647-08cb-431a-8e7c-5dc04980eaa9)\*\*  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a3e0d27c-8b29-4981-bdef-bcd037fd3408)\*  
(KB2621146)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=04878e9a-539a-4549-a5af-11d45add91da)\*  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b46f6da7-6d24-4262-8e55-3b657db39813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9323b9b9-e9b0-4941-afe0-196d22df9ab4)  
(深刻度なし<sup>[1]</sup>)
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
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5b2ebec4-cebb-47b6-864a-12d59a9a3e18)  
重要
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*\*\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールした場合、この更新プログラムの深刻度は低くなります。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS11-090 に関する注意

<sup>[1]</sup> この特定のオペレーティング システムは、このセキュリティ情報で説明している脆弱性の影響を受けません。この利用可能な更新プログラムは、サード パーティのコントロール用の Kill bit を設定します。

表 2

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-098](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7a6fcf8d-8c7b-4882-90d3-02db79a75238)  
重要
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=caa9360b-2fd8-4f46-99e6-2decf1b60ca7)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dc6dcd8c-c39f-4c4b-b5b2-b4c18c36973b)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f3906245-b6f6-464a-84b6-e1b6b195df95)  
重要
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2fa77733-70f5-46ff-9cfe-2262d292b870)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a0c55d9b-8529-4d3d-910d-1a822a825be2)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3e60e996-8850-4d25-b994-39646e2cc25e)  
重要
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-098](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=281e5bd4-4582-4aa9-af88-518ad3152132)  
重要
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=759041cf-fd8b-4e04-b289-d74112bf978b)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1b4af92-3ff1-4727-9ba3-52764a7b81bb)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1cbe9469-05f4-4305-bbfd-76b4a04cd598)  
(注意)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7538762a-50e9-4f13-a60e-ff99aa8fbbf8)  
(KB2656358)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5587eca8-86e9-4a63-81cb-81f68178a6c0)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7a87f890-f106-41ab-bc53-4ca44dc99cb1)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a42fa727-482c-4578-9a30-61fdf14ed4da)  
(注意)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=02d5c057-d551-411b-917b-43d7795111bc)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2fccb214-6c79-4ef6-9d6e-df4f16ef792e)  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-098](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](http://go.microsoft.com/fwlink/?linkid=232432)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a6c7c960-768d-40d4-8fe5-7d59f48ead1d)  
重要
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0adc422f-73f2-46ee-973f-9b7603a76d1e)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4327147b-0481-4172-a835-8786abc50596)  
重要  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a0b19b35-1d48-4419-ba3d-66063cc472a7)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8a3f2351-380b-4566-b186-906dca426d39)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=987f0966-01de-4edf-a0d6-4032d1d72966)  
重要  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c951044b-4596-462f-bc8f-bdd9d6734297)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-098](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](http://go.microsoft.com/fwlink/?linkid=232432)
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
[注意](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5a4443f8-fec8-42be-ad67-8475920f1460)\*  
重要
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eaf587f0-9951-4480-a08b-377e61aaf72b)\*\*  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8f5af52f-dece-4f0c-9fc0-d4973e4f7b1a)\*\*  
(注意)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c03e65d6-4f92-4bc1-94b5-2f0183d0133e)\*\*  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2f18fc98-984a-4c02-951f-b8438a9e4f6b)\*\*  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=808d26f7-c8fa-446d-9d2f-e8c0babb0c4a)\*\*  
(注意)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b7a582f3-0a18-4fbf-9b99-21c664bfd979)\*\*  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc62df39-7185-448b-b356-25a5a07886ec)  
(深刻度なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-098](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eb2bd108-5ef1-45be-9157-e7cbfc8afd2a)  
重要
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=018610bb-e80a-432a-8f32-f50451f71ad9)  
重要  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ec2046a6-f069-4f02-9600-7640e57be0a3)  
重要
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dbe85b05-e252-4029-8e25-f2452db1c017)  
重要  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c773b3d-0ca3-4b9b-af9a-9d6edcd261f7)  
重要
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows 7 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-098](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[MS11-099](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[MS11-100](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2108b4ef-942f-4727-a1fc-ee7d0abb427c)\*\*  
(注意)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=72c1654e-526f-4ece-b7ad-767a0710e076)\*\*  
重要
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)\*  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)\*  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=74614510-e13c-43e8-90e7-d81e63895cf2)  
(注意)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS11-099 に関する注意

<sup>[1]</sup> 指定ソフトウェアのこの更新プログラムには深刻度が適用されません。このセキュリティ情報で説明する脆弱性に対する既知の攻撃方法は、既定の構成でブロックされるからです。しかし、マイクロソフトでは、このソフトウェアをご使用のお客様に、多層防御策としてこのセキュリティ更新プログラムの適用を推奨します。

MS11-100 に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「.NET Framework のインストール」を参照してください。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="6">
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-088](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[MS11-089](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[MS11-091](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[MS11-094](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[MS11-096](http://go.microsoft.com/fwlink/?linkid=232696)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
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
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=13f3e884-37bf-4ed2-b3ed-a0e7fb48e44f)  
(KB2553084)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5859014f-afc5-4958-82ea-6ba45a5ad4b3)  
(KB2596954)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2 および Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2 および Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e924cd85-5764-4056-bd32-b0e57dc25146)  
(KB2596785)  
重要
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 Service Pack 2 および Microsoft Publisher 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2856821e-f1fd-424b-b03c-e443685eea6d)  
(KB2596705)  
重要
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d0c3156c-c87c-4d3e-aca2-3fab9ff78711)  
(KB2596764)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d812621e-c35a-4cb0-ba26-928363f3422d)  
(KB2596511)  
重要
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e47c0694-a9a5-4dd7-bfba-e470d9855c28)  
(KB2589320)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd32d083-46e7-4835-ba83-c33332b920bd)  
(KB2553185)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c8d3ac17-5aca-4da3-961f-b753be4a3634)  
(KB2596511)  
重要
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6c2d5273-eef9-4ff6-be6f-8d86f417f004)  
(KB2589320)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f28b8cf6-8946-448a-ae4e-d11f8a76a679)  
(KB2553185)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-088](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[MS11-089](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[MS11-091](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[MS11-094](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[MS11-096](http://go.microsoft.com/fwlink/?linkid=232696)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
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
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ef3b559c-0bd2-45dd-8049-6946f6431a2a)  
(KB2644358)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
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
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2c4d0381-f7ab-49ed-a0c0-b381387d1e68)  
(KB2644354)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3c8017d6-232c-42a6-a133-96efe3ad3385)  
(KB2644347)  
重要
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
<th colspan="6">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-088](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[MS11-089](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[MS11-091](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[MS11-094](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[MS11-096](http://go.microsoft.com/fwlink/?linkid=232696)
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
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer 2007 Service Pack 2
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
[Microsoft PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4417592a-8db0-4e35-9895-d589bc341077)  
(KB2596912)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2
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
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e799f654-7e2d-40c7-a3b8-32e44d1aa6ee)  
(KB2596843)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 および Microsoft Office Pinyin New Experience Style 2010 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 および Microsoft Office Pinyin New Experience Style 2010 (32 ビット版)<sup>[1]</sup>
重要
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
Microsoft Office Pinyin SimpleFast Style 2010 および Microsoft Office Pinyin New Experience Style 2010 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 および Microsoft Office Pinyin New Experience Style 2010 (64 ビット版)<sup>[1]</sup>
重要
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
</table>

<p></p>

 
MS11-088 に関する注意

<sup>[1]</sup>このバージョンの Microsoft Office Pinyin は現在サポートされていません。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様はセーフティとセキュリティ センターを参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、Microsoft ダウンロード センターからもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「更新プログラムを自動的にチェックする」を参照してください。

さらに、セキュリティ更新プログラムは、Microsoft Update カタログからダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、Microsoft Update Catalog FAQ (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、サポート技術情報 961747 を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、Microsoft Baseline Security Analyzer を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、Microsoft Windows Server Update Services (WSUS) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](http://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、System Center Configuration Manager を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management (英語情報) を参照してください。SMS の詳細については、Systems Management Server を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、Deploying Software Updates Using the SMS Software Distribution Feature (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、サポート技術情報 913086 を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、IT プロフェッショナル セキュリティ コミュニティにアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/ja-jp/security/bulletin/policy)を表します。

-   MS11-087 で説明されている問題についてマイクロソフトと協力してくださった Symantec および Laboratory of Cryptography and System Security (CrySyS)
-   MS11-088 で説明されている問題を報告してくださった Yang Yanbei 氏
-   [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-089 で説明している問題を報告してくださった、Nikita Tarakanov 氏 (CISS Research Team) および Alexey Sintsov 氏 (Digital Security Research Group)
-   [VeriSign iDefense Labs](http://labs.idefense.com) と協力して、MS11-090 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-091 で説明している 3 件の問題を報告してくださった [CERT/CC](http://www.cert.org/) の Will Dormann 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com) と協力して、MS11-092 で説明している問題を報告してくださった匿名のリサーチャー
-   [VeriSign iDefense Labs](http://labs.idefense.com) と協力して、MS11-093 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-094 で説明している問題を報告してくださった [iSIGHT Partners Labs](http://www.isightpartners.com/) の Greg MacManus 氏
-   [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-094 で説明している問題を報告してくださった匿名のリサーチャー
-   [VeriSign iDefense Labs](http://labs.idefense.com) と協力して、MS11-096 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-097 で説明している問題を報告してくださった Winsider Seminars & Solutions Inc. の Alex Ionescu 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS11-098 で説明している問題を報告してくださった Matthew Jurczyk 氏
-   MS11-099 で説明している問題を報告してくださった Thomas Stehle 氏
-   MS11-099 で説明している問題を報告してくださった [Citrix Security Team](http://www.citrix.com) の Andy Cooper 氏
-   MS11-099 で説明している問題を報告してくださった [Google Inc.](http://www.google.com/) の [Robert Swiecki](http://www.swiecki.net/) 氏
-   MS11-099 で説明している問題についてマイクロソフトに協力してくださった [Yosuke Hasegawa](http://utf-8.jp/) 氏
-   MS11-099 に組み込まれている多層防御についてマイクロソフトに協力してくださった [Jan Schejbal](http://janschejbal.wordpress.com/) 氏
-   MS11-100 で説明している問題を報告してくださった [Seeker](http://www.seekersec.com) の Irene Abezgauz 氏
-   MS11-100 で説明している問題を報告してくださった [SEC Consult](https://www.sec-consult.com/) の Kestutis Gudinavicius 氏
-   MS11-100 で説明している問題を報告してくださった [LBi](http://www.lbi.com/) の Oliver Dewdney 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/?ln=ja)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2011/12/14): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2011/12/15): このセキュリティ情報ページを更新し、MS11-099 について、「影響を受けるソフトウェア」の表の深刻度を修正しました。また、MS11-088 について、Exploitability Index (悪用可能性指標) の「注意事項」を修正しました。これらは、いずれも情報のみの変更です。このセキュリティ情報のセキュリティ更新プログラムのファイルおよび検出ロジックへの変更はありません。
-   V2.0 (2011/12/30): マイクロソフト セキュリティ情報 MS11-100「.NET Framework の脆弱性により、特権が昇格される (2638420)」を追加しました。また、この定例外のセキュリティ情報に関する Webcast のリンク先も追加しました。
-   V2.1 (2012/2/24): MS11-088 について、Microsoft Office Pinyin SimpleFast Style 2010 および Microsoft Office Pinyin New Experience Style 2010 の製品サポート状況を明確にしました。これらのバージョンの Microsoft Office Pinyin は現在サポートされていません。(詳細はセキュリティ情報をご覧ください。)

*Built at 2014-04-18T01:50:00Z-07:00*
