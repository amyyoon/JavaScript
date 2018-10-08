# SPA

SPA(Single Page Application) 이란, 단일 페이지로 구성된 웹 애플리케이션이다. 처음 한번 엑세스하면 웹 페이지 전체를 취득하고, 그 이후 Javascript으로 웹 페이지를 갱신한다. Javascript만으로 처리 못하는 경우도 있는데 이 때 Ajax등 비동기 통신을 이용하여 데이터를 취득하여 갱신한다.


```
클라이언트 <-----> 서버 (java/PHP/ASP.NET 등)

1. 최초 액세스 요청
2. HTML 페이지 전체에 응답 / 이벤트 발생
3. 웹 페이지 갱신은 Ajax등 비동기 통신으로 요청
4. 웹페이지 갱신에 필요한 데이터에 응답
5. JavaScript로 웹 페이지에 변경 사항 반영
```

# 트랜스 컴파일러?

ES2015의 코드를 ES5 사양의 코드로 변환하기 위한 툴
```
ES2015 소스코드 -> 트랜스 컴파일러로 변환 -> JavaScript 코드-> 실행-> 일반 브라우저에서 동작
```

#Google Chrome 개발자 도구의 메뉴
```
Elements : HTML/CSS 상태 확인
Network      : 브라우저에서 발생한 통신을 추적
Sources      : 스크립트 디버스 (브레이크 포인트 설치 및 변수 감시)
Timeline     : 성능 측정
Profiles     : Javascript에서 사용하고 있는 CPU/memory 정보 수집
Application  : Cookies/ Storage 확인
Audits 	   : 웹 페이지 분석하여 최적화를 위한 힌트를 리스트를 표시
Console	   : 변수 정보 확인 및 에러 메세지 표시 
```