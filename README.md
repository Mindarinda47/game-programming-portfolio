# Game Programming Portfolio — 이종민

게임의 규칙과 플레이 흐름을 실제 시스템으로 구현하는 과정에 관심이 있습니다. Unity 게임플레이와 VR 네트워크 프로젝트를 중심으로 직접 만든 게임과 시스템 프로그래밍 작업을 정리했습니다.

## 주요 게임 프로젝트

### Unity 2D RPG Gameplay Systems

**Unity 6 · C# · ScriptableObject · JSON · 2D Physics**

탐색, NPC 대화, 퀘스트, 아이템, 전투, 보상과 저장·불러오기를 하나의 플레이 흐름으로 연결한 개인 프로젝트입니다. 시스템 사이의 상태 전달과 UI 동기화를 직접 구현했습니다.

[Repository](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems) · [설계](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems/blob/main/Docs/ARCHITECTURE.md) · [문제 해결](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems/blob/main/Docs/PROBLEM_SOLVING.md) · [대표 코드](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems/tree/main/Assets/Scripts)

### VR 재난 시뮬레이션

**Unity · C# · Netcode for GameObjects · XR · Vivox**

PC 관제자와 VR 참가자를 연결하는 3인 팀 프로젝트입니다. Host/Client 연결, 플레이어 생성과 소유권 이전, 위치 동기화, 관제 상호작용과 음성 기능 연동을 담당했습니다.

[Repository](https://github.com/Mindarinda47/vr-disaster-networking-portfolio) · [시연 영상](https://www.youtube.com/watch?v=iOX_i1il5Sw) · [담당 범위](https://github.com/Mindarinda47/vr-disaster-networking-portfolio/blob/main/docs/contribution.md) · [대표 코드](https://github.com/Mindarinda47/vr-disaster-networking-portfolio/tree/main/src/networking)

### Website Escape Game

**React · TypeScript · Canvas · Local Storage**

3일 동안 기획부터 완성한 1인 웹 방탈출 게임입니다. 전체 흐름과 규칙, 기능 우선순위를 정하고 Codex를 구현과 반복 수정에 활용했습니다.

[Repository](https://github.com/Mindarinda47/website-escape-game-portfolio) · [Play](https://mindarinda47.github.io/website-escape-game/)

## 진행 중인 프로젝트

### 2D Auto Battle / Instagram

**Godot · C# · Codex**

여러 작품의 캐릭터 특징을 하나의 2D 탑뷰 자동전투 규칙으로 옮겨, 관전 자체가 재미있는 대결 영상을 만드는 개인 프로젝트입니다. 캐릭터별 스킬, 공격 방식, 이동, 쿨타임과 전투 수치를 직접 정하고, Codex를 활용해 구현한 뒤 반복 플레이로 조정합니다.

완성한 전투는 Instagram Reels에 공개하고 있습니다. 2026년 10월 기준 팔로워 4,200명 이상이며, 단일 릴스 최고 160만 조회·12만 좋아요를 기록했습니다.

[Instagram 프로필](https://www.instagram.com/kunga.tan/) · [대표 Reel 1](https://www.instagram.com/reel/DdQ2jwJss-P/) · [대표 Reel 2](https://www.instagram.com/reel/Ddlj47TTFMh/)

등장 캐릭터의 원작 IP는 각 권리자에게 있습니다.

## CS 기반

### C Multi-client Room Chat

**C · TCP Socket · `select` · Protocol Framing**

학부 네트워크 과제 경험을 바탕으로 2026년에 다시 구현한 멀티클라이언트 채팅 서버입니다. TCP stream framing, partial send, 다중 클라이언트와 방 상태 관리를 구현했습니다.

[Repository](https://github.com/Mindarinda47/c-network-room-chat)

### xv6 Kernel Extensions

**C · xv6 · System Call · Scheduler · Virtual Memory**

시스템 콜, nice 기반 우선순위 스케줄링, FCFS와 page fault 기반 lazy allocation을 구현했습니다.

[Repository](https://github.com/Mindarinda47/xv6-kernel-extensions)

## 기타 프로젝트

### 붐비 — 부산 AI 혼잡 예보

**TypeScript · React · Rule Engine · AI Validation · API**

부산 주요 권역의 상대적 혼잡 가능성을 계산하는 1인 소프트웨어 프로젝트입니다. 규칙 기반 점수 엔진, AI 출력 범위 통제와 외부 데이터 장애 시 fallback을 구현했습니다.

[Repository](https://github.com/Mindarinda47/boombi-ai-crowd-forecast)

### STM32 Halli Galli

**Embedded C · STM32F10x · GPIO · Sensor Integration**

센서 입력, LCD·Bluetooth 출력과 게임 상태를 연결한 4인 팀 프로젝트입니다. 하드웨어 구성과 인터페이스, 디버깅과 최종 통합 테스트를 담당했습니다.

[Repository](https://github.com/Mindarinda47/stm32-halli-galli-system)
