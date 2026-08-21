<p align="center">
  <img width="100%" alt="Eunyoung Choi GitHub profile banner" src="https://github.com/user-attachments/assets/9179d199-dcba-434e-a12e-3249647d9d95" />
</p>

<h1 align="center">최은영 · Eunyoung Choi</h1>

<p align="center">
  프론트엔드에서 시작해 API 응답과 데이터 처리 과정까지 확인하는 개발자입니다.<br/>
  운영 중 발견한 문제를 재현하고, 실제로 사용할 수 있는 개선으로 만드는 일을 좋아합니다.
</p>

<p align="center">
  <a href="https://eunyoung-study.tistory.com/"><img src="https://img.shields.io/badge/Tech_Blog-FF5A4A?style=flat-square&logo=tistory&logoColor=white" alt="Tistory" /></a>
  <a href="mailto:kate3818@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=flat-square&logo=naver&logoColor=white" alt="Email" /></a>
</p>

---

## About

Angular·TypeScript 기반 웹서비스를 개발하고 운영해 왔습니다. 화면에서 오류가 발생하면 UI 코드만 수정하기보다 브라우저 요청과 API 응답을 함께 살펴 원인을 찾습니다.

자산관리 서비스에서는 단일 API 요청 제한으로 일부만 표시되던 약 12만 건의 데이터를 페이지 단위로 호출하고 병합하도록 개선했습니다. 최근에는 React 기반 상패 추천 시스템의 질문 흐름과 화면을 구현해 실제 쇼핑몰에 적용했습니다.

AI 도구는 반복 코드 작성, 디버깅, 문서 정리에 활용합니다. 생성된 결과는 API 계약, 예외 처리, 화면 상태를 기준으로 직접 확인하고 수정합니다.

## Experience

### EMOTIONART · System Engineer

`2026.04 – 2026.08`

- 용도·소재·예산을 묻는 7단계 상패 추천 화면과 사용자 흐름 기획
- React·JavaScript UI 구현 및 FastAPI·PostgreSQL 운영 데이터 연동
- 결과가 부족할 때 조건을 단계적으로 완화하고 점수순으로 정렬하는 방식 적용
- 관리자 상품 매핑 화면 구현 및 실제 쇼핑몰 적용
- Cafe24·Ecount·ChannelTalk을 활용한 주문·상담 업무 개선

### GYTNI · Web Developer

`2022.03 – 2024.10`

- Angular·TypeScript 기반 자산관리 웹서비스 개발 및 운영
- 페이지 반복 호출과 응답 병합으로 약 12만 건의 자산 데이터 조회 누락 해결
- 자산관리 데이터 마이그레이션 및 상태 관리 기능 추가
- 모바일 근태 기능의 주요 화면과 API 흐름을 웹으로 전환
- 기존 KNOX SSO 연동 오류 재현 및 수정

## Projects

### OpenTripPlanner

지역·날짜·이동수단을 입력하고 추천 장소를 선택해 지도와 일정표로 확인하는 여행 일정 서비스입니다.

- React Native·Expo 기반 입력, 추천, 일정 확인 화면 구현
- Context API로 인증·세션·장소·네트워크 상태 공유
- 여러 요청에서 401 오류가 동시에 발생해도 토큰 갱신을 한 번만 수행하도록 처리
- 회의록을 정리하고 번역해 다국적 팀원과 공유

[Frontend](https://github.com/Team-Y-FI/OpenTripPlanner-Front) · [Backend](https://github.com/Team-Y-FI/OpenTripPlanner-Backend)

`React Native` `Expo` `TypeScript` `Node.js` `Express` `MySQL`

### Mongle · 몽글몽글

반려동물 프로필, 일정, 병원·보호소 검색, 커뮤니티와 AI 건강 상담을 제공하는 웹서비스입니다.

- 프로필·캘린더·동물 사전·위치 검색·커뮤니티·AI 상담 화면 구현
- 공개 화면과 인증이 필요한 화면을 분리하고 Axios 기반 오류 처리
- FormData 이미지 업로드 과정의 Content-Type boundary 충돌 수정
- 전체 기능을 테스트하며 약 26개 QA 이슈 확인 및 수정
- Claude·Cursor를 활용하고 결과를 검토해 담당 화면 구현 기간을 약 4~5일에서 2일로 단축

[Frontend](https://github.com/mongle-project/front) · [Backend](https://github.com/mongle-project/back)

`React` `Vite` `Axios` `Node.js` `Express` `MySQL` `AWS S3` `OpenAI API`

### 조건 기반 상패 추천 시스템

고객의 답변과 운영 상품 데이터를 연결해 조건에 맞는 상패 5개를 보여주는 추천 기능입니다.

- 7단계 질문 화면과 추천 결과 UI 구현
- 답변을 운영 DB 코드로 변환해 상품을 필터링하고 점수순으로 정렬
- 일치하는 상품이 부족할 때 일부 조건을 단계적으로 완화
- 관리자가 추천 상품의 매핑 정보를 변경할 수 있는 화면 구현

`React` `JavaScript` `FastAPI` `PostgreSQL`

## Skills

| 구분 | 경험 기술 |
| --- | --- |
| Frontend | Angular, TypeScript, React, React Native, JavaScript, HTML/CSS |
| Backend / API | Java, Spring, Node.js, Express, FastAPI, Axios |
| Database / Data | MySQL, PostgreSQL, MongoDB, Oracle, Python, Pandas |
| DevOps / Collaboration | Git, GitHub, GitLab, Jenkins, Jira, Redmine, Slack, Notion |
| AI / Tools | OpenAI API, Gemini API, Claude, Cursor, ChannelTalk, Figma |

## Learning & Writing

- K-디지털트레이닝 AI 영상 객체 탐지 개발 양성과정 수료
- Python 데이터 처리, 객체 탐지 및 AI API 웹서비스 연동 프로젝트 수행
- 개발하며 확인한 개념과 문제 해결 과정을 [기술 블로그](https://eunyoung-study.tistory.com/)에 기록

---

<p align="center">
  오류의 원인을 끝까지 확인하고, 운영에 남는 개선을 만들겠습니다.
</p>
