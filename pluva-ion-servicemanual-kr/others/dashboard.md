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

# 대시보드

대시보드에서는 고객의 작업 현황과 원격 지원 요청, 설치 추이, OTA 버전 현황을 한눈에 확인할 수 있습니다.

{% hint style="info" %}
**데이터 갱신 안내**

* 기기 접속 상태와 원격 지원 현황은 실시간으로 반영됩니다.
* 그 외 데이터는 20분마다 갱신되며, 최종 갱신 시간은 화면 상단에서 확인할 수 있습니다.
{% endhint %}

***

## 화면 설명

### PC 환경

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

화면은 크게 다섯 개 영역으로 구분합니다.

<img src="../.gitbook/assets/image (205).png" alt="" data-size="line"> **날짜 선택**

<img src="../.gitbook/assets/image (206).png" alt="" data-size="line"> **작업 및 기기 현황**

<img src="../.gitbook/assets/image (207).png" alt="" data-size="line"> **원격 지원 현황**

<img src="../.gitbook/assets/image (208).png" alt="" data-size="line"> **설치 추이 및 OTA 버전 현황**

<img src="../.gitbook/assets/image (209).png" alt="" data-size="line"> **작업 활성 추이**

아래에서 영역별 상세 안내를 확인해 주세요.

***



#### <img src="../.gitbook/assets/image (203).png" alt="" data-size="line"> 날짜 선택

* ![](<../.gitbook/assets/image (239).png>)에서 날짜를 선택하면 작업 현황·기기 목록·원격 지원 건수·설치 추이를 해당 날짜 기준으로 볼 수 있습니다.
* ![](<../.gitbook/assets/image (240).png>)을 누르면 현재 화면으로 돌아갑니다.

{% hint style="info" %}
현재 접속 가능 기기 수와 OTA 버전 현황은 날짜 선택과 관계없이 현재 기준입니다.
{% endhint %}

{% hint style="info" %}
날짜를 선택하지 않은 경우 조회 당일 기준으로 데이터가 조회 됩니다.
{% endhint %}

#### <img src="../.gitbook/assets/image (204).png" alt="" data-size="line"> 작업 및 기기 현황

<figure><img src="../.gitbook/assets/image (212).png" alt=""><figcaption></figcaption></figure>

1. **작업 및 기기 현황**

* 오늘작업 기기: 작업 이력이 있는 기기 수입니다.
* 오늘작업 면적: 수행된 작업 면적의 합계입니다.
* 오늘 작업 거리: 수동·자율주행으로 이동한 거리의 합계입니다
* 오늘 자율주행 비율: 전체 주행 거리 중 자율주행으로 이동한 거리의 비율입니다.

{% hint style="info" %}
\[다른 날짜 보기]에서 날짜를 선택하면 상단 작업 현황이 해당 날짜 기준으로 변경됩니다. 각 항목 아래에서 전날 수치도 함께 확인할 수 있습니다.
{% endhint %}

2. **기기 리스트**

* 선택한 날짜에 작업한 기기의 소유자와 시리얼 넘버를 확인할 수 있습니다.
* 오늘 화면에서는 온라인 상태도 표시됩니다.
* 기기 카드를 누르면 작업 이력이 열립니다.

<details>

<summary><strong>작업 이력·위치 확인 방법</strong><br>클릭하면 상세 설명이 열립니다.</summary>

**기기별 작업 이력 목록 보기**

{% stepper %}
{% step %}
기기 리스트에서 확인할 기기의 카드를 누릅니다.

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
오른쪽 패널에서 선택한 날짜의 작업 이력을 확인합니다.

* 상단에는 전체 작업 면적과 거리가 표시됩니다.
* 각 작업의 시작 시간, 작업 면적·거리, 자율주행 비율을 확인할 수 있습니다.
* 작업 시작 시간을 누르면 상세 이력이 열립니다.
* 자세한 내용은 작업 이력(링크)을 참고해주세요.

<figure><img src="../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

**작업 위치 보기**

{% stepper %}
{% step %}
기기 리스트에서 \[위치보기]를 누릅니다.

<figure><img src="../.gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
해당 기기의 작업지로 지도가 이동합니다.

* 선택한 기기의 작업 위치로 지도가 확대됩니다.
* 선택한 날짜에 작업이 여러 건이면 가장 최근 작업 위치가 표시됩니다.
* <img src="../.gitbook/assets/image (223).png" alt="" data-size="original"> 다시 누르면 선택이 해제되고 전체 지도로 돌아갑니다.

<figure><img src="../.gitbook/assets/image (221).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}



</details>

3. **지도 영역**

* 지도를 원하는 위치로 드래그 할 수 있으며, 마우스 휠이나 손가락을 사용하여 확대/축소가 가능합니다.
* ![](<../.gitbook/assets/image (227).png>) 누르면 전체보기로 보기 설정을 초기화 합니다.
* 또한 ![](<../.gitbook/assets/image (228).png>) ![](<../.gitbook/assets/image (229).png>) 버튼을 클릭하여 화면을 확대/축소 합니다.

#### <img src="../.gitbook/assets/image (230).png" alt="" data-size="line"> **원격 지원 현황**&#x20;

<figure><img src="../.gitbook/assets/image (264).png" alt=""><figcaption></figcaption></figure>

* 현재 접속 가능한 기기 수와 목록을 확인할 수 있습니다.
  * 목록의 \[접속 중]은 원격 지원이 진행 중인 상태, \[접속 가능]은 원격 지원을 시작할 수 있는 상태입니다.
* 원격 지원 건수는 조회한 날짜가 포함된 주를 기준으로 표시되며, 날짜를 선택하지 않으면 이번 주 기준으로 표시됩니다.

#### <img src="../.gitbook/assets/image (232).png" alt="" data-size="line"> 설치 추이 및 OTA 버전 현황

<figure><img src="../.gitbook/assets/image (233).png" alt=""><figcaption></figcaption></figure>

1. **설치 추이**

* ![](<../.gitbook/assets/image (235).png>)을 눌러 설치 완료 건수의 변화를 확인합니다.

{% hint style="info" %}
선택한 날짜를 기준으로 이전 기간이 표시되며, 날짜를 선택하지 않으면 오늘 기준입니다.
{% endhint %}

2. **OTA 버전 현황**

* 개통 제품의 OTA 버전별 기기 수와 비율을 확인합니다.
* 날짜를 선택하지 않으면 현재 기준으로 표시되며, 날짜를 선택하면 해당 영역은 사라집니다.

#### <img src="../.gitbook/assets/image (236).png" alt="" data-size="line"> **작업 활성 추이**

<figure><img src="../.gitbook/assets/image (263).png" alt=""><figcaption></figcaption></figure>

* ![](<../.gitbook/assets/image (238).png>) 을 선택해 작업 기기 수·면적·거리와 자율주행 비율의 변화를 그래프로 확인합니다. 각 항목에는 기간 평균도 표시됩니다.

{% hint style="info" %}
기간 평균은 화면에 표시된 값들의 평균값을 표시합니다.
{% endhint %}

***

### 모바일환경

<div align="left"><figure><img src="../.gitbook/assets/image (242).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**모바일 환경 대시보드 이용 참고사항**

모바일 환경에서는 간소화한 데이터만 제공되며, 상세 데이터는 PC에서 확인하실 수 있습니다.
{% endhint %}

#### <img src="../.gitbook/assets/image (243).png" alt="" data-size="line"> **원격 지원 현황**

<div align="left"><figure><img src="../.gitbook/assets/image (265).png" alt="" width="375"><figcaption></figcaption></figure></div>

* 현재 접속 가능한 기기 수와 목록을 확인할 수 있습니다.
  * 목록의 \[접속 중]은 원격 지원이 진행 중인 상태, \[접속 가능]은 원격 지원을 시작할 수 있는 상태입니다.
* 원격 지원 건수는 조회한 날짜가 포함된 주를 기준으로 표시되며, 날짜를 선택하지 않으면 이번 주 기준으로 표시됩니다.

#### <img src="../.gitbook/assets/image (244).png" alt="" data-size="line"> **작업 및 기기 현황**

<div align="left"><figure><img src="../.gitbook/assets/image (246).png" alt="" width="370"><figcaption></figcaption></figure></div>

* 오늘작업 기기: 작업 이력이 있는 기기 수입니다.
* 오늘작업 면적: 수행된 작업 면적의 합계입니다.
* 오늘 작업 거리: 수동·자율주행으로 이동한 거리의 합계입니다
  * 자율주행 비율: 전체 주행 거리 중 자율주행으로 이동한 거리의 비율입니다.

{% hint style="info" %}
각 항목 아래에서 전날 수치도 함께 확인할 수 있습니다.
{% endhint %}
