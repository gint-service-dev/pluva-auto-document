# オペレーターアカウントの管理

オペレーター管理は、アドミンにアクセスする運営担当者（オペレーター）のアカウントを作成および管理するメニューです。役割に応じた権限の付与や、アカウントの有効化・無効化によるアクセス制御が可能です。

{% hint style="warning" %}
このメニューは、パートナーアドミン以上の役割、またはGINTアカウントでのみアクセスできます。
{% endhint %}

***

### アクセス方法

{% stepper %}
{% step %}
左のメニューから「オペレーター管理」を選択します。

<figure><img src="../../.gitbook/assets/operator-management-menu-open-1 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
下部メニューから「オペレーターアカウント一覧」を選択すると、アカウント一覧画面へアクセスできます。

<figure><img src="../../.gitbook/assets/operator-management-menu-select-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### オペレーターアカウントの作成

{% stepper %}
{% step %}
オペレーター一覧画面の右上の\[アカウントの作成]をタップします。

<figure><img src="../../.gitbook/assets/operator-management-account-add-1 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
下記の項目を入力します。\*表示は入力必須です。

<figure><img src="../../.gitbook/assets/operator-management-account-add-2 (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
所属はこのアカウントの管理範囲を決定します。所属に応じて閲覧可能な製品・アカウント・履歴情報が異なります。
{% endhint %}

{% hint style="info" %}
**役割ごとの権限一覧**

* **メンバー**
  * パートナー社に所属する一般社員に付与されます。注文の作成・閲覧、取り付けチケットの処理、お客様アカウントの閲覧など、現場サービス業務を行います。
* **パートナーアドミン**
  * パートナー社内のアカウントや組織を運営する担当者に付与されます。所属組織内におけるオペレーターアカウントの作成・無効化・役割の変更など、組織運営全般を担当します。
* **一般マネージャー**
  * GINT所属の運営担当者に付与されます。お客様アカウントの閲覧、リモートサポート、OTAリリース状況の確認など、運営実務を担当します。GINTマスターアカウントからのみ付与可能です。
* **アドミン**
  * GINT所属の運営管理者に付与されます。オペレーターアカウントの作成・管理、OTAリリースの作成、RTKアカウントの管理など、システム全般の統括を行います。GITNマスターアカウントからのみ付与可能です。
{% endhint %}
{% endstep %}

{% step %}
全ての必須項目を入力すると\[アカウントの作成]が有効になります。ボタンを選択し、アカウントの作成を完了させます。

<figure><img src="../../.gitbook/assets/operator-management-account-add-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**アカウントを作成すると、登録済みのメールアドレス宛に仮パスワードが送信されます。**\
メールアドレスが受信できない場合は、迷惑メールフォルダをご確認ください。
{% endhint %}
{% endstep %}
{% endstepper %}

***

### オペレーター情報の修正

{% stepper %}
{% step %}
オペレーターの詳細から ![](../../.gitbook/assets/ic_more.svg)ボタンをタップし\[修正]を選択します。

<figure><img src="../../.gitbook/assets/operator-management-account-edit-1 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
内容を変更し\[修正完了]をタップします。

<figure><img src="../../.gitbook/assets/operator-management-account-edit-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
修正が完了します。

<figure><img src="../../.gitbook/assets/operator-management-account-edit-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### オペレーターの無効化 / 有効化

アカウントの使用を一時中断、或いは再度有効化できます。

{% hint style="info" %}
オペレーターアカウントは削除されず、無効化することでアクセスが遮断されます。無効になったアカウントはログイン不可となりますが、履歴はそのまま保存されます。
{% endhint %}

{% stepper %}
{% step %}
オペレーター詳細から ![](../../.gitbook/assets/ic_more.svg)をタップし\[無効化]を選択します。

<figure><img src="../../.gitbook/assets/operator-management-account-status-toggle-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
確認ポップアップが表示されたら\[確認]をタップします。

<figure><img src="../../.gitbook/assets/operator-management-account-status-toggle-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
アカウントが無効になります。

<figure><img src="../../.gitbook/assets/operator-management-account-status-toggle-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
アカウントが無効の状態では、有効化オプションのみ表示されます。該当する項目を選択すると、アカウントが有効になります。
{% endhint %}

<figure><img src="../../.gitbook/assets/operator-management-account-active.png" alt=""><figcaption></figcaption></figure>

***

### オペレーターアカウントの詳細情報

アカウント一覧からお客様を選択すると、そのアカウントの詳細情報画面へ移動します。

#### PC環境

<figure><img src="../../.gitbook/assets/operator-management-account-detail-pc-1 (1).png" alt=""><figcaption></figcaption></figure>

![](../../.gitbook/assets/icon-square-1.svg) ステータス

![](../../.gitbook/assets/icon-square-2.svg) お名前

![](../../.gitbook/assets/icon-square-3.svg) 詳細ボタン

{% hint style="info" %}
クリックすると\[修正]、\[無効化]（あるいは\[有効化]）を選択できます。
{% endhint %}

![](../../.gitbook/assets/icon-square-4.svg) 役割

![](../../.gitbook/assets/icon-square-5.svg) 作成日

![](../../.gitbook/assets/icon-square-6.svg) メールアドレス

![](../../.gitbook/assets/icon-square-7.svg) 携帯電話番号

![](../../.gitbook/assets/icon-square-8.svg) 所属

{% hint style="info" %}
所属をクリックすると、該当する所属の詳細画面へ移動します。
{% endhint %}

![](../../.gitbook/assets/icon-square-9.svg) タグ

* 所属に関する情報が表示されます。

#### モバイル環境

<div align="left"><figure><img src="../../.gitbook/assets/operator-management-account-detail-mobile-1.png" alt="" width="273"><figcaption></figcaption></figure></div>

![](../../.gitbook/assets/icon-square-1.svg) ステータス

![](../../.gitbook/assets/icon-square-2.svg) お名前

![](../../.gitbook/assets/icon-square-3.svg) 詳細ボタン

{% hint style="info" %}
タップすると\[修正]、\[無効化]（あるいは\[有効化]）を選択できます。
{% endhint %}

![](../../.gitbook/assets/icon-square-4.svg) 役割

![](../../.gitbook/assets/icon-square-5.svg) 作成日

![](../../.gitbook/assets/icon-square-6.svg) メールアドレス

![](../../.gitbook/assets/icon-square-7.svg) 携帯電話番号

![](../../.gitbook/assets/icon-square-8.svg) 所属

{% hint style="info" %}
所属をタップすると、該当する所属の詳細画面へ移動します。
{% endhint %}

![](../../.gitbook/assets/icon-square-9.svg) タグ

* 所属に関する情報が表示されます。
