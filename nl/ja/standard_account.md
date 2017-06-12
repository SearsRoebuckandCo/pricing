---



copyright:

  years: 2016, 2017
lastupdated: "2017-05-02"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# IBM {{site.data.keyword.Bluemix_notm}} 標準アカウント (ベータ版) 
{: #betaintro}

{{site.data.keyword.Bluemix}} 標準アカウント (ベータ版) は、新しい無料アカウントであり、{{site.data.keyword.Bluemix_notm}} パブリック・クラウドの新しい利用方法を提供します。{{site.data.keyword.Bluemix_notm}} トライアルの 30 日とは違って、標準アカウントには有効期限はありません。時間的な制約を気にすることなく、{{site.data.keyword.Bluemix_notm}} アプリケーションに関する作業を続けることができます。
{:shortdesc}

標準アカウント (ベータ版) には招待を介してのみ加入できます。招待を受け入れて標準アカウントを作成したら、ベータ版に加入するように友人や同僚を招待できます。  

## {{site.data.keyword.Bluemix_notm}} 標準アカウントの概要
{: #standardaccount}

ここでは、標準アカウントとトライアル・アカウントの違いについて説明します。{{site.data.keyword.Bluemix_notm}} 標準アカウントの主な特長を以下の表に要約して示します。 

|標準アカウントの新しい点 |    
|-----------------|
| アカウントには有効期限がありません。 |
| Cloud Foundry アプリケーションは 256 MB までの瞬間的ランタイム・メモリーに無料でアクセスできます。 |
| Cloudant NoSQL DB および Internet of Things Platform の無料ライト・プランにアクセスでき、近い将来さらに多くのサービスが加わります。 |
| アプリケーションは、開発アクティビティーが 10 日間ない場合はスリープ状態になります。 |
| サービス・インスタンスは、非アクティブな状態が 30 日間続くと削除されます。 |
{:caption="表 1. 標準アカウントの新しい点" caption-side="top"}

|トライアル・アカウントから移行しても変わらない点 | 
|-----------------|
|アカウントは無料です。クレジット・カードは必要ありません。 |
|Cloudant NoSQL DB および Internet of Things Platform のライト版のすべてのインスタンス。これらのサービスのそれぞれについて 1 つのライト版インスタンスを新規アカウントに移行できます。 |
|組織、スペース、および関連付けられたチーム・メンバーのアクセス設定は変わりません。1 つの組織を新規アカウントに移行できます。 |
|{{site.data.keyword.Bluemix_notm}} サポートのレベルは変わりません。 |
{:caption="表 2. 変わらない点" caption-side="top"}

**注**: トライアル・アカウントから移行されない場合、その理由を説明するメッセージが表示されます。既存のトライアル・アカウントに複数の組織があるか、移行できないアプリケーションがある可能性があります。適切な処置を行った後、アカウントの変換を再試行してください。

標準アカウントの登録が終わったら、組織およびスペースで共同作業を行えるようにチーム・メンバーを招待したり、使用量の表示、スペースの作成、アカウント・プロファイルの更新、または組織の管理を行ったりできます。詳しくは、『[アカウントの管理](/docs/admin/adminpublic.html#account)』を参照してください。

## ライト・プラン
{: #liteplans}
   
ライト・プランは、無料割り当て量という料金体系になっています。従量課金 (PAYG) アカウントでも利用可能です。偶発的に請求が発生するというリスクはなく、安心してプロジェクトの作業を行うことができます。割り当て量は特定の期間 (例: 1 カ月) で、または 1 回限りの使用量ベースで運用されます。以下に、ライト・プラン割り当て量の例をいくつか示します。

<ul>
<li>登録済みデバイスの最大数。</li>
<li>アプリケーション・バインディングの最大数。</li>
<li>暗号化データ・ストレージ限度 (例: 1 GB)。</li>
<li>プロビジョンされたスループットのキャパシティー。</li>
</ul> 

標準アカウントでは、ライト・プランがあるものであれば、{{site.data.keyword.Bluemix_notm}} カタログ内のどれでも使用できます。ライト・プランは簡単に見つけることができます。デフォルトでは、カタログを開くと、ライト・プランのあるすべてのサービスが表示され、「ライト」タグ ![「ライト」タグ](../icons/Lite.svg) で示されます。サービスを選択すると、関連付けられたライト・プランの割り当て量の詳細を表示できます。

## 標準アカウントで使用可能なもの
{: #whatsavailable}

標準アカウントでは、Cloud Foundry アプリケーションは最大 256 MB の瞬間的ランタイム・メモリーにアクセスできます。割り振られた割り当て量を超える場合、一部のアプリケーションを停止してランタイム・メモリーを解放することができます。 

標準アカウント (ベータ版) では、以下のサービスでライト・プランが提供されています。

<ul>
<li>Cloudant NoSQL DB</li>
<li>Internet of Things Platform</li>
</ul>

このサービス・リストへの追加が予定されていますのでご期待ください。

割り当て量の限度に達すると、アプリケーションが停止されるか、サービスが使用不可にされます。割り当て量が月ベースで提供されるようにライト・プランで指定されている場合、リソース使用量は毎月 1 日にリセットされるので、その時点でサービスでの処理を再開できます。割り当て量の限度に近づいている場合、または、割り当て量の限度に達した場合、通知 E メールを受け取ります。 

ライト・プランごとに 1 つのインスタンスをプロビジョンできます。 

**注**: これらの制約は、標準アカウントにのみ適用されます。請求が行われる従量課金 (PAYG) アカウントまたはサブスクリプション・アカウントにいつでもアップグレードできます。お支払いは、無料枠を超えて使用した分のみが対象になります。従量課金 (PAYG) アカウントおよびサブスクリプション・アカウントについて詳しくは、『[アカウント・タイプ](/docs/pricing/index.html#pay-accounts)』を参照してください。

## 開発アクティビティー
{: #devactivity}

標準アカウントのユーザーが各自のリソースについて最適な管理を行えるように、開発アクティビティーと使用法に基づいた 2 つの効率化機能が導入されました。

 * 開発アクティビティーが 10 日間ないと、アプリケーションはスリープ状態になります。新しいアプリケーションに関する作業を行いたい場合、256 MB のメモリー割り当て量限度に達することがないため、この機能が役立ちます。アプリケーションをウェイクアップするには、Cloud Foundry コマンド・ラインまたは {{site.data.keyword.Bluemix_notm}} コンソールでそのアプリケーションに関する作業を再び開始します。 
 
 以下に、アプリケーションをウェイクアップするすべてのコマンドを示します。
  * cf push
  * cf restate
  * cf restart
  * cf ssh
  * cf scale
  * cf stop
  * cf start
  * cf create-route
  * cf map-route
  * cf unmap-route
  * cf delete-route
  * cf enable-ssh
  * cf disable-ssh

 **注**: アプリケーションで既に ssh が有効化されている場合、`cf enable-ssh` コマンドおよび `cf disable-sh` コマンドはアプリケーションをウェイクアップしません。 

 * ライト・プランのサービスは、サービスに関するアクティビティーが 30 日間何もないと削除されます。その後で新規インスタンスを作成する際、非アクティブなインスタンスを削除する必要がありません。現時点では、この機能を使用しているのは Internet of Things Platform サービスのみです。 
 
 Internet of Things Platform サービス・インスタンスのダッシュボードにログインすることによって、Internet of Things Platform Lite インスタンスをアクティブに保ってください。
 
## 標準アカウント (ベータ版) への加入
{: #betainvitation}

ベータ版に加入するように選ばれると、{{site.data.keyword.Bluemix_notm}} トライアル・アカウントに関連付けられた E メール・アドレス宛てに招待メールが送信されます。招待メールを受け取ったら、メールに記載されている指示に従って標準アカウントの登録を行います。 

標準アカウント (ベータ版) オファリングへの加入に関心がある場合、友人や同僚に尋ねてみてください。ベータ版に加入するよう招待され、既に標準アカウントを作成した人がいれば、その人に招待してもらうことができます。 