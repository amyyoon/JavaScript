#Var

###var


```
var msg = '안녕하세요, JavaScript';
var x 	= 10;
```

```=```는 오른쪽 내용을 변수에 대입하라는 명령 연산자임. 변수 msg에 '안녕하세요, JavaScript'라는 문자를, 변수 x에 10이라는 숫자를 각각 대입한다는 의미

##Difference between var and let

###let

```
// Default 선언
let msg;

// Mutiple var 선언
let x, y;

// 초기값 설정
let greeting = 'Hello, World';

```

###What's the difference between var and let? <br />
1. let 은 블록 스코프를 인식 <br />
2. let은 변수 중복을 허가하지 않음 <br />
동일 명칭의 변수를 허가하지 않지만, var는 중복 허용해서 문제없이 동작함
아래 코드에서 msg는 goodday로 덮어쓰임

```
let msg = 'lalala';
let msg = 'goodday';
```


##Rule on naming
1. 첫번째 문자는 영문자/언더스코어(_)/달러($) 중 하나여야 함
2. 두번째 문자 이후에는 첫번째에서 사용할 수 있는 문자 또는 숫자여야 함
3. 변수명에 포함된 영문자의 대소문자 구별되어야 함
4. JavaScript에서 의미를 갖는 예약어가 아니어야 함

JavaScript 예약어 <br />

```
break, case, catch, class, const, continue,
debugger, default, delete, do,
else, export, extends,
finally, for, function,
if, import, implemets, in, insteadof, interface,
new, package, private, protected, public, return,
supper, switch, this, throw, try, typeof, var, void, 
while, with, yield
```

아래와 같은 케이스도 조심하자!
* 앞으로 예약어로 채택될 가능성 있는 키워드(enum,await 등)
* JavaScript에서 이미 정의된 객체나 그 멤버명 (String, eval 등)

###읽기 쉬운 코드?
* 내용 유추하기 쉬울 것
* 너무 길거나 짧지 않을 것
* 혼동하기 쉬움 안됨
* 언더스코어를 첫번째 문자에 사용하지말자
* 미리 정해진 룰이 있다면 통일되게 사용

1. camelCase:HelloMyWorld (변수/함수명에 사용)
2. Pascal:Newyork (클래스명에 사용)
3. Underscore:where_are_you_from (상수명에 사용)


#Const
변수는 데이터를 넣어두는 그릇.
그러므로 스크립트 중간에서 내용을 바꾸어도 상관없음.
상수는 그릇과 내용물이 한 셋트로 도중에 내용물 변경할 수 없음. 
코드안에 나타나는 의미 있는 값으로 미리 이름을 붙여둔다. 

```
const hello = value;
```

상수의 네이밍 규칙은 변수와 거의 비슷하지만, 상수인 것을 식별하기 위해 모든 문자를 대문자로, 단어를 언더스코어로 구분한다. 
예를 들어, CONSUMPTION_TAX, USER_NAME

```
const TAX = 1.08;
var price = 100;
console.log(price * TAX); //결과 108
```

#var and const