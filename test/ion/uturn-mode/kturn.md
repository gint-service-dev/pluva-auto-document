---
metaLinks:
  alternates:
    - https://app.gitbook.com/s/4rNrDNCqOFVCh006UOXy/ion/uturn-mode/kturn
---

# K턴

K턴은 좁은 헤드랜드에서 전진 → 후진 → 전진의 3단계 구간으로 방향을 전환하여 다음 작업 라인으로 이동하는 턴 형태입니다.

***

### 사용 방법

{% stepper %}
{% step %}
턴 형태에서 K턴을 선택합니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2650-104127&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}

{% step %}
![](../../.gitbook/assets/drive-button.svg)\[자율 주행 시작] 버튼을 누르고 K턴 지점에 도달하면 즉시 작업기를 올리세요.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2757-109225&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}

{% step %}
전진 기어를 유지한 상태로 차량이 방향을 전환합니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2757-109610&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}

{% step %}
차량이 후진하며 다음 작업 라인 방향으로 정렬됩니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2757-109884&t=hCS5qBIYZpUDsa9g-1" %}

{% hint style="warning" %}
**후진 전 반드시 변속기를 후진 기어로 변경하세요.**&#x20;

실제 후진은 운전자가 직접 후진 기어로 변경해야 주행이 이루어집니다. 기어를 변경하지 않으면 K턴이 정상적으로 완료되지 않습니다.
{% endhint %}
{% endstep %}

{% step %}
전진 기어를 유지한 상태로 차량이 다음 작업 라인 방향으로 이동합니다. 다음 작업 라인에 진입하기 전 작업기를 내립니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2760-110690&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}

{% step %}
새 작업 라인에서 자율주행 작업이 재개됩니다.

{% embed url="https://www.figma.com/design/Su0Eve5h4QCKU9y0P8sbsY/%EC%B0%A8%EC%84%B8%EB%8C%80-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2760-110923&t=hCS5qBIYZpUDsa9g-1" %}
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**경로 이탈했을 때**

* **원인**
  * 경사진 지형, 미끄러운 노면, 타이어 헛돎 등으로 가이드라인 추종에 실패하면 자율주행이 중단됩니다.
* **대응 방법**
  * 수동으로 차량을 조작하여 턴을 완료하세요. 작업 라인에 진입한 후 \[자율주행] 버튼을 다시 누르면 자율주행이 재개됩니다.
{% endhint %}
