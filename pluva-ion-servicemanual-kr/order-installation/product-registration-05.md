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
  actions:
    visible: true
  anchors:
    visible: true
tags:
  - tag: kr-jp
    primary: true
---

# 설치티켓으로 제품 개통 - New

설치티켓에 제품을 등록하여 개통키를 발급합니다. 원활한 설치를 위해 설치 전 개통을 권장합니다.

{% hint style="info" %}
설치티켓이 무엇인가요?

주문한 상품별로 **설치 상태를 체크할 수 있는 관리 티켓**입니다.
{% endhint %}

***

#### 주문 제품별 개통 구성품

각 주문 제품에 따라 아래 구성품을 준비합니다.

1. **플루바 아이온**

* 모든 주요 구성품을 등록합니다.
  * 태블릿
  * GNSS 수신기
  * 전동 스티어링 휠

2. **플루바 아이온 Expansion Kit (확장키트)**

* 태블릿을 제외한 구성품들을 등록합니다.
  * GNSS 수신기
  * 전동 스티어링 휠

3. **추가 옵션**

* 스위치

***

#### 시리얼 넘버 등록 (패키징 넘버)

제품 등록은 제품에 부착된 QR 코드(시리얼 넘버 혹은 패키징 넘버)를 스캔해 진행합니다.

* 패키징 넘버(패키지 박스 QR)를 등록하면, 구성품을 **한 번에 등록**할 수 있습니다.

#### QR 코드 위치 안내

#### 패캐지 시리얼 넘버

{% columns %}
{% column width="58.333333333333336%" %}
박스 측면의 QR코드를 확인합니다.

<figure><img src="../.gitbook/assets/serial-number-package.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="41.666666666666664%" %}

{% endcolumn %}
{% endcolumns %}

#### 개별 시리얼 넘버

{% columns %}
{% column %}
**태블릿**

후면의 QR코드를 확인합니다.

<figure><img src="../.gitbook/assets/serial-number-tablet.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
**GNSS 수신기**

우측면 또는 하단의 QR 코드를 확인합니다.

<figure><img src="../.gitbook/assets/serial-number-gnss.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column %}
**전동 스티어링 휠**

모터 측면에 QR 코드를 확인합니다.

<figure><img src="../.gitbook/assets/serial-number-wheel.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
**스위치**

후면의 QR코드를 확인합니다.

<figure><img src="../.gitbook/assets/serial-number-switch.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

***

#### 설치 티켓 목록 진입 방법

{% stepper %}
{% step %}
[어드민 페이지](https://gint-admin.pluva.kr/auth/operators/login)에 로그인합니다.

<div align="left"><figure><img src="../.gitbook/assets/enter-ticket-1.png" alt="" width="348"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
설치 관리 → 설치 티켓 목록에 진입하고 \[설치 등록]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (301).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
왼쪽 상단 더보기 버튼을 누르고 설치 관리 > 설치 목록에 접속할 수 있습니다.

![](<../.gitbook/assets/image (320).png>)
{% endhint %}
{% endstep %}
{% endstepper %}

***

#### 제품 개통 방법

제품 개통 방법은 아래의 세가지 방법을 확인할 수 있습니다.

1. **플루바 아이온**: 자율 주행 키트 본품
2. **Expension Kit**: 자율 주행 확장 키트
3. **스위치**: 옵션 품목

<details>

<summary><strong>플루바 아이온 개통 방법</strong><br>클릭하면 설명이 열립니다.</summary>

{% stepper %}
{% step %}
담당 조직과 설치 제품을 선택합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (308).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
설치 제품 선택 시 플루바 아이온을 선택합니다.

![](<../.gitbook/assets/image (332).png>)
{% endhint %}
{% endstep %}

{% step %}
설치할 제품을 선택하면 제품 목록이 자동으로 생성됩니다. 확인 후 \[등록 시작]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (307).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
\[패키지로 한번에 개통]을 눌러 주요 제품을 개통합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (309).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
패키지 넘버 QR 코드를 스캔합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (314).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
카메라 스캔으로 올바른 코드가 입력되지 않을 경우, \[시리얼 번호 직접 입력]을 눌러 직접 입력합니다.

![](<../.gitbook/assets/image (377).png>)
{% endhint %}
{% endstep %}

{% step %}
패키지 넘버를 확인한 뒤 \[확인 완료]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (315).png" alt="" width="375"><figcaption></figcaption></figure></div>

&#x20;
{% endstep %}

{% step %}
스캔이 완료되면 \[다음]을 누릅니다

<div align="left"><figure><img src="../.gitbook/assets/image (317).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
추가 옵션을 주문할 경우 주요 제품 개통 이후 추가 옵션 개통을 진행해야 개통이 완료됩니다.

![](<../.gitbook/assets/image (319).png>)
{% endhint %}
{% endstep %}

{% step %}
유심을 등록한 뒤 \[다음]을 누릅니다.

{% hint style="info" %}
유심 등록은 선택 사항이며, 추후 등록할 수 있습니다.
{% endhint %}

<div align="left"><figure><img src="../.gitbook/assets/image (340).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
**유심 등록 방법**

1.  \[등록] 버튼을 누릅니다.

    <div align="left"><figure><img src="../.gitbook/assets/image (336).png" alt="" width="375"><figcaption></figcaption></figure></div>
2.  \[직접 입력] 하거나 \[촬영하기]를 통해 유심 바코드를 등록합니다.

    <div align="left"><figure><img src="../.gitbook/assets/image (337).png" alt="" width="360"><figcaption></figcaption></figure></div>
3.  유심 번호를 확인하고 \[확인 완료]를 누릅니다.

    <div align="left"><figure><img src="../.gitbook/assets/image (339).png" alt="" width="375"><figcaption></figcaption></figure></div>
4.  유심 등록이 완료됩니다.

    <div align="left"><figure><img src="../.gitbook/assets/image (341).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endhint %}
{% endstep %}

{% step %}
설치 등록 정보를 확인한 뒤 \[등록]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (351).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
설치 등록을 확인하는 모달창에서 \[등록 완료]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (330).png" alt="" width="360"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
등록이 완료 됩니다.

<div align="left"><figure><img src="../.gitbook/assets/image (331).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
고객이 로그인하기 전까지는 \[설치 취소] 버튼을 통하여 취소가 가능합니다.
{% endhint %}
{% endstep %}
{% endstepper %}

</details>

<details>

<summary><strong>Expension Kit 개통 방법</strong><br>클릭하면 설명이 열립니다.</summary>

{% stepper %}
{% step %}
담당 조직과 설치 제품을 선택합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (308).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
설치 제품 선택 시 Expension Kit를 선택합니다.

![](<../.gitbook/assets/image (333).png>)
{% endhint %}
{% endstep %}

{% step %}
설치할 제품을 선택하면 제품 목록이 자동으로 생성됩니다. 확인 후 \[등록 시작]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (334).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
\[패키지로 한번에 개통]을 눌러 주요 제품을 개통합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (335).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
패키지 넘버 QR 코드를 스캔합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (314).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
카메라 스캔으로 올바른 코드가 입력되지 않을 경우, \[시리얼 번호 직접 입력]을 눌러 직접 입력합니다.

![](<../.gitbook/assets/image (378).png>)
{% endhint %}
{% endstep %}

{% step %}
패키지 넘버를 확인한 뒤 \[확인 완료]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (315).png" alt="" width="375"><figcaption></figcaption></figure></div>

&#x20;
{% endstep %}

{% step %}
스캔이 완료되면 \[다음]을 누릅니다

<div align="left"><figure><img src="../.gitbook/assets/image (317).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
추가 옵션을 주문할 경우 주요 제품 개통 이후 추가 옵션 개통을 진행해야 개통이 완료됩니다.

![](<../.gitbook/assets/image (319).png>)
{% endhint %}
{% endstep %}

{% step %}
설치 등록 정보를 확인한 뒤 \[등록]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (353).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
설치 등록을 확인하는 모달창에서 \[등록 완료]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (330).png" alt="" width="360"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
등록이 완료 됩니다.

<div align="left"><figure><img src="../.gitbook/assets/image (381).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
고객이 로그인하기 전까지는 \[설치 취소] 버튼을 통하여 취소가 가능합니다.
{% endhint %}
{% endstep %}
{% endstepper %}

</details>

<details>

<summary><strong>스위치 개통 방법</strong><br>클릭하면 설명이 열립니다.</summary>

{% stepper %}
{% step %}
담당 조직과 설치 제품을 선택합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (308).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
설치 제품 선택 시 Expension Kit를 선택합니다.

![](<../.gitbook/assets/image (342).png>)
{% endhint %}
{% endstep %}

{% step %}
설치할 제품을 선택하면 제품 목록이 자동으로 생성됩니다. 확인 후 \[등록 시작]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (343).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
\[스위치]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (344).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
스위치 넘버 QR 코드를 스캔합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (345).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="info" %}
카메라 스캔으로 올바른 코드가 입력되지 않을 경우, \[시리얼 번호 직접 입력]을 눌러 직접 입력합니다.

![](<../.gitbook/assets/image (379).png>)
{% endhint %}
{% endstep %}

{% step %}
스위치 넘버를 확인한 뒤 \[확인 완료]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (315).png" alt="" width="375"><figcaption></figcaption></figure></div>

&#x20;
{% endstep %}

{% step %}
스캔이 완료되면 \[다음]을 누 릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (348).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
이후 사용자 계정 선택 화면에서 설치 사용자 이름을 검색합니다.

<div align="left"><figure><img src="../.gitbook/assets/image (349).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
설치 사용자 카드를 선택한 뒤 \[다음]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (350).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
설치 등록 정보를 확인한 뒤 \[등록]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (384).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
설치 등록을 확인하는 모달창에서 \[등록 완료]를 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (385).png" alt="" width="360"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
등록이 완료 됩니다.
{% endstep %}
{% endstepper %}

</details>

***

#### 이후 단계

[제품 설치](product-installation/)를 완료해 주세요.
