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
metaLinks:
  alternates:
    - https://app.gitbook.com/s/jOhU5MWpMqraceI5pg9u/ion/overview/gnss-receiver
---

# GNSS受信機

### GNSS受信機

GNSS受信機は、RTKを基盤とした高精度位置情報を利用し、農業機械の位置を精密に把握できます。補正データを用いて位置補正が行われ、設定内容は使用環境により変更される場合があります。

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버.png" alt="" width="563"><figcaption></figcaption></figure></div>

![](../../.gitbook/assets/1.svg) ステータス表示LED

**左側のLED**

表示状態: 電源及びシステムのハードウェアにおける異常有無

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED.png" alt="" width="375"><figcaption></figcaption></figure></div>

<table data-header-hidden><thead><tr><th width="100.4921875"></th><th></th><th></th></tr></thead><tbody><tr><td>色</td><td>青（点灯）</td><td>黄色で点滅</td></tr><tr><td>ステータス</td><td>正常</td><td>エラー発生</td></tr><tr><td>이미지</td><td><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED(정상).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED(오류 발생).png" alt=""></td></tr></tbody></table>



**中央のLED**

表示状態: GNSS補正情報の受信有無

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버 - 중앙 LED.png" alt="" width="375"><figcaption></figcaption></figure></div>

<table data-header-hidden><thead><tr><th width="99.57421875"></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>色</td><td>青（点灯）</td><td>青で点滅</td><td>OFF</td></tr><tr><td>ステータス</td><td>正常</td><td>5秒以上未受信</td><td>60秒以上未受信<br>（または受信記録なし）</td></tr><tr><td>이미지</td><td><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED(정상).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 중앙 LED(5초 이상 미수신).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 중앙 LED(60초 이상 미수신 ).png" alt=""></td></tr></tbody></table>



**右側のLED**

表示状態: GNSS RTKのステータス

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED.png" alt="" width="375"><figcaption></figcaption></figure></div>

<table data-header-hidden><thead><tr><th width="126.7890625"></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>色</td><td>青（点灯）</td><td>青で点滅</td><td>OFF</td></tr><tr><td>ステータス</td><td>RTK信号良好</td><td>RTK信号普通</td><td>その他のステータス</td></tr><tr><td>이미지</td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(RTK Fixed).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(RTK Fixed Float).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(그밖의 상태).png" alt=""></td></tr></tbody></table>

![](../../.gitbook/assets/2.svg) QRコード：製品登録時に使用されるQRコードです。

