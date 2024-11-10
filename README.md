# 코어 자바스크립트 꼬리질문 스터디

## 🗓️ 기간

- 9/3(화) ~ <br />
  <br/>

## 🍚 멤버

- 김초원, 심승혁, 형예은 <br />
  <br/>

## 📖 목차 [링크]

### CHAPTER01 데이터 타입

1. [데이터 타입의 종류](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/steve-shim/240903.md)
2. [데이터 타입에 관한 배경지식](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/steve-shim/240903.md)
3. [변수 선언과 데이터 할당](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/steve-shim/240903.md)
4. [기본형 데이터와 참조형 데이터](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/steve-shim/240903.md)
5. [불변 객체](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/tsihnavy99/240907.md) / [꼬리질문](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/steve-shim/240907.md)
6. [undefined와 null](https://github.com/Bob-Buddy/core-javascript/blob/master/ch1/kimifield98/240907.md)

<br/>

### CHAPTER02 실행 컨텍스트

1. [실행 컨텍스트란?](https://github.com/Bob-Buddy/core-javascript/blob/master/ch2/steve-shim/240910.md)
2. [VariableEnvironment](https://github.com/Bob-Buddy/core-javascript/blob/master/ch2/steve-shim/240910.md)
3. [LexicalEnvironment](https://github.com/Bob-Buddy/core-javascript/blob/master/ch2/steve-shim/240910.md)<br />
   3-1. [LexicalEnvironment - environmentRecord와 호이스팅](https://github.com/Bob-Buddy/core-javascript/blob/master/ch2/tsihnavy99/240910.md) <br />
   3-2. [LexicalEnvironment - 스코프, 스코프 체인, outerEnvironmentReference](https://github.com/Bob-Buddy/core-javascript/blob/master/ch2/kimfield98/240910.md)
   
<br/>

### CHAPTER03 this

1. 상황에 따라 달라지는 this<br/>
   1-1. [전역 공간에서의 this](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/steve-shim/240917.md)<br/>
   1-2. [메서드로서 호출할 때 그 메서드 내부에서의 this](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/steve-shim/240917.md)<br/>
   1-3. [함수로서 호출할 때 그 함수 내부에서의 this](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/steve-shim/240917.md)<br/>
   1-4. [콜백 함수 호출 시 그 함수 내부에서의 this](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/tsihnavy99/240917.md)<br/>
   1-5. [생성자 함수 내부에서의 this](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/tsihnavy99/240917.md)<br/>
2. 명시적으로 this를 바인딩하는 방법<br/>
   2-1. [call 메서드](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/tsihnavy99/240917.md)<br/>
   2-2. [apply 메서드](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/tsihnavy99/240917.md)<br/>
   2-3. [call / apply 메서드의 활용](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/tsihnavy99/240917.md)<br/>
   2-4. [bind 메서드](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/kimfield98/240917.md)<br/>
   2-5. [화살표 함수의 예외사항](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/kimfield98/240917.md)<br/>
   2-6. [별도의 인자로 this를 받는 경우(콜백 함수 내에서의 this)](https://github.com/Bob-Buddy/core-javascript/blob/master/ch3/kimfield98/240917.md)

<br/>

### CHAPTER04 콜백 함수

1. [콜백 함수란?](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/steve-shim/240917.md)
2. [제어권](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/steve-shim/240917.md)<br/>
   2-1. [호출 시점](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/steve-shim/240917.md)<br/>
   2-2. [인자](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/steve-shim/240917.md)<br/>
   2-3. [this](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/steve-shim/240917.md)<br/>
3. [콜백 함수는 함수다](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/tsihnavy99/240917.md)<br/>
4. [콜백 함수 내부의 this에 다른 값 바인딩하기](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/tsihnavy99/240917.md)<br/>
5. [콜백 지옥과 비동기제어](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/kimfield98/240917.md)

<br/>

### CHAPTER05 클로저

1. 클로저의 의미 및 원리 이해<br/>
2. 클로저의 메모리 관리<br/>
3. 클로저 활용 사례<br/>
   3-1. [콜백 함수 내부에서 외부 데이터를 사용하고자 할 때](https://github.com/Bob-Buddy/core-javascript/blob/master/ch5/tsihnavy99/241020.md)<br/>
   3-2. [접근 권한 제어(정보 은닉)](https://github.com/Bob-Buddy/core-javascript/blob/master/ch5/tsihnavy99/241020.md)<br/>
   3-3. [부분 적용 함수](https://github.com/Bob-Buddy/core-javascript/blob/master/ch5/kimfield98/241020.md)<br/>
   3-4. [커링 함수](https://github.com/Bob-Buddy/core-javascript/blob/master/ch5/kimfield98/241020.md)

<br/>

### CHAPTER06 프로토타입

1. 프로토타입의 개념 이해<br/>
   1-1. constructor, prototype, instance<br/>
   1-2. constructor 프로퍼티<br/>
2. 프로토타입 체인<br/>
   2-1. [메서드 오버라이드](https://github.com/Bob-Buddy/core-javascript/blob/master/ch6/tsihnavy99/241103.md)<br/>
   2-2. [프로토타입 체인](https://github.com/Bob-Buddy/core-javascript/blob/master/ch6/tsihnavy99/241103.md)<br/>
   2-3. [객체 전용 메서드의 예외사항](https://github.com/Bob-Buddy/core-javascript/blob/master/ch6/kimfield98/241110.md)<br/>
   2-4. [다중 프로토타입 체인](https://github.com/Bob-Buddy/core-javascript/blob/master/ch6/kimfield98/241110.md)

<br/>

### CHAPTER07 클래스

1. 클래스와 인스턴스의 개념 이해<br/>
2. 자바스크립트의 클래스<br/>
3. 클래스 상속<br/>
   3-1. 기본 구현<br/>
   3-2. 클래스가 구체적인 데이터를 지니지 않게 하는 방법<br/>
   3-3. constructor 복구하기<br/>
   3-4. 상위 클래스에서의 접근 수단 제공<br/>
4. ES6의 클래스 및 클래스 상속
