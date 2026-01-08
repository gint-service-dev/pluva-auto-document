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

# 주행 화면 설명

### 주행 화면 설명

<figure><img src="../../.gitbook/assets/Group 1000001057.png" alt=""><figcaption><p>그림 iON 주행 화면</p></figcaption></figure>

![](../../.gitbook/assets/1.svg) **작업 상태**

* 실시간 농작업 상태를 3D 화면으로 표시하는 영역이다.
* 차량과 작업기의 움직임, 등간격 및 궤적을 실시간으로 확인할 수 있다.
* 작업 진행 상황, 속도, 면적, 작업 모드 등 현재 농작업에 필요한 핵심 정보를 직관적으로 제공한다.

![](../../.gitbook/assets/2.svg) **화면 비율 조정 기능**

* 화면 상단에 위치한 영역으로, 농작업에 필요한 핵심 시스템 정보를 실시간으로 표시한다.
* 작업 상황에 따라 3D 상세 정보와 전체 지도 정보의 비율을 조절하여 최적의 작업 환경을 구성한다.

![](../../.gitbook/assets/3.svg) **작업 메뉴 모음**

* 농작업 중 자주 사용하는 주요 기능에 빠르게 접근할 수 있는 하단 고정 메뉴 영역이다.
* 작업을 중단하지 않고 필수 메뉴를 원터치로 실행할 수 있어 작업 효율을 높인다.

![](../../.gitbook/assets/4.svg) **작업 영역**

* 전체 농지를 위성 지도 형태로 표시하여 작업 영역과 진행 상황을 보여주는 영역이다.\
  바운더리, AB 라인, 전체 경로 등 농지 전체의 맥락 정보를 제공하여 전체 작업 계획과 진행도를 파악할 수 있다.

***

### 작업 상태

<figure><img src="../../.gitbook/assets/Group 1000001058.png" alt=""><figcaption><p>그림 iON 주행 화면</p></figcaption></figure>

![](../../.gitbook/assets/1.svg) **주행 정보**

* 주행 모드, 주행 시간, 주행 면적, 주행 속도를 표시하는 영역입니다.

![](../../.gitbook/assets/2.svg) **OTE 정보**

* 현재 차량이 설정된 주행 라인을 기준으로 좌우로 얼마나 벗어났는지 실시간으로 표시하는 정밀도 지표입니다.
* 중앙(0)에서 멀어질수록 편차가 크다는 의미이며, 운전자가 직진 정확도를 즉시 확인할 수 있습니다.

{% hint style="info" %}
AB 라인 설정 시에만 노출됩니다.
{% endhint %}

![](../../.gitbook/assets/3.svg) **실시간 작업 상태**

* 현재 차량과 부착된 작업기의 상태를 3차원으로 시각화하는 영역입니다.
* GPS, IMU 센서, 조향각 데이터를 기반으로 작업 상태, 주행 상태, 부착 상태를 직관적으로 표현하여 실시간 상황을 한눈에 파악할 수 있습니다.

***

### 작업 영역

<figure><img src="../../.gitbook/assets/Group 1000001059 (1).png" alt=""><figcaption><p>그림 iON 주행 화면</p></figcaption></figure>

![](../../.gitbook/assets/1.svg) **시스템 상태**

* 화면 최상단에 위치하며, 농작업에 필요한 핵심 시스템 정보를 실시간으로 표시하는 영역입니다.
* GPS 신호, 통신 상태, RTK 정밀도 등 서비스 구동에 필요한 필수 연결 상태와 현재 환경 정보를 한눈에 확인할 수 있습니다.

![](../../.gitbook/assets/2.svg) **주행 메세지**

* 주행 상태에 따른 실시간 안내 및 경고 메시지를 표시하는 영역입니다.

![](../../.gitbook/assets/3.svg) **나침판**

* 차량 헤딩 방향을 실시간으로 표시하는 나침반 영역입니다.
* 작업 상황에 따라 지도 줌 레벨을 전환하며, 차량이 향하는 방위를 직관적으로 확인할 수 있습니다.
* 차량 이동에 따라 지도가 실시간으로 회전하며 방위를 갱신합니다.

![](../../.gitbook/assets/3.svg) **지도 스케일 전환**

* AB 라인 설정과 자율주행 제어를 한 영역에서 관리하는 컨텍스트 기반 버튼입니다.
* 작업 상태에 따라 버튼이 자동으로 전환됩니다.

![](../../.gitbook/assets/3.svg) **\[A/B/A+]점 버튼, 자율주행 버튼**

* AB 라인 설정과 자율주행 제어를 한 영역에서 관리하는 컨텍스트 기반 버튼입니다. 작업 상태에 따라 버튼이 자동으로 전환됩니다.

{% tabs %}
{% tab title="A/B/A+ 버튼" %}
현재 차량 위치를 기준점으로 설정합니다.

<div align="left"><figure><img src="../../.gitbook/assets/btn_drivea (1).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/btn_drive (3).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/btn_drive-1 (2).png" alt=""><figcaption></figcaption></figure></div>
{% endtab %}

{% tab title="시작 버튼" %}
자율주행 모드를 활성화합니다.

<div align="left"><figure><img src="../../.gitbook/assets/btn_drive-3.png" alt=""><figcaption></figcaption></figure></div>
{% endtab %}

{% tab title="정지 버튼" %}
자율주행을 즉시 해제합니다.

<div align="left"><figure><img src="../../.gitbook/assets/btn_drive-2.png" alt=""><figcaption></figcaption></figure></div>
{% endtab %}
{% endtabs %}

***

### 주행 기능

{% content-ref url="undefined-1/" %}
[undefined-1](undefined-1/)
{% endcontent-ref %}

{% content-ref url="undefined-2/" %}
[undefined-2](undefined-2/)
{% endcontent-ref %}

