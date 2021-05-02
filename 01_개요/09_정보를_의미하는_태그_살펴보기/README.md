## 정보를 의미하는 태그 살펴보기

```html
<!doctype html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible"content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet"href="./main.css">
    <script src="./main.js"></script>
    <style>
        div {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div>Hello world!</div>
</body>
</html>
```

## Title

```html
<title> Naver </title>
```

HTML 문서의 제목(title)을 정의.

웹 브라우저 탭에 표시 됨!!

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5eeb95f-17ac-480d-8742-ce60405132a2/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5eeb95f-17ac-480d-8742-ce60405132a2/Untitled.png)

## Link

```html
<link rel="stylesheet" href="./main.css" />

<link rel="icon" href="./favicon.png">
```

외부 문서를 가져와 연결할 때 사용. ( 대부분 CSS 파일 )

rel ⇒ **가져올** 문서와 **관계**

href ⇒ **가져올** 문서의 **경로**

Favicon ⇒ favorite Icon 줄임말 

## Style

스타일(CSS)를 HTML 문서 안에서 작성하는 경우에 사용.

```html
<style>
    div {
        text-decoration: underline;
    }
</style>
```

## Script

1. 자바스크립트(JS) 파일 가져오는 경우.

```html
<script src="./main.js"></script>
```

2. 자바스크립트(JS)를 HTML 문서 안에서 작성하는 경우

```html
<script> console.log('Hellow world')</script>
```

## Meta

```html
<meta charset="UTF-8"> // 문자인코딩 방식
<meta name="author" content="yerinko" /> // 제작자
<meta name="viewport"
content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
<meta http-equiv="X-UA-Compatible"content="ie=edge"> // 모바일에서만 필요함
```

<meta/>는 HTML 문서(웹페이지)의 제작자, 내용, 키워드 같은, 여러 정보를 검색엔진이나 브라우저에게 제공.