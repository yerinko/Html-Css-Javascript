## DOM API
Document Object Model ( div, p, span ... ), Application Programming Interface

-  ' Javscript에서 Html을 제어하는 명령들 '


## HTML요소 (Elemenet) 1개 검색/찾기
```
const boxEl = document.querySelector('.box');
```

## HTML 요소에 적용할 수 있는 메소드!
```
boxEl.addEventListener();
```

## 인수(Arguments)를 추가 기능!
```
boxEl.addEventListener(1,2);
```

## 1 - 이벤트(Event, 상황)
```
boxEl.addEventListener('click', 2);
```

## 2- 핸들러(Handler, 실행할 함수)
```
boxEl.addEventListener('click', function() {
console.log('Click~!');
});
```

## HTML 요소(Element) 검색/찾기
```
const boxEl = document.querySelector('.box');
```

## 요소의 클래스 정보 객체 활용!
```
boxEl.classList.add('active');
let isContains = boxEl.classList.contains('active');
console.log(isContains); //true
```
```
boxEl.classList.remove('active');
let isContains = boxEl.classList.contains('active');
console.log(isContains); //true
```



