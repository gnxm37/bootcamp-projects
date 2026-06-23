# 📁 Portfolio · 부트캠프 & 초기 프로젝트 모음

부트캠프 시기에 진행한 학습·팀 프로젝트와 기획 문서를 모아 둔 저장소입니다.
Java/Spring 기반 웹 애플리케이션부터 Python 데이터 수집까지, 백엔드를 익혀 나가던 과정을 담고 있습니다.

> 📌 현재(2025~) 실무 백엔드 작업은 별도 포트폴리오에 정리되어 있습니다 — [github.com/gnxm37](https://github.com/gnxm37)

---

## 🗂️ 프로젝트

### [📞 phonebook](./phonebook) · 개인
로그인·검색이 있는 전화번호부 CRUD 웹 애플리케이션
- **기술** — Spring Boot · JSP · MVC · SQL
- 회원가입·로그인 필터, 연락처 등록/수정/삭제/검색, MVC 기반 화면 구성
- 📹 데모 영상 포함

### [💹 trading-web](./trading-web) · 팀
3초 주기로 갱신되는 실시간 주식 차트 + 뉴스·거래 대시보드
- **기술** — Spring Boot · MariaDB · JavaScript 차트
- 클라우드로 증권·뉴스 데이터 수집 → DB 저장 → 실시간 그래프·뉴스 리스트 표시
- 📹 데모 영상 포함

### [📰 news](./news) · 데이터 수집
뉴스·금융 데이터 수집 및 Redis pub/sub 파이프라인 (`trading-web` 연계)
- **기술** — Python · Redis · Jupyter
- 수집 데이터를 Redis 채널로 발행/구독해 실시간 전달

> 각 프로젝트 폴더의 `README.md`에 실행 영상 · 환경 설정 · 동작 방식 · 회고가 정리되어 있습니다.

---

## 📄 기획 · 발표 문서

| 문서 | 설명 |
|---|---|
| `일릭서_아이디어개발기획서_2023-11-01.pdf` | 아이디어 구상 · 개발 방향 · 필요 기능을 정리한 기획서 |
| `trading-web_발표자료.pdf` | `trading-web` · `news` 팀 프로젝트 발표 자료 |

---

## 🛠️ 사용 기술 한눈에

`Java` · `Spring Boot` · `JSP` · `MariaDB` · `JavaScript` · `Python` · `Redis` · `Bootstrap`
