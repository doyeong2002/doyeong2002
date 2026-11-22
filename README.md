# 김도영

명지대학교 컴퓨터공학과에서 공부하고 있습니다. 데이터가 저장되고 조회되어 API와 화면의 기능으로 이어지는 과정에 관심이 있습니다. 수업 프로젝트에서는 데이터베이스를 설계했고, 팀 프로젝트에서는 계정·인증 API를, 개인 프로젝트에서는 증권 API를 연결한 조회 화면을 만들었습니다.

## About Me

- **관심 분야:** 백엔드 개발, 데이터베이스, 외부 API를 활용한 서비스 개발
- **해본 일:** Spring Boot 계정·인증 API, MySQL 잔액·거래 조회 SQL, React·TypeScript 계좌 현황 화면
- **데이터 경험:** LG Aimers에서 결측치 확인과 전처리에 참여했고, AI 도구의 도움을 받아 예측 코드를 개선했습니다.

## Education

| 학교 | 전공 | 상태 |
| --- | --- | --- |
| 명지대학교 | 컴퓨터공학과 | 재학 중 |

## Tech Stack

프로젝트에서 사용한 기술을 적었습니다. 각 저장소에서 제가 맡은 범위를 확인할 수 있습니다.

| Backend & API | Frontend |
| --- | --- |
| ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) | ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) |
| **Database** | **Data & Tools** |
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

## Projects

### 어르신 교통 동행 안내 서비스 · 팀 프로젝트

**역할:** 백엔드 계정·인증 영역<br>
**기술:** Java, Spring Boot, SQL

어르신과 보호자가 이용하는 서비스에서 계정 및 어르신 정보 API, 보호자 연결, 알림, 문자 인증과 로그인 상태 유지 기능을 구현했습니다. 팀 저장소의 전체 작업과 제가 작성한 변경 사항을 구분해 볼 수 있습니다.

- [팀 백엔드 저장소](https://github.com/yongyongthon-team13/BE)
- [계정·어르신 정보·보호자 연결·알림 API](https://github.com/yongyongthon-team13/BE/pull/3) · [문자 인증 후 로그인 상태 유지](https://github.com/yongyongthon-team13/BE/pull/7) · [문자 발송 서비스 연동](https://github.com/yongyongthon-team13/BE/pull/9)

### Replay · 개인 프로젝트

**역할:** 화면 및 서버 API 연동<br>
**기술:** React, TypeScript, Next.js

계좌 현황을 조회하는 화면을 만들고, 서버에서 토스증권 Open API를 호출하도록 구성했습니다. API 인증정보 누락과 허용 IP 문제를 확인하며 연동 문제를 해결했습니다. [소스 코드와 실행 방법](https://github.com/doyeong2002/replay-investing)

### 해외여행 다통화 환전·결제 DB · 팀 프로젝트

**역할:** 데이터 관계 설계와 조회 SQL<br>
**기술:** MySQL, SQL, Flask

사용자, 원화 계좌, 외화 지갑, 트래블카드, 거래 내역의 관계를 설계하고 잔액·거래 조회 SQL을 작성했습니다. Flask 화면에서 조회 결과를 확인했습니다. [공개용 SQL과 프로젝트 설명](https://github.com/doyeong2002/travelpay-db)

### LG Aimers 9기 해커톤 · 팀 프로젝트

**역할:** 결측치 확인과 데이터 전처리 참여<br>
**기술:** Python

투구 제구 성공 확률 예측 과제에 참여했습니다. 제공된 베이스라인을 바탕으로 파생변수, 모델 학습·앙상블, 시간순 검증 등을 개선하는 과정에는 AI 도구의 코드 작성·수정 지원을 활용했습니다. 대회 데이터와 학습된 모델을 제외한 [코드와 작업 설명](https://github.com/doyeong2002/lg-aimers-pitch-prediction)을 공개했습니다. [데이콘 코드 공유 글](https://dacon.io/competitions/official/236743/codeshare/14200)
