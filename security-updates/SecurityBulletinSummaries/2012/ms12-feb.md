---
TOCTitle: 'MS12-FEB'
Title: 2012 年 2 月のセキュリティ情報
ms:assetid: 'ms12-feb'
ms:contentKeyID: 61229697
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-feb(v=Security.10)'
--- 

2012 年 2 月のセキュリティ情報
==============================

公開日: 2012年2月15日

**バージョン:** 1.0

[](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627276.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627276.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)[](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2012 年 2 月公開のセキュリティ情報の一覧です。

2012 年 2 月のセキュリティ情報の公開により、2012 年 2 月 10 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「マイクロソフト セキュリティ情報の事前通知」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2012 年 2 月 15 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 2 月 15 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。 [2 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499501) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、 [Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238387">MS12-008</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2660465) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の非公開で報告された脆弱性および 1 件の一般に公開された脆弱性を解決します。これらの脆弱性のより深刻な状況では、特別に細工したコンテンツが含まれている Web サイトをユーザーが訪問した場合、または、特別な細工がされたアプリケーションをユーザーがローカルに実行した場合、リモートでコードが実行される可能性があります。攻撃者は、悪意のある Web サイトにユーザーを強制的に訪問させることはできません。そのかわり、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせて攻撃者の Web サイトに誘導することにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=236989">MS12-010</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2647516) <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 4 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238617">MS12-013</a></td>
<td style="border:1px solid black;">C ランタイム ライブラリの脆弱性により、リモートでコードが実行される (2654428) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが Web サイトでホストされている、または電子メールの添付として送信された特別に細工されているメディア ファイルを開いた場合に、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235370">MS12-016</a></td>
<td style="border:1px solid black;">.NET Framework および Microsoft Silverlight の脆弱性により、リモートでコードが実行される (2651026) <br />
<br />
このセキュリティ更新プログラムは Microsoft .NET Framework および Microsoft Silverlight に存在する 1 件の公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。この脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) または Silverlight アプリケーションを使用して、特別に細工された Web ページを閲覧した場合に、クライアント システムでリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft .NET Framework、<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238474">MS12-009</a></td>
<td style="border:1px solid black;">Ancillary Function ドライバーの脆弱性により、特権が昇格される (2645640) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性により、攻撃者がユーザーのシステムにログオンし、特別な細工が施されたアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238500">MS12-011</a></td>
<td style="border:1px solid black;">Microsoft SharePoint の脆弱性により、特権が昇格される (2663841) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft SharePoint および Microsoft SharePoint Foundation の脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された URL をクリックした場合、特権の昇格または情報の漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239941">MS12-012</a></td>
<td style="border:1px solid black;">カラー コントロール パネルの脆弱性により、リモートでコードが実行される (2643719) <br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じディレクトリにある正当なファイル (.icm ファイルや .icc ファイルなど) を開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239945">MS12-014</a></td>
<td style="border:1px solid black;">Indeo コーデックの脆弱性により、リモートでコードが実行される (2661637) <br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じディレクトリにある正当なファイル (.avi ファイルなど) を開いた場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ログオン ユーザーとして任意のコードを実行する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを完全に制御する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238400">MS12-015</a></td>
<td style="border:1px solid black;">Microsoft Visio Viewer 2010 の脆弱性により、リモートでコードが実行される (2663510) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 5 件の Microsoft Office に存在する脆弱性を解決します。特別に細工された Visio ファイルをユーザーが開いた場合、この脆弱性によりリモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
  
| セキュリティ情報 ID                                       | 脆弱性のタイトル                                                 | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価               | 旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価       | サービス拒否の悪用可能性の評価 | 注意事項                                                                                                                                             |  
|-----------------------------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS12-008](http://go.microsoft.com/fwlink/?linkid=238387) | キーボード レイアウトの解放後使用の脆弱性                        | [CVE-2012-0154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0154) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                                               |  
| [MS12-008](http://go.microsoft.com/fwlink/?linkid=238387) | GDI のアクセス違反の脆弱性                                       | [CVE-2011-5046](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-5046) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | 永続的                         | この脆弱性は一般で公開されていました。                                                                                                               |  
| [MS12-009](http://go.microsoft.com/fwlink/?linkid=238474) | AfdPoll の特権の昇格の脆弱性                                     | [CVE-2012-0148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0148) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 永続的                         | x64 は悪用される可能性があります。x86 については悪用される可能性はありません。                                                                       |  
| [MS12-009](http://go.microsoft.com/fwlink/?linkid=238474) | Ancillary Function ドライバーの特権の昇格の脆弱性                | [CVE-2012-0149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0149) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | Windows Server 2003 のみが影響を受けます。                                                                                                           |  
| [MS12-010](http://go.microsoft.com/fwlink/?linkid=236989) | HTML レイアウトのリモートでコードが実行される脆弱性              | [CVE-2012-0011](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0011) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 一時的                         | (なし)                                                                                                                                               |  
| [MS12-010](http://go.microsoft.com/fwlink/?linkid=236989) | Null バイトの情報漏えいの脆弱性                                  | [CVE-2012-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0012) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 影響なし                                                                              | 対象外                         | これは情報漏えいの脆弱性です。                                                                                                                       |  
| [MS12-010](http://go.microsoft.com/fwlink/?linkid=236989) | VML のリモートでコードが実行される脆弱性                         | [CVE-2012-0155](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0155) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 一時的                         | (なし)                                                                                                                                               |  
| [MS12-011](http://go.microsoft.com/fwlink/?linkid=238500) | inplview.aspx の XSS の脆弱性                                    | [CVE-2012-0017](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0017) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | (なし)                                                                                                                                               |  
| [MS12-011](http://go.microsoft.com/fwlink/?linkid=238500) | themeweb.aspx の XSS の脆弱性                                    | [CVE-2012-0144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0144) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | (なし)                                                                                                                                               |  
| [MS12-011](http://go.microsoft.com/fwlink/?linkid=238500) | wizardlist.aspx の XSS の脆弱性                                  | [CVE-2012-0145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0145) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | (なし)                                                                                                                                               |  
| [MS12-012](http://go.microsoft.com/fwlink/?linkid=239941) | カラー コントロール パネルの安全でないライブラリのロードの脆弱性 | [CVE-2010-5082](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-5082) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | この脆弱性は一般で公開されていました。                                                                                                               |  
| [MS12-013](http://go.microsoft.com/fwlink/?linkid=238617) | Msvcrt.dll のバッファー オーバーフローの脆弱性                   | [CVE-2012-0150](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0150) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 一時的                         | (なし)                                                                                                                                               |  
| [MS12-014](http://go.microsoft.com/fwlink/?linkid=239945) | Indeo コーデックの安全でないライブラリのロードの脆弱性           | [CVE-2010-3138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3138) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | この脆弱性は一般で公開されていました。                                                                                                               |  
| [MS12-015](http://go.microsoft.com/fwlink/?linkid=238400) | VSD ファイル形式のメモリ破損の脆弱性                             | [CVE-2012-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0019) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | これは Visio Viewer 2010 および Visio Viewer 2010 Service Pack 1 (これらは Visio Viewer の唯一サポートされているバージョンです) に影響を及ぼします。 |  
| [MS12-015](http://go.microsoft.com/fwlink/?linkid=238400) | VSD ファイル形式のメモリ破損の脆弱性                             | [CVE-2012-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0020) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                              | 対象外                         | これは Visio Viewer 2010 および Visio Viewer 2010 Service Pack 1 (これらは Visio Viewer の唯一サポートされているバージョンです) に影響を及ぼします。 |  
| [MS12-015](http://go.microsoft.com/fwlink/?linkid=238400) | VSD ファイル形式のメモリ破損の脆弱性                             | [CVE-2012-0136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0136) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 影響なし                                                                              | 対象外                         | これは Visio Viewer 2010 および Visio Viewer 2010 Service Pack 1 (これらは Visio Viewer の唯一サポートされているバージョンです) に影響を及ぼします。 |  
| [MS12-015](http://go.microsoft.com/fwlink/?linkid=238400) | VSD ファイル形式のメモリ破損の脆弱性                             | [CVE-2012-0137](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0137) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 影響なし                                                                              | 対象外                         | これは Visio Viewer 2010 および Visio Viewer 2010 Service Pack 1 (Visio Viewer の唯一サポートされているバージョンです) に影響を及ぼします。          |  
| [MS12-015](http://go.microsoft.com/fwlink/?linkid=238400) | VSD ファイル形式のメモリ破損の脆弱性                             | [CVE-2012-0138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0138) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 影響なし                                                                              | 対象外                         | これは Visio Viewer 2010 および Visio Viewer 2010 Service Pack 1 (これらは Visio Viewer の唯一サポートされているバージョンです) に影響を及ぼします。 |  
| [MS12-016](http://go.microsoft.com/fwlink/?linkid=235370) | .NET Framework のアンマネージ オブジェクトの脆弱性               | [CVE-2012-0014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0014) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                                                                                                               |  
| [MS12-016](http://go.microsoft.com/fwlink/?linkid=235370) | .NET Framework のヒープ破損の脆弱性                              | [CVE-2012-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0015) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | この脆弱性は一般で公開されていました。                                                                                                               |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="8">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
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
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=832afe5e-d61e-4554-b889-9174df042b32)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a7d59fa8-0a49-4985-9f14-92218d3b5cea)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6025c5d6-696c-49cd-9264-96af5766d318)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5b37f5b1-207f-4fa1-9769-c873d672e80c)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=32e5c9ad-b610-4afb-b6f0-bb0b5fbdd1f6)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ff2c141c-08b4-42c6-9f66-580f8678c01f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=96d404e7-8928-494e-8a3c-3897817cda7b)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b40bc334-edbc-48d5-9196-b7fb0e19966e)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2fc9d519-94b3-4b56-92fd-4c0ccf8210fe)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=82f5c503-d2ea-4fed-8f9d-f30bee2f60b3)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f0e6e06d-89db-45ad-9660-7959c6f9b546)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c4642890-2fba-45da-bbe9-fcaa84e4aa0c)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9e157b88-2c11-44dc-b13d-1051f9c39890)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bf8ad019-e710-4e16-be4f-8168df5c5343)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5ee4bef7-b355-4aae-8bba-834a16d44744)  
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b81decda-9d82-4ffb-baae-78b190e553ea)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c4a52801-55b5-4eef-9db3-c29a45863198)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f162ad36-c096-43ba-a440-ec4d3fb54c21)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ef4a9002-b2da-40af-abc0-737565fea179)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b53cf810-0ea3-4cb0-91f9-de1406ccfc96)  
(重要)
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
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8dcd71c8-82ad-4f86-b386-7f1ea09e157f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3b42f935-7f59-4871-a01f-480033c3ad40)  
(深刻度なし<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24fe7c08-4736-455b-9b98-1b6a65718143)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3b18d22d-e192-498b-a105-b946a5f5bfad)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5852118c-fc39-45e2-8b44-ce1401d310e2)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6ec23c7e-0166-47dc-ae86-c49b505206bb)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbf627df-0bc0-478f-aa34-a7e5f039e589)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d287496a-411c-4c1b-9d98-bacc553041ae)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c503c7b1-24f8-40a4-8283-c1e4abf90b57)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
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
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5161d16d-1037-49d5-8d4d-c353288cb41c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b30a8cc5-b9ad-476f-928c-c49c993d0e80)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3a8b966a-bf34-42fd-8758-9a5e8e3c7689)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22cc0245-1877-4c76-914f-dd68f6cd45f0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ddbd9fcf-10c4-4089-88c0-c2a6c288222b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73e240a6-2d5e-4ceb-8500-8dacca0e4a43)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=45c6c511-a4fa-4c3b-af26-6c113f6f5f5e)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=21f7dba4-fe97-487e-8b37-45914e106db0)\*\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=98d5b024-0eda-4e5d-ba9d-b828ad3d048e)\*\*  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=025a5af0-39f1-481c-920c-43d2b3d85dc5)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0c1812af-f57d-455d-a81d-5e03db99b2f7)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3f6f89b3-3bc8-4325-b8d8-9a5a398b99c6)\*\*  
(重要)
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
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=046932cf-0671-49e6-8ddf-98abfc97c5f0)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2cd8e296-dae8-41ce-8373-f8a71b4555e9)\*\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=246f9995-fe19-43d0-8f67-0e91eb961bab)\*\*  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c216e01d-2f46-4a46-bdc7-9d0fe98193a3)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1b66bb5-ea12-44a5-807a-f21ede0dc76d)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0e06e77d-7e5d-4d57-98b2-0817f68a1ebb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=35e6bd04-594f-42ef-97f8-abcf578b4f10)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=304bd0c5-f4ee-4f8c-89b4-4cbaaf418679)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=05c0e6eb-c641-43ab-958a-f43933cdbba7)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3a96ab34-8f45-48bf-a98b-9e683b50aaa0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=56cbeba9-0c39-4418-9042-7244ac9d03db)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d1d51b26-2d01-42a9-9bb1-9fb82c1fb914)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
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
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3e5ca1bf-9415-412c-9dff-dd1abc57e74d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b423683-cd29-4049-82d6-f0845842e7f0)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c83a9c74-a5a7-4b3e-ba36-7a7024d99fd8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=403f355c-2273-42ac-8263-d662f5d7740c)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=78cbbe02-a3d3-4cef-9b54-a3e78c1b885a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a5d00138-4e24-4a07-92dd-3d8a14476197)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbc9d6ae-9ec5-401f-bf16-4811b63709d1)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8bd8e804-ca4d-4326-bc60-345e2975b7aa)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=299d107d-ab9f-42b6-8f94-a2f1d242c127)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6b228ad6-d5a4-4b91-8aa8-0874deb22116)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3074a898-54bb-44ff-a8f4-77f831c28771)\*\*  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1896a6da-f7ee-484b-a97c-455fce7b82b8)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d868c5ef-165a-46a0-b832-e6ca55a910f9)\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)\*  
(KB2633879)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)\*  
(KB2633873)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)\*<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=576192d3-f050-4718-a7da-c84fce6bf744)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8c51e09b-51c3-4860-836e-6bcffde75f04)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=922b2438-0cfc-49e3-b9a0-52c68b69126a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7f7c0bc3-fc26-4ee8-aedb-c251247cbeb5)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e5416371-495b-4dc7-a239-f9185f968969)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
(緊急)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6a9b2c9-7582-4953-8ab1-a55c63fcc8dc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fba58a1b-9d9f-4a10-b1df-08a0ebfa2358)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*\*\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールした場合、この更新プログラムの深刻度は低くなります。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS12-010 に関する注意

<sup>[1]</sup> 指定ソフトウェアのこの更新プログラムには深刻度が適用されません。このセキュリティ情報で説明する脆弱性に対する既知の攻撃方法は、既定の構成でブロックされるからです。しかし、マイクロソフトでは、このソフトウェアをご使用のお客様に、多層防御策としてこのセキュリティ更新プログラムの適用を推奨します。

MS12-016に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「.NET Framework のインストール」を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-015](http://go.microsoft.com/fwlink/?linkid=238400)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=173dc4e6-31b4-42ec-808c-f8cd005517ab)  
(KB2597170)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34b234e1-1322-4edc-829c-7bc2fbd99338)  
(KB2597170)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-011](http://go.microsoft.com/fwlink/?linkid=238500)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 および Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 および Microsoft SharePoint Server 2010 Service Pack 1 (moss)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=44a8eb5a-e469-4d36-b5a0-7e030c1d3244)  
(KB2597124)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-011](http://go.microsoft.com/fwlink/?linkid=238500)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 および Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 および Microsoft SharePoint Foundation 2010 Service Pack 1 (sts)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dd348109-953b-4154-b265-85e4694238e6)  
(KB2553413)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40)  
(KB2668562)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40)  
(KB2668562)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40)  
(KB2668562)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
MS12-016 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様はセーフティとセキュリティ センターを参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

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

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、Microsoft Active Protections Program (MAPP) パートナーに記載されている各社の Web サイトを参照してください。

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

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い [謝意](http://technet.microsoft.com/ja-jp/security/bulletin/policy) を表します。

-   MS12-008 で説明している問題を報告してくださった [Azimuth Security](http://www.azimuthsecurity.com/) の Tarjei Mandt 氏
-   MS12-009 で説明している問題を報告してくださった [Azimuth Security](http://www.azimuthsecurity.com/) の Tarjei Mandt 氏
-   MS12-010 で説明している問題を報告してくだささった [Jan Schejbal](http://janschejbal.wordpress.com/)氏
-   MS12-010 で説明している 2 件の問題を報告してくださった、[TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している [Harmony Security](http://www.harmonysecurity.com/) の Stephen Fewer 氏
-   MS12-010 で説明している問題を報告してくださった [HP Cloud Services](http://www.hpcloud.com/)の Jason Hullinger 氏
-   MS12-011 で説明している問題を報告してくだささった John Hollenberger 氏
-   MS12-011 で説明している問題を報告してくださった Rocco Calvi 氏
-   MS12-011 の多層防御の更新プログラムについてマイクロソフトに協力してくださった Minded Security の Giorgio Fedon 氏
-   MS12-013 で説明している問題を報告してくださった [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Alexander Gavrun 氏
-   MS12-015 で説明している 5 件の問題を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS12-016 で説明している問題を報告してくださった [Sumatra](http://www.sumatra.nl/) の Jeroen Frijters 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/?ln=ja)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/2/15):このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
