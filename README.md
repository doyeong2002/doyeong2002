# 김도영

명지대학교 컴퓨터공학과에서 공부하고 있습니다. 데이터를 설계하고 조회하는 작업이 API와 화면으로 이어져, 사용자가 실제로 기능을 이용할 수 있게 만드는 데 관심이 있습니다.

수업에서는 다통화 환전·결제 서비스의 데이터베이스를 설계했고, 팀 프로젝트에서는 계정·인증 API를 맡았습니다. 개인 프로젝트 Replay에서는 증권 API의 계좌 데이터를 화면에 연결했습니다. 최근에는 LG Aimers에서 데이터 전처리와 예측 코드 개선을 경험했습니다. 각 프로젝트에서 제가 맡은 작업과 팀 전체 결과물을 구분해 소개합니다.

## 관심과 경험

- **백엔드와 데이터:** Spring Boot로 계정·인증 API를 구현하고, MySQL에서 테이블 관계와 잔액·거래 조회 SQL을 작성했습니다.
- **화면과 외부 API 연결:** React·TypeScript로 계좌 현황 화면을 만들고, Next.js 서버 경로에서 증권 API를 호출했습니다.
- **데이터 처리:** Python으로 결측치와 전처리 작업에 참여했고, AI 도구의 도움을 받아 모델 학습·검증 코드를 개선했습니다.

## 프로젝트

### 어르신 교통 동행 안내 서비스 · 팀 프로젝트

어르신과 보호자가 이용하는 교통 동행 안내 서비스에서 백엔드의 계정·인증 영역을 맡았습니다. Java, Spring Boot, SQL을 사용해 계정 및 어르신 정보 API, 보호자 연결, 알림, 문자 인증과 로그인 상태 유지 기능을 구현했습니다. 팀 저장소에서 제가 작성한 변경 사항을 확인할 수 있습니다.

- [팀 백엔드 저장소](https://github.com/yongyongthon-team13/BE)
- [계정·어르신 정보·보호자 연결·알림 API](https://github.com/yongyongthon-team13/BE/pull/3)
- [문자 인증 후 로그인 상태 유지](https://github.com/yongyongthon-team13/BE/pull/7)
- [문자 발송 서비스 연동](https://github.com/yongyongthon-team13/BE/pull/9)

### Replay · 개인 프로젝트

React와 TypeScript로 계좌 현황을 조회하는 화면을 만들고, 서버에서 토스증권 Open API를 호출하도록 구성했습니다. API 인증정보와 허용 IP 조건을 확인하며 연동 문제를 해결했습니다. [소스 코드와 실행 방법](https://github.com/doyeong2002/replay-investing)을 볼 수 있습니다.

### 해외여행 다통화 환전·결제 DB · 팀 프로젝트

MySQL로 사용자, 원화 계좌, 외화 지갑, 트래블카드, 거래 내역의 관계를 설계하고 잔액·거래 조회 SQL을 작성했습니다. Flask 화면에서 조회 결과를 확인했습니다. 공개용 SQL과 프로젝트 설명은 [별도 저장소](https://github.com/doyeong2002/travelpay-db)에 정리했습니다.

### LG Aimers 9기 해커톤 · 팀 프로젝트

투구 제구 성공 확률 예측 과제에서 결측치 확인과 데이터 전처리에 참여했습니다. 대회에서 제공한 베이스라인을 바탕으로 파생변수, 모델 학습·앙상블, 시간순 검증 등을 개선하는 과정에는 AI 도구의 코드 작성·수정 지원을 활용했습니다. 대회 데이터와 학습된 모델은 제외하고 [코드와 작업 설명](https://github.com/doyeong2002/lg-aimers-pitch-prediction)을 공개했습니다. [데이콘 코드 공유 글](https://dacon.io/competitions/official/236743/codeshare/14200)에서도 작업 내용을 볼 수 있습니다.
