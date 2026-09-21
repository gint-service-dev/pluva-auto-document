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

어드민에 로그인하면 대시보드가 열립니다. 담당 조직과 하위 조직의 작업·원격 지원·설치·OTA 현황을 확인할 수 있습니다.

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

<div align="left"><figure><img src="../.gitbook/assets/image (210).png" alt="" width="297"><figcaption></figcaption></figure></div>

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

* 선택한 날짜에 작업한 기기 수, 작업 면적·거리, 자율주행 비율을 보여줍니다.
* 각 지표 아래에는 전날 수치가 표시됩니다.

2. **기기 리스트**

* 선택한 날짜에 작업한 기기의 소유자와 시리얼 넘버를 확인할 수 있습니다.
* 오늘 화면에서는 온라인 상태도 표시됩니다.
* 기기 카드를 누르면 작업 이력이 열립니다.

<details>

<summary><strong>작업 이력·위치 확인 방법</strong><br>클릭하면 상세 설명이 열립니다.</summary>

**기기별 작업 이력 목록 보기**

{% stepper %}
{% step %}
기기 리스트에서 기기 카드를 누릅니다.

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
오른쪽 패널에 작업 시작 시간별 이력이 표시됩니다.

* 상단에서 전체 작업 면적·거리를 표시합니다.
* 각 카드에서 작업별 면적·거리·자율주행 비율을 확인할 수 있습니다.
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

* 선택한 기기의 작업지로 지도가 확대되어 위치를 지도에서 쉽게 확인할 수 있도록 표시합니다.
* <img src="../.gitbook/assets/image (223).png" alt="" data-size="original"> 를 누르면 보고 있는 기기의 작업지 선택을 취소하여 지도를 되돌립니다.

<figure><img src="../.gitbook/assets/image (221).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}



</details>

3. **지도 영역**

* 지도를 원하는 위치로 드래그 할 수 있으며, 마우스 휠이나 손가락을 사용하여 확대/축소가 가능합니다.
* ![](<../.gitbook/assets/image (227).png>) 누르면 전체보기로 보기 설정을 초기화 합니다.
* 또한 ![](<../.gitbook/assets/image (228).png>) ![](<../.gitbook/assets/image (229).png>) 버튼을 클릭하여 화면을 확대/축소 합니다.

#### <img src="../.gitbook/assets/image (230).png" alt="" data-size="line"> **원격 지원 현황**&#x20;

<figure><img src="../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

1. **현재 접속 가능 기기 수**

* 접속이 가능한 기기 수를 표시합니다.

2. **원격 지원 건수**

* 오늘은 이번 주, 날짜를 선택하면 해당 주의 원격 지원 건수를 표시합니다.

3. **접속 가능한 기기 목록**

* 현재 접속 가능한 기기가 있으면 목록이 표시됩니다.

#### <img src="../.gitbook/assets/image (232).png" alt="" data-size="line"> 설치 추이 및 OTA 버전 현황

<figure><img src="../.gitbook/assets/image (233).png" alt=""><figcaption></figcaption></figure>

1. **설치 추이**

* ![](<../.gitbook/assets/image (235).png>)을 눌러 설치 완료 건수의 변화를 확인합니다.

{% hint style="info" %}
선택한 날짜를 기준으로 이전 기간이 표시되며, 날짜를 선택하지 않으면 오늘 기준입니다.
{% endhint %}

2. **OTA 버전 현황**

* 개통 제품의 OTA 버전별 기기 수와 비율을 확인합니다.
* 날짜를 바꿔도 현재 기준으로 표시됩니다.

#### <img src="../.gitbook/assets/image (236).png" alt="" data-size="line"> **작업 활성 추이**

<figure><img src="../.gitbook/assets/image (237).png" alt=""><figcaption></figcaption></figure>

* ![](<../.gitbook/assets/image (238).png>) 을 선택해 작업 기기 수·면적·거리와 자율주행 비율의 변화를 그래프로 확인합니다. 각 항목에는 기간 평균도 표시됩니다.
