### 선언 방식
## 1. 내장 방식
style의 내용(Contents)으로 스타일을 작성하는 방식

장점

- 별도의 CSS 파일을 만들지 않아도 된다. 

단점

- 구별해서 관리하기 어렵다.
- 유지보수 측면에서 단점이 많다.

### 2. 링크 방식 (병렬방식)
link로 외부 CSS 문서를 가져와서 연결하는 방식
```
<link rel="styleshhet" href="./css/main.css">

../main.css
div {
	color: red;
}
```

### 3. 인라인 방식
요소의 style 속성에 직접 스타일을 작성하는 방식
```
<div style="color: red; margin: 20px;"> </div>
```
단점
- 우선순위로 유지보수가 어렵다.

### 4. import 방식 (직렬방식)
CSS의 @import 규칙으로 CSS문서 안에서 또 다른 CSS 문서를 가져와 연결하는 방식
```
<link rel="stylesheet" href="./css/main.css">
```