---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/8Sqfw92xyQ8XV1LQEpTt/undefined/driving-1/undefined-2
---

# 위치보정 설정

### 위치보정 설정

위치 보정은 RTK 보정 신호를 연결해 위치 정확도를 높이는 설정입니다. 현장 환경에 맞는 방식을 선택해 연결 상태를 구성합니다.



#### 위치 보정은 무엇인가요?

위성 신호가 계산한 “기본 위치”에서 오차를 줄이는 보정 정보를 받아 정밀도를 올리는 작업입니다.\
네트워크 상태가 불안정하면 정밀도가 떨어지거나 끊길 수 있습니다.

{% hint style="info" %}
설정된 값은 태블릿의 [위치보정 설정](undefined-2.md)에서 확인하고 변경할 수 있습니다.
{% endhint %}

***

#### RTK 직접 수신 연결

RTK 직접 수신은 태블릿이 RTK 서비스에 직접 연결하여 보정 신호를 수신하는 방식입니다.

{% stepper %}
{% step %}
RTK 직접 수신 연결을 선택하고 \[확인]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=320-12742&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
기지국/서버 정보를 입력한 뒤 \[연결]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=320-13014&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
연결이 되지 않거나 자주 끊기는 경우 네트워크 상태와 입력 정보(주소/포트/계정/마운트포인트)를 먼저 확인합니다. 영어 대소문자를 정확히 입력하고 불필요한 띄어쓰기를 하지 않아야 서비스를 정상적으로 이용할 수 있다.
{% endhint %}
{% endstep %}

{% step %}
RTK 직접 수신 설정이 완료됩니다. \[다음 단계로] 버튼을 누르면 차량 추가 단계로 진입합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=320-13092&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}

{% hint style="info" %}
고객이 사전에 RTK-GPS 계정을 발급받도록 안내합니다. 계정 정보를 잊었다면, 신청서에 기재한 이메일로 로그인해 가입 당시 수신한 메일을 확인하도록 안내합니다.
{% endhint %}

***

#### RTK 블루투스 연결

RTK 블루투스 연결은 스마트폰의 RTK 앱과 블루투스로 페어링하여, RTK 보정 신호를 GNSS 수신기로 전달하는 설정입니다.



{% stepper %}
{% step %}
RTK 블루투스 연결을 선택하고 \[확인]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=367-13093&t=PM760HAi58K4ZabD-1" %}
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
RTK 블루투스 설정이 완료됩니다. \[다음 단계로] 버튼을 누르면 차량 추가 단계로 진입합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=320-13092&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}

#### RTK 블루투스 연결 유의사항

플루바 아이온의 정확한 자율조향을 위해서는 작업 중 RTK-GPS 앱이 계속 작동되어야 한다. RTK가 잡히지 않을 경우 가장 먼저 RTK-GPS 앱이 꺼져 있는지 확인합니다.

> **RTK-GPS 앱이 꺼지는 주요 원인**
>
> 1. 사용자가 종료한 경우
>
> * 최근 실행 목록에서 앱을 위로 밀어 닫으면 종료됩니다.
> * 최근 실행 목록에서 \[모두 닫기\*를 누르면 함께 종료됩니다.
> * 메모리 정리 앱 사용 시 종료될 수 있습니다.
>
>
>
> 2. 안드로이드가 자동 종료한 경우
>
> * 배터리 절약 기능이 백그라운드 앱을 자동 종료할 수 있습니다.
> * 앱 설정에서 **배터리 최적화 OFF**로 설정합니다.
> * 안드로이드 설정에서 **자동 절전 예외 앱**으로 등록합니다.
>
>
>
> **RTK-GPS 외부 앱 종료 예방법**
>
> * 작업 시간에 맞춰 보조 배터리를 준비하거나 충전기를 연결해서 사용한다.
> * 정기적으로 RTK 연결 상태를 확인한다.

{% hint style="info" %}
고객이 계정 정보를 잊었다면, 신청서에 기재한 이메일로 로그인해 가입 당시 수신한 메일을 확인하도록 안내합니다. 해당 메일에는 ID, 비밀번호, 기지국 정보 등이 포함되어 있습니다.
{% endhint %}

{% hint style="info" %}
RTK-GPS 앱에서 연결 오류가 발생한다면, 앱에 정보가 정확하게 입력되었는지 확인한다.\
ID, 비밀번호, 포트번호 등 RTK-GPS 사업자가 제공한 정보 그대로 입력해야 서비스를 정상적으로 이용할 수 있다.
{% endhint %}
