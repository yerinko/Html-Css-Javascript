## Doctype(DTD), HTML, HEAD, BODY

```html
// index.html

<!doctypehtml>
<htmllang="en">
<head>
    <metacharset="UTF-8">
    <metaname="viewport"
content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <metahttp-equiv="X-UA-Compatible"content="ie=edge">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

Tag는 영역을 말합니다.

우리는 정해진 규칙을 통해서 코드를 만들어야 합니다 ✍🏻

```html
<!doctype html>
<htmllang="en">
<head>
   
</head>
<body>

</body>
</html>
```

## <!doctype html>

- 문서(페이지)의 HTML 버전을 지정
- DOCTYPE(DTD, Document Type Definition) 은 마크업 언어에서 문서 형식을 정의하며, 웹 브라우저가 어떤 HTML 버전의 해석 방식으로 페이지를 이해하면 되는지를 알려주는 용도.

HTML1, HTML2, HTML3, HTML4, XHTML, **HTML5(표준)**

index.html 파일을 HTML 문서라고도 부릅니다. 혹은 main.css 파일을 CSS 문서, main.js 파일을 JavaScript 문서라고도 부릅니다. 그리고 우리가 브라우저로 접속하는 각 웹페이지는 기본적으로 하나의 HTML 파일이 동작하는 것이기 때문에, HTML(특히 index.html)을 하나의 페이지로 이해할 수도 있습니다.

## html 시작태그 ... 종료태그

- 문서의 **전체** 범위
- HTML 문서가 어디에서 시작하고, 어디에서 끝나는지 브라우저에게 알려주는 역할

## head

- 문서의 **정보**를 나타내는 범위
- 웹 브라우저가 해석해야 할 웹 페이지의 제목, 설명, 사용할 파일 위치, 스타일(CSS)같은 웹페이지의 보이지 않는 정보를 작성하는 범위.

## body

- 문서의 **구조를** 나타내는 범위
- 사용자 화면을 통해 보여지는 로고, 헤더, 푸터, 내비게이션, 메뉴, 버튼, 이미지 같은 웹 페이지의 보여지는 구조를 작성하는 범위