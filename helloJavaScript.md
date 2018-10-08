# "Hello, JavaScript" in JavaScript

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Master JavaScript</title>
  </head>
  <body>
     <script type="text/javascript">
	  //window.alert 은 지정된 문자열을 대화상자로 표시해주는 명령어
	  window.alert('Hello, JavaScript");
	  </script>
	  <noscript>JavaScript를 이용할 수 없습니다</noscript>
	  //JavaScript를 이용할 수 없는 경우
  </body>
</html>
```

<br/>

#Import JavaScript files


```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Master JavaScript</title>
  </head>
  <body>
     <script type="text/javascript" src="script/hello.js"></script>
	  <noscript>JavaScript를 이용할 수 없습니다</noscript>
	  //JavaScript를 이용할 수 없는 경우
  </body>
</html>
```

<br/>

###When writing script with the imported JavaScript files 
src property를 사용할 경우 '<'script> 태그안의 콘텐츠는 무시되기 때문에, 태그 분리하여 사용함

```
<script type="text/Javascript" src="goodday.js">
window.alert('Hello, JavaScript");
//해당 내용 무시됨
</script>
```

```
<script type="text/Javascript" src="goodday.js"></script>
<script type="text/Javascript">
window.alert('Hello, JavaScript");
</script>
```
<br />
<br/>

#Script in Anchor Tag
Anchor tag의 href속성에 'Javascript:~" 의 형식으로 스크립트 넣을 수 있음.
JavaScript 의사 프로토콜이라 함

```
<a href="Javascript:스크립트 코드"> 링크 텍스트 </a>
```

예) 링크 클릭 시, 대화상자를 표기하고 싶을 경우, 아래 코드와 같이 표기함

```
<a href="Javascript:window.alert('hello,world');"> 대화상자 표시 </a>
```

<br/>
<br/>


#Comment in JavaScript 


```
//  comment        : comment in 1 line
/*  comment */     : comment in multiple lines
/** comment */	   : comment in document
```







