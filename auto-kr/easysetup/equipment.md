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

# 4. 장비 등록

## 3-4. 장비 등록

자율주행에 사용되는 장비를 등록하는 과정이다.

***

### a. 차량 정보 입력

{% stepper %}
{% step %}
#### 장비 등록 순서를 확인하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. 차량 정보 입력 (1).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}

{% step %}
#### 차량 정보를 입력하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. 차량 정보 입력 (2).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}
{% endstepper %}

> **ℹ️ &#x20;**<mark style="color:$primary;">**Step 1. 차량 정보 입력**</mark>**&#x20;화면에는 주문서에서 작성한 정보가 자동으로 입력된다. (수정 가능)**
>
> **ℹ️  선택 항목에 알맞은 제조사, 모델이 없을 경우&#x20;**<mark style="color:$primary;">**직접 입력 토글**</mark>**을 눌러 새로운 장비 정보를 입력한다.**
>
> <p align="center"><img src="../.gitbook/assets/3-4. 차량 정보 입력 (3).png" alt="" data-size="original"></p>

***

### b. 차량 치수 입력

{% stepper %}
{% step %}
#### 안내에 따라 차량 치수를 측정하고 값을 입력한다.

<figure><img src="../.gitbook/assets/3-4. 차량 치수입력 (1).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}

{% step %}
#### 좌우 스와이프로 다음 항목을 선택한다.

<figure><img src="../.gitbook/assets/3-4. 차량 치수입력 (2).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}

{% step %}
#### 모든 치수를 입력하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. 차량 치수입력 (3).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

> **ℹ️  앞 단계(Step 1)에서 입력한 차량 타입(트랙터, 이앙기)에 맞는 안내가 표시된다.**
>
> **ℹ️  차량 타입(트랙터, 이앙기)에 맞는 가이드 치수가 플레이스홀더에 표시된다.**
>
> <img src="../.gitbook/assets/3-4. 차량 치수입력 (4).png" alt="" data-size="original">
>
> \[참고] 이앙기 치수 입력 화면
>
>
>
> **ℹ️  차량 치수는 플루바오토 앱의&#x20;**<mark style="color:$primary;">**\[장비]**</mark>**&#x20;메뉴에서 수정할 수 있다.**

***

### c. 메인컨트롤러 설치 위치 입력

{% stepper %}
{% step %}
#### 안내에 따라 메인컨트롤러를 설치한 위치를 측정하고 값을 입력한다.

<figure><img src="../.gitbook/assets/3-4. 메인컨트롤러 설치 위치 입력 (1).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}

{% step %}
#### 좌우 스와이프로 다음 항목을 선택한다.

<figure><img src="../.gitbook/assets/3-4. 메인컨트롤러 설치 위치 입력 (2).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### 모든 값을 입력하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. 메인컨트롤러 설치 위치 입력 (3).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

> **ℹ️  입력값의 부호(+,-)는 방향을 의미한다. 소수점 둘째자리까지 입력할 수 있다.**
>
> **ℹ️  메인컨트롤러 설치 위치는 플루바오토 앱의&#x20;**<mark style="color:$primary;">**\[장비]**</mark>**&#x20;메뉴에서 수정할 수 있다.**

***

### d. IMU 초기값 입력

{% stepper %}
{% step %}
#### 안내에 따라 IMU 초기값을 입력하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. IMU 초기값 입력 (4).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}
{% endstepper %}

<details>

<summary>IMU 피치값 측정 방법</summary>

1. 차량을 평지에 주차한 후 시동을 끈다.
2. 캐빈 바닥면 각도를 측정한다. (캐빈 바닥 중 가장 평평한 부분을 찾아 측정)
3. 메인컨트롤러 상단면 각도를 측정한다.
4. 피치값을 계산하여 입력한다.

<figure><img src="../.gitbook/assets/피치 값 측정 방법.png" alt=""><figcaption></figcaption></figure>

* **입력 수치 = - {캐빈측정 각도 + 메인컨트롤러 각도}**
  * 예시: - {(-0.3) + (-10.6)} = 10.9
*   트랙터는 대부분 앞쪽으로 메인컨트롤러가 기울어져 있기 때문에 각도가 음수(-)로 측정된다.

    * <img src="../.gitbook/assets/대리점 메뉴얼 (한국어 V 2.1.5) (찐) 4.png" alt="" data-size="original">

    &#x20;        수준기, 수평계

</details>

> * **IMU 초기값은 경사지나 불규칙한 지형에서도 정확한 방향과 위치를 유지할 수 있도록 메인컨트롤러의 기울어짐 정도를 보정하기 위해 사용된다.**
> * **해당 값을 입력하지 않아도 다음 단계를 진행할 수 있지만 설치한 메인컨트롤러의 기울어짐이 눈에 띄는 정도라면 아래 방법을 따라 피치값을 입력하여 보정하는 것을 권장한다.**
> * **IMU 초기값 정보는 플루바오토 앱의&#x20;**<mark style="color:$primary;">**\[장비]**</mark>**&#x20;메뉴에서 수정할 수 있다.**

***

### e. 작업기 정보 및 치수 입력

{% stepper %}
{% step %}
#### 작업기 타입을 선택하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. 작업기 정보 및 치수 입력 (1).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}

{% step %}
#### 안내에 따라 필요한 값을 입력하고 \[다음]을 누른다.

<figure><img src="../.gitbook/assets/3-4. 작업기 정보 및 치수 입력 (2) (1).png" alt="" width="248"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

> **ℹ️  작업기 정보는 선택사항이므로 입력하지 않아도 다음을 진행할 수 있다.**
>
> **ℹ️  이앙기의 경우 작업기 정보 입력 단계가 생략된다.**
>
> **ℹ️  작업기 정보 입력 화면에서 선택 항목에 원하는 작업기가 없을 경우&#x20;**<mark style="color:$primary;">**직접 입력 토글**</mark>**을 눌러 작업기 정보를 입력한다.**
>
> **ℹ️  작업기 정보는 플루바오토 앱의&#x20;**<mark style="color:$primary;">**\[장비]**</mark>**&#x20;메뉴에서 추가, 수정할 수 있다.**

***

### f. 입력한 정보 확인

{% stepper %}
{% step %}
#### 입력한 정보를 확인하고 \[완료]를 누른다.

<figure><img src="../.gitbook/assets/3-4. 입력한 정보 확인 (1).png" alt="" width="248"><figcaption></figcaption></figure>


{% endstep %}
{% endstepper %}

> **ℹ️ &#x20;**<mark style="color:$primary;">**\[완료]**</mark>**&#x20;버튼을 누른 후에는 Easy Setup에서 장비 정보를 수정할 수 없다. (플루바오토 앱에서 수정 가능)**
>
> **ℹ️ &#x20;**<mark style="color:$primary;">**이전, 다음**</mark>**을 눌러 입력한 장비 정보를 확인할 수 있다.**

<figure><img src="../.gitbook/assets/3-4. 입력한 정보 확인 (2) (3).png" alt="" width="563"><figcaption></figcaption></figure>
