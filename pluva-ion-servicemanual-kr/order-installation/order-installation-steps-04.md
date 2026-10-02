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

# 주문/설치 단계 설명

플루바 아이온은 전문 설치 과정이 필요한 제품입니다. 어드민의 **주문-설치 프로세스**를 통해 전문 엔지니어의 안전한 설치를 지원하고, 설치 이력을 투명하게 관리합니다.

***

### 주문 /설치 과정

{% stepper %}
{% step %}
**주문 등록**

* 어드민에 주문 정보를 입력하면 고객이 주문한 제품 수만큼 설치티켓이 자동 발행됩니다.\
  설치티켓은 설치에 필요한 정보를 포함하며 제품 등록, 개통, 설치 완료까지 전 과정을 관리하는 단위입니다.
* 자세한 내용은 [<mark style="color:$primary;">주문 등록</mark>](order-registration-04.md)를 참고하세요.
{% endstep %}

{% step %}
**고객 계정 준비**

* 서비스 사용에 필요한 고객 계정을 사전에 준비합니다. 해당 고객 계정 정보를 기반으로 맞춤 자율주행 서비스가 제공됩니다.
* 자세한 내용은 [<mark style="color:$primary;">고객 계정 준비</mark>](pre-installation-overview/preparing-accounts.md)를 참고하세요.
{% endstep %}

{% step %}
**설치티켓으로 제품 개통**

{% hint style="info" %}
설치티켓이 무엇인가요?

설치할 제품과 구성품을 등록하고, 설치 진행 상태를 관리하는 티켓입니다.
{% endhint %}

* 어드민에서 설치할 제품과 옵션을 선택하고, 패키지 또는 구성품의 시리얼 번호를 등록합니다. 등록을 완료하면 설치 티켓이 \[설치 중] 상태로 변경됩니다. 퀵셋업 전에 제품 등록을 완료해 주세요.
* 자세한 내용은 [<mark style="color:$primary;">제품 등록</mark>](product-registration-05.md)을 참고하세요.
{% endstep %}

{% step %}
**설치**

* 차량에 제품를 설치합니다. 기존 핸들을 자율주행용 핸들로 교체하고, 각종 센서 및 장치를 연결하는 작업을 포함합니다.
* 자세한 내용은 [<mark style="color:$primary;">제품 설치</mark>](product-installation/)를 참고하세요.
{% endstep %}

{% step %}
**퀵셋업**

{% hint style="info" %}
퀵셋업은 무엇인가요?

제품 설치 후 태블릿에서 사용에 필요한 초기 설정을 진행하는 과정입니다.
{% endhint %}

* 태블릿 화면 안내에 따라 네트워크와 장비 연결을 확인하고, 차량 등록·보정과 고객 계정 로그인 등 초기 설정을 진행합니다.
* 자세한 내용은 [<mark style="color:$primary;">퀵셋업</mark>](quick-setup-1/)을 참고하세요.
{% endstep %}

{% step %}
**시범 운행**

* 설치가 완료된 제품을 시범 운행하여, 설치 상태를 점검하고 **오작동/이상 여부를 확인**합니다. 문제가 발견되면 원인을 확인하고 필요한 조치를 진행합니다.
{% endstep %}

{% step %}
**고객 교육**

* 제품 설치가 완료된 후, 고객이 제품을 안전하게 사용할 수 있도록 **주요 기능과 사용 방법을 안내**합니다.
* 해당 내용은 [<mark style="color:$primary;">사용법</mark>](https://app.gitbook.com/s/9HnyeIfS3GCTBWJmvOCO/usage/initial-setup)을 참고하세요.
{% endstep %}

{% step %}
**설치 완료**

설치 티켓은 제품 종류에 따라 자동으로 \[완료] 처리됩니다.

* **기본 키트**: 태블릿에서 고객 계정 로그인을 완료하면 자동으로 처리됩니다.
* **확장 키트**: 등록한 장비가 기존 차량에 연결되면 자동으로 처리됩니다. 반영까지 최대 10분이 걸릴 수 있습니다.
{% endstep %}
{% endstepper %}
