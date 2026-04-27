---
layout:
  width: default
  title:
    visible: true
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
  tags:
    visible: true
metaLinks:
  alternates:
    - /broken/spaces/YgZGmmCCfllSmVLHO3Uz/pages/dPPAQXkAxq7Xk0KEpD0E
---

# 車両の補正

正確な自動操舵のための車両補正を行います。車両の補正は計3項目あり「全ての補正を進める」をタップし、まとめて進めることができます。

***

#### 車両タイプごとの補正項目

**一般車両**

それぞれの補正項目を**1回ずつ**進めます。

1. [GNSS受信機の位置設定](vehicle-calibration.md#gnss)
2. [オートステア補正](vehicle-calibration.md#auto)

**倍速モード機能付き車両**

倍速モード機能付き車両は、**倍速モードOFF/ONのそれぞれの状態で**オートステア補正を行います。\
つまり、オートステア補正は、**合計2回**実施されます。

{% hint style="warning" %}
車両追加時&#x306B;**\[倍速モード車両]のトグルを必ずON**に設定し登録してください。\
トグルの設定に従って、倍速モード車両に適合した補正が開始されます。
{% endhint %}

1. [GNSS受信機の位置設定](vehicle-calibration.md#gnss)
2. [オートステア補正](vehicle-calibration.md#auto)
   * 1回目：倍速モード**OFF**の状態で補正が進められる。
   * 2回目：倍速モード**ON**の状態で補正が進められる。

***

#### 車両の補正を開始する

{% stepper %}
{% step %}
\[全ての補正を進める]をタップし、補正を開始します。

<figure><img src="../../.gitbook/assets/set-calibration.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

#### GNSS受信機の位置設定

傾斜地や不整地でも正確な方向と姿勢を維持するために、GNSS受信機の基準値を調整する機能です。取り付け状態によって傾きが大きい場合は、数値を入力して補正を行うことができます。

{% stepper %}
{% step %}
GNSS受信機の縦方向、横方向、取り付け高さを入力し\[確認]を選択します。

<figure><img src="../../.gitbook/assets/set-location-gnss-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
ロール、ピッチ、ヨー値を入力し、\[確認]を選択するとGNSS受信機の位置設定が完了します。

<figure><img src="../../.gitbook/assets/set-location-gnss-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**GNSS受信機の位置入力に関する注意事項**

\
1\. 縦方向を測定する際には、シールの裏面を測定してください。

<img src="../../.gitbook/assets/set-location-gnss-middle-1.png" alt="" data-size="original">

2. 横方向を測定する際には、GNSS受信機下部の突起部分を測定してください。

![](../../.gitbook/assets/set-location-gnss-middle-2.png)<br>
{% endhint %}

#### GNSS受信機の位置設定に関するご案内

1. **縦方向、横方向、取り付け高さの設定**

*   縦方向の位置：フロントアクスルを基準に前側 - 後ろ側 +<br>

    <figure><img src="../../.gitbook/assets/set-location-gnss-tractor-1.png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/set-location-gnss-leeangi-1.png" alt=""><figcaption></figcaption></figure>
*   横方向の位置：アクスル中央を基準に右側 + 左側 -<br>

    <figure><img src="../../.gitbook/assets/set-location-gnss-tractor-2.png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/set-location-gnss-leeangi-2.png" alt=""><figcaption></figcaption></figure>
*   取り付け高さ：地面から受信機の取り付け位置までの距離<br>

    <figure><img src="../../.gitbook/assets/set-location-gnss-tractor-3.png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/set-location-gnss-leeangi-3.png" alt=""><figcaption></figcaption></figure>

2. **ロール/ピッチ/ヨー設定**

<figure><img src="../../.gitbook/assets/set-location-gnss-pitch.png" alt=""><figcaption></figcaption></figure>

![](../../.gitbook/assets/icon-square-1.svg) **ROLL ロール**

* GNSS受信機が左右方向に傾いた角度を表します。

![](../../.gitbook/assets/icon-square-2.svg) **Pitch ピッチ**

* GNSS受信機が前後方向に傾いた角度を表します。

![](../../.gitbook/assets/icon-square-3.svg) **Yaw ヨー**

* GNSS受信機が垂直軸を基準に回転した角度を表します。

***

#### 一般車両のオートステア補正 <a href="#auto" id="auto"></a>

オートステア補正は、設定された経路をスムーズに追従するよう、ステアリング範囲と直進基準値を補正するプロセスです。トラクターは2ステップ、田植え機は3ステップで行われます。

**トラクター（2ステップ）**

* ハンドル範囲補正 - 直進ステアリング補正
*

```
<figure><img src="../../.gitbook/assets/vehicle-calibration-tractor.png" alt=""><figcaption></figcaption></figure>
```

**田植え機 （3ステップ）**

* ハンドル範囲補正 - 直進ステアリング補正 - ステアリング角度補正
*

```
<figure><img src="../../.gitbook/assets/vehicle-calibration-leeangi.png" alt=""><figcaption></figcaption></figure>
```

***

#### トラクターのオートステア補正

1. **ハンドル範囲補正**

{% stepper %}
{% step %}
\[全ての補正を進める]をタップすると、オートステア補正が開始します。

<figure><img src="../../.gitbook/assets/handle-calibration-tractor-1.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
各ステップの開始を選択すると、該当するステップの補正のみが行われます。
{% endhint %}
{% endstep %}

{% step %}
案内に従ってハンドルを左いっぱいに回してから車両を停止し、\[確認]をタップします。

<figure><img src="../../.gitbook/assets/handle-calibration-tractor-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従ってハンドルを右いっぱいに回してから車両を停止し、\[確認]をタップします。

<figure><img src="../../.gitbook/assets/handle-calibration-tractor-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従ってハンドルを回し、車輪を中央に位置させ車両を停止してから\[確認]をタップします。

<figure><img src="../../.gitbook/assets/handle-calibration-tractor-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
ハンドル範囲補正が完了します。

<figure><img src="../../.gitbook/assets/handle-calibration-tractor-5.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

2. **直進ステアリング補正**

{% stepper %}
{% step %}
直進ステアリング補正に必要な案内を確認し、\[確認]をタップします。

<figure><img src="../../.gitbook/assets/straight-calibration-tractor-1.png" alt="" width="563"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従って\[時速2km]で走行し\[自動補正の開始]をタップします。

<figure><img src="../../.gitbook/assets/straight-calibration-tractor-2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
補正時のトラクターの制限速度は時速2kmであり、スピードを超えると、ボタンが有効になりません。
{% endhint %}

{% hint style="info" %}
トラクターが停止した場合、直進ステアリング補正を最初からやり直す必要があります。
{% endhint %}

{% hint style="info" %}
直進ステアリング補正中には、ハンドルが自動で回ります。自動操作中にはハンドルを無理に操作しないでください。
{% endhint %}
{% endstep %}

{% step %}
引き続き時速2km以下で走行します。

<figure><img src="../../.gitbook/assets/straight-calibration-tractor-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
補正時に必要なスペースが確保できない、または走行不可の場合、緊急停止をタップしてください。
{% endhint %}
{% endstep %}

{% step %}
補正が終了すると\[確認]ボタンが有効になります。タップし、補正を完了してください。

<figure><img src="../../.gitbook/assets/straight-calibration-tractor-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

#### 田植え機のオートステア補正

1. **ハンドル範囲補正**

{% stepper %}
{% step %}
\[全ての補正を進める]をタップすると、オートステア補正が開始します。

<figure><img src="../../.gitbook/assets/handle-calibration-leeangi-1.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
各ステップの「開始」をタップすると、該当するステップの補正のみを実施できます。
{% endhint %}
{% endstep %}

{% step %}
案内に従ってハンドルを左いっぱいに回してから車両を停止し、\[確認]をタップします。

<figure><img src="../../.gitbook/assets/handle-calibration-leeangi-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従ってハンドルを右いっぱいに回してから車両を停止し、\[確認]をタップします。

<figure><img src="../../.gitbook/assets/handle-calibration-leeangi-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従ってハンドルを回し、車輪を中央に位置させ車両を停止してから\[確認]をタップします。

<figure><img src="../../.gitbook/assets/handle-calibration-leeangi-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
ハンドル範囲補正が完了します。

<figure><img src="../../.gitbook/assets/handle-calibration-leeangi-5.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

2. **直進ステアリング補正**

{% stepper %}
{% step %}
直進ステアリング補正に必要な案内を確認してから\[確認]をタップします。

<figure><img src="../../.gitbook/assets/straight-calibration-leeangi-1.png" alt="" width="563"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従って\[時速2km]で走行し\[自動補正の開始]をタップします。

<figure><img src="../../.gitbook/assets/straight-calibration-leeangi-2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
補正時の田植え機の制限速度は時速2kmであり、スピードを超えると、ボタンが有効になりません。
{% endhint %}

{% hint style="info" %}
田植え機が停止した場合、直進ステアリング補正を最初からやり直す必要があります。
{% endhint %}

{% hint style="info" %}
直進ステアリング補正中には、ハンドルが自動で回ります。自動操作中にはハンドルを無理に操作しないでください。
{% endhint %}
{% endstep %}

{% step %}
引き続き時速2km以下で走行します。

<figure><img src="../../.gitbook/assets/straight-calibration-leeangi-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
補正時に必要なスペースが確保できない、または走行不可の場合、緊急停止をタップしてください。
{% endhint %}
{% endstep %}

{% step %}
補正が完了すると\[ステアリング角度補正の開始]ボタンが表示されます。タップし、次の補正を開始してください。

<figure><img src="../../.gitbook/assets/straight-calibration-leeangi-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

3. **ステアリング角度補正**

{% stepper %}
{% step %}
案内に従って\[時速2km]で走行し\[自動補正の開始]をタップします。

<figure><img src="../../.gitbook/assets/straight-calibration-leeangi-2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
補正時の田植え機の制限速度は時速2kmであり、スピードを超えると、ボタンが有効になりません。
{% endhint %}

{% hint style="info" %}
田植え機が停止した場合、直進ステアリング補正を最初からやり直す必要があります。
{% endhint %}

{% hint style="info" %}
直進ステアリング補正中には、ハンドルが自動で回ります。自動操作中にはハンドルを無理に操作しないでください。
{% endhint %}
{% endstep %}

{% step %}
引き続き時速2km以下で走行します。

<figure><img src="../../.gitbook/assets/straight-calibration-leeangi-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
補正時に必要なスペースが確保できない、または走行不可の場合、緊急停止をタップしてください。
{% endhint %}
{% endstep %}

{% step %}
補正が完了すると\[確認]ボタンが有効になります。タップすると補正が完了され、圃場の設定に進みます。

<figure><img src="../../.gitbook/assets/angle-calibration-leeangi-complete.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### 倍速モード車両のオートステア補正

倍速モード車両は、**倍速モードOFF/ONのそれぞれの状態で**同一の補正を行います。

{% hint style="warning" %}
倍速モード車両のオートステア補正は、車両追加時に\[倍速モード車両]のトグルをONに設定した場合のみ実施できます。\
倍速モード車両の場合、必ずこのオプションをONにしてください。
{% endhint %}

{% hint style="info" %}
倍速モードは、トラクター専用のオプションです。田植え機には倍速ターンのオプションが表示されません。
{% endhint %}

***

#### 倍速モードの補正プロセス

オートステア補正は計2回行われ、2回目まで終了すると補正が完了します。

* **1回目（倍速モードOFF状態）**
  * ハンドル範囲補正
  * 直進ステアリング補正
* **2回目（倍速モードON状態）**
  * 直進ステアリング補正

{% stepper %}
{% step %}
\[全ての補正を進める]をタップします。

<figure><img src="../../.gitbook/assets/calibration-speed-1 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
倍速モードを**OFF**に切り替え、**\[確認]**&#x3092;タップします。

<figure><img src="../../.gitbook/assets/calibration-speed-2 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
ハンドル範囲補正を進めます。

<figure><img src="../../.gitbook/assets/calibration-speed-3 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
案内に従って**ハンドル範囲補正**を完了します。引き続&#x304D;**\[直進ステアリング補正の開始]**&#x3092;タップします。

<figure><img src="../../.gitbook/assets/calibration-speed-4 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
直進ステアリング補正の画面の案内を確認します。

<figure><img src="../../.gitbook/assets/calibration-speed-5 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
1回目の直進ステアリング補正を進めます。

<figure><img src="../../.gitbook/assets/calibration-speed-6 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
1回目の直進ステアリング補正が完了したら、\[2回目の直進ステアリング補正の開始]をタップします。

<figure><img src="../../.gitbook/assets/calibration-speed-7.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
倍速モードの設定確認のポップアップが表示されます。倍速ターンをONに切り替え\[確認]をタップします。

<figure><img src="../../.gitbook/assets/calibration-speed-8 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**2回目の直進ステアリング補正**を進めます。

<figure><img src="../../.gitbook/assets/calibration-speed-9.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**2回目の直進ステアリング補正**が完了したら、倍速モード車両のオートステア補正が完了されます。**\[次のステップへ]**&#x3092;タップし、**圃場の設定**にアクセスします。

<figure><img src="../../.gitbook/assets/calibration-speed-10 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
