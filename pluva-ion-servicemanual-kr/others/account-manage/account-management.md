# 계정 목록 및 상세

고객 계정의 기본 정보와 보유 작업·원격지원·제품·장비·필드·설치 이력을 조회합니다.

{% hint style="info" %}
계정 생성, 수정, 삭제는 이 화면에서 제공되지 않습니다. 고객 계정은 통합 회원가입 페이지를 통해 생성되며, 계정 정보 변경이 필요한 경우 고객에게 직접 통합 회원가입 페이지에서 수정하도록 안내해주세요.
{% endhint %}

***

### 진입 방법 <a href="#how-to" id="how-to"></a>

{% stepper %}
{% step %}
좌측 메뉴에서 **계정 목록**을 진입한 뒤 원하는 계정을 선택합니다.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
원하는 계정 항목을 선택하면 계정 상세 진입이 완료됩니다.

<figure><img src="../../.gitbook/assets/image (161).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### 계정 상세 정보 화면 설명 <a href="#detail" id="detail"></a>

#### PC 환경 <a href="#detail-desktop" id="detail-desktop"></a>

<figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

![](../../.gitbook/assets/icon-square-1.svg) 계정 이름

![](../../.gitbook/assets/icon-square-2.svg) 담당 조직 및 생성일

{% hint style="info" %}
**참고**: 담당 조직은 제품을 판매·설치하고 고객의 지속적인 제품 이용을 지원하는 서비스 주체입니다.
{% endhint %}

![](../../.gitbook/assets/icon-square-3.svg) 계정 정보

* 해당 계정에 등록된 휴대폰 번호와 이메일 주소가 표시됩니다.

{% hint style="info" %}
**참고**: 휴대폰 번호와 이메일 주소 항목 옆의 복사 버튼을 누르면 클립보드에 바로 복사됩니다.
{% endhint %}

![](../../.gitbook/assets/icon-square-4.svg) 메모

* **⋮ 버튼**을 눌러 내용을 수정하거나 삭제할 수 있습니다.
* **작성자 이름**과 **작성 일시**가 함께 표시됩니다.

![](../../.gitbook/assets/icon-square-5.svg) 계정 상세 정보

* 계정 상세 화면 하단에서 **작업, 제품, 장비, 필드, 설치, 원격 지원** 탭을 선택하여 각 이력을 조회합니다. 목록 조회만 가능하며, 직접 추가·수정은 지원하지 않습니다.
  * **작업 탭**: 고객이 작업한 내역을 확인합니다.
    * 작업 차량, 작업 시간, 작업 경로가 표시되며, 해당 작업의 상세 내용 확인이 가능합니다.
  * **제품 탭**: 고객이 보유한 제품 정보를 확인합니다.
    * 등록된 제품과 구성품의 목록 및 총 수량이 표시됩니다.
  * **장비 탭**: 고객이 보유한 장비 정보를 확인합니다.
    * 차량을 클릭하면 해당 차량의 치수, 보정 정보, GNSS 수신기 위치, 차량 제어 설정을 볼 수 있습니다.
    *   작업기를 클릭하면 작업기의 타입, 너비, 고랑 폭, 작업기 편차를 확인할 수 있습니다.

        <figure><img src="../../.gitbook/assets/image (254).png" alt=""><figcaption></figcaption></figure>
    *   차량 카드에는 차량 치수 또는 보정값 중 가장 심각한 상태가 \[이상값] 또는 \[확인 필요] 배지로 표시됩니다. 차량을 선택하면 문제 항목과 필요한 조치를 확인할 수 있습니다.

        * \[이상값]: 차량 치수 또는 보정값이 유효하지 않은 상태입니다. \[재입력 필요] 또는 \[재보정 필요] 항목을 확인한 뒤, 태블릿에서 치수를 다시 입력하거나 차량 보정을 진행하세요.\
          \[확인 필요]: 조향 보정값이 일반 범위를 벗어났지만 차량에 따라 사용할 수 있습니다. 현재 보정값으로 자율주행에 문제가 없는지 확인한 뒤, 이상이 없으면 \[확인 필요]를 눌러 \[정상 처리]하세요.
        * 차량 치수 수정은 [내 차량 진입 및 화면 설명](https://usermanual.pluva.io/ion/korea/kr/usage/vehicle-settings/entering-my-vehicle)을 참고하세요.
        * 보정값 수정은 [오토스티어 보정](https://usermanual.pluva.io/ion/korea/kr/usage/vehicle-settings/autostere-calibration)을 참고하세요.

        <figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>
  * **필드 탭**: 고객이 등록한 필드 목록과 총 수량을 확인합니다.
    * 농장명, 작물 뱃지, 필드명, 필드 면적을 확인할 수 있습니다.
  * **설치 탭**: 고객의 설치 이력을 확인합니다.
    * 설치한 상세 내역 (설치티켓)을 볼 수 있습니다.
  * **원격 지원 탭**: 이 고객/기기에 원격 지원을 언제, 몇 번 했는지 확인합니다.
    * 이번달, 최근 6개월, 최근 1년을 선택하면 기간 내 이력이 기기별로 표시됩니다.

#### 모바일 환경 <a href="#detail-mobile" id="detail-mobile"></a>

<div align="left"><figure><img src="../../.gitbook/assets/image (113).png" alt="" width="375"><figcaption></figcaption></figure></div>

![](../../.gitbook/assets/icon-square-1.svg) 계정 이름

![](../../.gitbook/assets/icon-square-2.svg) 담당 조직 및 생성일

{% hint style="info" %}
**참고**: 담당 조직은 제품을 판매·설치하고 고객 정보를 관리하는 대리점입니다.
{% endhint %}

![](../../.gitbook/assets/icon-square-3.svg) 계정 정보

* 해당 계정에 등록된 휴대폰 번호와 이메일 주소가 표시됩니다.

{% hint style="info" %}
**참고**: 휴대폰 번호와 이메일 주소 항목 옆의 복사 버튼을 누르면 클립보드에 바로 복사됩니다.
{% endhint %}

![](../../.gitbook/assets/icon-square-4.svg) 메모

* **⋮ 버튼**을 눌러 내용을 수정하거나 삭제할 수 있습니다.
* **작성자 이름**과 **작성 일시**가 함께 표시됩니다.

![](../../.gitbook/assets/icon-square-5.svg) 계정 상세 정보

* 계정 상세 화면 하단에서 **작업, 제품, 장비, 필드, 설치, 원격 지원** 탭을 선택하여 각 이력을 조회합니다.\
  목록 조회만 가능하며, 직접 추가·수정은 지원하지 않습니다.
  * **작업 탭**: 고객이 작업한 내역을 확인합니다.
    * 작업 차량, 작업 시간, 작업 경로가 표시되며, 해당 작업의 상세 내용 확인이 가능합니다.
  * **제품 탭**: 고객이 보유한 제품 정보를 확인합니다.
    * 등록된 제품과 구성품의 목록 및 총 수량이 표시됩니다.
  * **장비 탭**: 고객이 보유한 장비 정보를 확인합니다.
    * 차량을 클릭하면 해당 차량의 치수, 보정 정보, GNSS 수신기 위치, 차량 제어 설정을 볼 수 있습니다.
    *   작업기를 클릭하면 작업기의 타입, 너비, 고랑 폭, 작업기 편차를 확인할 수 있습니다.

        <div align="left"><figure><img src="../../.gitbook/assets/image (255).png" alt="" width="375"><figcaption></figcaption></figure></div>
    * 차량 카드에는 차량 치수 또는 보정값 중 가장 심각한 상태가 \[이상값] 또는 \[확인 필요] 배지로 표시됩니다. 차량을 선택하면 문제 항목과 필요한 조치를 확인할 수 있습니다.
      * \[이상값]: 차량 치수 또는 보정값이 유효하지 않은 상태입니다. \[재입력 필요] 또는 \[재보정 필요] 항목을 확인한 뒤, 태블릿에서 치수를 다시 입력하거나 차량 보정을 진행하세요.\
        \[확인 필요]: 조향 보정값이 일반 범위를 벗어났지만 차량에 따라 사용할 수 있습니다. 현재 보정값으로 자율주행에 문제가 없는지 확인한 뒤, 이상이 없으면 \[확인 필요]를 눌러 \[정상 처리]하세요.
      * 차량 치수 수정은 [내 차량 진입 및 화면 설명](https://usermanual.pluva.io/ion/korea/kr/usage/vehicle-settings/entering-my-vehicle)을 참고하세요.
      *   보정값 수정은 [오토스티어 보정](https://usermanual.pluva.io/ion/korea/kr/usage/vehicle-settings/autostere-calibration)을 참고하세요.

          <div align="left"><figure><img src="../../.gitbook/assets/image (256).png" alt="" width="375"><figcaption></figcaption></figure></div>
  * **필드 탭**: 고객이 등록한 필드 목록과 총 수량을 확인합니다.
    * 농장명, 작물 뱃지, 필드명, 필드 면적을 확인할 수 있습니다.
  * **설치 탭**: 고객의 설치 이력을 확인합니다.
    * 클릭하면 설치한 상세 내역 (설치티켓)을 볼 수 있습니다.
  * **원격 지원 탭**: 이 고객/기기에 원격 지원을 언제, 몇 번 했는지 확인합니다.
    * 이번달, 최근 6개월, 최근 1년을 선택하면 기간 내 이력이 기기별로 표시됩니다.
