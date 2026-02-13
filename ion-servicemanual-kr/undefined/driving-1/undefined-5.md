---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/8Sqfw92xyQ8XV1LQEpTt/undefined/driving-1/undefined-5
---

# 차량 보정

### 차량 보정

정확한 자율주행을 위한 차량 보정 작업을 진행합니다. 차량 보정은 총 세가지로 한번에 시작하기를 통해 한번에 진행할 수 있습니다.



#### 차량 보정 항목

1. [GNSS 수신기 위치 설정](undefined-5.md#gnss)
2. [오토스티어 보정](undefined-5.md#undefined-4)
3. [관성센서 보정](https://app.gitbook.com/o/qCjx7YRpvDahoGijeERY/s/8Sqfw92xyQ8XV1LQEpTt/~/edit/~/changes/13/undefined/driving-1/undefined-5#undefined-6)

***

#### 차량 보정 시작하기

{% stepper %}
{% step %}
\[전체 한번에 시작하기] 버튼을 눌러 보정을 시작합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=530-14287&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}

***

#### GNSS 수신기 위치 설정

경사지나 불규칙한 지형에서도 정확한 방향과 자세를 유지하기 위해, GNSS수신기의 기준값을 조정하는 기능입니다. 설치 상태에 따라 기울어짐이 큰 경우 값을 입력해 보정할 수 있습니다.

{% stepper %}
{% step %}
롤, 피치, 요 값을 입력하고 \[확인]을 누르면 위치 설정이 완료됩니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=530-14430&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}

#### GNSS 수신기 위치 설정 설명

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2092-10360&t=q8g76lClR1lyrQfM-1" %}

&#x20;![](<../../.gitbook/assets/icon-square-1 (1).svg>) **ROll 롤**

* GNSS 수신기가 좌/우 방향으로 기울어진 각도를 의미합니다.

&#x20;![](<../../.gitbook/assets/icon-square-2 (1).svg>) **Pitch 피치**

* GNSS 수신기가 앞/뒤 방향으로 기울어진 각도를 의미합니다.

&#x20;![](<../../.gitbook/assets/icon-square-3 (1).svg>) **Yaw 요**

* GNSS 수신기가 수직축을 기준으로 회전한 각도를 의미합니다.

***

#### 오토스티어 보정

오토스티어 보정은 설정된 경로를 안정적으로 추종할 수 있도록 조향 범위와 직진 기준값을\
보정하는 절차입니다. 트랙터는 2단계, 이앙기는 3단계로 진행됩니다.

**트랙터 (2단계)**

* 핸들 범위 보정 - 직진 조향 보정

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=530-14464&t=PM760HAi58K4ZabD-1" %}

**이앙기 (3단계)**

* 핸들 범위 보정 - 직진 조향 보정 - 조향 각도 보정

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-3810&t=PM760HAi58K4ZabD-1" %}

***

#### 트랙터 오토스티어 보정

1. **핸들 범위 보정**

{% stepper %}
{% step %}
\[전체 한번에 진행] 버튼을 누르면 오토스티어 보정이 시작됩니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-7570&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
각 단계 시작 버튼을 누르면 해당 단계 보정만 진행할 수 있습니다.
{% endhint %}
{% endstep %}

{% step %}
안내에 따라 핸들을 왼쪽으로 끝까지 돌린 후 차량을 멈추고 \[확인] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-3711&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
안내에 따라 핸들을 오른쪽으로 끝까지 돌린 후 차량을 멈추고 \[확인] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-3891&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
안내에 따라 핸들을 이용하여 바퀴를 중앙에 위치시키고 차량을 멈추고 \[확인] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-3987&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
핸들 범위 보정 완료됩니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-3691&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}



2. **직진 조향 보정**

{% stepper %}
{% step %}
직진 조향 보정에 필요한 설명을 읽은 후 \[확인]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-8282&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
안내에 따라 \[2km 시속]으로 주행하고 \[자동 보정 시작] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-5938&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
트랙터 제한 속도는 2km로 초과 시 버튼이 활성화 되지않습니다.
{% endhint %}

{% hint style="info" %}
트랙터 정지 시 직진 조향 보정의 처음부터 다시 시작합니다.
{% endhint %}

{% hint style="info" %}
직진 조향 보정 중에는 핸들이 자동으로 움직입니다. 자동 조작 중에는 핸들을 강제로 조작하지 마세요.
{% endhint %}
{% endstep %}

{% step %}
지속해서 2km 이하로 주행합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-6403&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
보정 시 필요 면적이 확보되지않거나 주행이 불가능할 경우 긴급 정지를 누릅니다.
{% endhint %}
{% endstep %}

{% step %}
보정 과정이 끝나면 \[확인] 버튼이 활성화됩니다. 버튼을 눌러 보정을 완료하세요.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-6520&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}

***

#### 이앙기 오토스티어 보정

1. **핸들 범위 보정**

{% stepper %}
{% step %}
\[전체 한번에 진행] 버튼을 누르면 오토스티어 보정이 시작됩니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-7569&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
각 단계 시작 버튼을 누르면 해당 단계 보정만 진행할 수 있습니다.
{% endhint %}
{% endstep %}

{% step %}
안내에 따라 핸들을 왼쪽으로 끝까지 돌린 후 차량을 멈추고 \[확인] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-7749&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
안내에 따라 핸들을 오른쪽으로 끝까지 돌린 후 차량을 멈추고 \[확인] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-7781&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
안내에 따라 핸들을 이용하여 바퀴를 중앙에 위치시키고 차량을 멈추고 \[확인] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-7813&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
핸들 범위 보정 완료됩니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-3691&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}



2. **직진 조향 보정**

{% stepper %}
{% step %}
직진 조향 보정에 필요한 설명을 읽은 후 \[확인]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-8424&t=PM760HAi58K4ZabD-1" %}
{% endstep %}

{% step %}
안내에 따라 \[1km 시속]으로 주행하고 \[자동 보정 시작] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-6331&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
이앙기 제한 속도는 1km로 초과 시 버튼이 활성화 되지않습니다.
{% endhint %}

{% hint style="info" %}
이앙기 정지 시 직진 조향 보정의 처음부터 다시 시작합니다.
{% endhint %}

{% hint style="info" %}
직진 조향 보정 중에는 핸들이 자동으로 움직입니다. 자동 조작 중에는 핸들을 강제로 조작하지 마세요.
{% endhint %}
{% endstep %}

{% step %}
지속해서 1km이하로 주행한다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-5992&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
보정 시 필요 면적이 확보되지않거나 주행이 불가능할 경우 긴급 정지를 누릅니다.
{% endhint %}
{% endstep %}

{% step %}
보정이 완료되면 \[조향 각도 보정 시작] 버튼이 표시됩니다. 버튼을 눌러 다음 보정을 진행합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-6132&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}



3. **조향 각도 보정**

{% stepper %}
{% step %}
안내에 따라 \[1km 시속]으로 주행하고 \[자동 보정 시작] 버튼을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-6331&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
이앙기 제한 속도는 1km로 초과 시 버튼이 활성화 되지않습니다.
{% endhint %}

{% hint style="info" %}
이앙기 정지 시 직진 조향 보정의 처음부터 다시 시작합니다.
{% endhint %}

{% hint style="info" %}
직진 조향 보정 중에는 핸들이 자동으로 움직입니다. 자동 조작 중에는 핸들을 강제로 조작하지 마세요.
{% endhint %}
{% endstep %}

{% step %}
지속해서 1km이하로 주행합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-5992&t=PM760HAi58K4ZabD-1" %}

{% hint style="info" %}
보정 시 필요 면적이 확보되지않거나 주행이 불가능할 경우 긴급 정지를 누릅니다.
{% endhint %}
{% endstep %}

{% step %}
보정 과정이 끝나면 \[확인] 버튼이 활성화됩니다. 버튼을 눌러 보정을 완료하세요.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=543-7319&t=PM760HAi58K4ZabD-1" %}
{% endstep %}
{% endstepper %}

***

### 관성센서 보정

관성센서 보정은 차량의 기울기, 회전, 진동 데이터를 기준값으로 보정하여 자율주행 시 경로 추종 적확도를 높이는 절차입니다. 반드시 차량을 정차하고 시동을 끈 상태에서 진행합니다.

***

#### 관성센서 보정 설명

{% stepper %}
{% step %}
\[보정 시작]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2092-9213&t=q8g76lClR1lyrQfM-1" %}

{% hint style="info" %}
반드시 차량을 정차하고 시동을 끈 후 시작합니다.
{% endhint %}
{% endstep %}

{% step %}
관성센서 보정이 진행됩니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2092-10127&t=q8g76lClR1lyrQfM-1" %}
{% endstep %}

{% step %}
교정이 완료되면 \[확인]을 누릅니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=2092-10359&t=q8g76lClR1lyrQfM-1" %}

{% hint style="info" %}
보정에 실패하면 다시 시도를 하거나 대리점에 문의해주세요.

<img src="../../.gitbook/assets/calibration-failed.png" alt="" data-size="original">
{% endhint %}
{% endstep %}

{% step %}
보정을 완료하면 차량 보정 메인 화면으로 진입합니다. \[다음 단계로] 버튼을 눌러 작업지 설정에 진입합니다.

{% embed url="https://www.figma.com/design/3caVmkxMdvjppUG5NWSjbb/%EC%B0%A8%EC%84%B8%EB%8C%80-%EB%8C%80%EB%A6%AC%EC%A0%90-%EB%A9%94%EB%89%B4%EC%96%BC?node-id=1585-7179&t=Z6KsYEEodpFnLnOH-1" %}
{% endstep %}
{% endstepper %}
