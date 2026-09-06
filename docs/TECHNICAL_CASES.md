# 전공 기술 사례

[← 포트폴리오 허브로 돌아가기](../README.md)

게임 프로그래밍 프로젝트를 보완하는 운영체제, 네트워크와 임베디드 기술 사례입니다.
각 저장소에서 핵심 구현, 문제 해결 과정과 확인 가능한 결과를 바로 볼 수 있습니다.

## 권장 확인 순서

| 순서 | 사례 | 먼저 볼 내용 | 핵심 역량 | 대표 결과 |
|---|---|---|---|---|
| 1 | C 다중 클라이언트 채팅 | TCP stream framing 문제와 독립 테스트 | C, socket, `select`, 상태 관리, 테스트 | 검증 완료 |
| 2 | xv6 Kernel Extensions | nice 스케줄러와 lazy page allocation | 커널 경로, 프로세스 상태, 가상 메모리 | 당시 실행 기록 포함 |
| 3 | STM32 Halli Galli | 제약에 따른 범위 조정과 통합 디버깅 | 임베디드 통합, 하드웨어 설계, 협업 | 협업 사례 정리 완료 |

## 01. C 다중 클라이언트 채팅

2023년 과제 경험을 바탕으로 2026년에 로비·채팅방 서버를 독립 구조로 다시 구현했습니다.
TCP가 응용 메시지 경계를 보존하지 않는 문제를 누적 버퍼와 newline framing으로 처리하고,
partial send, 방 격리, 연결 종료를 독립 테스트로 검증했습니다.

- **가장 먼저 볼 것:** README의 `문제 발견과 보완`, 독립 테스트 구성
- **코드 진입점:** protocol, server, integration test
- **검증 결과:** warning-free build, protocol test와 3-client integration test 통과
- **한계:** blocking slow client에 대한 output queue는 후속 확장 항목
- [상세 저장소 열기](https://github.com/Mindarinda47/c-network-room-chat)

## 02. xv6 Kernel Extensions

xv6-public을 기반으로 시스템 콜, nice 우선순위 스케줄러와 lazy page allocation을
구현한 학부 운영체제 사례입니다. 2026년에는 과제 명세와 코드를 다시 대조해 타이머
인터럽트 경로의 비선점 정책 불일치를 수정하고 독립 테스트를 구성했습니다.

- **가장 먼저 볼 것:** 15초 요약, 스케줄러 정책, lazy allocation 흐름
- **코드 진입점:** `proc.c`, `sysproc.c`, `trap.c`, `vm.c`, `portfolio_*_test.c`
- **확인 자료:** 과제 1·2 당시 실행 기록, 구현 코드와 독립 테스트 코드 5개
- **출처:** MIT 기반 코드와 개인 변경 범위를 README·LICENSE·UPSTREAM에 명시

- [상세 저장소 열기](https://github.com/Mindarinda47/xv6-kernel-extensions)

## 03. STM32 Halli Galli

4인 팀이 STM32로 1인 대 컴퓨터 할리갈리 게임을 완성한 협업·통합 사례입니다. 포트와
안정성 제약에 따라 초기 범위를 조정하고, LCD·센서·Bluetooth·게임 상태를 통합하는
과정에서 인터페이스 설계, 하드웨어 배치, 디버깅과 반복 테스트를 담당했습니다.

- **가장 먼저 볼 것:** 개인 기여, 대표 문제해결, 협업 과정
- **확인 자료:** 당시 결과 문서, 역할 기록과 대표 센서 코드 2개
- **담당 범위:** 팀의 완성 결과와 개인 기여를 분리하고, 보존된 센서 코드를 대표 구현으로 제시

- [상세 저장소 열기](https://github.com/Mindarinda47/stm32-halli-galli-system)

학부 당시 구현과 이후 보완 작업은 각 저장소에서 구분하며, 팀 프로젝트는 확인 가능한 개인 기여만 설명합니다.
