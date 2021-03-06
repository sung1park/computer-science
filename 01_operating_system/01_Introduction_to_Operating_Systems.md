# Introduction to Operating Systems

> 운영체제 과목 소개



### 운영체제(Operating System)란?

- 컴퓨터 하드웨어 바로 위에 설치되어 사용자 및 다른 모든 소프트웨어와 하드웨어를 연결하는 소프트웨어 계층
- 좁은 의미의 운영체제 (커널)
  - 운영체제의 핵심 부분으로 메모리에 상주하는 부분
- 넓은 의미의 운영체제
  - 커널 뿐 아니라 각종 주변 시스템 유틸리티를 포함한 개념



### 운영 체제의 목적

- 컴퓨터 시스템을 편리하게 사용할 수 있는 환경을 제공
  - 동시 사용자/ 프로그램들이 각각 독자적 컴퓨터에서 수행되는것 같은 환상을 제공
  - 하드웨어를 직접 다루는 복잡한 부분을 운영체제가 대행
- 컴퓨터 시스템의 **자원을 효율적으로 관리**
  - 프로세서, 기억장치, 입출력 장치 등의 리소스를 효율적 관리
    - 사용자 간의 형평성 있는 자원 분배
    - 주어진 자원으로 최대한의 성능을 내도록
  - 사용자 및 운영체제 자신의 보호 
  - 프로세스, 파일, 메시지 등을 관리



### 운영 체제의 분류

##### 다중 작업 지원 여부

- 단일 작업 (single tasking)
  - 한 번에 하나의 작업만 처리
- **다중 작업** (multi tasking) - 오늘날의 운영체제
  - 동시에 두 개 이상의 작업 처리



##### 사용자의 수

- 단일 사용자 (single user) - MS DOS, MS Windows
- **다중 사용자** (multi user)  - UNIX, NT server



##### 처리 방식

- 일괄 처리 (batch processing)
  - 작업 요청의 일정량 모아서 한꺼번에 처리
  - 작업이 완전 종료될 때까지 기다려야 함
- **시분할** (time sharing)
  - 여러 작업을 수행할 때 컴퓨터 처리 능력을 일정한 시간 단위로 분할하여 사용
  - 일괄 처리 시스템에 비해 짧은 응답 시간을 가짐
  - Interactive 한 방식
- 실시간 (realtime OS)
  - 정해진 시간 안에 어떤 일이 반드시 종료됨이 보장되어야 하는 실시간 시스템을 위한 OS
  - 원자로/공장 제어, 미사일 제어, 반도체 장비, 로보트 제어
  - Hard realtime system
  - Soft realtime system



### 용어

- Multitasking
- Multiprogramming: 여러 프로그램이 메모리에 올라가 있음을 강조
- Time sharing           : CPU의 시간을 분할하여 나누어 쓴다는 의미를 강조
- Multiprocess
- **Multiprocessor**     : 하나의 컴퓨터에 CPU(프로세서)가 여러개 붙어 있음을 의미



### 운영 체제의 예

- UNIX 계열
  - 코드 대부분을 C언어로 작성
  - 높은 이식성 - C언어로 작성되어 있기 때문
  - 최소한의 커널 구조 - 확장성이 좋음
  - 복잡한 시스템에 맞게 확장 용이
  - 소스 코드 공개
  - 프로그램 개발에 용이
  - 다양한 버전
    - System V, FreeBSD, SunOS, Solaris
    - Linux
- DOS (Disk Operating System)
  - 단일 사용자용 운영체제, 메모리 관리 능력의 한계
- MS Windows
  - GUI 기반 운영체제
  - Plug and Play, 네트워크 환경 강화
  - DOS용 응용 프로그램과 호환성 제공
  - 불안정성
  - 풍부한 지원 소프트웨어
- Handheld Devices를 위한 OS



### 운영 체제의 구조

- CPU 스케줄링
- 메모리 관리
- 파일 관리
- 입출력 관리
- 프로세스 관리
  - 프로세스 생성과 삭제
  - 자원 할당 및 반환
  - 프로세스 간 협력
- 그 외
  - 보호 시스템
  - 네트워킹
  - 명령어 해석기


