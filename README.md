# Game Programming Portfolio

게임 네트워크, Unity 게임플레이 시스템, C 시스템 프로그래밍 경험을 빠르게 확인할 수 있도록 구성한 포트폴리오 허브입니다. 각 저장소에서 구현 코드, 담당 범위와 문제 해결 과정을 확인할 수 있습니다.

## 프로젝트 지도

| | 프로젝트 | 형태·역할 | 핵심 역량 | 바로 보기 |
|---:|---|---|---|---|
| 1 | VR 재난 시뮬레이션 | 3인 팀 · 네트워크 담당 | Unity 멀티플레이, 소유권·동기화, 비동기 생성 순서, 협업 | [Repository](https://github.com/Mindarinda47/vr-disaster-networking-portfolio) |
| 2 | Unity 2D RPG Gameplay Systems | 개인 프로젝트 · 게임플레이 구현 | 퀘스트, 대화, 인벤토리, 전투, 저장, 이벤트 기반 UI | [Repository](https://github.com/Mindarinda47/unity-2d-rpg-gameplay-systems) |
| 3 | 웹 방탈출 게임 | 1인 프로젝트 · 전체 구현 | 퍼즐 상태 관리, 게임 밸런스, 반복 플레이 검증 | [Repository](https://github.com/Mindarinda47/website-escape-game-portfolio) |
| 4 | 붐비 혼잡 예보 | 1인 프로젝트 · 전체 구현 | 요구사항 구조화, 혼잡도 규칙, 데이터와 서비스 설계 | [Repository](https://github.com/Mindarinda47/boombi-ai-crowd-forecast) |
| 기술사례   | C 다중 클라이언트 채팅 | 개인 재구현 | TCP framing, `select`, 연결·방 상태, 통합 테스트 | [Repository](https://github.com/Mindarinda47/c-network-room-chat) |
| 기술사례   | xv6 Kernel Extensions | 학부 과제·재검증 | 시스템 콜, 우선순위 스케줄링, lazy allocation | [Repository](https://github.com/Mindarinda47/xv6-kernel-extensions) |
| 기술사례   | STM32 Halli Galli | 4인 팀 · 센서·통합 기여 | 임베디드 통합, 하드웨어 디버깅, 협업 | [Repository](https://github.com/Mindarinda47/stm32-halli-galli-system) |

전공 사례의 구현 범위는 [Technical Cases](docs/TECHNICAL_CASES.md)에 비교 정리했습니다.

## 역량 요약

### Unity 게임플레이 프로그래밍

- 퀘스트·대화·인벤토리·저장 시스템 연결
- 플레이어·적 전투 상태와 이벤트 기반 UI 동기화

### 게임 네트워크

- Host/Client 연결, 서버 주도 생성과 플레이어 소유권 이전
- RPC 기반 관제 상호작용, 위치 동기화와 PC·VR 역할 분리

### 시스템 기반

- C 소켓의 stream framing과 xv6 커널 실행 경로 구현
- STM32 센서·LCD·Bluetooth·게임 상태 통합 경험

## 공개 기준

팀 프로젝트는 확인 가능한 개인 기여만 설명하며, 팀원 코드·개인정보·권리 미확인 외부 리소스는 공개하지 않습니다. 학부 당시 구현과 이후 보완 작업은 각 저장소에서 구분해 설명합니다.
