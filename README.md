# Jossi02

Linux와 시스템·인프라 운영을 중심으로 공부하며, 직접 구성하고 검증하는 과정을 기록하고 있습니다.

로그와 시스템 상태를 근거로 문제 원인을 좁히고, 반복 작업을 자동화하며, 운영 안정성과 보안 경계를 명확히 하는 데 관심이 있습니다.

## Focus

**Systems / Operations**  
Linux · System Administration · Infrastructure Operations · Automation · Security

**Implementation Tools**  
Python · Bash · PowerShell · Docker · systemd · GitHub Actions

## Featured Projects

### [Naver Restock Monitor](https://github.com/Jossi02/naver-restock-monitor)

네이버 브랜드스토어의 재입고 상태를 확인하고 Discord·Telegram으로 알림을 전송하는 Python 모니터입니다.

Persistent state, retry와 pending delivery, HTTP 429 cooldown, graceful shutdown, single-instance lock을 다루며 Docker·systemd 실행 구성을 제공합니다. 현재 100개 자동 테스트와 GitHub Actions로 검증 범위를 기록하고 있습니다.

### [Server Security Check Automation](https://github.com/Jossi02/server-security-check-automation)

KISA 2021 수업 가이드를 바탕으로 Linux·Windows 서버 보안 점검을 Bash와 PowerShell로 구현한 2인 팀 프로젝트입니다.

탐지와 조치의 경계를 구분하고, 위험한 시스템 변경은 미실행 범위로 명시했습니다. 비파괴 fixture 테스트와 CI로 파싱·탐지·정적 분석 범위를 검증했습니다.

### [Embedded Linux System Programming](https://github.com/Jossi02/embedded-linux-system-programming)

2인 Embedded System coursework에서 수행한 Linux system programming 프로젝트의 fork입니다.

GPIO interrupt, kernel timer, character device driver, PIR sensor와 user/kernel communication을 다뤘으며, 수업 당시 hardware validation과 이후 portfolio hardening 검증을 구분해 기록했습니다.

## Other Projects

- [PickDream](https://github.com/Jossi02/pickdream-classroom-reservation) — 2025년 대학 기초캡스톤 팀 프로젝트를 fork한 뒤, Firebase 예약 시스템의 concurrency, idempotency, authorization boundary를 보강하고 emulator tests로 검증
- [KoJa](https://github.com/Jossi02/chrome-jlpt-word-replacer) — Chrome MV3 기반 JLPT 학습 확장으로, deterministic DOM 처리와 사전 build pipeline을 39개 테스트와 CI로 검증
- [HealthMate](https://github.com/Jossi02/healthmate-ai-healthcare) — 2026년 대학 심화캡스톤 팀 프로젝트로, LangGraph·FastAPI 기반 AI 건강 코칭 시스템 개발과 연구에 참여
- [Android Sudoku Coursework](https://github.com/Jossi02/android-sudoku-generator) — instructor-provided board generator를 활용한 Android Java coursework

## Research & Collaboration

- HealthMate 논문 집필과 제1저자로 참여했으며, 한국정보기술학회 논문 경진대회에서 팀 연구 성과로 은상을 수상했습니다.
- 팀 프로젝트, coursework, fork 이후 maintenance와 AI-assisted 작업의 범위는 각 repository README에서 구분해 기록했습니다.

## Tech

- **Systems / Operations:** Linux, systemd, Docker
- **Programming / Automation:** Python, Bash, PowerShell, C
- **Systems Programming:** Linux kernel modules, GPIO, character devices
- **Services / Tooling:** GitHub Actions, Firebase, Firestore, Cloud Functions
