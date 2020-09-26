# Java

    기본적인 단어부터 이해하기 어려운 개념까지 . . .

***


## 제1장 자바 시작


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

     
***
     
## 제2장 자바 기본 프로그래밍

     
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

   ![자바의 기본 타입](https://user-images.githubusercontent.com/71385038/94329602-62ee2280-fff7-11ea-9bf7-4721b7237cc4.png)

