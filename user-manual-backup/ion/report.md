# 작업 리포트

작업 이력에서는 완료된 작업 기록을 날짜별로 확인하고, 작업 궤적·효율·환경 정보를 한눈에 파악할 수 있습니다.\
단순한 기록 보관을 넘어, 작업 당시의 날씨·장비 상태와 결과를 연결하여 다음 작업의 효율을 높이는 근거 데이터로 활용할 수 있습니다.

***

### 진입 방법

{% stepper %}
{% step %}
홈 화면에서 ![](../.gitbook/assets/ic_menu.svg) 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2867-105065&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}

{% step %}
\[작업 리포트]를 누르면 작업 리포트 목록으로 진입합니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2867-107655&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}
{% endstepper %}

{% hint style="info" %}
작업 완료 직후에는 완료 화면의 \[작업 기록 보기]를 누르면 바로 진입할 수 있습니다.
{% endhint %}

***

### 목록 화면

작업 이력 목록은 날짜별로 묶인 카드 형태로 표시됩니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2867-107656&t=Ph1xwRv3derJ6qDg-1" %}

&#x20;![](../.gitbook/assets/icon-square-1-1.svg) **정렬**

* 최신순, 오래된 순으로 정렬합니다.

&#x20;![](../.gitbook/assets/icon-square-2.svg) **일자**

* 일자를 선택하면 해당 작업을 확인할 수 있습니다.
* 상단 캘린더 아이콘을 누르면 년/월을 변경할 수 있습니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2995-102821&t=Ph1xwRv3derJ6qDg-1" %}

&#x20;![](../.gitbook/assets/icon-square-3.svg) **필드 이름**

&#x20;![](../.gitbook/assets/icon-square-4.svg) **작업 시작·종료 시각**

&#x20;![](../.gitbook/assets/icon-square-5.svg) **총 작업 시간**

&#x20;![](../.gitbook/assets/icon-square-6.svg) **총작업 면적**

&#x20;![](../.gitbook/assets/icon-square-7.svg) **작업 상태 태그**

***

### 상세 화면

목록에서 카드를 누르면 해당 작업의 상세 정보를 확인할 수 있습니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2995-102822&t=Ph1xwRv3derJ6qDg-1" %}

&#x20;![](../.gitbook/assets/icon-square-1.svg) **농장명 및 작업 시간**

* 작업이 이루어진 농장 이름과 작업 시작·종료 시각입니다.

&#x20;![](../.gitbook/assets/icon-square-2-2.svg) **총 작업 면적**

* 실제 작업이 완료된 총 면적입니다.

&#x20;![](../.gitbook/assets/icon-square-3.svg) **작업 지도**

* 작업 경로와 작업 완료 구간을 지도 위에 시각화하여 보여줍니다.

&#x20;![](../.gitbook/assets/icon-square-4.svg) **총 작업 시간**

* 자율주행 또는 수동으로 실제 작업을 수행한 총 시간입니다.

&#x20;![](../.gitbook/assets/icon-square-5.svg) **총 체류시간**

* 작업 시작부터 종료까지 필드 내에 머문 전체 시간입니다. 대기·이동 시간이 포함됩니다.

&#x20;![](../.gitbook/assets/icon-square-6.svg) **작업 중단 횟수**

* 주행 중 자율주행이 중단된 횟수입니다.

&#x20;![](../.gitbook/assets/icon-square-7.svg) **작업 기온 / 습도**

* 작업 당시의 기온과 습도입니다.

&#x20;![](../.gitbook/assets/icon-square-8.svg) **풍속**

* 작업 당시의 풍속입니다.

&#x20;![](../.gitbook/assets/icon-square-9.svg) **작업 시간대**

* 작업이 이루어진 시간대를 표시합니다.

&#x20;![](../.gitbook/assets/icon-square-10.svg) **RTK 위치정보**

* RTK의 통신 상태를 표시합니다.

{% hint style="warning" %}
RTK 위치 정보는 통신 상태가 불안정할 경우 표시되는 정보입니다. 통신 불안정이 지속될 경우 네트워크 환경을 점검하세요.
{% endhint %}

&#x20;![](../.gitbook/assets/icon-square-11.svg) **장비 정보**

* 해당 작업에 사용된 차량 및 작업기 정보입니다.

&#x20;![](../.gitbook/assets/icon-square-12.svg) **메모**

* 작업 시 입력한 메모를 확인합니다.

&#x20;![](../.gitbook/assets/icon-square-13.svg) **이미지로 공유하기**

* 작업 결과를 이미지 형태로 이메일로 공유할 수 있습니다.
