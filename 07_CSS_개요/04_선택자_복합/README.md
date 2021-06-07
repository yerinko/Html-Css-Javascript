### 선택자 복합
## 일치 선택자
선택자 ABC와 XYZ를 동시에 만족하는 요소 선택
```
span.orange {
	color: red;
} // 태그 선택자가 꼭 앞에 위치해야한다.
```

## 자식 선택자
선택자 ABC의 자식 요소 XYZ 선택
ABC > XYZ
```
ul > .orange {
	color: red;
} // 클래스가 orange인데, 부모가 ul이어야 한다.
```

## 하위(후손) 선택자
선택자 ABC의 하위 요소 XYZ 선택.

'띄어쓰기'가 선택자의 기호 ! 

ABC XYZ
```
div .orange {
	color: red;
}
```

## 인접 형제 선택자
선택자 ABC의 다음 형제 요소 XYZ 하나를 선택
```
.ornage + li {
	color: red;
}
```

## 일반 형제 선택자
선택자 ABC의 다음 형제 요소 XYZ 모두를 선택
```
.ornage ~ li {
    color: red;
}
```