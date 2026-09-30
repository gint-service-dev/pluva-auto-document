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

# 제품 개통 확인 화면이 나타나는 경우

퀵셋업을 시작하면 태블릿의 제품 등록 상태를 자동으로 확인합니다. 어드민에서 제품 등록이 완료되지 않은 경우에만 아래 화면이 나타납니다.

<figure><img src="../../.gitbook/assets/image (358).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**QR 코드는 어디에서 스캔하나요?**

이 화면에서 태블릿으로 QR 코드를 스캔하는 것이 아닙니다. 어드민의 설치 티켓에서 태블릿과 구성품의 QR 코드를 등록해 주세요.

자세한 내용은 [설치티켓으로 제품 개통](../product-registration-05.md)을 참고하세요.
{% endhint %}

***

<mark style="color:$danger;">**(아래 내용 삭제 예정)**</mark>

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
