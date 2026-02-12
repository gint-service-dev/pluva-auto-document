# GNSS 수신기

### GNSS 수신기

GNSS 수신기는 RTK 기반 고정밀 위치정보를 이용하여 농기계의 위치를 정밀하게 파악합니다.보정 데이터를 통해 위치 보정이 이루어지며, 관련 설정은 사용 환경에 따라 달라질 수 있습니다.

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버.png" alt="gnss" width="563"><figcaption></figcaption></figure></div>

![](../../.gitbook/assets/1.svg) 상태 표시 LED

1. 좌측 LED
   1. 전원 및 시스템의 H/W 이상 여부

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED (1).png" alt="gnss" width="375"><figcaption></figcaption></figure></div>

상태 구분

<table data-header-hidden><thead><tr><th width="100.4921875"></th><th></th><th></th></tr></thead><tbody><tr><td>색상</td><td>파란색 (점등)</td><td>노란색 점멸</td></tr><tr><td>상태</td><td>정상</td><td>오류 발생</td></tr><tr><td>이미지</td><td><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED(정상).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED(오류 발생).png" alt=""></td></tr></tbody></table>



2. 중앙 LED
   1. GNSS 보정 정보 수신 여부

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버 - 중앙 LED(60초 이상 미수신 ).png" alt="" width="375"><figcaption></figcaption></figure></div>

상태 구분

<table data-header-hidden><thead><tr><th width="99.57421875"></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>색상</td><td>파란색 (점등)</td><td>파란색 점멸</td><td>OFF</td></tr><tr><td>상태</td><td>정상</td><td>5초 이상 미수신</td><td>60초 이상 미수신 (또는 수신된적 없음)</td></tr><tr><td>이미지</td><td><img src="../../.gitbook/assets/GNSS 리시버 - 좌측 LED(정상).png" alt="GNSS"></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 중앙 LED(5초 이상 미수신).png" alt="GNSS"></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(그밖의 상태).png" alt="GNSS"></td></tr></tbody></table>



3. 우측 LED
   1. GNSS RTK 상태

<div align="left"><figure><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED.png" alt="" width="375"><figcaption></figcaption></figure></div>

상태 구분

<table data-header-hidden><thead><tr><th width="126.7890625"></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>색상</td><td>파란색 (점등)</td><td>파란색 점멸</td><td>OFF</td></tr><tr><td>상태</td><td>RTK Fixed</td><td>RTK Fixed Float</td><td>그 밖의 상태</td></tr><tr><td>이미지</td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(RTK Fixed).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(RTK Fixed Float).png" alt=""></td><td><img src="../../.gitbook/assets/GNSS 리시버 - 우측 LED(그밖의 상태).png" alt=""></td></tr></tbody></table>

![](../../.gitbook/assets/2.svg) QR코드: 제품 등록시 사용되는 QR 코드입니다.
