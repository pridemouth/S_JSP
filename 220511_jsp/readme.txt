<JSP>

	절차지향적임.
	parseInt() 의 경우에도 따로 객체/클래스 언급 필요가 없음.
	
	*******
	Number() vs parseInt()
	
		Number(String)
			문자열을 숫자형으로 변환
			숫자 + 문자가 입력될 경우, NaN(Not a Number) 반환.
			
		parseInt(String)
			문자열을 정수로 변환
			숫자 + 문자가 입력될 경우, 숫자부만 변환 후 반환.
			문자 + 숫자의 경우, NaN 반환.
	
	*******
	식별자 표기법
	
		파스칼 표기법	MyClassName
		카멜 표기법		myClassName
		스네이크(팟홀) 표기법	my_class_name
		케밥 표기법		my-class-name

	*******
	var vs let
	
		var의 문제점
			1. 변수 중복 선언이 가능하여, 예기치 못한 값을 반환 가능.
			2. 함수 레벨 스코프(유효범위)로 인해 함수 외부에서 선언한 변수는 모두 전역 변수가 됨.
			3. 변수 선언문 이전에 변수를 참조하면 언제나 undefined를 반환함.
		
		let의 해결방법(차이점)
			1. 중복선언시 오류 발생.
			2. 블록 레벨 스코프를 사용.
			3. 선언 단계와 초기화 단계의 분리 - 초기화되지 않은 변수에 접근 시 오류 뱉음.