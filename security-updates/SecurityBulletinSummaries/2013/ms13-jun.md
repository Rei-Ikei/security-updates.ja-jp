---
TOCTitle: 'MS13-JUN'
Title: 2013 年 6 月のセキュリティ情報
ms:assetid: 'ms13-jun'
ms:contentKeyID: 61229712
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-jun(v=Security.10)'
---


2013 年 6 月のセキュリティ情報
==============================

公開日: 2013年6月12日

**バージョン:** 1.0

[![](../../images/Dn627292.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627292.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 6 月公開のセキュリティ情報の一覧です。

2013 年 6 月のセキュリティ情報の公開により、2013 年 6 月 7 日に公開した事前通知を、このセキュリティ情報の概要に置き換えました。事前通知サービスの詳細については、[「マイクロソフト セキュリティ情報の事前通知」](http://go.microsoft.com/fwlink/?linkid=217213)を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2013 年 6 月 12 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 6 月 12 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[6 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us) (英語)。この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)で利用可能となります。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

#### 概要

次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299498">MS13-047</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2838727)  <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 19 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301748">MS13-048</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、情報漏えいが起こる (2839229) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行、あるいはローカルでログオンしているユーザーに特別な細工がされたアプリケーションを実行するよう誘導した場合、情報漏えいが起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。この脆弱性により、攻撃者は直接コードを実行したり、自らのユーザー権限を昇格させたりすることはできませんが、攻撃者はこの脆弱性を悪用し、影響を受けるコンピューターをさらに侵害する目的で悪用する情報を作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301749">MS13-049</a></td>
<td style="border:1px solid black;">カーネルモード ドライバーの脆弱性により、サービス拒否が起こる (2845690)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、サーバーに特別に細工したパケットを送信した場合、サービス拒否の状態が起こる可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299243">MS13-050</a></td>
<td style="border:1px solid black;">Windows 印刷スプーラー コンポーネントの脆弱性により、特権が昇格される (2839894)  <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、認証された攻撃者がプリンターの接続を削除した場合に特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296303">MS13-051</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、リモートでコードが実行される (2839571) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。ユーザーが、影響を受けるバージョンの Microsoft Office ソフトウェアを使用して、特別に細工された Office ドキュメントを開いた場合、または Microsoft Word を電子メール リーダーとして使用して、特別に細工された電子メール メッセージを Outlook でプレビューしたり開いたりした場合、この脆弱性によりリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
| セキュリティ情報 ID                                       | 脆弱性のタイトル                           | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価               | 旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価     | サービス拒否の悪用可能性の評価 | 注意事項                                                               |  
|-----------------------------------------------------------|--------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------------------------|------------------------------------------------------------------------|  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3110) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3111) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3112) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3113) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3114) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3116) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3117) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3118) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                            | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3119](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3119) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3120) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                            | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3121) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3122) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3123) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3124) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3125) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 影響なし                                                                            | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3139) | 対象外                                                                                | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | これは最新ソフトウェアの多層防御策です。                               |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3141) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Internet Explorer のメモリ破損の脆弱性     | [CVE-2013-3142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3142) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | (なし)                                                                 |  
| [MS13-048](http://go.microsoft.com/fwlink/?linkid=301748) | カーネルの情報漏えいの脆弱性               | [CVE-2013-3136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3136) | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低      | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低    | 永続的                         | これは情報漏えいの脆弱性です。                                         |  
| [MS13-049](http://go.microsoft.com/fwlink/?linkid=301749) | TCP/IP の整数オーバーフローの脆弱性        | [CVE-2013-3138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3138) | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低      | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低    | 永続的                         | これは、サービス拒否の脆弱性です。                                     |  
| [MS13-050](http://go.microsoft.com/fwlink/?linkid=299243) | 印刷スプーラーの脆弱性                     | [CVE-2013-1339](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1339) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 永続的                         | (なし)                                                                 |  
| [MS13-051](http://go.microsoft.com/fwlink/?linkid=296303) | Office のバッファー オーバーフローの脆弱性 | [CVE-2013-1331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1331) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性 | 対象外                         | マイクロソフトはこの脆弱性を悪用しようとする標的型攻撃を確認しました。 |
  
影響を受けるソフトウェア  
------------------------
  
<span></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(緊急)  
Internet Explorer 7   
(2838727)  
(緊急)  
Internet Explorer 8   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2839229)  
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(緊急)  
Internet Explorer 7   
(2838727)  
(緊急)  
Internet Explorer 8   
(2838727)  
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
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 6   
(2838727)  
(警告)  
Internet Explorer 7  
(2838727)  
(警告)  
Internet Explorer 8  
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2839229)  
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
Internet Explorer 6   
(2838727)  
(警告)  
Internet Explorer 7  
(2838727)  
(警告)  
Internet Explorer 8  
(2838727)  
(警告)
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
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(警告)  
Internet Explorer 7  
(2838727)  
(警告)
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
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 7  
(2838727)  
(緊急)  
Internet Explorer 8  
(2838727)  
(緊急)  
Internet Explorer 9   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2839229)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2839894)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(緊急)  
Internet Explorer 8  
(2838727)  
(緊急)  
Internet Explorer 9   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 7  
(2838727)  
(警告)  
Internet Explorer 8  
(2838727)  
(警告)  
Internet Explorer 9   
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2839229)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2839894)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(警告)  
Internet Explorer 8  
(2838727)  
(警告)  
Internet Explorer 9   
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2839894)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(緊急)  
Internet Explorer 9   
(2838727)  
(緊急)  
Internet Explorer 10   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2839229)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2839894)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(緊急)  
Internet Explorer 9   
(2838727)  
(緊急)  
Internet Explorer 10   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(警告)  
Internet Explorer 9   
(2838727)  
(警告)  
Internet Explorer 10   
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2839894)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
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
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2839229)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2845690)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2839894)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2845690)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845690)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows RT  
(2845690)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT  
(2839894)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-047](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[MS13-048](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[MS13-049](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[MS13-050](http://go.microsoft.com/fwlink/?linkid=299243)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2839229)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2839894)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2839894)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2845690)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2839894)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2845690)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2839894)  
(重要)
</td>
</tr>
</table>
 

#### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-051](http://go.microsoft.com/fwlink/?linkid=296303)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(2817421)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2848689)  
(重要)
</td>
</tr>
</table>
 

検出および展開ツールとガイダンス
--------------------------------

<span></span>
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[TechNet セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には「セキュリティ更新プログラム」リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索で容易に見つけられます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (たとえば “MS13-001” など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/wsus/default) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。System Center Configuration Manager の詳細については、[System Center テクニカル リソース](http://technet.microsoft.com/ja-jp/systemcenter/bb980621)を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199/ja) :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

MS13-047

-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3110) を報告してくださった [Security-Assessment.com](http://www.security-assessment.com/) の Scott Bell 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3111) を報告してくださった SkyLined 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3112) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3113) を報告してくださった [Google Security Team](http://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3114) を報告してくださった [Google Security Team](http://www.google.com/) のIvan Fratric 氏と Ben Hawkes 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3116) を報告してくださった [Google Security Team](http://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3117) を報告してくださった [Google Security Team](http://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3118) を報告してくださった [Omair](http://krash.in/) 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3119) を報告してくださった [Harmony Security](http://www.harmonysecurity.com/) の Stephen Fewer 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3120) を報告してくださった SkyLined 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3121) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3122) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3123) を報告してくださった [Aniway.Aniway@gmail.com](mailto:aniway.anyway@gmail.com) 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3124) を報告してくださった [Omair](http://krash.in/) 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3124) を報告してくださった Amol Naik 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3125) を報告してくださった [Omair](http://krash.in/) 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3125) を報告してくださった Amol Naik 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer スクリプト デバッグの脆弱性 (CVE-2013-3126) を報告してくださった [Aniway.Aniway@gmail.com](mailto:aniway.anyway@gmail.com) 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3141) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3142) を報告してくださった Toan Pham Van 氏

MS13-048

-   カーネルの情報漏えいの脆弱性 (CVE-2013-3136) を報告してくださった [Google Inc](http://www.google.com/) の [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏

MS13-051

-   Office のバッファー オーバーフローの脆弱性 (CVE-2013-1331) を報告してくださった [Google Inc](http://www.google.com/) の Andrew Lyons 氏および Neel Mehta 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/06/12):このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
