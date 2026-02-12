---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/8Sqfw92xyQ8XV1LQEpTt/undefined-1/network-settings/rtk-setting
---

# 위치 보정 설정

### 위치 보정 설정

위치 보정은 RTK 등의 보정 신호를 연결해 위치 정확도를 높이는 설정입니다. 현장 환경에 맞는 방식을 선택해 연결 상태를 구성합니다.



#### 위치 보정은 무엇인가요?

위성 신호가 계산한 “기본 위치”에서 오차를 줄이는 보정 정보를 받아 정밀도를 올리는 작업입니다.\
네트워크 상태가 불안정하면 정밀도가 떨어지거나 끊길 수 있습니다.

***

#### 위치 보정 설정 접근 방법

{% stepper %}
{% step %}
![](../../.gitbook/assets/ic_menu.svg) 전체 메뉴 아이콘을 누릅니다.

<figure><img src="../../.gitbook/assets/position-calibration-settings-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
\[네트워크 설정]을 누릅니다.

<figure><img src="../../.gitbook/assets/position-calibration-settings-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
\[위치 보정]을 누릅니다.

<figure><img src="../../.gitbook/assets/position-calibration-settings-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
원하는 보정 방식을 선택해 설정합니다.

<figure><img src="../../.gitbook/assets/position-calibration-settings-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

#### 위치 보정 설정 화면 설명

<div align="left"><figure><img src="../../.gitbook/assets/position-calibration-settings-screen.png" alt=""><figcaption></figcaption></figure></div>

&#x20;![](<../../.gitbook/assets/icon-square-1 (1).svg>) **RTK 직접 수신 연결**

* 서버 정보를 입력해 보정 신호를 직접 수신합니다.

&#x20;![](<../../.gitbook/assets/icon-square-2 (1).svg>) **RTK 블루투스 연결**

* 스마트폰의 외부 앱을 통해 보정 신호를 받은 뒤, 블루투스로 연결합니다.\
  외부 앱이 꺼지면 보정 신호가 끊길 수 있습니다.

***

#### RTK 직접 수신 연결

RTK 직접 수신은 태블릿이 RTK 서비스에 직접 연결하여 보정 신호를 수신하는 방식입니다.

{% stepper %}
{% step %}
\[RTK 직접 수신 연결]에서 \[정보 입력]을 누릅니다.

<figure><img src="../../.gitbook/assets/rtk-direct-receive-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
기지국/서버 정보를 입력한 뒤 \[연결]을 누릅니다.

<figure><img src="../../.gitbook/assets/rtk-direct-receive-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
RTK 직접 수신 연결이 완료됩니다.

<figure><img src="../../.gitbook/assets/rtk-direct-receive-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
연결이 되지 않거나 자주 끊기는 경우 네트워크 상태와 입력 정보(주소/포트/계정/마운트포인트)를 먼저 확인합니다. 영어 대소문자를 정확히 입력하고 불필요한 띄어쓰기를 하지 않아야 서비스를 정상적으로 이용할 수 있다.
{% endhint %}
{% endstep %}
{% endstepper %}

***

#### RTK 블루투스 연결

RTK 블루투스 연결은 스마트폰의 RTK 앱과 블루투스로 페어링하여, 기지국(RTK) 보정 신호를 GNSS 수신기로 전달하는 설정입니다.

{% stepper %}
{% step %}
RTK 블루투스 연결의 \[선택]을 누릅니다.

<figure><img src="../../.gitbook/assets/rtk-bluetooth-connection-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
아래 절차에 따라 외부 블루투스 앱(RTK-GPS 등)에서 RTK 블루투스 연결 설정을 진행합니다.

1. RTK-GPS 앱이 설치된 스마트폰에서 블루투스(Bluetooth)를 켭니다.
2. 스마트폰/태블릿에서 RTK-GPS 앱을 실행합니다.
3. 앱 설정에서 기지국 신호 입력 방식을 Bluetooth(블루투스)로 선택합니다.
4. 플루바 아이온을 사용 가능한 디바이스 목록에서 선택합니다.
5. 비밀번호를 입력해 페어링을 완료합니다.
6. 앱 또는 스마트폰/태블릿의 블루투스 화면에서 연결됨 상태인지 확인합니다.
{% endstep %}

{% step %}
블루투스 연결이 진행됩니다.

<figure><img src="../../.gitbook/assets/rtk-bluetooth-connection-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
연결이 완료되면 \[확인]을 누릅니다.

<figure><img src="../../.gitbook/assets/rtk-bluetooth-connection-4 (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
연결을 실패할 경우 확인사항을 체크한 후 \[다시시도]를 누릅니다.

<img src="../../.gitbook/assets/bluetooth-connection-failure.png" alt="" data-size="original">
{% endhint %}
