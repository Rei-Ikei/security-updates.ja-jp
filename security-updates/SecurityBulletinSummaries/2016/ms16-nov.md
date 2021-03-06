---
TOCTitle: 'MS16-NOV'
Title: 2016 年 11 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-nov'
ms:contentKeyID: 74241286
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-nov(v=Security.10)'
---

2016 年 11 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日: 2016 年 11 月 9 日 | 最終更新日: 2016 年 11 月 24 日

**バージョン:** 1.1

このセキュリティ情報の概要は 2016 年 11 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定するときに役立つ情報も提供します。「**関連情報**」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次の「**影響を受けるソフトウェア**」のセクションを参照してください。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度<br />
と脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>既知の<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830431">MS16-129</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3199057)</strong><br />
このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限を持つユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3200970">3200970</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833191">MS16-130</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 用のセキュリティ更新プログラム (3199172)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ローカルで認証された攻撃者が特別に細工されたアプリケーションを実行した場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a>  <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833189">MS16-131</a></td>
<td style="border:1px solid black;"><strong>Microsoft ビデオ コントロール用のセキュリティ更新プログラム (3199151)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性は、Microsoft ビデオ コントロールがメモリ内のオブジェクトを適切に処理できなかった場合に、リモートでのコードの実行を可能にします。攻撃者がこの脆弱性を悪用すると、現在のユーザーのコンテキストで任意のコードを実行できる可能性があります。しかし、まず Web ページまたは電子メール メッセージから特別に細工されたファイルまたはプログラムをユーザーに開かせることが、攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830425">MS16-132</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3199120)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、リモートでコードが実行される可能性があります。特別に細工し埋め込まれたフォントを Windows フォント ライブラリが正しく処理しない場合に、この脆弱性が存在します。攻撃者によりこの脆弱性が悪用された場合、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントの作成が行われる可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833188">MS16-133</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3199168)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。最も深刻な脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=828018">MS16-134</a></td>
<td style="border:1px solid black;"><strong>共通ログ ファイル システム ドライバーのセキュリティ更新プログラム (3193706)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。Windows 共通ログ ファイル システム (CLFS) ドライバーがメモリ内のオブジェクトを不適切に処理した場合、この脆弱性によって特権の昇格が起こる可能性があります。ローカル攻撃のシナリオでは、攻撃者は特別に細工したアプリケーションを実行して影響を受けるシステムを制御することで、これらの脆弱性を悪用する可能性があります。この脆弱性の悪用に成功した攻撃者が、昇格されたコンテキストでプロセスを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830428">MS16-135</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3199135)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で最も深刻なものでは、攻撃者が影響を受けるコンピューターにログオンし、脆弱性を悪用したり影響を受けるコンピューターを制御したりできる特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830963">MS16-136</a></td>
<td style="border:1px solid black;"><strong>SQL Server 用のセキュリティ更新プログラム (3199641)<br />
</strong>このセキュリティ更新プログラムは、Microsoft SQL Server に存在する脆弱性を解決します。これらの脆弱性で最も深刻なものでは、攻撃者が昇格された特権を取得し、その特権を使用して、データの表示、変更、削除などを行ったり、新たなアカウントを作成したりする可能性があります。このセキュリティ更新プログラムは、SQL Server がポインターのキャストを処理する方法を修正することにより、この最も深刻な脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=833192">MS16-137</a></td>
<td style="border:1px solid black;"><strong>Windows 認証方式用のセキュリティ更新プログラム (3199173)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で比較的深刻なものが悪用された場合、特権の昇格が起こる可能性があります。この脆弱性を悪用するには、攻撃者はまず有効なユーザーの資格情報を使用して、ドメインに接続されている標的のシステムで認証を行う必要があります。攻撃者がこの脆弱性を悪用した場合、特権のないユーザー アカウントの権限を管理者に昇格させる可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。攻撃者は、さらに NTLM のパスワード変更要求を操作するように特別に細工されたアプリケーションをローカルで実行することにより、特権を昇格させようとする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830965">MS16-138</a></td>
<td style="border:1px solid black;"><strong>Microsoft 仮想ハード ディスク ドライバー用のセキュリティ更新プログラム (3199647)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。Windows 仮想ハード ディスク ドライバーが、特定のファイルに対するユーザー アクセスを正しく処理していません。攻撃者はこの脆弱性を悪用して、ユーザーの使用が想定されていない場所にあるファイルを操作する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830430">MS16-139</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル用のセキュリティ更新プログラム (3199720)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工されたアプリケーションを実行して機密情報にアクセスした場合、特権の昇格が起こる可能性があります。ローカルで認証された攻撃者が、特別に細工したアプリケーションを実行することによって、これらの脆弱性を悪用する可能性があります。攻撃者は、この方法を使用して、ユーザーの使用が想定されていない情報にアクセスする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827857">MS16-140</a></td>
<td style="border:1px solid black;"><strong>ブート マネージャー用のセキュリティ更新プログラム (3193479)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、物理的に存在する攻撃者が影響を受けたブート ポリシーをインストールした場合に、セキュリティ機能のバイパスが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3200970">3200970</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><a href="https://support.microsoft.com/ja-jp/kb/3193479">3193479</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834404">MS16-141</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3202790)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10、および Windows Server 2016 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=830372">MS16-142</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3198467)<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3197873">3197873</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197874">3197874</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197876">3197876</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197877">3197877</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197867">3197867</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3197868">3197868</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
</tbody>
</table>
 

Exploitability Index (悪用可能性指標)
-------------------------------------

<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報 ID、CVE ID の順でリストされています。掲示板での重要度評価が緊急または重要である脆弱性のみが含まれています。

**この表はどのように使用しますか?**

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、「[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259)」 を参照してください。

下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE の識別番号**                    

</td>
<td style="border:1px solid black;">
**脆弱性のタイトル**

</td>
<td style="border:1px solid black;">
**最新のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**過去のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**サービス拒否  
悪用可能性評価**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-129: Microsoft Edge 用の累積的なセキュリティ更新プログラム (3199057)**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7195](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7195)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7196](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7196)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7198)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7199)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7200](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7200)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7201)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7202)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7203)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7204](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7204)

</td>
<td style="border:1px solid black;">
Microsoft Edge の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7208](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7208)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7209](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7209)

</td>
<td style="border:1px solid black;">
Microsoft Edge のなりすましの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7227)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7239)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えい

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7240)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7241)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7242)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7243)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-130: Microsoft Windows 用のセキュリティ更新プログラム (3199172)**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7212](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7212)

</td>
<td style="border:1px solid black;">
Windows のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7221)

</td>
<td style="border:1px solid black;">
Windows IME の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7222)

</td>
<td style="border:1px solid black;">
タスク スケジューラの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-131: Microsoft ビデオ コントロール用のセキュリティ更新プログラム (3199151)**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-cve-2016-7248)

</td>
<td style="border:1px solid black;">
Microsoft ビデオ コントロール用のセキュリティ更新プログラム

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-132: Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3192884)**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7205)

</td>
<td style="border:1px solid black;">
Windows Animation Manager のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7210](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7210)

</td>
<td style="border:1px solid black;">
OpenType フォントの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7217)

</td>
<td style="border:1px solid black;">
メディア ファンデーションのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7256)

</td>
<td style="border:1px solid black;">
OpenType フォントのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-133: Microsoft Office 用のセキュリティ更新プログラム (3199168)**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7213)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7228)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7229](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7229)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7230)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7231)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7232)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7233)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7234)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7235)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7236)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7244](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7244)

</td>
<td style="border:1px solid black;">
Microsoft Office のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7245)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-134: 共通ログ ファイル システム ドライバーのセキュリティ更新プログラム (3193706)**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0026)

</td>
<td style="border:1px solid black;">
Windows CLFS の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3332](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3332)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3333](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3333)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3334](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3334)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3335](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3335)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3338](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3338)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3340](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3340)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3342](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3342)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3343](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3343)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7184](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7184)

</td>
<td style="border:1px solid black;">
Windows CLFS の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-135: Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3199135)**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7214)

</td>
<td style="border:1px solid black;">
Win32k の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7215)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7218)

</td>
<td style="border:1px solid black;">
Bowser.sys の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7246)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7255)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-136: SQL Server 用のセキュリティ更新プログラム (3199641)**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7249)

</td>
<td style="border:1px solid black;">
SQL RDBMS Engine の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7250)

</td>
<td style="border:1px solid black;">
SQL RDBMS Engine の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7251)

</td>
<td style="border:1px solid black;">
MDS API XSS の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7252)

</td>
<td style="border:1px solid black;">
SQL Analysis Services の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7253)

</td>
<td style="border:1px solid black;">
SQL Server Agent の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7254)

</td>
<td style="border:1px solid black;">
SQL RDBMS Engine の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-137:Windows 認証方式用のセキュリティ更新プログラム (3199173)**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7220)

</td>
<td style="border:1px solid black;">
仮想保護モードの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7237)

</td>
<td style="border:1px solid black;">
ローカル セキュリティ機関サブシステム サービスのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7238)

</td>
<td style="border:1px solid black;">
Windows NTLM の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-138: Microsoft 仮想ハード ディスク ドライバー用のセキュリティ更新プログラム (3199647)**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7223](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7223)

</td>
<td style="border:1px solid black;">
VHDFS ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7224](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7224)

</td>
<td style="border:1px solid black;">
VHDFS ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7225)

</td>
<td style="border:1px solid black;">
VHDFS ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7226](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7226)

</td>
<td style="border:1px solid black;">
VHDFS ドライバーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-139: Windows カーネル用のセキュリティ更新プログラム (3193227)**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7216)

</td>
<td style="border:1px solid black;">
Windows カーネルの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-140: ブート マネージャー用のセキュリティ更新プログラム (3193479)**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7247)

</td>
<td style="border:1px solid black;">
セキュア ブートのセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-141: Adobe Flash Player のセキュリティ更新プログラム (3202790)**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-37](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-37.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度と更新プログラムの優先度の評価については、Adobe Security Bulletin [APSB16-37](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-37.html) を参照してください。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-142: Internet Explorer 用の累積的なセキュリティ更新プログラム (3198467)**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7239)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えい

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7227)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7198)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7199)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7195](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7195)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7196](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7196)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7241)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 

影響を受けるソフトウェア
------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報 ID の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。

### Windows オペレーティング システムとコンポーネント (表 1/3)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3193418)  
(重要)  
Windows Vista Service Pack 2  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3198218)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3203859)  
(重要)

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
Windows Vista x64 Edition Service Pack 2  
(3193418)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3198218)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3203859)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**    

</td>
<td style="border:1px solid black;">
**なし**  

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3193418)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3203859)  
(重要)

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
Windows Server 2008 for x64-based Systems Service Pack 2  
(3193418)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3203859)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3193418)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3203859)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**    

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**    

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**    

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197873)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197873)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197874)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197873)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197873)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197874)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**    

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1<span></span>
(3197874)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3198585)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3198585)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3198585)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3198585)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3198585)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3198585)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3198585)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3198585)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3198585)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3198585)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3198586)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3200970)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-129**](https://go.microsoft.com/fwlink/?linkid=830431)

</td>
<td style="border:1px solid black;">
[**MS16-130**](https://go.microsoft.com/fwlink/?linkid=833191)

</td>
<td style="border:1px solid black;">
[**MS16-131**](https://go.microsoft.com/fwlink/?linkid=833189)

</td>
<td style="border:1px solid black;">
[**MS16-132**](https://go.microsoft.com/fwlink/?linkid=830425)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3193418)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3203859)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x86-bit Systems Service Pack 2 (Server Core インストール)  
(3193418)  
(重要)  
Windows Server 2008 for x86-bit Systems Service Pack 2 (Server Core インストール)  
(3196718)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x86-bit Systems Service Pack 2 (Server Core インストール)  
(3203859)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3197867)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3197868)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3197876)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3197876)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3197877)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3197877)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3197873)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3197873)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3197874)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3197874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(緊急)

</td>
</tr>
</table>
 
### Windows オペレーティング システムとコンポーネント (表 2/3)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Vista Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Vista Service Pack 2  
(3198234)  
(重要)  
Windows Vista Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Vista Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Vista x64 Edition Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Vista x64 Edition Service Pack 2  
(3198234)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Vista x64 Edition Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3198234)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3198234)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3198234)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3194371)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3198510)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3198483)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1 for 32-bit Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for 32-bit Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1 for 32-bit Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for 32-bit Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1 for 32-bit Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for 32-bit Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1 for 32-bit Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for 32-bit Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1 for x64-based Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for x64-based Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1 for x64-based Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for x64-based Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows 8.1 for x64-based Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for x64-based Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 8.1 for x64-based Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 8.1 for x64-based Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 for 32-bit Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 for 32-bit Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 for 32-bit Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 for 32-bit Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 for x64-based Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 for x64-based Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 for x64-based Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 for x64-based Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2016 for x64-based Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2016 for x64-based Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2016 for x64-based Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-134**](http://go.microsoft.com/fwlink/?linkid=828018)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-135**](https://go.microsoft.com/fwlink/?linkid=830428)

</td>
<td style="border:1px solid black;" colspan="4">
[**MS16-137**](https://go.microsoft.com/fwlink/?linkid=833192)

</td>
<td style="border:1px solid black;" colspan="3">
[**MS16-138**](https://go.microsoft.com/fwlink/?linkid=830965)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-139**](https://go.microsoft.com/fwlink/?linkid=830430)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="4">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="3">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 for 32-bit Systems Service Pack 2<span></span>(Server Core インストール)  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 for 32-bit Systems Service Pack 2<span></span>(Server Core インストール)  
(3198234)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 for 32-bit Systems Service Pack 2<span></span>(Server Core インストール)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3196718)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 for x64-based Systems Service Pack 2<span></span>(Server Core インストール)  
(3181707)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2008 for x64-based Systems Service Pack 2<span></span>(Server Core インストール)  
(3198234)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 for x64-based Systems Service Pack 2<span></span>(Server Core インストール)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3196718)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197867)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197868)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012<span></span>(Server Core インストール)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012<span></span>(Server Core インストール)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012<span></span>(Server Core インストール)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012<span></span>(Server Core インストール)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012<span></span>(Server Core インストール)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012<span></span>(Server Core インストール)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
対象外

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="4">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="3">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
** **

### Windows オペレーティング システムとコンポーネント (表 3/3)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;" colspan="2">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;" colspan="2">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3197655)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://catalog.update.microsoft.com/v7/site/search.aspx?q=kb3193418)  
(3193418)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;" colspan="2">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;" colspan="2">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197867)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197868)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
**警告**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3197876)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3197877)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197873)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(警告)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3197874)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=832634)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198585)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3198585)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198585)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198586)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3198586)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3198586)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3200970)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems<span></span>
(3200970)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
Adobe Flash Player  
(3202790)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3200970)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;" colspan="2">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3200970)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**  

</td>
<td style="border:1px solid black;">
[**MS16-140**](http://go.microsoft.com/fwlink/?linkid=827857)

</td>
<td style="border:1px solid black;" colspan="2">
[**MS16-141**](https://go.microsoft.com/fwlink/?linkid=834404)

</td>
<td style="border:1px solid black;">
[**MS16-142**](https://go.microsoft.com/fwlink/?linkid=830372)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;" colspan="2">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2<span></span>(Server Core インストール)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2<span></span>(Server Core インストール)  
(3190847)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197867)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1<span></span>(Server Core インストール)  
(3197868)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012<span></span>(Server Core インストール)  
(3197876)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012<span></span>(Server Core インストール)  
(3197877)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197873)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2<span></span>(Server Core インストール)  
(3197874)  
(重要)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3200970)  
(緊急)

</td>
<td style="border:1px solid black;" colspan="2">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
### Microsoft Office スイートおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2007**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3118395)  
(重要)  
Microsoft Word 2007  
(3127949)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(3118396)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2986253)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2010**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3127951)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3118390)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3127953)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 ビット版)  
(3118378)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3115120)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3127951)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3127951)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3127953)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 ビット版)  
(3118378)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3115120)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2013**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3127921)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3115153)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3127932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3127921)  
(Important  
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3115153)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3127932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2013 RT**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3127921)  
(重要)  
Microsoft Office 2013 RT Service Pack 1  
(3115153)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3127932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office 2016**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 ビット版)  
(3127904)  
(重要)  
Microsoft Office 2016 (32 ビット版)  
(3115135)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 ビット版)  
(3127904)  
(重要)  
Microsoft Office 2016 (64 ビット版)  
(3115135)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft Office for Mac 2011**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3198807)  
(重要)  
Microsoft Word for Mac 2011  
(3198807)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3198798)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
その他の Office ソフトウェア

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(3127889)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3127948)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3127893)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3118382)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office Services および Web Apps

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3118381)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3127950)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3127927)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3127954)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-133**](https://go.microsoft.com/fwlink/?linkid=833188)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3127929)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft SQL Server

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 Service Pack 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 2  
(GDR)  
(3194719)  
(重要)  
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 2  
(3194725)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 Service Pack 3**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 3  
(GDR)  
(3194721)  
(重要)  
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 3  
(3194724)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014 Service Pack 1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 Service Pack 1 for 32-bit Systems  
(GDR)  
(3194720)  
(重要)  
Microsoft SQL Server 2014 Service Pack 1 for 32-bit Systems  
(3194722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014 Service Pack 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 Service Pack 2 for 32-bit Systems  
(GDR)  
(3194714)  
(重要)  
Microsoft SQL Server 2014 Service Pack 2 for 32-bit Systems  
(3194718)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-136**](https://go.microsoft.com/fwlink/?linkid=830963)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2016 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2016 for 32-bit Systems  
(GDR)  
(3194716)  
(重要)  
Microsoft SQL Server 2016 for 32-bit Systems  
(3194717)  
(重要)

</td>
</tr>
</table>
 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび検証を効率化するときに役立ちます。

利用可能なこれらのツールと他のツールの詳細については、[IT 管理者向けセキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/mt674627.aspx)を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード検索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション: [TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ: [ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/ja-jp/contactus/cu_sc_virsec_master)

国ごとのローカル サポート: [インターナショナル サポート](http://support.microsoft.com/ja-jp/common/international.aspx)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2016/11/09): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2016/11/24): このセキュリティ情報の概要ページを更新し、Windows Servers 2012、Windows Server 2012 R2、および Windows Server 2016 を実行する特定のサーバーで検出を変更したことをお知らせしました。影響を受けるサーバーは、セキュリティ更新プログラムを自動的に受け取ることはできません。この検出の変更により影響を受けるサーバーの詳細については、[サポート技術情報 3193479](https://support.microsoft.com/ja-jp/kb/3193479) を参照してください。

*Page generated 2017-04-14 09:10-07:00.*
