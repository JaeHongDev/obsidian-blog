- 앨런 튜링은 튜링 기계라는 시스템을 만듦
	- 튜링 기계란 긴 테이프(저장장치)에 쓰여 있는 여러가지 기호(코드)를 일정한 규칙에 따라 바꾸는 가상의 기계다. 
- 이후 컴퓨터 과학 분야에서는 튜링 기계의 변형 모델로 비결정론적 튜링 기계를 제시
- 기존의 튜링 기계가 일련의 규칙을 엄격히 준수하며 한 가지 방식으로 결정론적으로 동작하는 반면, 
- 비결정론적 튜링 기계는 다양한 선택지가 있고 이동할 수 있는 상태의 개수도 상황에 따라 여러 개가 되거나 아예 없을 수 있다는 차이점이 있다. 
![[Pasted image 20240403171104.png]]
- 튜링 기계를 이용해 문제를 풀이할 때 다항 시간 내에 풀이한다고 이야기 한다.
	- 이는 시간 범위 내에서 문제 해결이 가능하다는 의미이다.
	- 반대 이미로는 지수시간이 있으며, 지수 시간이 2^n의 경우 100만 되어도 계산 결과는 큰 값이 되기 떄문에 이런 경우는 다항 시간 내에 풀이가 불가능하다. 

정리
- 결정론적 튜링 기계로 다항 시간 내에 풀 수 있는 문제를 P문제
	- 2차 방정식이 대표적인 P문제
- 비결정론적 튜링 기계로 다항 시간 내에 풀 수 있는 문제는 NP문제라 한다.
	- 다양한 가능성을 시도하며 풀이하는 소인수분해 같은 문제는 NP문제


	