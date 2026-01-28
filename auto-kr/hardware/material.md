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

# 1. 플루바오토 구성품 준비

## 2-1. 플루바 오토 구성품 준비

***

### <mark style="background-color:$primary;">a. 메인 컨트롤러</mark>

<figure><img src="../.gitbook/assets/2-1-1. 메인컨트롤러 본체.png" alt="" width="563"><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="99.8359375">용도</th><th>크기</th></tr></thead><tbody><tr><td>용도</td><td>RTK-GPS(고 정밀 위치 정보) 기술을 활용한 농기계_의 실시간 위치 데이터를 파악, 별도의 설정 없이 자동 위치 보정 서비스 지원</td></tr><tr><td>크기</td><td>249 X 143 X 70 (가로X세로X높이)</td></tr><tr><td>무게</td><td>1.008kg</td></tr><tr><td>재질</td><td>ABS</td></tr><tr><td>핵심기술</td><td><ol><li>RTK-GPS</li><li>IMU Sensor</li><li>자율주행 알고리즘</li></ol></td></tr></tbody></table>

#### 🎨 단말기 LED 색상별 상태정보

<figure><img src="../.gitbook/assets/2-1-1. 메인컨트롤러.png" alt=""><figcaption></figcaption></figure>

***

### <mark style="background-color:$primary;">b. 인터페이스 박스</mark>

<figure><img src="../.gitbook/assets/2-1-1.인터페이스 박스.png" alt="" width="563"><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="99.71484375">용도</th><th>크기</th></tr></thead><tbody><tr><td>용도</td><td><ol><li>전원 연결 및 외부 단자 등 연결할 수 있는 장비</li><li>센서나 액추에이터를 추가 연결하여 플루바 클라우드와 연동한 확장 서비스 이용 가능</li></ol></td></tr><tr><td>크기</td><td>215 X 158 X 59 (가로X세로X높이)</td></tr><tr><td>무게</td><td>0.449 kg</td></tr><tr><td>재질</td><td>ABS</td></tr><tr><td>핵심기술</td><td><ol><li>전원, 통신 분배기</li><li>방수 방진 IP 67</li></ol></td></tr></tbody></table>

#### 🔌 단자별 역할

<figure><img src="../.gitbook/assets/2-1-1.인터페이스 박스 단자별.png" alt=""><figcaption></figcaption></figure>

***

### <mark style="background-color:$primary;">c. 원터치 스위치</mark>

<figure><img src="../.gitbook/assets/2-1-1.원터치 스위치.png" alt="" width="563"><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="99.7890625">용도</th><th>크기</th></tr></thead><tbody><tr><td>용도</td><td><p></p><ul><li>어플리케이션 및 원터치 스위치를 통해 자율주행 조작이 가능</li><li>직관적인 사용법으로 누구나 쉽게 경로를 생성하고 주행이 가능</li></ul></td></tr><tr><td>크기</td><td>76 X 151 X 18 (가로X세로X높이)</td></tr><tr><td>무게</td><td>0.144 kg</td></tr><tr><td>재질</td><td>ABS</td></tr><tr><td>핵심기술</td><td><ol><li>직진/후진/선회주행 설정</li><li>방수 방진 IP 67</li></ol></td></tr></tbody></table>

#### 📱 버튼별 역할

<figure><img src="../.gitbook/assets/2-1-1.원터치 스위치 버튼역할(1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/2-1-1.원터치 스위치 버튼역할(2).png" alt=""><figcaption></figcaption></figure>



<div><figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(부팅중) (1).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>부팅 중</strong></mark></p></figcaption></figure> <figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(연결중) (1).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>연결 중</strong></mark></p></figcaption></figure> <figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(OTA 진행중).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>OTA 진행 중</strong></mark></p></figcaption></figure> <figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(준비완료).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>준비 완료</strong></mark></p></figcaption></figure></div>

| 부팅 중                                       | 연결 중                                            |
| ------------------------------------------ | ----------------------------------------------- |
| <ul><li>LDE 화면에 PLUVA 로고가 표시됩니다.</li></ul> | <ul><li>LCD 화면상의 GPS의 문자가 녹색으로 점등됩니다.</li></ul> |

| OTA 진행 중                                                                            | 준비 완료                                      |
| ----------------------------------------------------------------------------------- | ------------------------------------------ |
| <p></p><ul><li>업데이트가 필요할 경우 진행을 합니다.</li><li>LED 화면상의 단말기 OTA 종료으로 표시됩니다.</li></ul> | <ul><li>연결 완료가 되면 해당 이미지가 표시됩니다.</li></ul> |

<div><figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(구간 지정 A점).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>구간 지정 (A점)</strong></mark></p></figcaption></figure> <figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(구간 지정 B점).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>구간 지정 (B점)</strong></mark></p></figcaption></figure> <figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(자율주행 준비).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>자율주행 준비</strong></mark></p></figcaption></figure> <figure><img src="../.gitbook/assets/2-1-1.원터치 스위치(자율주행 중).png" alt=""><figcaption><p><mark style="color:$primary;"><strong>자율주행 중</strong></mark></p></figcaption></figure></div>

| 구간 지정 (A 점)                                                                                                | 구간 지정 (B 점)                                                                 |
| ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| <p></p><ul><li>주행모드 선택 후 직진 주행을 누르면 해당 아이콘이 나옵니다.</li><li>AB직선 모드를 선택하면 B점 화면이 신지 선택 화면으로 전환됩니다.</li></ul> | <ul><li>10M 이상 주행 후 B지점 선택 화면이 표시됩니다.</li><li>B 지점 선택화면으로 전환 됩니다.</li></ul> |

| 자율주행 준비                                                          | 자율주행 중                                                                                                        |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| <ul><li>운전 버튼 선택 화면으로 전환 됩니다.</li><li>부저가 1초에 3회 울립니다.</li></ul> | <ul><li>자율주행 버튼을 누르면 자율주행이 시작합니다.</li><li>안정화 구간은 진입할 때 부저가 3회 울립니다.</li><li>A, B 경로 다다르면 부저가 울립니다.</li></ul> |

***

### <mark style="background-color:$primary;">d. 오토 스티어링</mark>

<figure><img src="../.gitbook/assets/2-1-1. 오토스티어링.png" alt="" width="563"><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="99.625">용도</th><th>크기</th></tr></thead><tbody><tr><td>용도</td><td><ol><li>기존 기기의 핸들을 탈거 후 스티어링 모터를 장착하여 사용</li><li>생성된 경로 추종, 직진 성능 유지</li><li>전원 ON/OFF 하여 기기의 전원 공급</li></ol></td></tr><tr><td>크기</td><td>350 X 350 X 80 (가로X세로X높이)</td></tr><tr><td>무게</td><td>6.802 kg</td></tr><tr><td>재질</td><td>다이캐스팅 / 알루미늄</td></tr><tr><td>핵심기술</td><td><ol><li>좌우 모터 제어</li><li>전원 ON/OFF</li><li>방수 방진 IP 67</li></ol></td></tr></tbody></table>

#### 🔩 프론트 브라켓

<figure><img src="../.gitbook/assets/2-1-1. 프론트브라켓.png" alt=""><figcaption></figcaption></figure>

***

### <mark style="background-color:$primary;">e. 각종 하네스</mark>

<figure><img src="../.gitbook/assets/2-1-1. 각종 하네스.png" alt=""><figcaption></figcaption></figure>

***

### <mark style="background-color:$primary;">f. 세레이션</mark>

<figure><img src="../.gitbook/assets/2-1-1. 세레이션.png" alt=""><figcaption></figcaption></figure>
