# Java

    기본적인 단어부터 이해하기 어려운 개념까지 . . .

***
<details markdown = "1">
<summary> 제 1장 자바 시작 </summary>


#### JDK와 JRE
- JDK(Java Development Kit) : 자바 개발자에게 무료로 배포하는 소프트웨어, 자바 컴파일러 등의 개발 도구 + JRE로 구성
- JRE(Java Runtime Environment) : 자바 응용프로그램이 실행될 때 필요한 소프드웨어, 개발자가 아닌 일반 사용자의 경우 JRE만 필요

    ![JDK-JRE](https://user-images.githubusercontent.com/71385038/94160426-90d04b80-febf-11ea-9c60-afe70f6afb9b.png)

#### 자바 IDE
- IDE(Integrated Development Environment) : 소스 코드 편집, 컴파일, 디버깅을 한꺼번에 할 수 있는 통합 개발 환경(소프트웨어)

    ex) 이클립스(eclipse), 비주얼 스튜디오

#### 자바 언어의 활용
 - 자바 언어로 개발되는 응용 분야
 
 
     * 데스크톱 응용프로그램
     exe
     * 자바 서블릿(java servlet) 응용프로그램
     웹 서버에서 실행되는 서버용 자바 프로그램
     * 안드로이드(Android) 응용프로그램
     
***


- [실습문제1-1](https://github.com/ahnjisu/Java/blob/master/%EC%8B%A4%EC%8A%B5%EB%AC%B8%EC%A0%9C/1-1)
- [실습문제1-2](https://github.com/ahnjisu/Java/blob/master/%EC%8B%A4%EC%8A%B5%EB%AC%B8%EC%A0%9C/1-2)

</details>
     
***

<details markdown = "1">
<summary> 제2장 자바 기본 프로그래밍 </summary>
     
#### 식별자
- 식별자 이름 규칙
    * 특수문자, 공백은 식별자로 사용 X, _ 와 $ 는 예외
    * 한글도 식별자로 사용 가능
    * if, while, class 등 자바 언어의 키워드는 식별자로 사용 X
    * 식별자의 첫 번째 문자로 숫자 사용 X
    * 대소문자 구별 O
    * 길이 제한 X
    
- 좋은 이름붙이는 관습
    * 클래스 : 첫번째 문자는 **대문자**, 여러 단어가 복합되면 각 단어의 첫 번째 문자만 대문자로 표시
    * 변수, 메소드 : 첫단어는 **소문자**로 표기하고 이후 각 단어의 첫 번째 문자만 대문자로 표기 (변수와 클래스를 쉽게 구분하기 위해)
    
#### 자바의 기본 타입

   ![자바의 기본 타입](https://user-images.githubusercontent.com/71385038/94329826-5cf94100-fff9-11ea-885d-b9cc923ab851.png)
- **문자열**은 자바의 기본 타입에 속하지 않기 때문에, 자바 라이브러리에서 제공하는 **String 클래스**를 이용한다.

#### 변수, 리터럴, 상수

- 변수 : 데이터를 저장하는 공간, 값이 변할 수 있음


    *ex) int **apple** = 5; , int **사과**;*
    
- 리터럴 : 프로그램에서 직접 표현한 값, 소스 코드의 고정된 값을 대표하는 용어
    * 리터럴의 종류 : 정수, 실수, 문자, 논리, 문자열 리터럴, 특수문자 리터럴


    *ex) int apple = **5**; , boolean a = **true**;*

- 상수 : 변수와 달리 0값을 한번 입력하면 그 값을 다시는 바꿀 수 없음, 상수를 만들기 위해서는 final 키워드 사용


    *ex) final double PI = 3.141592;*

#### nextLine()과 next()

- "Seoul Korea"와 같이 **공백이 낀 문자열**을 입력받기 위해서는 **nextLine()**을 이용

#### 연산자 우선순위

   ![연산자 우선순위](https://user-images.githubusercontent.com/71385038/95161545-685d2100-07de-11eb-9594-5a6c32f4beeb.jpg)


#### 비트 시프트 연산

- << 연산자 : 왼쪽 시프트 연산자, 각 비트를 **왼쪽**으로 이동시키며, 오른쪽 끝에는 항상 **비트 0**이 삽입된다. 1비트 시프트 할 때마다 **곱하기 2**의 효과가 나타난다.
- \>\> 연산자 : 오른쪽 시프트 연산자, 각 비트를 **오른쪽**으로 이동시키며, 왼쪽 끝에는 **이전의 최상위 비트**가 삽입된다. 1비트 시프트 할 때마다 **나누기 2**의 효과가 나타난다.
- \>\>\> 연산자 : 비트를 **오른쪽**으로 이동시키며, 왼쪽 끝에는 항상 **비트 0**이 삽입된다. 

#### 조건문
 - if문
 - if-else문
 - 다중 if-else문
 - 중첩 if-else문
 - switch문
     * switch문의 case에 break;문이 생략되면 다음 break문 만날 때까지 계속 실행
     * case문의 값으로는 리터럴(정수, 문자, 문자열)만 사용 가능, 변수나 실수나 식은 사용 불가능
     * default문 생략가능, default문에는 break;문 X

***


- [실습문제2-1](https://github.com/ahnjisu/Java/blob/master/%EC%8B%A4%EC%8A%B5%EB%AC%B8%EC%A0%9C/2-1)
- [실습문제2-2](https://github.com/ahnjisu/Java/blob/master/%EC%8B%A4%EC%8A%B5%EB%AC%B8%EC%A0%9C/2-2)


</details>
