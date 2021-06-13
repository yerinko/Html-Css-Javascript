### 선택자 가상 클래스(2)
## 가상 클래스 선택자 (Pseudo-Classes) 
FIRST CHILD
선택자 ABC가 형제 요소 중 첫째라면 선택.
ABC:first-child
```
.fruits span:first-child {
    color: red;
}
```

## 가상 클래스 선택자
LAST CHILD
선택자 ABC가 형제 요소 중 막내라면 선택.
ABC:last-child
```
.fruits h3:last-child {
    color: red;
}
```

## 가상 클래스 선택자
NTH CHILD
선택자 ABC가 형제 요소 중 (n)째라면 선택.
```
.fruits *:nth-child(2) {
    color: red;
}
.fruits *:nth-child(2n) {
    color: red;
}
.fruits *:nth-child(2n+1) {
    color: red;
}
```

## 부정 선택자(Negation) NOT
선택자 XYZ가 아닌 ABC요소 선택
```
.fruits *:not(span) {
    color: red;
}
```