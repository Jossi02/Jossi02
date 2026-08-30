# Jossi02

Linux와 시스템·인프라 운영을 중심으로, 서버와 서비스를 직접 구성하고 검증하며 문제를 해결한 경험을 정리하고 있습니다.

로그와 시스템 상태를 근거로 원인을 좁히고, 반복 작업을 자동화하며, 실행한 검증과 미검증 범위를 구분해 기록하는 것을 중요하게 생각합니다.

## Focus

**Systems / Operations**  
Linux · System Administration · Infrastructure Operations · Automation · Security

**Implementation Tools**  
Python · Bash · PowerShell · Docker · systemd · GitHub Actions

## Featured Projects

### [Naver Restock Monitor](https://github.com/Jossi02/naver-restock-monitor)

네이버 브랜드스토어의 재입고 상태를 확인하고 Discord·Telegram으로 알림을 전송하는 Python 모니터입니다.

장시간 실행되는 모니터링 서비스의 상태 보존, 알림 실패 재시도, rate limit 대응, graceful shutdown을 다뤘으며, Docker·systemd 실행 구성과 100개 자동 테스트·GitHub Actions로 검증 범위를 관리했습니다.

### [Server Security Check Automation](https://github.com/Jossi02/server-security-check-automation)

KISA 2021 수업 가이드를 바탕으로 Linux·Windows 서버 보안 점검을 Bash와 PowerShell로 구현한 2인 팀 프로젝트입니다.

탐지와 조치의 경계를 구분하고, 위험한 시스템 변경은 미실행 범위로 명시했습니다. 비파괴 fixture 테스트와 CI로 파싱·탐지·정적 분석 범위를 검증했습니다.

### [Embedded Linux System Programming](https://github.com/Jossi02/embedded-linux-system-programming)

2인 Embedded System coursework에서 수행한 Linux system programming 프로젝트의 fork입니다.

GPIO interrupt, kernel timer, character device driver, PIR sensor와 user/kernel communication을 다뤘으며, 수업 당시 ES-101 hardware validation과 이후 코드 점검·미재시험 범위를 구분해 기록했습니다.

## Other Projects

- [PickDream](https://github.com/Jossi02/pickdream-classroom-reservation) — 2025년 대학 기초캡스톤 팀 프로젝트를 fork한 뒤, Firebase 예약 시스템의 concurrency·idempotency·authorization 개선을 검토·통합하고 emulator tests로 검증
- [KoJa](https://github.com/Jossi02/chrome-jlpt-word-replacer) — 3인 해커톤에서 만든 Chrome MV3 기반 JLPT 학습 확장으로, 이후 integration과 data build pipeline을 정리하고 39개 테스트와 CI로 검증
- [HealthMate](https://github.com/Jossi02/healthmate-ai-healthcare) — 2026년 대학 심화캡스톤 팀 프로젝트로, LangGraph·FastAPI 기반 AI 건강 코칭 시스템 개발과 연구에 참여
- [Android Sudoku Coursework](https://github.com/Jossi02/android-sudoku-generator) — instructor-provided board generator를 활용한 Android Java coursework

## Research & Collaboration

- HealthMate 논문 집필과 제1저자로 참여했으며, 한국정보기술학회 논문 경진대회에서 팀 연구 성과로 은상을 수상했습니다.
- 프로젝트별 README에서 팀·개인 기여 범위와 실제 검증 범위를 구분해 기록했습니다.

## Tech

- **Systems / Operations:** Linux · systemd · Docker · Bash · PowerShell
- **Automation / Programming:** Python · C
- **Systems Programming:** Linux kernel modules · GPIO · character devices
- **Tooling / Services:** GitHub Actions · Firebase · Firestore
