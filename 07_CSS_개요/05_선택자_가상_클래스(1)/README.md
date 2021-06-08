### 선택자 가상 클래스
## HOVER
선택자 ABC요소에 마우스 커서가 올라가 있는 동안 선택
ABC:hover
```
a:hover {
    color: red;
}
```
```
.box {
  width: 100px;
  height: 100px;
  background-color: orange;
  transition: 1s;
}
.box:hover {
  width: 300px;
  background-color: royalblue;
}
```

## ACTIVE
선택자 ABC요소에 마우스를 클릭하고 있는 동안 선택
ABC:active
```
a:active {
    color: red;
}
```
```
.box {
  width: 100px;
  height: 100px;
  background-color: orange;
  transition: 1s;
}
.box:active {
  width: 300px;
  background-color: royalblue;
}
```

## FOCUS
선택자 ABC요소가 포커스되면 선택
```
input:focus {
	background-color: orange;
}
```
⚠️ **tabIndex**: 속성을 통해 Focuse가 될 수 있는 요소를 만들 수 있습니다.
  이름에서도 알 수 있듯, Tab 키를 사용해 Focus할 수 있는 순서를 지정하는 속성입니다.
  순서(값)로 -1이 아닌 다른 값을 넣는 것은 논리적 흐름을 방해하기 떄문에 권장하지 않습니다.