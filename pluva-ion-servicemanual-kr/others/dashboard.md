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

어드민을 로그인하면 가장 처음 대시보드 화면을 확인할 수 있습니다. 대시보드에서는 담당 조직과 하위 조직의 기기 운행, 원격 지원, 설치 및 OTA 현황을 한눈에 확인할 수 있습니다.

{% hint style="info" %}
**데이터 갱신 안내**

* 기기 접속 상태와 원격 지원 현황은 실시간으로 반영됩니다.
* 그 외 데이터는 20분마다 갱신되며, 최근 갱신 시간은 화면 상단에서 확인할 수 있습니다.
{% endhint %}

***

## 화면 설명

### PC 환경

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

화면은 크게 다섯개 영역으로 구분합니다.

<img src="../.gitbook/assets/image (205).png" alt="" data-size="line"> **날짜별 현황 조회 버튼**

<img src="../.gitbook/assets/image (206).png" alt="" data-size="line"> **작업 및 기기 현황**

<img src="../.gitbook/assets/image (207).png" alt="" data-size="line"> **원격 지원 현황**

<img src="../.gitbook/assets/image (208).png" alt="" data-size="line"> **기기 설치 추이 및 OTA 버전 현황**

<img src="../.gitbook/assets/image (209).png" alt="" data-size="line"> **작업 활성 추이**

아래에서 영역별 상세 안내를 확인해 주세요.

***



#### <img src="../.gitbook/assets/image (203).png" alt="" data-size="line"> 날짜별 현황 조회 버튼

<div align="left"><figure><img src="../.gitbook/assets/image (210).png" alt="" width="297"><figcaption></figcaption></figure></div>

* \[다른 날짜 보기]를 눌러 조회하고 싶은 날짜를 선택할 수 있습니다.
* 날짜를 누르면 해당 날짜를 기준으로 대시보드가 설정됩니다.

{% hint style="info" %}
날짜를 선택하지 않은 경우 조회 당일 기준으로 데이터가 조회 됩니다.
{% endhint %}

#### <img src="../.gitbook/assets/image (204).png" alt="" data-size="line"> 작업 및 기기 현황

<figure><img src="../.gitbook/assets/image (212).png" alt=""><figcaption></figcaption></figure>

1. **작업 및 기기 현황**

* 작업 기기 수, 작업 면적, 작업 거리, 자율 주행 비율을 표시합니다.

{% hint style="info" %}
\[다른 날짜 보기]를 눌러 날짜를 변경하면 해당 날짜의 정보가 표시됩니다.
{% endhint %}

2. **기기 리스트**

* 소유자, 기기 시리얼 넘버, 온라인 상태를 카드 형태로 확인할 수 있습니다.
* 카드의 기기 \[시리얼 넘버]를 누르면 해당 기기의 상세 이력을 표시합니다.

<details>

<summary><strong>기기 작업 이력 상세 설명 보기</strong><br>클릭하면 상세 설명이 열립니다.</summary>

**기기별 작업 이력 목록 보기**

{% stepper %}
{% step %}
기기 리스트에서 \[시리얼 넘버]를 누릅니다.

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
사이드 패널을 통해 해당 날짜의 기기 작업 목록이 표시됩니다.

* 상단에는 기기의 전체 작업 면적과 작업 거리가 확인 됩니다.
* 하단에는 기기의 작업 시작 시간을 기준으로 카드로 묶어분류 됩니다.
* 작업 이력 카드의 시간을 누르면 해당 작업의 상세 이력을 확인합니다.
  * 자세한 내용은 작업 이력(링크)을 참고해주세요.
* 카드 하단에는 작업별 면적과 거리, 자율주행 비율을 표시 합니다.

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
해당 작업의 위치로 지도를 확대합니다.

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

2. **이번주 원격 지원 수**

* 오늘, 또는 선택한 날짜가 속한 주의 원격 지원 횟수를 표시합니다.

3. **접속 가능한 기기 목록**

* 현재 접속 가능한 기기의 목록을 표시합니다.

#### <img src="../.gitbook/assets/image (232).png" alt="" data-size="line"> **기기 설치 추이 및 OTA 버전 현황**

<figure><img src="../.gitbook/assets/image (233).png" alt=""><figcaption></figcaption></figure>

1. **설치 추이**

* ![](<../.gitbook/assets/image (235).png>)을 눌러 기간을 설정할 수 있습니다.
* 조회 기간 내에 설치된 기기의 갯수를 표시합니다.

{% hint style="info" %}
- \[날짜별 현황 조회] 버튼으로 날짜를 설정하지 않은 경우, 오늘을 기준으로 과거의 주별, 월별 데이터를 표시합니다.
- \[날짜별 현황 조회] 버튼으로 날짜를 설정한 경우, 선택한 날짜를 기준으로 과거의 주별, 월별 데이터를 표시합니다.
{% endhint %}

2. **OTA 버전 현황**

* 현재 조회된 기기들의 OTA 버전을 확인할 수 있습니다.

{% hint style="info" %}
OTA 버전 현황은 \[날짜별 현황 조회]를 통해 날짜를 설정한 것과 무관하게 모든 기기의 OTA 버전을 표시합니다.
{% endhint %}

#### <img src="../.gitbook/assets/image (236).png" alt="" data-size="line"> **작업 활성 추이**

<figure><img src="../.gitbook/assets/image (237).png" alt=""><figcaption></figcaption></figure>

* ![](<../.gitbook/assets/image (238).png>) 을 눌러 기간을 설정할 수 있습니다.
* 작업 기기 수, 작업 면적, 작업 거리, 자율 주행 비율을 시계열로 표시합니다.
