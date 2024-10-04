# C# 주요 속성 정리

* hello world 1
* hello world 2

Boxing, UnBoxing

일단 값 타입과 참조타입에 대해 알 필요가 있다.
- 값 타임
1. 구조체, 열거 타입 등은 값 타입입니다.
2. System.ValueType으로부터 상속
3. 스택에 할당이 됩니다.

- 참조타입
1. 클래스는 참조 타입입니다.
2. System.Object로부터 상속
3. 힙에 저장이 되며 GC의 관리 대상이 됩니다.

Boxing은 값 -> 참조 타입으로 변경
UnBoxing은 참조 -> 값 타입으로 변경