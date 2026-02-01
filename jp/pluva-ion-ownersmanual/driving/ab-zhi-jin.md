---
layout:
  width: default
  title:
    visible: false
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# AB直進

### AB直進

AB直進

* A点とB点を結ぶ方向へ直進走行します。

<div align="left"><figure><img src="../../.gitbook/assets/ab-straight-forward.png" alt="" width="150"><figcaption></figcaption></figure></div>



{% stepper %}
{% step %}
<img src="../../.gitbook/assets/a-button.png" alt="" data-size="line"> を押してA地点を生成します。

<figure><img src="../../.gitbook/assets/ab-straight-explanation-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
10m以上直進走行した後、ご希望の地点で <img src="../../.gitbook/assets/b-button.png" alt="" data-size="line"> を押してB地点を生成します。

<figure><img src="../../.gitbook/assets/ab-straight-explanation-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
AB直進経路が生成されたら <img src="../../.gitbook/assets/drive-button.png" alt="" data-size="line"> \[自動操舵の開始]を押して自動操舵を始めます。

<figure><img src="../../.gitbook/assets/ab-straight-explanation-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

#### 自動ABラインの生成

自動ABラインの生成は、圃場の条件に合わせて直進基準経路を自動で作ってくれる機能です。 生成後にプレビュー上で間隔/余裕区間などの値を必要に応じて調整できます。

{% stepper %}
{% step %}
AB直進モードで、 <img src="../../.gitbook/assets/automatic-path-button.png" alt="" data-size="line"> \[ABラインの自動生成ボタン]を押します。

<figure><img src="../../.gitbook/assets/automatic-path-explanation-1.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
生成された圃場がない場合は、ガイドに従ってすぐ圃場を登録できます。

<img src="../../.gitbook/assets/automatic-path-nonefield.png" alt="" data-size="original">
{% endhint %}
{% endstep %}

{% step %}
圃場エリアが有効になり自動ABラインが生成されます。

<figure><img src="../../.gitbook/assets/automatic-path-explanation-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
生成完了後、プレビューが表示されます。 必要に応じて設定を調整し\[確認]をタップしてください。

<figure><img src="../../.gitbook/assets/automatic-path-explanation-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
次の設定で細かい調整ができます。

* 現在地を基準に生成：現在地を基準にラインを生成します。
* ![](../../.gitbook/assets/my-location-criteria.png)
  * 従来の生成ライン：白
  * 現在地を基準に生成されたライン：青
* 横走行（縦走行）：進行方向の基準が切り替わります。タップすると縦走行ボタンに切り替わります。
* ![縦走行](../../.gitbook/assets/vertical-drive.png)
  * 縦走行
* ![縦走行](../../.gitbook/assets/horizontal-drive.png)
  * 横走行
* A/B点の入れ替え：A点とB点を入れ替えます。
* ![](../../.gitbook/assets/before-replace-abpoints.png)
  * 変更前
* ![](../../.gitbook/assets/after-replace-abpoints.png)
  * 変更後
* 等間隔：数値で等間隔を調整します。
* ![](../../.gitbook/assets/equidistant-interval.png)
* 枕地：数値で枕地の間隔を調整します。
* ![](../../.gitbook/assets/headland.png)
{% endhint %}


{% endstep %}

{% step %}
<img src="../../.gitbook/assets/drive_ai-button.png" alt="" data-size="line">\[自動操舵]ボタンを押すと、生成された経路に沿って走行が開始されます。

<figure><img src="../../.gitbook/assets/automatic-path-explanation-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
