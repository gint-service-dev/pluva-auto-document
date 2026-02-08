---
layout:
  width: default
  title:
    visible: false
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
---

# AB직진

### AB직진

AB 직진

* A점과 B점을 잇는 방향으로 직진 주행합니다.

<div align="left"><figure><img src="../../.gitbook/assets/ab-straight-forward.png" alt="" width="150"><figcaption></figcaption></figure></div>



{% stepper %}
{% step %}
<img src="../../.gitbook/assets/a-button.svg" alt="" data-size="original">버튼을 눌러 A 지점을 생성합니다.

<figure><img src="../../.gitbook/assets/ab-straight-explanation-1.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
10m 이상 직진 주행한 뒤, 원하는 지점에서 <img src="../../.gitbook/assets/b-button.svg" alt="" data-size="original"> 버튼을 눌러 B 지점을 생성합니다.

<figure><img src="../../.gitbook/assets/ab-straight-explanation-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
AB 직진 경로가 생성되면<img src="../../.gitbook/assets/drive-button.svg" alt="" data-size="original">\[자율주행 시작] 버튼을 눌러 자율주행을 시작합니다.

<figure><img src="../../.gitbook/assets/ab-straight-explanation-3.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

#### 자동 AB 라인 생성

자동 AB 라인 생성은 필드 조건에 맞춰 직진 기준 경로를 자동으로 만들어주는 기능입니다. 생성 후 미리보기에서 값(간격/여유 구간 등)을 필요에 따라 조정할 수 있습니다.

{% stepper %}
{% step %}
AB 직진 모드에서、<img src="../../.gitbook/assets/automatic-path-button.svg" alt="" data-size="original"> \[AB 라인 자동 생성 버튼]을 누릅니다.

<figure><img src="../../.gitbook/assets/automatic-path-explanation-1.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
생성된 필드가 없는 경우, 안내에 따라 필드 등록을 바로 진행할 수 있습니다.

<img src="../../.gitbook/assets/automatic-path-nonefield.png" alt="" data-size="original">
{% endhint %}
{% endstep %}

{% step %}
필드 영역이 활성화되며 자동 AB 라인이 생성됩니다.

<figure><img src="../../.gitbook/assets/automatic-path-explanation-2.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
생성이 완료되면 미리보기가 표시됩니다. 필요에 따라 설정을 조정한 후 \[확인]을 누르세요.

<figure><img src="../../.gitbook/assets/automatic-path-explanation-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
다음 설정으로 세부 조정이 가능합니다.

* 내 위치 기준 생성: 현재 위치를 기준으로 라인을 생성합니다.
* ![](../../.gitbook/assets/my-location-criteria.png)
  * 기존 생성 라인: 하얀색
  * 내 위치 기준 생성 라인: 파란색
* 가로 주행(세로 주행): 진행 방향 기준을 전환합니다. 클릭 시 세로 주행 버튼으로 전환됩니다.
* ![縦走行](../../.gitbook/assets/vertical-drive.png)
  * 세로주행
* ![縦走行](../../.gitbook/assets/horizontal-drive.png)
  * 가로주행
* A/B점 교체: A점과 B점을 서로 바꿉니다.
* ![](../../.gitbook/assets/before-replace-abpoints.png)
  * 변경 전
* ![](../../.gitbook/assets/after-replace-abpoints.png)
  * 변경 후
* 등간격: 수치로 등간격을 조절합니다.
* ![](../../.gitbook/assets/equidistant-interval.png)
* 헤드랜드: 수치로 헤드랜드 간격을 조절합니다.
* ![](../../.gitbook/assets/headland.png)
{% endhint %}


{% endstep %}

{% step %}
<img src="../../.gitbook/assets/drive_ai-button.svg" alt="" data-size="original">\[자율주행]버튼을 누르면 생성된 경로를 따라 주행이 시작됩니다.

<figure><img src="../../.gitbook/assets/automatic-path-explanation-4.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
