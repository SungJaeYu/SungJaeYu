### Hi, I'm SungJae Yu 👋

**Flight Software Test Lead @ Republic of Korea Air Force**  
항공기 탑재 SW 개발 · 통합/검증 · 실시간 시스템 · AI/RAG

🌐 **Portfolio & Blog** — https://sungjae-blog.vercel.app/  
💼 **LinkedIn** — https://www.linkedin.com/in/sungjae-yu-582b95203/

---

컴퓨터공학 기반으로 **항공기 탑재 소프트웨어 개발과 통합·검증**을 수행해 왔습니다.
VxWorks/C 기반 실시간 탑재 SW의 기능 변경·추가와 결함 수정, 단위시험을 경험했고,
현재는 **Test Lead**로서 요구사항부터 통합시험·운용시험까지 개발과 검증을 연결하는 역할을 담당하고 있습니다.

개발과 시험 양쪽의 경험을 바탕으로 문제를 코드와 시스템 관점에서 함께 분석하며,
반복되는 시험·분석 업무는 C/C++·Python 기반 도구와 자동화로 개선해 왔습니다.
강화학습, LLM/RAG, 데이터셋 구축과 사내 AI·C++ 교육 경험도 있습니다.

## Experience

### Test Lead · Software Integration & Verification · 2022.12 ~ Present
- 항공기 탑재 SW 통합·검증 및 운용시험평가
- 임무·항법·통신 등 복수 탑재 시스템과의 연동 검증
- 요구사항 기반 시험계획·시험절차 및 검증 산출물 작성
- 결함 분석, 수정사항 확인, 재시험 및 회귀시험 수행
- 시험장비 기반 검증과 실제 운용환경 시험 지원
- 프로젝트별 시험 일정·자원 조율 및 결과 종합

### Avionics Software Development · 2020.06 ~ 2022.12
- VxWorks/C 기반 항공기 탑재 실시간 SW 기능 개발·변경
- 기존 시스템에 기능·함수·컴포넌트 추가 및 결함 수정
- 요구사항·설계 산출물 작성과 단위시험 수행
- 탑재 시스템 인터페이스 및 MIL-STD-1553 데이터 검증
- C++ 기반 PC 시뮬레이션 도구를 제작해 통합시험 전 선행 검증 환경 구축

### AI & Education
- 강화학습 기반 항공 시뮬레이션 로직 개선 연구
- 폐쇄망 LLM/RAG 적용 검토 및 데이터셋 구축 관련 업무
- 공군 AI 역량강화 교육 및 C++ 교육 교관

## Selected Projects

### [radar-track-fcc-hil](https://github.com/SungJaeYu/radar-track-fcc-hil)
**STM32 + Zephyr 기반 레이더 트래킹 HIL 시스템 — 개발 중**  
PC 시뮬레이터와 STM32를 연결해 실시간 프레이밍·CRC·ISR·링버퍼·RTOS 메시지 처리와 트래킹 검증 환경을 구현하고 있습니다.

### [flightdyn-wasm](https://github.com/SungJaeYu/flightdyn-wasm)
**Header-only C++17 비행역학 계산 코어 + WebAssembly**  
Strongly-typed units, ISA atmosphere, CAS/EAS/TAS, attitude, wind triangle을 구현하고 요구사항 기반 테스트와 CI로 검증합니다.

### [geodesy-wasm](https://github.com/SungJaeYu/geodesy-wasm)
**C++17 지오데시 계산 엔진 + WebAssembly**  
GeographicLib 기반 geodesic, 좌표 변환, 방위·거리 계산, dead reckoning을 구현하고 known-answer test로 검증합니다.

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

`C` `C++` `Python` `VxWorks` `MIL-STD-1553` `STM32` `Zephyr RTOS` `WebAssembly` `CMake` `GoogleTest` `GitHub Actions` `HIL` `ML/RL` `LLM/RAG`
