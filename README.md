# 코어 자바스크립트 꼬리질문 스터디

## 🗓️ 기간

- 9/3(화) ~ 9/28(토) <br />
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
   1-1. 전역 공간에서의 this<br/>
   1-2. 메서드로서 호출할 때 그 메서드 내부에서의 this<br/>
   1-3. 함수로서 호출할 때 그 함수 내부에서의 this<br/>
   1-4. 콜백 함수 호출 시 그 함수 내부에서의 this<br/>
   1-5. 생성자 함수 내부에서의 this<br/>
2. 명시적으로 this를 바인딩하는 방법<br/>
   2-1. call 메서드<br/>
   2-2. apply 메서드<br/>
   2-3. call / apply 메서드의 활용<br/>
   2-4. [bind 메서드](https://github.com/Bob-Buddy/core-javascript/commit/9c97d35f2b55c8e19c5e6fb1e85640b51ae7871b)<br/>
   2-5. [화살표 함수의 예외사항](https://github.com/Bob-Buddy/core-javascript/commit/9c97d35f2b55c8e19c5e6fb1e85640b51ae7871b)<br/>
   2-6. [별도의 인자로 this를 받는 경우(콜백 함수 내에서의 this)](https://github.com/Bob-Buddy/core-javascript/commit/9c97d35f2b55c8e19c5e6fb1e85640b51ae7871b)<br/>

### CHAPTER04 콜백 함수

1. 콜백 함수란?
2. 제어권
  2-1. 호출 시점
  2-2. 인자
  2-3. this
3. 콜백 함수는 함수다
4. 콜백 함수 내부의 this에 다른 값 바인딩하기
5. [콜백 지옥과 비동기제어](https://github.com/Bob-Buddy/core-javascript/blob/master/ch4/kimfield98/240917.md)
