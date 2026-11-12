### Hi, I'm SungJae Yu 👋

**Avionics & Embedded Software Engineer**  
C/C++ · 실시간 탑재 소프트웨어 · 장비 인터페이스 · AI 응용

[Portfolio & Blog](https://sungjae-blog.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/sungjae-yu-582b95203/)

---

공군에서 **VxWorks/C 기반 항공기 탑재 SW 개발과 실장비 통합·시험평가**를 경험했습니다.
훈련모드 내부 로직과 시현 기능을 개발하고, C++/MFC 기반 PC 도구로 실제 장비 투입 전 기능을 확인하는 환경을 만들었습니다.

요구사항을 코드로 구현하고, 장비 인터페이스와 운용환경에서 발생하는 결함까지 추적하는 개발에 관심이 있습니다.
현재는 **STM32·Zephyr 기반 센서 트래킹 HIL**을 개발하며 통신·스레드·추적·오류 복구를 연결하고 있습니다.
항공·임베디드 경험을 기반으로 AI를 실제 시스템에 적용하고, 실시간 실행과 추론 성능을 다루는 방향으로 역량을 확장하고 있습니다.

## Selected Projects

### [Radar Track FCC HIL](https://github.com/SungJaeYu/radar-track-fcc-hil)
**C · STM32F746G-DISCO · Zephyr RTOS · Python | 개발 중**

PC의 합성 레이더 측정값을 STM32로 보내 단일표적 추적과 통신 오류 복구를 확인하는 HIL 테스트 환경입니다.

- UART ISR·링버퍼·CRC-16 프레임 파서와 RX → 처리 → TX 메시지 큐·스레드 구조
- 거리·방위각 CV 칼만 필터, 게이팅, 트랙 상태 관리 및 무수신 timeout
- PC 시뮬레이터·GUI, C/Python 호스트 테스트, 요구사항 추적표와 실보드 시험 기록
- 정상 수신·오류 후 복귀·중지/재시작 등을 보드에서 확인했으며, **추정값 반환·폐루프 정확도 평가·TX 실보드 검증은 진행 예정**

핵심 수신·파싱 코드를 단계별로 직접 구현·점검하며 확장하고 있습니다.
문제정의·인터페이스·검증 기준을 정하고 AI 코딩 도구를 구현과 리뷰에 활용합니다.

### [Wingman Review](https://github.com/SungJaeYu/wingman-review)
**규칙 기반 분석 · RAG · LLM | 합성 데이터 기반 프로토타입** · [Demo](https://wingman-review.vercel.app/)

비행훈련 과정의 이탈을 탐지하고, 근거와 함께 설명하는 AI 디브리핑 데모입니다.

- 정량 판단은 규칙 엔진, 근거 검색은 RAG, 설명 초안은 LLM, 최종 확인은 사람이 담당하도록 설계
- AI 응답 검증과 규칙 기반 설명으로의 폴백을 포함한 검토 흐름
- 담당: 현업 문제정의, 요구사항·역할 분리 설계, 데모 검토·개선 — 구현에 AI 코딩 도구 활용
- **2026 제8회 공군 해커톤 자유공모 부문 장려상 선정**

공개 데모는 합성 비행자료·합성 훈련자료를 사용하며, 실제 운용 시스템과 구분합니다.

### [Korean BM25 Retriever](https://github.com/SungJaeYu/llamaindex_korbm25)
**Python · LlamaIndex · BM25 | 2024 해커톤 개발 기록**

한국어 RAG에서 발생한 검색 문제를 해결하기 위해 **Okt 형태소 분석을 적용한 LlamaIndex 호환 검색기를 직접 구현**했습니다.
2024 제6회 공군 해커톤 AI 프로그램 부문 장려상 수상 프로젝트의 검색 구성요소이며, 당시 문제 해결 과정을 기록한 저장소입니다.

기타 공개 도구: [do-178c-skill](https://github.com/SungJaeYu/do-178c-skill) — 요구사항·추적성·시험 산출물 작성·검토를 돕는 Agent Skill.

## Experience

**Republic of Korea Air Force · 2020.06 ~ Present**

### Avionics Software Development · 2020.06 ~ 2022.12
- VxWorks/C 기반 실시간 탑재 SW의 훈련모드 내부 로직·시현 기능 개발 및 결함 수정
- C++/MFC 기반 PC 테스트 도구 제작으로 통합시험 전 로직 실행·변수 확인·디버깅 지원
- 요구사항·설계 산출물 작성, 코드 검토 및 단위시험
- MIL-STD-1553 운용데이터 추출·메시지 검증과 Python 데이터 점검·전처리 도구 개발

### Software Integration & Verification · 2022.12 ~ Present
- 항공 SW 통합·운용시험과 임무·항법·통신 장비 인터페이스 검증
- 결함 재현·분석, 변경 영향 확인, 수정 SW 재시험·회귀검증
- CPU·메모리·통신 자원 사용량 측정·분석과 요구사항 기반 시험 산출물 작성
- 조종사·정비인원·개발자와 시험 준비 및 현장 결함 대응 협업
- 시험평가 총괄 업무 대리(2024.12 ~ 2025.06): 기종별 일정·자원 조율 및 결과 종합

### AI & Technical Education
- 강화학습 기반 항공 시뮬레이션 항적 개선 연구
- 이미지 인스턴스 분할 모델 비교·실험, 한국어 RAG 검색기 개발
- 군수·정비 데이터 기반 AI 적용 자문 및 폐쇄망 LLM 활용 검토
- 공군 AI 역량강화 교육·C++ 교육 교관 및 SW공학 강의

## Tech & Focus

| 구분 | 경험·기술 |
| --- | --- |
| 실무 개발·도구 | C, C++, Python, VxWorks, MFC |
| 탑재 시스템·통합 | MIL-STD-1553, 장비 인터페이스, 결함 분석, 자원 사용량 분석 |
| 현재 개인 프로젝트 | STM32, Zephyr RTOS, UART, 상태기계, 메시지 큐, 칼만 필터, HIL |
| AI 프로젝트 경험 | LlamaIndex, 한국어 BM25/RAG, 이미지 인스턴스 분할, 강화학습 |
| 확장 방향 | Modern C++, 실시간 AI 시스템, 추론 성능 최적화 |

## Awards & Certifications

- 제8회 공군 해커톤 **자유공모 부문 장려상 선정** — Wingman Review (2026, 시상식 전)
- 공군 AI 역량강화 교육 우수교관 (2025)
- 제6회 공군 해커톤 AI 프로그램 부문 장려상 (2024)
- 제5회 공군 해커톤 AI 프로그램 부문 최우수상 (2023)
- 항공무기체계 SW 학술연구 발표대회 우수상 (2022)
- 빅데이터분석기사 · ISTQB® Foundation Level · ADsP · 정보처리기사
- TOEIC 900
