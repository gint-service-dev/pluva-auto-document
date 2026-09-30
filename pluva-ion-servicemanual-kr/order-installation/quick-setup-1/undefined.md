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
---

# 제품 개통 확인

태블릿에서 제품과 설치 티켓의 등록 상태를 확인합니다. 어드민에서 제품 등록을 완료하고 설치 티켓이 \[설치 중] 상태여야 다음 단계로 진행할 수 있습니다.

{% hint style="info" %}
**개통 확인 전 준비**

태블릿에서 개통을 확인하기 전에 다음 작업을 완료해 주세요.

1. 어드민에서 설치 티켓을 생성합니다.
2. 패키지 또는 구성품의 시리얼 번호를 등록합니다.
3. 설치 티켓이 \[설치 중] 상태인지 확인합니다.

자세한 방법은 [설치 티켓으로 제품 개통](../product-registration-05.md)을 참고하세요.
{% endhint %}

***

#### 개통 확인 방법

{% stepper %}
{% step %}
어드민에서 제품 등록을 완료하고 설치 티켓이 \[설치 중] 상태인지 확인합니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (426).png" alt="" width="360"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
태블릿에서 \[개통 확인]을 누릅니다. 확인이 완료되면 다음 퀵셋업 단계로 진행합니다.

<figure><img src="../../.gitbook/assets/image (358).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**개통을 확인할 수 없는 경우**

1. **설치 티켓이 없거나 취소된 경우**: 새 설치 티켓을 생성하고 제품과 구성품의 시리얼 번호를 등록합니다. 티켓이 \[설치 중]으로 변경되면 다시 \[개통 확인]을 누릅니다.
2. **설치 티켓의 제품 등록이 완료되지 않은 경우**: 설치 티켓에서 누락된 제품과 구성품의 시리얼 번호를 등록합니다. 등록을 완료하고 티켓이 \[설치 중]인지 확인한 후 다시 \[개통 확인]을 누릅니다.
3. **기기 정보를 찾을 수 없는 경우:** 설치 티켓에 등록된 태블릿의 시리얼 번호가 올바른지 확인합니다. 문제가 계속되면 대리점에 문의해 주세요.
{% endhint %}
{% endstep %}
{% endstepper %}
