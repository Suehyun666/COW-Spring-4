# [WEEK 01] 온보딩 (기간 : 9/23 ~ 9/26)

## COW SPRING 4기 PRE-ONBOARDING 학습 과제

본격적으로 Spring 학습에 들어가기 전에 여러분은 객체지향 코드에 대해 학습하고 이해하는 시간을 가지실겁니다!

객체지향 코드를 짜기 위해서는 우리가 사용할 언어인 JAVA에 대해 이해하고 있어야합니다.

이 온보딩 과제는 이번 COW Server 파트에 함께 하시는 7분의 개개인의 역량이 다르기 때문에 가장 최소한으로 알고 계셔야 할 내용을 중심으로 선정해봤어요!

많은 양의 정리를 요구하지 않는 과제이니 이해하신 내용을 토대로 간단하게 정리해주시면 됩니다. (1, 2, 3기의 학습자료가 github에 나와있으니 참고하셔도 좋아요☺️)

개인적으로, 분명 학습했던걸 다 기억하실 수 없으실거예요! 저도 마찬가지이고요.. 공부했던 것을 잘 정리해두는 습관을 가지는 것은 분명 큰 도움으로 돌아올 것이라 생각합니다. 그런 의미로 다들 파이팅해봐요!

---
> 아래의 필수 질문은 모든 분들이 정리하고 학습하셔야하는 내용입니다. 선택 질문은 원하시는 분들만 하시면 되지만 분명 학습하시면 큰 도움이 될 것들을 추려봤습니다!

# 필수

## www.google.com 을 치면 일어나는일
Keywords : DNS, TCP/IP프로토콜, WS, WAS

---
커밋 및 푸시


## API, HTTP통신

API란, 운영체제와 응용프로그램 사이에 통신에 사용되는 언어나 메세지 형식을 말한다.<br/>
API는 프로그램 내에서 실행을 위해 특정 서브루틴에 연결을 제공하는 함수를 호출해 구현한다.<br/>
쉽게 말해서 응용 프로그램과 소통하기 위한 일련의 약속이 API라고 할 수 있다.<br/>
최근에는 여러 기업이나 국가 기관이 자체 서버를 운영하며 데이터를 관리하고 있는데, 이런 서버에 접근하여 데이터를 사용할 수 있도록 '오픈 API'라는 형태로 API를 공개하고 있다.<br/>

HTTP 통신이란, Hyper Text Transfer Protocol의 약자로 클라이언트와 서버 간 통신을 위한 통신 규칙 세트 또는 프로토콜을 말한다.<br/>
네트워크 통신을 작동하게 하는 기본 기술으로, HTTPS는 HTTP에서 서버와 클라이언트 간 통신에서 암호화된 연결을 지원하는 기술이다.<br/>
HTTP 통신은 먼저 HTTP 클라이언트가 요청문, 헤더, 바디로 구성된 형식에 맞춰서 HTTP 서버에 요청 메시지를 보낸다.<br/>
그 후 HTTP 서버는 HTTP 클라이언트가 보낸 요청 메시지를 수신해 상태문, 헤더, 바디로 구성된 형식에 맞춰 응답 메시지를 보낸다.<br/>
이러한 통신 방식을 비상태 연결이라고 한다.<br/>
HTTP의 요청 및 응답 메시지는 MIME(Multipurpose Internet Message Extensions) 유사 구조를 사용해 데이터를 전송한다.<br/>

---

## 백엔드가 하는 일

1. 데이터베이스 제작, 유지 및 보수<br/>
2. 데이터 유효성 검사<br/>
3. 서버 측 소프트웨어 프로그래밍<br/>

이 외에도 서버 측에서 발생하는 모든 코드를 작성하는 것이 백엔드의 업무이기에, 계산 수행이나 머신 러닝 사용 등의 업무도 맡을 수 있다.


---

## 객체지향 특징 및 장점

프로세스 지향 방법과 데이터 지향 방법의 문제점을 해결하기 위해 고안된 것이 객체 지향(Object-oriented) 방법이다.<br/>
기능이나 데이터 대신 객체가 중심이 되는 것이 특징으로, 데이터(속성)를 가장 먼저 찾고 그 데이터를 조작하는 메서드(함수)를 찾아 그 둘을 객체로 묶어 모듈을 구성한다.<br/>
또한 필요한 객체를 간단히 추가할 수 있어 확장성이 높고, 객체의 재사용을 통해 개발 비용과 시간을 줄일 수 있다.<br/>

---
## 코드 컨벤션이란
코드 컨벤션이란 프로그램 개발을 위한 스타일 가이드라인이다.<br/>
기본적으로 변수와 함수에 대한 명명 및 선언에 대한 규칙, 공백 및 들여쓰기 사용 규칙 등을 포함하고 있으며, 개발 환경에 따라 추가되기도 한다.<br/>
이러한 코드 컨벤션을 사용하면 코드 가독성의 향상을 기대할 수 있으며, 프로젝트에서 코드의 유지 및 관리가 원활해질 수 있다.<br/>
Oracle에서 97년에 투고한 Java 코드 컨벤션에 코드 컨벤션은 '소프트웨어의 가독성을 높여주며 새 엔지니어들이 코드를 더 빠르고 철저히 이해할 수 있도록 한다.' 라고 명시되어 있을 정도로 예전부터 개발의 중요한 축이었다고 할 수 있다.
<br/>
---

## MVC 패턴
소프트웨어 설계에서 3가지의 구성 요소인 모델(Model), 뷰(View), 컨트롤러(Controller)를 활용한 설계 방식이다.<br/>
모델(Model)은 소프트웨어 내에서 데이터(Data)를 의미하고, 뷰(View)는 사용자에게 보이는 영역을 의미한다.<br/>
이러한 모델과 뷰의 상호작용을 컨트롤러(Controller)가 관리하는 구조로 MVC는 구성되어 있다.<br/>
이러한 모델, 뷰, 컨트롤러가 독립적으로 분리되어있기 때문에 다수의 프로그래머가 각 기능을 개발할 수 있고, 기능을 업데이트 할 때에도 기존 요소를 활용할 수 있어 편리하다.<br/>
GUI 개발에 지속적으로 사용되어 왔으며 오늘날 업계 표준 개발 프레임워크로 사용되고 있다.<br/>
MVC 모델을 웹 애플리케이션에 쉽게 적용가능한 라이브러리로는 앵귤러자바스크립트(AngularJS), 엠버자바스크립트(EmberJS), 자바스크립트엠브이시(javaScriptMVC) 등이 있다.<br/>
<br/>

1. 컨트롤러(Controller)<br/>
컨트롤러는 기본적으로 뷰와 모델 간 상호 연결을 중개하는 역할을 맡는다.<br/>
사용자의 입력을 받아 모델을 업데이트하고 맞는 뷰를 찾아 데이터를 전송한다.<br/>
<br/>
2. 뷰(View)<br/>
사용자를 위한 사용자 인터페이스를 생성한다.<br/>
뷰에 띄우는 데이터는 모델에 구성되어 있으며 컨트롤러를 통해 데이터를 가져온다.<br/>
즉 뷰는 컨트롤러와만 상호작용하지 모델과는 상호작용 하지 않는다.<br/>
<br/>
3. 모델(Model)<br/>
일반적인 유저 데이터 부터 비즈니스 로직 관련 데이터 등 모든 데이터 관련 논리는 모델에 해당한다.<br/>
데이터베이스에서 데이터를 추가할 수 있으며, 컨트롤러는 자체적으로 데이터베이스와 상호 작용할 수 없기 때문에 필연적으로 모델을 거쳐 상호 작용한다.<br/>
<br/>
---

## 참고 자료
[모델 · 뷰 · 컨트롤러](https://terms.naver.com/entry.naver?docId=5714708&cid=42346&categoryId=42346)<br/>
[MVC Framework Introduction](https://www.geeksforgeeks.org/mvc-framework-introduction/#what-is-mvc)<br/>
[JavaScript Style Guide](https://www.w3schools.com/js/js_conventions.asp#:~:text=Coding%20conventions%20are%20style%20guidelines%20for%20programming.%20They,the%20use%20of%20white%20space%2C%20indentation%2C%20and%20comments.)<br/>
[Java Code Conventions](https://www.oracle.com/technetwork/java/codeconventions-150003.pdf)<br/>
[객체지향 방법](https://terms.naver.com/entry.naver?docId=3532990&cid=58528&categoryId=58528)<br/>
[What Does a Back-End Developer Do?](https://www.codecademy.com/resources/blog/what-does-a-back-end-developer-do/?utm_source=ccblog&utm_medium=ccblog&utm_campaign=ccblog&utm_content=cw_what_is_back_end_blog)<br/>
[API](https://terms.naver.com/entry.naver?docId=1179553&cid=40942&categoryId=32837)<br/>
[API](https://terms.naver.com/entry.naver?docId=6653674&cid=69974&categoryId=69974)<br/>
[HTTP와 HTTPS의 차이점은 무엇인가요?](https://aws.amazon.com/ko/compare/the-difference-between-https-and-http/)<br/>
[요청과 응답](https://terms.naver.com/entry.naver?docId=2271986&cid=51207&categoryId=51207&expCategoryId=51207)<br/>
[HTTP의 동작 과정](https://terms.naver.com/entry.naver?docId=2271987&cid=51207&categoryId=51207&expCategoryId=51207)<br/>