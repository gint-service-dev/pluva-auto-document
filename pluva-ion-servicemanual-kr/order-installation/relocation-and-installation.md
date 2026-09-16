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

# 1+1 차량 이전 설치

하나의 플루바 아이온 장치를 이앙기와 트랙터에 번갈아 설치하여 사용하는 경우, 다음 순서에 따라 차량을 전환하고 보정 상태를 확인합니다.

***

### 적용 대상

* 하나의 플루바 아이온 장치를 두 대의 차량에 번갈아 설치하는 경우
* 이앙기와 트랙터 사이에서 제품을 이전 설치하는 경우
* 두 차량이 태블릿의 \[내차량]에 이미 등록되어 있는 경우

{% hint style="info" %}
**처음 연결하는 차량인 경우**

* \[내 차량]에 등록되지 않은 차량은 [내 차량 추가](https://servicemanual.pluva.io/ion/korea/kr/usage/vehicle-settings/add-vehicle) 절차에 따라 먼저 등록해 주세요.
* 아래 차량 전환 절차는 이미 등록된 두 차량을 번갈아 사용하는 경우에 적용됩니다.
{% endhint %}

### 이전 설치 순서

{% hint style="warning" %}
**차량 이전 설치 후 자율주행 전 확인**

* 소프트웨어 버전 1.4.5 이하인 경우, 차량 이전 설치를 완료한 후에는 반드시 태블릿 재부팅을 진행해 주세요.
* 재부팅 후 \[내 차량]에서 현재 차량 정보와 \[오토스티어 보정] 상태를 반드시 확인하세요.
* 차량 정보와 보정 상태가 모두 정상인지 확인한 후에만 자율주행을 시작하세요.
{% endhint %}

{% stepper %}
{% step %}
대상 차량에 제품 이전 설치와 하네스 연결을 완료합니다.\

{% endstep %}

{% step %}
태블릿을 재부팅하고, GNSS 수신기를 연결합니다.\

{% endstep %}

{% step %}
확인되는 팝업에서 \[확인]을 누릅니다.

<div align="left"><figure><img src="../.gitbook/assets/image (14).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
\[차량 변경]에서 변경할 차량을 선택합니다.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**차량 변경 시 유의 사항**

* 등록된 차량은 새로 추가하지 말고 \[차량 변경]에서 선택해 주세요.
* 같은 차량을 중복 등록했다면 중복 차량을 삭제해 주세요.
{% endhint %}
{% endstep %}

{% step %}
\[오토스티어 보정] 화면에서 보정 완료 상태와 기존 보정값을 확인합니다.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
보정값이 초기화되었거나 정상적으로 반영되지 않았다면 \[전체 한번에 시작하기]를 눌러 전체 보정을 다시 진행합니다.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
차량 정보와 보정 상태가 모두 정상인지 확인한 후 자율주행 기능을 사용합니다.
{% endstep %}
{% endstepper %}

