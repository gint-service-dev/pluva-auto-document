---
layout:
  width: wide
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

# 1. RTK-GPS 데이터 설정

## 4-1. RTK-GPS 데이터 설정

***

### a. 블루투스 RTK-GPS 설정

> **ℹ️ 고객이 사전에 RTK-GPS 계정을 발급받도록 안내한다.** 블루투스 연결을 사용할 경우 플루바오토 앱에서 별도의 설정을 진행하지 않아도 된다.

{% stepper %}
{% step %}
#### 스위치를 눌러 플루바오토의 전원을 켠다.
{% endstep %}

{% step %}
#### RTK-GPS 앱이 설치된 스마트폰 또는 태블릿에서 블루투스를 켠다.
{% endstep %}

{% step %}
#### RTK-GPS 앱을 실행한다.
{% endstep %}

{% step %}
#### 플루바오토 페어링을 진행한다.

> 1. 호쿠렌 앱 사용 시: 접속 설정
> 2. 데이터 전송
> 3. 기지국 신호
> 4. 설정
> 5. 블루투스 디바이스 설정
> 6. 블루투스 시스템 설정
> 7. 사용 가능한 디바이스
> 8. SerialADTXX(X는 숫자 또는 알파벳) 선택
> 9. 비밀번호 1234 입력
> 10. OK

> **ℹ️** \[참고] 블루투스가 연결된 호쿠렌 RTK-GPS 앱 화면
>
> <img src="../.gitbook/assets/4-1. 호쿠렌 앱 (1).png" alt="" data-size="original">
{% endstep %}

{% step %}
#### 블루투스가 연결되었는지 확인한다.
{% endstep %}
{% endstepper %}

> **ℹ️ 고객이 계정 정보를 잊었다면, RTK-GPS 시스템 이용 신청 시 신청서에 기재한 이메일에 로그인하여 가입 당시 수신한 메일을 확인하도록 안내한다.** 해당 메일에는 ID, 비밀번호 기지국 정보 등이 포함되어 있다.
>
> **ℹ️ RTK-GPS 앱에서 연결 오류가 발생한다면, 앱에 정보가 정확하게 입력되었는지 확인한다.**\
> ID, 비밀번호, 포트번호 등 RTK-GPS 사업자가 제공한 정보 그대로 입력해야 서비스를 정상적으로 이용할 수 있다.
>
> **ℹ️ 블루투스는 인터페이스 박스와 페어링된다.**&#xBA54;인컨트롤러를 다른 차량에 옮겨 사용할 경우, 블루투스 연결 대상을 다른 차량에 설치된 인터페이스 박스로 변경하도록 고객에게 안내한다.

***

### b. 블루투스 RTK-GPS 사용 시 유의사항

> **ℹ️** 플루바오토의 정확한 자율조향을 위해서는 작업 중 RTK-GPS 앱이 계속 작동되어야 한다. RTK가 잡히지 않을 경우 가장 먼저 RTK-GPS 앱이 꺼져 있는지 확인한다.

#### <mark style="background-color:$primary;">RTK-GPS 앱이 계속 꺼지는 이유</mark>

1. 앱이 백그라운드에 있을 때 고객이 실수로 앱을 종료할 수 있다. 아래 상황에서 앱이 꺼지므로 이런 동작을 하지 않도록 고객에게 미리 안내한다.

> * 최근 실행 앱 목록에서 RTK-GPS 앱을 위로 밀어 닫은 경우
> * 최근 실행 앱 목록에서 \[모두 닫기] 버튼을 누른 경우
> * 메모리 정리 앱을 사용한 경우

2. 배터리 절약을 위해 안드로이드가 앱을 자동으로 종료할 수 있다. 앱 자동 종료를 방지하기 위해 다음과 같이 설정한다.

> * 앱 설정에서 “배터리 최적화” 사용 OFF (사용하지 않는 앱의 백그라운드 활동을 제한하는 옵션 끄기)
> * 안드로이드 설정 > 백그라운드 앱 사용 제한에서 “자동 절전 예외 앱"으로 등록 (절전 모드 작동 시 절전 상태로 사용하지 않을 앱으로 설정하기)

#### <mark style="background-color:$primary;">RTK-GPS 앱 종료 예방법</mark>

1. 작업 시간에 맞춰 보조 배터리를 준비하거나 충전기를 연결해서 사용한다.
2. 정기적으로 RTK 연결 상태를 확인한다.

***

### c. 직접 수신 RTK-GPS 설정

{% stepper %}
{% step %}
#### 설정 화면에서 \[RTK 데이터 설정]을 선택한다.

<figure><img src="../.gitbook/assets/4-1.직접 설정(1).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 메인컨트롤러를 선택한다.

<figure><img src="../.gitbook/assets/4-1.직접 설정(2).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### RTK-GPS 시스템 정보를 입력하고 \[저장]을 누른다.

<figure><img src="../.gitbook/assets/4-1.직접 설정(3).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
