#JavaScript Data

* 기본형

```
number
strong  : 큰따옴표,작은따옴표로 감싸져있는 0개 이상의 문자 집합
boolean : true/false
symbol
null/undefined : 값이 미정의된 것
```

* 참조형

```
array    : 데이터의 집합 (각 요소에는 인덱스 번호로 접근 가능)
object   : 데이터의 집합 (각 요소에는 이름으로 접근 가능)
function : 일련의 처리(절차)의 집합
```

<br />
<br />

##문자열 리터럴 주요 이스케이프 시퀀스
* `\b` : backspace
* `\f` : 새로운 페이지
* `\n` : 개행 (LF:Line Feed)
* `\r` : 복귀 (CR:Carriage Return)
* `\t` : 탭문자
* `\\` : \마크
* `\'` : 작은따옴표
* `\"` : 큰따옴표
* `\xXX` : Latin-1 문자(XX는 진수) 예:\x61 (a)
* `\uXXX` : Unicode 문자 (XXXX는 16진수) 예:\uC815 (정)
* `\u{XXXXX}` : Oxffff(4개의 16진수)을 넘는 Unicode 문자. 예:\u{20b9f}

```
window.alert('hello, ich bin Euni! \n Wie geht's dir?');

Result ===>

hello, ich bun Euni!
Wie geth's dir?
```

<br />
<br />


##Template String

* 문자열 안에 변수 삽입
* 복수행에 걸친 (=개행 문자를 포함한) 문자열

템플릿 문자열에서 작은따옴표/큰따옴표 대신 `(backsquats)로 문자열을 감싼다.

```
let name ="Reni"
let str = `Good morning. Mr. ${name}
It's nice weather!`;
console.log(str);

Result  ==>

Good mornig. Mr. Reni
It's nice weather!
 
```
우선
