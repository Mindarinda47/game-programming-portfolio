# Game Programming Portfolio 이종민 Jong Min Lee

Unity 게임플레이와 멀티플레이 네트워크 프로젝트를 중심으로, C 네트워크·운영체제·임베디드 기반 경험을 함께 정리한 포트폴리오 허브입니다. 각 저장소에서 구현 코드, 담당 범위와 문제 해결 과정을 확인할 수 있습니다.

## Featured Game Projects

### 1. VR 재난 시뮬레이션

**Unity · C# · Netcode for GameObjects · XR · Vivox**

PC 관제자와 VR 참가자를 연결하는 3인 팀 프로젝트입니다. Host/Client 연결, 플레이어 생성과 Ownership 이전, 위치 동기화, 관제 상호작용과 음성 기능 연동을 담당했습니다.

[Repository](https://github.com/Mindarinda47/vr-disaster-networking-portfolio) · [시연 영상](https://www.youtube.com/watch?v=iOX_i1il5Sw) · [담당 범위](https://github.com/Mindarinda47/vr-disaster-networking-portfolio/blob/main/docs/contribution.md) · [대표 코드](https://github.com/Mindarinda47/vr-disaster-networking-portfolio/tree/main/src/networking)

### 2. Unity 2D RPG Gameplay Systems

**Unity 6 · C# · ScriptableObject · JSON · 2D Physics**

탐색, 전투, NPC 대화, 퀘스트, 인벤토리와 저장·불러오기를 하나의 플레이 흐름으로 연결한 개인 프로젝트입니다. 상태 전이와 시스템 간 데이터·UI 동기화에 중점을 두었습니다.

[Repository](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems) · [설계](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems/blob/main/Docs/ARCHITECTURE.md) · [문제 해결](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems/blob/main/Docs/PROBLEM_SOLVING.md) · [대표 코드](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems/tree/main/Assets/Scripts)

### 3. Website Escape Game

**React · TypeScript · Canvas · Local Storage**

퍼즐, 아이템, 저장 상태와 Canvas 기반 미니게임을 연결한 1인 웹 방탈출 게임입니다. 게임 규칙과 상태 전이, 힌트 난이도와 플레이 흐름을 조정하고 자동화 테스트로 핵심 동작을 검증했습니다.

[Repository](https://github.com/Mindarinda47/website-escape-game-portfolio) · [Play](https://mindarinda47.github.io/website-escape-game/)

## Computer Science & Systems

### 4. C Multi-client Room Chat

**C · TCP Socket · `select` · Protocol Framing**

TCP stream framing, partial send, 다중 클라이언트와 방 상태 관리를 구현하고 단위·통합 테스트로 검증한 네트워크 프로그래밍 사례입니다.

[Repository](https://github.com/Mindarinda47/c-network-room-chat)

### 5. xv6 Kernel Extensions

**C · xv6 · System Call · Scheduler · Virtual Memory**

시스템 콜, nice 기반 우선순위 스케줄링, FCFS와 page fault 기반 lazy allocation을 구현한 운영체제 과제·재검증 사례입니다.

[Repository](https://github.com/Mindarinda47/xv6-kernel-extensions)

### 6. STM32 Halli Galli

**Embedded C · STM32F10x · GPIO · Sensor Integration**

센서 입력, LCD·Bluetooth 출력과 게임 상태를 통합한 4인 팀 프로젝트입니다. 보존된 코드 범위 안에서 하드웨어 통합, 디버깅과 협업 경험을 설명합니다.

[Repository](https://github.com/Mindarinda47/stm32-halli-galli-system)

## Other Engineering Project

### 7. 붐비 — 부산 AI 혼잡 예보

**TypeScript · React · Rule Engine · AI Validation · API**

부산 주요 권역의 상대적 혼잡 가능성을 계산하는 1인 소프트웨어 프로젝트입니다. 규칙 기반 점수 엔진, AI 출력 범위 통제, 외부 데이터 파이프라인과 fallback 구조를 구현했습니다.

[Repository](https://github.com/Mindarinda47/boombi-ai-crowd-forecast)

## 역량 요약

### Unity 게임플레이 프로그래밍

- 퀘스트·대화·인벤토리·저장 시스템 연결
- 플레이어·적 전투 상태와 이벤트 기반 UI 동기화

### 게임 네트워크

- Host/Client 연결, 서버 주도 생성과 플레이어 소유권 이전
- RPC 기반 관제 상호작용, 위치 동기화와 PC·VR 역할 분리

### 시스템 기반

- C 소켓의 stream framing과 xv6 커널 실행 경로 구현
- STM32 센서·LCD·Bluetooth·게임 상태 통합 경로
