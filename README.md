# Hi, I’m Sungjae Yu

**Avionics & Embedded Software Engineer**  
C/C++ · RTOS · Real-Time Systems · Hardware/Software Integration

[Portfolio & Engineering Blog](https://sungjae-blog.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/sungjae-yu-582b95203/)

I develop aircraft software, build engineering tools, and work on integration with real hardware.

My experience includes C/VxWorks-based avionics development, C++/MFC tools for running and debugging software before hardware integration, and aircraft software integration and operational evaluation.

I approach software with safety and maintainability in mind: predictable behavior, clear interfaces, explicit error handling, and changes that can be understood and verified.

## Selected Projects

### [Radar Tracking Bench](https://github.com/SungJaeYu/radar-tracking-bench)

**C · STM32F746G-DISCO · Zephyr RTOS · Python — V1 completed November 19, 2026**

A hardware-in-the-loop testbed for single-target tracking. A PC sends synthetic range and azimuth measurements to an STM32, then compares the returned estimates with known ground truth.

**Implementation**

- UART ISR, ring buffer, CRC-16 framing, and RX/processing/TX threads connected by bounded message queues.
- Constant-velocity Kalman filters, fixed gating, and track acquisition, coasting, and loss handling.
- Recovery from corrupted or incomplete frames, communication interruptions, and buffer or queue saturation.
- PC tools for scenario generation, visualization, CSV recording, and quantitative evaluation.

**Recorded board results**

- A 30-minute load run matched all **89,990 measurements** with responses.
- PC round-trip latency: **p99 8.049 ms**, maximum **34.894 ms** in that run.
- Completed **100 noise-evaluation runs** and passed **49/49 spike-recovery cases**.

The load run used a stationary target with zero noise, a target measurement rate of 50 Hz, and UART at 115200 baud. Round-trip latency includes the host, USB/UART, and board; it is not MCU execution time alone. Noise and spike evaluations were separate runs.

**My contribution:** problem definition, architecture, validation criteria, and STM32/Zephyr firmware. I used AI coding tools for the PC simulator, GUI, and test-support implementation.

[Architecture](https://github.com/SungJaeYu/radar-tracking-bench/blob/main/EXPLAINER.en.md) · [Board Results](https://github.com/SungJaeYu/radar-tracking-bench#board-results) · [Scope & Roadmap](https://github.com/SungJaeYu/radar-tracking-bench/blob/main/docs/roadmap.md)

### [Korean BM25 Retriever](https://github.com/SungJaeYu/llamaindex_korbm25)

**Python · LlamaIndex · Korean NLP**

A custom retriever developed while working on a RAG project for the 2024 ROKAF Hackathon.

After observing reduced retrieval performance with the existing BM25 implementation, I implemented an Okt-based Korean BM25 retriever compatible with LlamaIndex.

This repository contains the retrieval component, rather than the entire competition system. The team project received an **Encouragement Award in the AI Programming category**.

### [Wingman Review](https://wingman-review.vercel.app/)

**Rule-Based Analysis · RAG · LLM — Hackathon Prototype**

An AI-assisted flight debriefing prototype that connects detected deviations with supporting references and explanations.

- Rule-based logic handles quantitative assessment.
- RAG retrieves supporting reference material.
- An LLM drafts explanations for human review.

**My contribution:** problem definition, requirements, system architecture, and review and refinement of AI-assisted implementation.

Built with synthetic flight data and fictional reference documents. It is a prototype, not an operationally deployed system.

**Award:** Encouragement Award, Open Category, 8th ROKAF Hackathon — November 18, 2026, Team AutoNix.

## Professional Background

**Republic of Korea Air Force · June 2020–Present**

- **Aircraft software development:** training-mode logic, cockpit display functions, defect fixes, and unit-level verification in C on VxWorks.
- **Engineering tools:** C++/MFC PC test tools and Python utilities for data checks and repetitive engineering tasks.
- **Integration and evaluation:** avionics interfaces, defect investigation, resource-usage analysis, and operational evaluation with pilots and maintenance personnel.
- **Technical training:** internal courses in Python, AI, C++, and software engineering.

More detailed experience and project write-ups are available on my [portfolio](https://sungjae-blog.vercel.app/).

## Technologies

| Area | Experience |
|---|---|
| Languages & tools | C, C++, Python, MFC |
| Embedded systems | VxWorks, Zephyr, STM32, UART |
| Avionics & integration | MIL-STD-1553, hardware/software interfaces, resource analysis |
| AI projects | LlamaIndex, Korean BM25/RAG, image instance segmentation, reinforcement learning experiments |

I’m extending this foundation toward AI deployment on physical systems, with a focus on latency, resource constraints, and reliable execution.

## Engineering Tools

[do-178c-skill](https://github.com/SungJaeYu/do-178c-skill) — An agent skill for drafting and reviewing requirements, traceability, and verification artifacts. This is a workflow tool, not evidence of certification experience.
