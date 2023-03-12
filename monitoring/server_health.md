# Monitoring - 서버 건강상태

## CPU

- `top` 명령어 실행 후, `P` 키를 누르면 메모리 사용량 기준으로 프로세스 정렬 가능
- `top` 명령어 실행 후, `1` 키를 누르면 CPU 코어 별 사용량 확인 가능
- `uptime` 명령어로 CPU 부하(load average)를 알수 있음 - [자세히 알아보기](/docs/uptime.md)

## Memory

- `top` 명령어 실행 후, `M` 키를 누르면 메모리 사용량 기준으로 프로세스 정렬 가능

## Disk

- `df -h` 디스크 사용량 확인
- `du -h -d1` 파일 또는 dir 의 디스크 사용량 확인
- `lsblk` 블록 장치(HDD, partition) 정보 확인
- `fdisk` 디스크 파티션 정보 확인

## Process

- `top` 명령어 실행 후, `T` 키를 누르면 프로세스 스레드 정보 확인 가능
