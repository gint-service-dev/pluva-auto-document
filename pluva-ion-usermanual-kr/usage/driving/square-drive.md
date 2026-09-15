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

# 사각주행

설정한 필드 경계를 따라 바깥쪽에서 안쪽으로 또는 안쪽에서 바깥쪽으로 경로를 생성하는 주행모드입니다. 논처럼 반듯한 사각형 밭에서 효율적으로 작업할 수 있습니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (79).png" alt="" width="188"><figcaption></figcaption></figure></div>

***

{% stepper %}
{% step %}
주행모드 목록에서 \[사각주행]을 선택한 뒤 확인을 누릅니다.

<figure><img src="../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
차량을 이동하며 A, B, C, D점을 순서대로 설정합니다.

{% hint style="info" %}
A, B, C, D 포인트를 설정하는 것은 작업할 영역의 경계(바운더리)를 지정하는 작업입니다. 설정한 포인트를 꼭지점으로 하는 다각형 영역이 바운더리로 확정되며, 사각경로는 이 바운더리 안쪽으로 자동 생성됩니다.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
D점부터 \[경계 완료]를 눌러 완료 하거나, 다음 점을 추가할 수 있습니다.

{% hint style="info" %}
**최소 설정 점수**: 경로를 생성하려면 최소 4점(A\~D)을 설정해야 합니다.
{% endhint %}

{% hint style="info" %}
**최대 추가 점수**: 최대 6점(A\~F)까지 추가할 수 있습니다.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**포인트 수정**

* 설정 직후 해당 점의 **수정** 버튼이 표시됩니다.
* 위치가 정확하지 않으면 수정 버튼으로 재설정합니다.

<img src="../../.gitbook/assets/image (97).png" alt="" data-size="original">
{% endhint %}
{% endstep %}

{% step %}
사각경로가 자동 생성됩니다.

<figure><img src="../../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**경로가 생성되지 않는 경우**

* 경로를 만들 수 없으면 경로 생성 불가 팝업이 표시됩니다.
* \[밖 → 안]에서는 생성 실패 사유가 함께 표시됩니다.
* \[안 → 밖]에서는 상세 사유가 표시되지 않습니다.
* 설정을 조정한 후 \[다시 시도]를 누릅니다.



***



* \[밖 → 안]: 실패 사유가 표시되는 화면

![](<../../.gitbook/assets/image (101).png>)

* \[밖 → 안]: 실패 사유가 표시되는 화면

![](<../../.gitbook/assets/image (105).png>)
{% endhint %}
{% endstep %}

{% step %}
주행 방식을 선택합니다.

{% hint style="info" %}
**\[밖 → 안]**: 경계선부터 안쪽으로 좁혀가며 작업합니다.
{% endhint %}

{% hint style="info" %}
**\[안 → 밖]**: 안쪽부터 바깥쪽으로 넓혀가며 작업합니다.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
시작점과시작 방향을 선택한 뒤 \[주행 시작]을 누르고 안내된 시작점으로 이동합니다.

<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**시작점과 시작 방향**

* 시작점은 경로를 시작할 위치이며, 시작 방향은 처음 주행할 변을 정합니다.
* 선택 결과는 미리보기의 파란색 선과 화살표로 표시됩니다.
{% endhint %}
{% endstep %}

{% step %}
시작점 주변에서 \[자율주행 시작] 버튼이 활성화되면 주행을 시작합니다.

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
