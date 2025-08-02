# DSG, Do Something Good

## Space with You, Worlty

![Version v0.0.0][version-shield]

- [버전 기록정보](#version-history)
- [안내사항](#안내사항)
- [준비물](#준비물)
- [설치방법](#설치방법)
- [추가방법](#추가방법)

문의 : 월티 [홈페이지](https://worlty.com)

<br/>

## 버전 기록정보

|             버전              |    날짜    | 내용                                                                               |
| :---------------------------: | :--------: | :--------------------------------------------------------------------------------- |
| 2025-08-02T15:20:53.031055195 | 2025.08.03 | 보일러 외출모드 지원 시 외출모드일 때 상태 꺼짐으로 표시되도록 수정                |
| 2025-07-26T03:03:43.800506374 | 2025.07.26 | 가스밸브 카테고리 지정, 번역 일부 수정, 장치타입 일부 변경, 현관움직임 감지 활성화 |
| 2025-04-17T06:29:51.067542339 | 2025.04.17 | 하위장치 지원 추가                                                                 |
| 2025-03-07T14:24:28.703814291 | 2025.03.07 | 장치검색 및 장치포트 변경 관련 대응 추가                                           |
| 2025-03-06T06:00:18.386952642 | 2025.03.06 | discovery 관련 대응 패치 및 연결 시 platform 이름 추가                             |
| 2025-03-04T17:28:04.932878624 | 2025.03.05 | 로컬 연결 안정성 향상                                                              |
| 2024-12-11T01:54:38.567312796 | 2024.12.11 | 카드 내 항목 제어 관련 bug fix                                                     |
|             0.0.4             | 2024.12.10 | 연결 안정성 관련 minor fix, 이벤트카드 내 엘리베이터 추가                          |
|             0.0.3             | 2024.12.09 | 카드 내 있는 엘리베이터 추가                                                       |
|             0.0.2             | 2024.12.09 | 로컬 연결 관련 minor fix                                                           |
|             0.0.1             | 2024.12.03 | 엘리베이터 스위치 미등록 오류 수정 및 minor fix                                    |
|             0.0.0             | 2024.09.01 | 서비스 공개                                                                        |

<br/>

## 안내사항

- 지능형 홈네트워크의 모든 기능을 이용하려면 홈네트워크 장치 제조사 혹은 건설사의 `정식 서비스를 이용`하시기 바랍니다.
- 본 서비스는 `스마트홈 기기제어 프로토콜`인 `KSX4506`을 지원합니다.

<br/>

## 준비물

- SmartThings 허브, 스테이션 등 `엣지드라이버 설치가 가능한 제품`
- 지능형 홈네트워크가 설치되어 있는 주거공간
- `아파트 시공상황에 따라서 지원되는 항목이 다를 수 있습니다.`

### 비밀번호(Access Token) 발급 방법

- 월티 앱 실행
  ![worlty_token_01](/img/worlty_token_01.jpg)
  <br/>

- 메뉴 클릭 > 내 장치 목록
  ![worlty_token_02](/img/worlty_token_02.jpg)
  <br/>

- 장치 클릭
  ![worlty_token_03](/img/worlty_token_03.jpg)
  <br/>

- 토큰 발급하기
  ![worlty_token_04](/img/worlty_token_04.jpg)
  <br/>

- 최대 연결 개수, 포트 설정 후 발급하기 클릭
  ![worlty_token_05](/img/worlty_token_05.jpg)
  <br/>

- 비밀번호(Access Token) 확인
  ![worlty_token_06](/img/worlty_token_06.jpg)

<br/>

## 설치방법

- 엣지드라이버 설치 [링크](https://bestow-regional.api.smartthings.com/invite/kVM5OGyOZxl5)
  ![install_01](/img/install_01.jpg)
  <br/>

- Enroll 클릭
  ![install_02](/img/install_02.jpg)
  <br/>

- Available Drivers 클릭
  ![install_03](/img/install_03.jpg)
  <br/>

- Install 클릭
  ![install_03](/img/install_03.jpg)
  <br/>

- SmartThings 앱 실행 후 기기 추가
  ![install_04](/img/install_04.jpg)
  <br/>

- 주변 검색
  ![install_05](/img/install_05.jpg)
  <br/>

- 허브 선택
  ![install_06](/img/install_06.jpg)
  ![install_07](/img/install_07.jpg)
  <br/>

- 완료 클릭
  ![install_08](/img/install_08.jpg)
  <br/>

- 추가된 월티패드 클릭 `장치를 불러오는 중이면 조금 기다려주세요`
  ![install_09](/img/install_09.jpg)
  <br/>

- 설정 클릭
  ![install_10](/img/install_10.jpg)
  <br/>

- 비밀번호(Access Token) 입력 후 저장
  ![install_11](/img/install_11.jpg)
  ![install_12](/img/install_12.jpg)
  <br/>

- 월티에 연결된 기기 추가 완료!
  ![install_13](/img/install_13.jpg)

[version-shield]: https://img.shields.io/badge/version-v0.0.0-orange.svg
