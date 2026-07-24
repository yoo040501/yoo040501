# 김동은 | Embedded Software Developer

메카트로닉스를 전공하고 STM32 기반 제어와 Linux 시스템 프로그래밍을 학습한 신입 임베디드 개발자입니다. 하드웨어 동작을 이해하고, 관찰 가능한 로그와 테스트 결과를 바탕으로 문제를 좁혀 가는 개발을 지향합니다.

## Core Skills

- **MCU/Firmware**: STM32, GPIO, UART, SPI, I2C, PWM, ADC, Encoder, PID
- **Embedded Linux**: Buildroot/QEMU 기반 이미지 빌드·부팅, Device Tree·부팅 로그 분석, `/dev` 장치 I/O 실습
- **Linux System**: C/C++, Process, Pipe, Signal, File Descriptor, Socket Programming
- **Tools**: STM32CubeIDE, IAR Embedded Workbench, Linux, Docker, Git, Makefile

## Featured Projects

### [Buildroot/QEMU Embedded Linux Study](https://github.com/yoo040501/buildroot-bsp-study)

Buildroot로 ARM Linux 이미지를 생성하고 QEMU Versatile PB와 VExpress A9에서 부팅했습니다. 커널·Device Tree·root filesystem의 역할을 로그로 분석하고, 간단한 character device driver와 user-space 프로그램의 read/write 흐름을 검증했습니다. VExpress 환경에서는 Ethernet 장치 인식과 host-to-guest TCP 통신을 확인했습니다.

> 실제 보드 포팅이나 제품 수준 드라이버 개발이 아닌 QEMU 기반 구조 학습 프로젝트입니다.

### [minishell](https://github.com/yoo040501/42seoul/tree/master/minishell)

2인 팀으로 Bash의 핵심 기능을 C로 구현했습니다. 개인적으로 쿼트 상태를 고려한 명령 파싱, 환경 변수 확장, 리디렉션·히어독 분석과 구문 오류 처리를 담당했습니다.

### [ft_irc](https://github.com/yoo040501/42seoul/tree/master/ft_irc)

3인 팀으로 RFC 1459 기반 IRC 서버를 C++98로 구현했습니다. TCP 비차단 소켓과 `kqueue`/`kevent` 이벤트 루프를 사용했으며, 개인적으로 `PASS`, `NICK`, `USER`, `JOIN`, `QUIT` 명령을 담당했습니다.

### [42Seoul Projects](https://github.com/yoo040501/42seoul)

C/C++ 기반 시스템 프로그래밍, 멀티스레딩, 네트워크, 컨테이너 프로젝트를 수행했습니다.

## Current Focus

- STM32 주변장치와 모터 제어 경험 정리
- Embedded Linux 부팅·장치 인식 흐름 학습
- Linux socket과 제어 로직을 결합한 테스트 가능한 프로젝트 구축

## Contact

- Email: yoo040501@naver.com
