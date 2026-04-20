---
metaLinks:
  alternates:
    - https://app.gitbook.com/s/S9QxvkgOCtdmIoYhCUqg/others/operator-management
---

# 管理者アカウントの管理

管理者の管理は、アドミンにアクセスする運用担当者（管理者）のアカウントを作成・管理するメニューです。割り当てられた担当に基づき権限が区分されるほか、アカウントの有効化‐無効化によりアクセスを制御することができます。

{% hint style="warning" %}
このメニューは、パートナーアドミン以上の担当、またはGINTアカウントでのみアクセス可能です。
{% endhint %}

***

### アクセス方法

{% stepper %}
{% step %}
左側のメニューから「管理者の管理」を選択します。

<figure><img src="../.gitbook/assets/operator-management-menu-open-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
下位メニューから管理者のアカウントリストを選択すると、アカウントリスト画面へ移動します。

<figure><img src="../.gitbook/assets/operator-management-menu-select-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### 管理者アカウントの作成

{% stepper %}
{% step %}
管理者リスト画面の右上の\[アカウントの作成]を選択します。

<figure><img src="../.gitbook/assets/operator-management-account-add-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
下記の項目を入力します。\*は必ず入力してください。

<figure><img src="../.gitbook/assets/operator-management-account-add-2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
所属部署は、このアカウントの管理範囲を決めます。所属部署に応じて確認可能な製品・アカウント・履歴情報が異なります。
{% endhint %}

{% hint style="info" %}
**担当ごとの権限に関するご案内**

* **メンバー**
  * パートナー会社に所属する一般社員向けの権限です。注文の作成及び照会、取り付けチケットの対応、お客様アカウントの確認など、現場のサービス業務を担当します。
* **パートナーアドミン**
  * パートナー会社内でアカウントと部署を管理する、管理者向けの権限です。所属部署の管理者アカウントの作成及び無効化、担当変更などの全体的な組織運営を担当します。
* **一般マネージャー**
  * GINTに所属する運用担当者向けの権限です。お客様のアカウント検索、リモートサポート、OTAの配信状況など、実務的な運用を担当します。GINTのマスターアカウントでのみ付与できます。
* **アドミン**
  * GINTに所属する運用担当者向けの権限です。管理者のアカウント作成及び管理、OTAの配信作成、RTKアカウントの管理など、全体的なシステムを統括します。GINTのマスターアカウントでのみ付与できます。
{% endhint %}
{% endstep %}

{% step %}
全ての必須項目を入力すると、\[アカウントの作成]ボタンが有効になります。ボタンを押し、アカウントの作成を完了します。

<figure><img src="../.gitbook/assets/operator-management-account-add-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**アカウントの作成時に、登録済みのメールアドレスに仮パスワードが送信されます。**\
メールが届かない場合は、迷惑メールフォルダーをご確認ください。
{% endhint %}
{% endstep %}
{% endstepper %}

***

### 管理者情報の修正

{% stepper %}
{% step %}
管理者の詳細から![](../.gitbook/assets/ic_more.svg)をクリックし、\[修正]を選択します。

<figure><img src="../.gitbook/assets/operator-management-account-edit-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
変更事項を記入し、\[修正完了]をクリックします。

<figure><img src="../.gitbook/assets/operator-management-account-add-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
修正完了しました。

<figure><img src="../.gitbook/assets/operator-management-account-edit-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### 管理者の無効化・有効化

アカウントの使用を一時的に中止し、または再度有効化できます。

{% hint style="info" %}
管理者アカウントは削除されません。無効にすることでアクセスを遮断します。無効になったアカウントではログインができませんが、履歴はそのまま保存されます。
{% endhint %}

{% stepper %}
{% step %}
管理者の詳細から![](../.gitbook/assets/ic_more.svg)をクリックし、\[無効化]を選択します。

<figure><img src="../.gitbook/assets/operator-management-account-status-toggle-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
確認のポップアップから\[確認]を選択します。

<figure><img src="../.gitbook/assets/operator-management-account-status-toggle-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
無効になりました。

<figure><img src="../.gitbook/assets/operator-management-account-status-toggle-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
無効のアカウント状態では、無効化ではなく有効化のオプションのみが表示されます。該当する項目を選択すると、アカウントが有効になります。
{% endhint %}

<figure><img src="../.gitbook/assets/operator-management-account-active.png" alt=""><figcaption></figcaption></figure>

***

### 管理者アカウントの詳細情報

アカウントリストからお客様を選択すると、そのアカウントの詳細情報画面へ移動します。

#### PC環境

<figure><img src="../.gitbook/assets/operator-management-account-detail-pc-1.png" alt=""><figcaption></figcaption></figure>

![](../.gitbook/assets/icon-square-1.svg) ステータス

![](../.gitbook/assets/icon-square-2.svg) 名前

![](../.gitbook/assets/icon-square-3.svg) 「詳細をみる」ボタン

{% hint style="info" %}
ボタンを押すと、\[修正]、\[無効化]（または、\[有効化]）オプションを選択できます。
{% endhint %}

![](../.gitbook/assets/icon-square-4.svg) 担当

![](../.gitbook/assets/icon-square-5.svg) 作成日

![](../.gitbook/assets/icon-square-6.svg) メールアドレス

![](../.gitbook/assets/icon-square-7.svg) 携帯電話番号

![](../.gitbook/assets/icon-square-8.svg) 部署名

{% hint style="info" %}
部署名をクリックすると、その部署の詳細画面へ移動します。
{% endhint %}

![](../.gitbook/assets/icon-square-9.svg) タグ

* 部署に関する情報が表示されます。

#### モバイル環境

<div align="left"><figure><img src="../.gitbook/assets/operator-management-account-detail-mobile-1.png" alt="" width="273"><figcaption></figcaption></figure></div>

![](../.gitbook/assets/icon-square-1.svg) ステータス

![](../.gitbook/assets/icon-square-2.svg) 名前

![](../.gitbook/assets/icon-square-3.svg) 「詳細をみる」ボタン

{% hint style="info" %}
ボタンを押すと、\[修正]、\[無効化]（または、\[有効化]）オプションを選択できます。
{% endhint %}

![](../.gitbook/assets/icon-square-4.svg) 担当

![](../.gitbook/assets/icon-square-5.svg) 作成日

![](../.gitbook/assets/icon-square-6.svg) メールアドレス

![](../.gitbook/assets/icon-square-7.svg) 携帯電話番号

![](../.gitbook/assets/icon-square-8.svg) 部署名

{% hint style="info" %}
部署名をクリックすると、その部署の詳細画面へ移動します。
{% endhint %}

![](../.gitbook/assets/icon-square-9.svg) タグ

* 部署に関する情報が表示されます。
