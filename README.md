# javatutorials-compare
1. 참,거짓 2. 비교연산자 

        package org.opentutorials.javatutorials.compare;

        public class EqualDemo {

	        public static void main(String[] args) {
		
		
boolean (참 거짓)
		
: 불린(Boolean)은 참과 거짓을 의미하는 데이터 타입으로 bool이라고도 불린다.
불린은 정수나 문자와 같이 하나의 데이터 타입인데, 참을 의미하는 true와 
거짓을 의미하는 false 두가지의 값을 가지고 있다.
		
비교연산자 
		
: programming에서 비교란 주어진 값들이 같은지, 다른지, 큰지, 작은지를
구분하는 것을 의미한다.
이때 비교 연산자를 사용하는데 비교 연산자의 결과는 true나 false 하나다.
true는 비교 결과가 참이라는 의미이고, false는 거짓이라는 뜻이다.
		
		System.out.println(1 == 2);     // false
		System.out.println(1 == 1);		// true
		System.out.println("one" == "two");		// false
		System.out.println("one" == "one");		// true
		
== 동등 비교 연산자 
==  좌항과 우항이 같냐?
1 = 2 이건 말이 안된다.
1 == 2 이건 1은 2와 같냐? 라는 비교연산자이기때문에 의미가 다르다.



    public class NotDemo {

	  public static void main(String[] args) {
	
!는 부정을 의미한다.
같다의 부정은 같지 않다이다.
이것을 기호로는 !=로 표시한다
==의 정반대가 != 이다.
				
		System.out.println(1!=2);  // 1과 2가 같지 않냐?true
		System.out.println(1!=1);  
		System.out.println("one"!="two");
		System.out.println("one"!="one");


  }

 }

    package org.opentutorials.javatutorials.compare;

    public class GreaterThanDemo {

    	public static void main(String[] args) {

좌항이 우항보다 크다면 참, 그렇지 않다면 거짓임을 알려주는 연산자.
		
		
		System.out.println(10>20);
		System.out.println(10>2);
		System.out.println(10>10);

		System.out.println(10>=20);
		System.out.println(10>=2);
		System.out.println(10>=10);
		
문자열을 비교하는 메소드.
EqualStringDemo
		
		String a = "Hello world";
		String b = new String("Hello world");
		
		System.out.println(a==b);  //false
		System.out.println(a.equals(b));   //true
		
문자열에선 '=='를 쓰지않고
.equals를 사용한다.
		
		
}

}


		
		
