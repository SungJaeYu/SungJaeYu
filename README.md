### Hi, I'm SungJae Yu 👋

**Flight Software Test & Verification Engineer @ ROKAF**  
안전필수 항공 임베디드 SW · C/C++ · 테스트/검증 · AI 응용

---

공군에서 전투기 탑재 소프트웨어의 **개발과 테스트·검증**을 담당해 왔습니다.  
비행 SW 엔지니어에서 테스트 엔지니어, 테스트 매니저로 역할을 넓히며
**요구사항 → 구현 → 시험 → 검증**이 연결되는 안전필수 소프트웨어 개발 과정을 경험했습니다.

현재는 방산·항공 SW 분야로의 전직을 준비하며, 실제 업무 경험과 연결되는
**임베디드 / 항공 계산 코어 / HIL / 검증 자동화** 프로젝트를 만들고 있습니다.

## Representative Projects

### [radar-track-fcc-hil](https://github.com/SungJaeYu/radar-track-fcc-hil)
**STM32 + Zephyr 기반 레이더 트래킹 HIL 시스템**  
PC 레이더 시뮬레이터와 STM32 FCC 역할의 임베디드 애플리케이션을 UART로 연결하고,
프레이밍·CRC·ISR·링버퍼·RTOS 메시지 처리부터 트래킹 및 정량 검증까지 구현하는 프로젝트입니다.

### [geodesy-wasm](https://github.com/SungJaeYu/geodesy-wasm)
**C++17 전술 좌표 / 지오데시 계산 엔진 + WebAssembly**  
GeographicLib 기반 geodesic 계산, Bullseye/BRAA, 레이더 기하, dead reckoning 등을 구현했으며,
요구사항(HLR)과 36개 known-answer GoogleTest를 추적 연결했습니다.

### [flightdyn-wasm](https://github.com/SungJaeYu/flightdyn-wasm)
**Header-only C++17 비행역학 계산 코어 + WebAssembly**  
Strongly-typed units, ISA atmosphere, CAS/EAS/TAS, attitude, wind triangle을 구현하고
요구사항 기반 테스트와 CI로 검증합니다. Bare-metal 이식을 고려해 heap/exceptions 없이 설계했습니다.

### [do-178c-skill](https://github.com/SungJaeYu/do-178c-skill)
**DO-178C / ED-12C 산출물 작성·검토용 Agent Skill**  
PSAC/SDP/SVP 등 계획 문서, 요구사항·추적성·시험 산출물, DAL별 objective review를
DO-178C의 objective 중심으로 다루도록 구성했습니다.

## AI / Retrieval

### [llamaindex_korbm25](https://github.com/SungJaeYu/llamaindex_korbm25)
2024년 **공군 해커톤(AI 프로그램)** 참가 프로젝트의 RAG 검색 개선 과정에서 개발한
LlamaIndex 호환 한국어 BM25 Retriever입니다. Okt/Kkma/Kiwi 형태소 분석을 적용했으며,
해당 해커톤 프로젝트는 **장려상**을 수상했습니다.

## Strengths

- **Safety-critical / Embedded SW** — C/C++, RTOS, 임베디드 개발, 테스트·검증
- **Aerospace domain** — 항법·레이더·비행 SW 관련 계산 및 시험 도메인
- **Requirements & Verification** — 요구사항 기반 설계, 추적성, 자동화 테스트, HIL
- **AI/ML application** — RAG, ML/RL/DL, AI 도구를 활용한 개발·검증 자동화

## Tech

`C` `C++17` `Python` `STM32` `Zephyr RTOS` `WebAssembly` `GoogleTest` `CMake` `GitHub Actions` `ML/RL/DL`

## Links

- 💼 [LinkedIn](https://www.linkedin.com/in/sungjae-yu-582b95203/)
