### Hi, I'm SungJae Yu 👋

**Flight Software Test Lead @ Republic of Korea Air Force**  
항공기 탑재 소프트웨어 개발 · 시험평가 · 실시간 임베디드 · AI/RAG

🌐 **Portfolio & Blog** — https://sungjae-blog.vercel.app/  
💼 **LinkedIn** — https://www.linkedin.com/in/sungjae-yu-582b95203/

---

공군에서 **항공기 탑재 소프트웨어 개발과 시험평가**를 수행하고 있습니다.
화력제어컴퓨터의 실시간 SW 개발에서 시작해, 현재는 **Test Lead**로서 탑재 SW 통합·검증과 운용시험평가를 담당하고 있습니다.

업무에서는 요구사항을 기준으로 설계·구현·시험 결과를 연결하고,
반복되는 시험·분석 업무는 C/C++·Python 기반 도구와 자동화로 개선해 왔습니다.
강화학습, LLM/RAG, 데이터셋 구축과 사내 AI 교육도 함께 경험했습니다.

## Experience

### Test Lead · Test & Verification · 2022.12 ~ Present
- 항공기 탑재 SW 통합·검증 및 운용시험평가
- 유도무장, 항법장비(EGI), 데이터링크, 무선 등 탑재 장비 연동 시험
- 결함 분석·재시험·회귀시험, CPU·메모리·MUX 자원 사용률 측정
- 요구사항 기반 시험 절차 및 시험 산출물 작성
- 프로젝트별 시험 일정·자원 조율 및 결과 종합

### Flight Software Development · 2020.06 ~ 2022.12
- 항공기 화력제어컴퓨터 실시간 SW 개발
- 무장 투하 이벤트, 공대공 미사일 훈련 모드 및 HUD 시현 로직 구현
- 데이터링크·무선 제어 코드 분석/수정, MIL-STD-1553 운용 데이터 검증

### AI & Education
- 강화학습 기반 항공기 시뮬레이터 항적 개선 연구
- 폐쇄망 LLM/RAG 적용 검토 및 AI·데이터셋 구축 관련 업무
- 공군 AI 역량강화 교육 및 C++ 교육 교관

## Selected Projects

### [radar-track-fcc-hil](https://github.com/SungJaeYu/radar-track-fcc-hil)
**STM32 + Zephyr 기반 레이더 트래킹 HIL 시스템 — 개발 중**  
PC 레이더 시뮬레이터와 STM32를 UART로 연결해 실시간 프레이밍·CRC·ISR·링버퍼·RTOS 메시지 처리와 트래킹 검증 환경을 구현하고 있습니다.

### [flightdyn-wasm](https://github.com/SungJaeYu/flightdyn-wasm)
**Header-only C++17 비행역학 계산 코어 + WebAssembly**  
Strongly-typed units, ISA atmosphere, CAS/EAS/TAS, attitude, wind triangle을 구현하고 요구사항 기반 테스트와 CI로 검증합니다.

### [geodesy-wasm](https://github.com/SungJaeYu/geodesy-wasm)
**C++17 전술 좌표 / 지오데시 계산 엔진 + WebAssembly**  
GeographicLib 기반 geodesic, Bullseye/BRAA, 레이더 기하, dead reckoning을 구현하고 HLR과 36개 known-answer GoogleTest를 추적 연결했습니다.

### [do-178c-skill](https://github.com/SungJaeYu/do-178c-skill)
**DO-178C / ED-12C 산출물 작성·검토용 Agent Skill**  
요구사항·추적성·시험 산출물과 DAL별 objective review를 DO-178C의 objective 중심으로 다루도록 구성했습니다.

### [llamaindex_korbm25](https://github.com/SungJaeYu/llamaindex_korbm25)
**LlamaIndex 호환 한국어 BM25 Retriever**  
2024년 공군 해커톤(AI 프로그램) 참가 프로젝트의 RAG 검색 개선 과정에서 개발했습니다. Okt/Kkma/Kiwi 형태소 분석을 적용했으며 해당 프로젝트는 장려상을 수상했습니다.

## Awards & Certification

- 공군 AI 역량강화 교육 우수교관 (2025)
- 제6회 공군 해커톤 AI 프로그램 부문 장려상 (2024)
- 제5회 공군 해커톤 AI 프로그램 부문 최우수상 (2023)
- 항공무기체계 SW 학술연구 발표대회 우수상 (2022)
- 빅데이터분석기사 · ISTQB® Foundation Level · ADsP · 정보처리기사
- TOEIC 900

## Tech

`C` `C++` `Python` `VxWorks` `MIL-STD-1553` `STM32` `Zephyr RTOS` `WebAssembly` `CMake` `GoogleTest` `GitHub Actions` `ML/RL` `LLM/RAG`
