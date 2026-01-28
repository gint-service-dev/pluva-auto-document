---
layout:
  width: wide
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

# 3. 조향 시스템 보정

## 4-3. 조향 시스템 보정

설정된 경로를 따라 안전하고 정밀하게 자율주행할 수 있도록 조향을 보정하는 과정으로, 농기계의 특성을 반영하여 트랙터는 2단계, 이앙기는 3단계의 보정을 거친다.

***

### a. 조향 시스템 보정 시작 방법

{% stepper %}
{% step %}
#### 설정 화면에서 \[조향 시스템 보정]을 누른다.

<figure><img src="../.gitbook/assets/4-3. 조향 시스템 보정(1).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 차량을 선택하고 \[확인]을 누른다.

<figure><img src="../.gitbook/assets/4-3. 조향 시스템 보정(2).png" alt="" width="236"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### \[전체 한번에 진행] 눌러 보정을 시작한다.

<figure><img src="../.gitbook/assets/4-3. 조향 시스템 보정(3).png" alt="" width="375"><figcaption></figcaption></figure>

> **ℹ️ 각 단계 시작 버튼을 누르면 해당 단계 보정만 진행할 수 있다.**
{% endstep %}
{% endstepper %}

***

### b. 트랙터 조향 시스템 보정

#### <mark style="background-color:$primary;">1) 핸들 범위 보정</mark>

{% stepper %}
{% step %}
#### 안내에 따라 핸들을 왼쪽으로 끝까지 돌린 후 \[확인] 버튼을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(1).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 안내에 따라 핸들을 오른쪽으로 끝까지 돌린 후 \[확인] 버튼을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(2).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 안내에 따라 핸들을 이용하여 바퀴를 중앙에 위치시키고 \[확인]  버튼을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(3).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 핸들 범위 보정 완료된다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(4).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

#### <mark style="background-color:$primary;">2) 직진 조향 보정</mark>

{% stepper %}
{% step %}
#### 필요한 면적 설명을 읽는다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(1).png" alt="" width="231"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 보정 방식 설명을 읽는다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(2).png" alt="" width="232"><figcaption></figcaption></figure>

> **ℹ️  핸들 범위 보정과 달리 직진 조향 보정에서는 핸들이 자동으로 움직인다.**
{% endstep %}

{% step %}
#### 보정 시작 방법을 읽고 \[확인]을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(3).png" alt="" width="232"><figcaption></figcaption></figure>

> **ℹ️  보정법 설명은 최초 2번만 보이고 이후에는  보정가이드 버튼을 눌러야 볼 수 있다.**
{% endstep %}

{% step %}
#### \[2km 시속]으로 주행하면 시작 버튼이 활성화됩니다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(4).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  트랙터 제한 속도는 2km로 초과 시 버튼 클릭이 불가하다.**
>
> **ℹ️  정지 시 직진 조향 보정의 처음부터 다시 시작한다.**
{% endstep %}

{% step %}
#### \[자동 보정 시작]을 누릅니다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(5).png" alt="" width="230"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 지속해서 2km미만 으로 주행합니다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(6).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  보정 시 필요 면적이 확보되지않거나 주행이 불가능할 경우 긴급 정지를 누른다.**
{% endstep %}

{% step %}
#### 완료되면 버튼이 활성화되며 \[확인]을 누르면 보정이 완료됩니다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(7).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  보정 실패 시 안내 문구가 나타나고 \[다시 시도]를 누르면 직진 조향 보정 첫 화면으로 이동한다.**
>
> <img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(8).png" alt="" data-size="original">
{% endstep %}
{% endstepper %}

***

### c. 이앙기 조향 시스템 보정

#### <mark style="background-color:$primary;">1) 핸들 범위 보정</mark>

{% stepper %}
{% step %}
#### 안내에 따라 핸들을 왼쪽으로 끝까지 돌린 후 \[확인] 버튼을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(1).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 안내에 따라 핸들을 오른쪽으로 끝까지 돌린 후 \[확인] 버튼을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(2).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 안내에 따라 핸들을 이용하여 바퀴를 중앙에 위치시키고 \[확인]  버튼을 누른다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(3).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 핸들 범위 보정 완료된다.

<figure><img src="../.gitbook/assets/4-3. 트랙터 핸들 보정(4).png" alt="" width="232"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

#### <mark style="background-color:$primary;">2) 직진 조향 보정</mark>

{% stepper %}
{% step %}
#### 필요한 면적 설명을 읽는다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(1).png" alt="" width="375"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 보정 방식 설명을 읽는다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(2).png" alt="" width="232"><figcaption></figcaption></figure>

> **ℹ️  핸들 범위 보정과 달리 직진 조향 보정에서는 핸들이 자동으로 움직인다.**
{% endstep %}

{% step %}
#### 보정 시작 방법을 읽고 \[확인]을 누른다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(3).png" alt="" width="232"><figcaption></figcaption></figure>

> **ℹ️  보정법 설명은 최초 2번만 보이고 이후에는  보정가이드 버튼을 눌러야 볼 수 있다.**
{% endstep %}

{% step %}
#### \[1km 시속]으로 주행하면 시작 버튼이 활성화됩니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(4).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  이앙기 제한 속도는 1km로 초과 시 버튼 클릭이 불가하다.**
>
> **ℹ️  정지 시 직진 조향 보정의 처음부터 다시 시작한다.**
{% endstep %}

{% step %}
#### \[자동 보정 시작]을 누릅니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(5).png" alt="" width="230"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 지속해서 1km미만 으로 주행합니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(6).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  보정 시 필요 면적이 확보되지않거나 주행이 불가능할 경우 긴급 정지를 누른다.**
{% endstep %}

{% step %}
#### 완료되면 버튼이 활성화되며 \[확인]을 누르면 보정이 완료됩니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(7).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  보정 실패 시 안내 문구가 나타나고 \[다시 시도]를 누르면 직진 조향 보정 첫 화면으로 이동한다.**
>
> <img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(8).png" alt="" data-size="original">
{% endstep %}
{% endstepper %}

#### <mark style="background-color:$primary;">3) 조향 각도 보정</mark>

{% stepper %}
{% step %}
#### \[1km 시속]으로 주행하면 시작 버튼이 활성화됩니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(4).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  이앙기 제한 속도는 1km로 초과 시 버튼 클릭이 불가하다.**
>
> **ℹ️  정지 시 직진 조향 보정의 처음부터 다시 시작한다.**
{% endstep %}

{% step %}
#### \[자동 보정 시작]을 누릅니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(5).png" alt="" width="230"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 지속해서 1km미만 으로 주행합니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(6).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️ 보정 시 필요 면적이 확보되지않거나 주행이 불가능할 경우 긴급 정지를 누른다.**
>
> **ℹ️ 조향 각도 보정에서는 핸들이 자동으로 움직인다.**
{% endstep %}

{% step %}
#### 완료되면 버튼이 활성화되며 \[확인]을 누르면 보정이 완료됩니다.

<figure><img src="../.gitbook/assets/4-3. 이앙기 직진 조향 보정(7).png" alt="" width="230"><figcaption></figcaption></figure>

> **ℹ️  보정 실패 시 안내 문구가 나타나고 \[다시 시도]를 누르면 직진 조향 보정 첫 화면으로 이동한다.**
>
> <img src="../.gitbook/assets/4-3. 트랙터 직진 조향 보정(8).png" alt="" data-size="original">
{% endstep %}
{% endstepper %}

