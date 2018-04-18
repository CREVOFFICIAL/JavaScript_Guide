# CREV STUDY HUB
> CREV에서 학습한 내용을 정리하는 저장소입니다.

### 규칙
- 네이밍 
- Git
  - 자유롭게 작성을 하고 변경사항은 자율적으로 PR / PUSH를..
- 기타 
  - 양이 많은 내용은 폴더를 통하여 관리합니다.


## 목차
- [HTML & CSS](#HTML&CSS)
- [JavaScript](#javascript)
- [swift](#swfit)
- [python](#python)
- OS
- Network
- Algorithm
- 유용한 URL
- [git](#git)
- [front-end](#front-end) 
- [back-end](#front-end) 

# JavaScript
## 자바스크립트의 자료형
> 자바스크립트는 느슨한 타입의 언어다.
타입은 프로그램이 처리되는 과정에서 자동으로 파악될 것이다.
 
### 기본 타입 (Primitive)
- Number
  JavaScript Numbers are Always 64-bit Floating Point. Unlike many other programming languages, JavaScript does not define different types of numbers, like integers, short, long, floating-point etc.
- String
  C언어와 다르게 자바스크립트의 문자열은 변경할수없다. (immutable)
  그러나 원래 문자열에서 일부가 수정된 다른 문자열을 만드는건 가능하다
  ````js
  var str = "hi crev";
  var strSub = str.substr(0,2); // strSub = "hi";
  str[0] = "j"; //  "j";
  console.log(str); // "hi crev";
  ````
- Boolean
  논리적인 요소, ``true``와 ``false``를 가진다.
- undefined
  자료형이 결정되지 않은 상태 
- null 
  null은 아무런 값도 나타내지 않는 특수한 값이다.
  딱 한가지 값 ``null``을 가질 수 있다.

  undefined 와 null 은 다르다!
- Symbol (ES6)

Object
- Array
- Function
- 정규표현식