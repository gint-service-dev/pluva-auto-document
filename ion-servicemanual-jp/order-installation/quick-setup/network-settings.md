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
    - /broken/spaces/YgZGmmCCfllSmVLHO3Uz/pages/rxpDeth5Md8BOyTlslfD
---

# ネットワーク設定

簡単セットアップの開始には、ネットワーク設定が必要です。

ネットワークに接続されていない場合、簡単セットアップを開始できませんので、必ず設定してください。

***

#### ネットワーク設定項目

1. セルラー（モバイルデータ通信）
2. Wi-Fi

{% hint style="info" %}
簡単セットアップ完了後も、タブレットのネットワーク設定よりネットワーク環境を確認及び設定変更できます。
{% endhint %}

***

#### セルラー接続

セルラーは、タブレットに挿入されたSimカードを介してモバイルネットワークに接続する方法です。

{% hint style="info" %}
セルラーは接続が安定しているため、リアルタイム補正信号が必要な精密作業には、セルラーの使用を推奨します。
{% endhint %}

{% hint style="info" %}
料金プランやデータ使用量に応じて費用が発生する場合があります。作業前に、Simカードの開通状態、データ残量、有効期限を必ずご確認ください。
{% endhint %}

{% stepper %}
{% step %}
セルラートグルをオンにします。

<figure><img src="../../.gitbook/assets/quick-setup-cellular-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
APNが自動的に接続されます。

<figure><img src="../../.gitbook/assets/quick-setup-cellular-2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
セルラー設定は、タブレットにSIｍカードが装着されている場合にのみ設定可能です。
{% endhint %}

{% hint style="info" %}
USIMカード挿入後、通信開始まで数分かかる場合があります。接続が確認できるまで電源を切らずにお待ちください。
{% endhint %}
{% endstep %}

{% step %}
\[次のステップへ]をタップするとネットワーク設定が完了します。

<figure><img src="../../.gitbook/assets/quick-setup-cellular-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

#### セルラー（LTE）へ接続不可時の対応フロー

セルラー（LTE）に接続できない場合には、下記のフローに従って確認してください。

{% hint style="warning" %}
状況

* <img src="../../.gitbook/assets/quick-setup-cellular_LTE.svg" alt="" data-size="line">セルラー（LTE）アイコンが表示されない場合
* セルラー（LTE）接続が頻繁に途切れる場合
{% endhint %}

{% stepper %}
{% step %}
**接続待機**

電源を入れてから最大**10分間**待機してください。ネットワーク登録及びAPN認証に時間がかかる場合があります。

{% hint style="info" %}
10分経っても繋がらない場合は、**APNの手動接続**を行ってください。

APN名の入力：ご使用のSimカードの通信事業者に合ったAPN名を入力します。

<img src="../../.gitbook/assets/quick-setup-cellular-direct (1).png" alt="" data-size="original">

* APN名の入力：ppsim.jp を入力します。

名前、パスワードなど任意の項目を入力した後、\[確認]をタップすると手動接続できます。
{% endhint %}

> **接続済み：** <img src="../../.gitbook/assets/quick-setup-cellular_LTE.svg" alt="" data-size="line">セルラー（LTE）アイコンの表示およびサーバー/RTKが正常接続した状態
>
> **接続失敗：** <img src="../../.gitbook/assets/quick-setup-cellular-bad.svg" alt="" data-size="line">信号なしの表示。ステップ2を進める。
{% endstep %}

{% step %}
**電源の再起動**

機器の電源を切ってから約10秒後に再び電源を入れます。再起動後、最大**5～10分間**待ちます。

> **接続済み：** <img src="../../.gitbook/assets/quick-setup-cellular_LTE.svg" alt="" data-size="line">セルラー（LET）接続アイコンの表示
>
> **接続失敗：** <img src="../../.gitbook/assets/quick-setup-cellular-bad.svg" alt="" data-size="line">信号なしの表示。ステップ3を進める。
{% endstep %}

{% step %}
**Simカードが正常認識されているかを確認し、再度差し込む**

1.  **Simカードの正常性確認**

    タブレットからSimカードを取り出し、スマートフォンに差し込んでからデータ通信（インターネット接続）できるかを確認します。

{% hint style="warning" %}
**接続失敗時：**&#x30B9;マートフォンでも接続できない場合は、通信事業者へお問い合わせするか、Simカードを交換してください。
{% endhint %}

2. **タブレットに再度差し込んでから確認する**\
   タブレットにSimカードを再度差し込み、電源を再起動してから最大**30分～1時間**待ちます。ネットワークへの再登録やIP割り当てに時間がかかる場合があります。

> **接続済み：** <img src="../../.gitbook/assets/quick-setup-cellular_LTE.svg" alt="" data-size="line">セルラー（LTE）へ接続済み
>
> **接続失敗：** <img src="../../.gitbook/assets/quick-setup-cellular-bad.svg" alt="" data-size="line">信号なし表示。ステップ4を進める。
{% endstep %}

{% step %}
**本社への取り合わせ**

1～3ステップまで全て進めたにもかかわらず接続できない場合は、以下の情報を確認のうえ、本社までお問い合わせください。

* Pluva iONのタブレット番号
* 接続できない状況が発生し始めた時間およびその内容
* 取り付け場所（地域）
* セルラー（LTE）アイコンのステータス（なし/弱い/繰り返し途切れる）
* 対応フロー（1～3ステップを進めたかどうか）
{% endstep %}
{% endstepper %}

***

#### Wi-Fi接続

Wi-Fiは、周辺の無線ルーターやスマートフォンのテザリングに接続して、インターネットを利用する方式です。

{% hint style="info" %}
通信環境によって信号が不安定、または範囲外になると接続が切れるおそれがあるため、限られた作業範囲内での使用を推奨します。
{% endhint %}

{% hint style="info" %}
テザリング使用時には、スマートフォンのバッテリー消耗やデータ使用量が増える場合があります。作業前にバッテリー残量や省電力設定をご確認ください。
{% endhint %}

{% stepper %}
{% step %}
\[Wi-Fi]タブをタップします。

<figure><img src="../../.gitbook/assets/quick-setup-wifi-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Wi-Fiのトグルをオンにします。

<figure><img src="../../.gitbook/assets/quick-setup-wifi-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
接続するWi-Fiネットワークを選択します。

<figure><img src="../../.gitbook/assets/quick-setup-wifi-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
\[次のステップへ]をタップすると、ネットワーク設定が完了します。

<figure><img src="../../.gitbook/assets/quick-setup-wifi-4.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Wi-Fiの通信範囲から離れると、接続が切断されるおそれがありますのでご注意ください。
{% endhint %}
{% endstep %}
{% endstepper %}
