# newyearproject
분식집 주문 시스템
사용자가 분식집에서 음식을 주문하는 시스템. 
다형성을 활용해 메뉴 선택 과정을 구현하고, 사용자의 입력을 처리해 선택한 메뉴와 총 금액을 계산한다.

A.시스템 요구사항
1. 사용자는 세가지 메뉴를 선택할 수 있다.
2. 키오스크는 사용자가 선택한 메뉴를 받을수 있다.
3. 키오스크는 처음에 메뉴를 보여주며 대기상태이다.
4. 사용자는 메뉴를 선택한다. 선택한 메뉴는 취소할 수 있다.
5. 사용자는 선택한 메뉴에 같은 메뉴나 다른메뉴를 추가할 수 있다.
6. 사용자의 결제방식은 현금,카드 두가지로 할 수 있다.
7. 사용자가 결제완료를 마치면 주문완료라고 뜬다.

B.필요한 객체
사용자, 키오스크

C.상호작용
-사용자
1.메뉴와 수량 선택
2.선택한 메뉴와 수량 확인
3.결제방식을 선택
4.결제를 완료
5.주문완료 확인

-키오스크
0.메뉴 안내 (메뉴가 보여지는 상태)
1.주문한 메뉴와, 수량 안내
2.결제 방식 안내
3.선택한 방법으로 결제
4.주문완료 메세지
