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

# 작업 이력 (임시)

고객이 수행한 작업 이력을 조회하고, 작업 경로와 데이터를 지도에서 분석·재생합니다. 작업 데이터로 상황을 재구성해 고객 문의·클레임의 원인을 파악하는 데 활용합니다.

***

## 진입 방법 <a href="#how-to" id="how-to"></a>

{% stepper %}
{% step %}
목록에서 조회할 계정을 선택해 계정 상세로 이동합니다.

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
계정 상세에서 작업 탭을 선택후 원하는 작업을 선택해 작업 이력 상세에 진입합니다

<figure><img src="../../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
작업 이력은 기준 시각까지 어드민에 동기화된 작업만 표시됩니다. 현장 작업 직후에는 아직 동기화 전이라 보이지 않을 수 있습니다.
{% endhint %}

{% hint style="info" %}
각 작업의 \[경로 보기]를 누르면 해당 경로를 미리 볼 수 있습니다.

<img src="../../.gitbook/assets/image (120).png" alt="" data-size="original">
{% endhint %}

***

## 작업 이력 상세 <a href="#detail" id="detail"></a>

작업의 경로와 데이터를 지도에서 확인하고, 시간 순서대로 재생할 수 있습니다.

### 데스크탑 환경

<figure><img src="../../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

작업 이력 상세 화면은 크게 네개 영역으로 구분합니다.

<img src="../../.gitbook/assets/image (167).png" alt="" data-size="line"> **지도 영역**

<img src="../../.gitbook/assets/image (168).png" alt="" data-size="line"> **재생 바 영역**

<img src="../../.gitbook/assets/image (169).png" alt="" data-size="line"> **사이드 바 상단 영역**&#x20;

<img src="../../.gitbook/assets/image (170).png" alt="" data-size="line"> **사이드 바 하단 영역**

아래에서 영역별 상세 안내를 확인해 주세요.

***

#### <img src="../../.gitbook/assets/image (189).png" alt="" data-size="line"> **지도 영역** <a href="#map-part" id="map-part"></a>

<figure><img src="../../.gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

1. **지도 및 경로**

* 시작 지점(S): 지도에서 작업이 시작된 지점입니다.
* 종료 지점(E): 지도에서 작업이 종료된 지점입니다.
* 지도에 해당 작업의 주행 궤적이 표시됩니다.
* 자동/수동 주행, 조건 필터 구간, 이벤트가 색상과 아이콘으로 나타납니다.

2. **경로 범례**

* 경로 범례를 누르면 지도에서 표시되는 자동, 수동, AB 라인, RTK Fixed 등의 설명을 확인할 수 있습니다.

<details>

<summary><strong>경로 범례 설명 보기</strong><br>클릭하면 설명이 열립니다.</summary>

<div align="left"><figure><img src="../../.gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure></div>

자동: 자동으로 운용한 구간

수동: 수동으로 운용한 구간

AB라인: A점과 B점을 잇는 작업 방향 기준 구간

RTK Fixed 아님: RTK 품질이 낮았던 구간

시작: 자율 주행을 시작한 지점

정지: 자율 주행을 완료한 지점

에러 발생: 문제가 발생하여 자율주행이 해제된 지점

에러 복구: 문제가 해결되어 다시 자율주행을 시작할 수 있는 지점

</details>

3. **작업 정보**

* \[작업 정보]를 누르면 해당 작업의 요약 정보를 표시합니다.

<details>

<summary><strong>작업 정보 미리보기</strong><br>클릭하면 미리보기가 열립니다.</summary>

<div align="left"><figure><img src="../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure></div>



</details>

4. **현재 위치**

* 지도를 현재 차량 위치로 이동합니다.

5. **경로 구분**

* 지도상에서 자동과 수동 경로를 구분하여 볼 수 있습니다.

#### <img src="../../.gitbook/assets/image (190).png" alt="" data-size="line"> 재생 바 영역 <a href="#control-panel-part" id="control-panel-part"></a>

<figure><img src="../../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

**상단**

재생 타임 라인 : 전체 작업 구간이 표시됩니다. 특정 시점을 선택하면 해당 시점으로 이동하며, 지도의 차량 위치와 실시간 데이터가 함께 바뀝니다.

**하단**

* 배속 조절 : 1배속으로 설정되어 있으며 2, 4, 8배속으로 조절이 가능합니다.
* 재생/일시정지 : \[▶]를 누르면 작업을 시간 순서대로 재생하고, 다시 누르면 일시정지 합니다.
* 시간 건너뛰기 : 10초를 되감거나, 건너뛸 수 있습니다.
* 자세한 재생바 : 클릭하면 RTK 품질이 낮았던 구간과 오프라인 구간이 화면에 표시됩니다.

#### <img src="../../.gitbook/assets/image (192).png" alt="" data-size="line"> **사이드 바 상단 영역**

<div align="left"><figure><img src="../../.gitbook/assets/image (178).png" alt="" width="362"><figcaption></figcaption></figure></div>

1. **작업지 주소**

* 선택한 작업의 주소가 표시됩니다.

2. **작업 시작 일시**

* 선택한 작업의 시작 날짜·시각이 표시됩니다.

3. **지도 / 로드뷰**

* \[지도보기]를 누르면 해당 위치의 지도를 확인할 수 있습니다.
* \[로드뷰]를 누르면 해당 위치의 로드뷰를 확인할 수 있습니다.

#### <img src="../../.gitbook/assets/image (199).png" alt="" data-size="line"> **사이드 바 하단 영역**

<div align="left"><figure><img src="../../.gitbook/assets/image (193).png" alt="" width="342"><figcaption></figcaption></figure></div>

1. **경로 표시 설정**

* 작업 데이터 분석 시 보고자 하는 조건을 세팅하여 확인이 가능합니다.
* \[경로 표시 설정]에서 지도에 표시할 정보를 조정합니다.
* \[조건 필터]와 \[표시 설정] 두 가지로 나뉩니다.

<details>

<summary><strong>조건 필터 설명 보기</strong><br>클릭하면 설명이 열립니다.</summary>

**조건 필터**

* 설정한 조건에 맞는 구간만 지도·타임라인에서 강조합니다.
* 여러 조건을 조합할 수 있고, 조건 없이 전체 경로를 볼 수도 있습니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure></div>

**조건 필터 예시**

아래와 같이 선택 시 AB직진 모드로 작업한 구간에서 자율주행 중 RTK 품질이 낮았던 경로만 표시됩니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure></div>

</details>

<details>

<summary><strong>표시 설정 설명 보기</strong><br>클릭하면 설명이 열립니다.</summary>

* 지도 위에 표시할 지도를 선택할 수 있습니다.
* 주행, 에러 등을 이벤트 아이콘으로 표시합니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure></div>

</details>

2. **RTK 품질**

* RTK 품질 상태를 표시합니다.

3. **속도**

* 속도를 표시합니다.

4. **추가 상세 수치**

* 좌표, 헤딩, 주행 상태 등 작업에 필요한 상세 수치를 표시합니다.

***

### 모바일 환경 <a href="#mobile-view" id="mobile-view"></a>

<div align="left"><figure><img src="../../.gitbook/assets/image (126).png" alt="" width="375"><figcaption></figcaption></figure></div>

<img src="../../.gitbook/assets/image (127).png" alt="" data-size="line"> **지도 및 경로**

* 시작 지점(E) : 지도에서 작업이 시작된 지점입니다.
* 종료 지점(E) : 지도에서 작업이 종료된 지점입니다.
* 지도에 해당 작업의 주행 궤적이 표시됩니다.
* 자동/수동 주행, 조건 필터 구간, 이벤트가 색상과 아이콘으로 나타납니다.
* 각 색상·아이콘의 의미는 <img src="../../.gitbook/assets/image (132).png" alt="" data-size="line"> 경로 범례에서 확인합니다.

<img src="../../.gitbook/assets/image (128).png" alt="" data-size="line"> **재생 바 영역**

**상단**

* 재생/일시정지 : \[▶]를 누르면 작업을 시간 순서대로 재생하고, 다시 누르면 일시정지 합니다.
* 배속 조절 : 1배속으로 설정되어 있으며 2, 4, 8배속으로 조절이 가능합니다.

**하단**

* 재생 타임 라인 : 전체 작업 구간이 표시됩니다. 특정 시점을 선택하면 해당 시점으로 이동하며, 지도의 차량 위치와 실시간 데이터가 함께 바뀝니다.

<img src="../../.gitbook/assets/image (129).png" alt="" data-size="line"> **RTK 품질**

* 재생 시점 기준 RTK 측위 품질을 표시합니다.

<img src="../../.gitbook/assets/image (130).png" alt="" data-size="line"> **속도**

* 재생 시점 기준 주행 속도를 표시합니다.

<img src="../../.gitbook/assets/image (131).png" alt="" data-size="line"> **현재 위치**

* 지도를 작업 위치로 이동합니다.

<img src="../../.gitbook/assets/image (132).png" alt="" data-size="line"> **경로 범례**

* 경로 범례를 누르면 지도에서 표시되는 자동, 수동, AB 라인, RTK Fixed 등의 설명을 확인할 수 있습니다.

<img src="../../.gitbook/assets/image (65).png" alt="" data-size="line"> **상세 정보**

* 해당 작업의 상세 정보를 표시합니다.
* 전체 이벤트 표시/숨김을 설정합니다.

{% hint style="info" %}
**참고**

모바일에서는 이벤트의 전체 표시/숨김만 설정할 수 있습니다. 조건 필터 등 세부 표시 설정은 PC에서 진행해 주세요.

![](<../../.gitbook/assets/image (66).png>)
{% endhint %}
