# CAN 통신

## CAN 통신,, 간단한 정의, 특징
 - 멀티마스터이 방식이며, ID 값에 따라 메시지의 우선 순위가 변경된다.
 - 보통 RS-232커넥터를 사용하고, CAN 컨트롤러, CAN 트랜시버, 리시버로 구성되어 있다.
 - 2번: CAN_L, 7번:CAN_H, 3번: GND로 구성된다.

## CAN 프로토콜
 - CANoe를 사용한 시뮬레이션이 잘 되지 않아서
 (Tx시에 No Ack error 발생, 알고보니 케이블 문제였음...)
 - ACK가 왜 오지 않을까를 생각해보던 중에 프로토콜까지 찾아봤었는데,
 - wikipedia가 제일 잘 정리된 듯하다.
 - https://en.wikipedia.org/wiki/CAN_bus

## 시뮬레이션 툴들
 - CAN메시지들이 프레임 단위로 기록된 파일을 DBC파일이라고 한다.
 - DBC 파일은 Vector사에서 만든 툴에서 사용하는 포멧이었지만, 표준처럼 자리잡았다.  
 - CANoe 같은 장비를 이용해서 DBC 파일을 시뮬레이션할 수 있다.
 - 최근에는 busmaster, CANdevStudio와 같은 무료 툴들도 있다.
