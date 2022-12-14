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


## 22.09.09
- kafka : Consumer의 읽기 Offset Commit
- Kafka : Consumer의 Auto Commit 이해 + 중복 읽기 발생 상황 이해
- Kafka : Consumer의 Auto Commit 


## 22.09.11
- kafka : Consumer 동기 / 비동기 Manual Commit
- Kafka : Consumer assign() / Sync()
- Kafka : Producer 어플리케이션 구현 (txt 파일 변경 감지 → 메세지 전송)
- Kafka : Consumer, 제네릭 이용한 Consumer 구현
- Kafka : Consumer, Broker → Postgresql 전송
- Kafka : 멀티 노드 카프카 클러스터
- Kafka : 멀티 노드 카프카, replication factor로 topic 생성
- Kafka : Leader / Follower 이해
- Kafka : boostrap.servers 설정 이해
- Kafka : 주키퍼 / 컨트롤러 브로커 

## 22.09.12
- Kafka : 주키퍼와 컨트롤러 이해 → 주키퍼 쉘 이용해서 확인
- Kafka : 컨트롤러와 Leader Election 이해

## 22.09.13
- Kafka : ISR, min,insync,replicas
- Kafka : Preferred / Unclean Leader election
- Kafka : custom 직렬/역직렬화 객체 구현
- kafka : 메세지 로그 세그먼트의 이해
- Python : 코루틴 / asyncio

## 22.09.14
- Kafka : 세그먼트 내 메세지 로그 살펴보기
- Kafka : 인덱스 / 타임 인덱스 세그먼트 이해
- Kafka : 세그먼트의 생명 주기 
- Kafka : log.cleanup.policy 정책 이해
- Kafka : Log Compaction 이해



