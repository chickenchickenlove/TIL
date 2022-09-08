# TIL (Today I Leanred)
- 그 날 공부한 내용을 간략하게 작성합니다.
- 블로그에 작성된 내용 중 공유할 수 있는 내용은 블로그 링크까지 함께 작성합니다.



<br>

## 22.09.02
- kafka producer / consumer
- kafka producer의 객체 직렬화 전송의 이해
- kafka key 값을 가지지 않는 메세지 전송
- kafka 여러 개의 파티션을 가지는 메세지 전송
- kafka key가 없는 메세지의 파티션 분배 전략 (Round Robin, Sticky Partition)
- kafka Consumer Group, Consumer Rebalancing
- kafka kafka-consumer-groups 명령어
<br>

## 22.09.05
- kafka : Java 기반 카프카 클라이언트 구현 설정 + 멀티 모듈 설정
- kafka : Java 기반에서 Producer 구현하기
- kafka : Producer Java 클라이언트 APi 내부 확인
- kafka : Producer의 메세지 동기화 / 비동기화 전송
- kafka : Producer에서 키 값을 가지는 메세지 전송 구현 + 키 타입의 변경 및 Custom Callback 구현
- kafka : 피자 주문 시뮬레이션 Producer 구현 
- erlang : if / case / loop 문 


## 22.09.06
- kafka : acks 설정에 따른 Producer 전송 방식 차이 이해 
- kafka : Producer 메세지 배치 전송 내부 메커니즘 이해
- kafka : producer 동기 / 비동기에서 배치 전송 차이
- kafka : producer 전송/재전송 내부 메커니즘 및 재전송 동작 관련 이해
- kafka : producer 재전송 관련 이해(최대 한번, 적어도 한번, 정확히 한번) + 멱등성
- kafka : customer partitioner 
- erlang : 책 2장 / 3장의 1/3정도

## 22.09.07
- kafka : consumer 주요 메커니즘 개요
- kafka : Java 기반 Consumer 구현
- kafka : poll() 메서드 동작 메커니즘 이해
- kafka : fetcher 관련 주요 파라미터 / 메커니즘 이해
- kafka : wakeup을 이용한 consumer 종료
- kafka : __consumer_offsets / auto.offset.reset 내부 동작 메커니즘


## 22.09.08
- kafka : Consumer 파티션 할당 전략
- kafka : Consumer 리밸런스의 Eager / Cooperative 모드
- kafka : Consumer 여러 개의 토픽 읽기
- kafka : Consumer Heartbeat 쓰레드 / 파라미터 이해
- kafka : Consumer Static group 멤버십
