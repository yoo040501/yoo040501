# 김동은 | Embedded Software Developer

메카트로닉스를 전공하고 STM32 기반 제어와 Linux 시스템 프로그래밍을 학습한 신입 임베디드 개발자입니다. 하드웨어 동작을 이해하고, 관찰 가능한 로그와 테스트 결과를 바탕으로 문제를 좁혀 가는 개발을 지향합니다.

## Core Skills

- **MCU/Firmware**: STM32, GPIO, UART, SPI, I2C, PWM, ADC, Encoder, PID
- **Linux System**: C/C++, Process, Pipe, Signal, File Descriptor, Socket Programming
- **Tools**: STM32CubeIDE, IAR Embedded Workbench, Linux, Docker, Git, Makefile

## Learning Now

- **Embedded Linux 입문**: Buildroot와 QEMU의 역할, ARM Linux 부팅 구성, Device Tree와 부팅 로그를 가이드에 따라 공부하고 있습니다.
- 현재는 도움 없이 BSP를 포팅하거나 Linux device driver를 개발할 수 있는 단계가 아닙니다.

## Featured Projects

### [Buildroot/QEMU Embedded Linux Learning Notes](https://github.com/yoo040501/buildroot-bsp-study) — In Progress

가이드와 도구의 도움을 받아 Buildroot/QEMU 예제의 부팅 과정과 로그를 따라 읽고 있습니다. ARM Linux 이미지 구성, `/dev` 장치 I/O, Ethernet 장치 인식과 TCP 포트포워딩 예제를 복습하는 입문 단계입니다.

> 독립적으로 수행한 BSP 포팅이나 Linux device driver 개발 경험이 아니라, 현재 진행 중인 학습 기록입니다.

### [minishell](https://github.com/yoo040501/42seoul/tree/master/minishell)

2인 팀으로 Bash의 핵심 기능을 C로 구현했습니다. 개인적으로 쿼트 상태를 고려한 명령 파싱, 환경 변수 확장, 리디렉션·히어독 분석과 구문 오류 처리를 담당했습니다.

### [ft_irc](https://github.com/yoo040501/42seoul/tree/master/ft_irc)

3인 팀으로 RFC 1459 기반 IRC 서버를 C++98로 구현했습니다. TCP 비차단 소켓과 `kqueue`/`kevent` 이벤트 루프를 사용했으며, 개인적으로 `PASS`, `NICK`, `USER`, `JOIN`, `QUIT` 명령을 담당했습니다.

### [42Seoul Projects](https://github.com/yoo040501/42seoul)

C/C++ 기반 시스템 프로그래밍, 멀티스레딩, 네트워크, 컨테이너 프로젝트를 수행했습니다.

## Current Focus

- STM32 주변장치와 모터 제어 경험 정리
- 가이드 없이 Buildroot/QEMU 부팅 과정을 재현하고 설명하는 연습
- Linux socket과 제어 로직을 결합한 테스트 가능한 프로젝트 구축

## Contact

- Email: yoo040501@naver.com
