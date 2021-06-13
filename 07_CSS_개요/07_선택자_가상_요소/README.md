### 선택자 가상 요소
## 가상 요소 선택자 (Pseudo-Elements) BEFORE

선택자 ABC 요소의 내부 앞에 내용을 삽입.

ABC::before (인라인 글자 요소)

```css
.box::before{
	content: "앞!";
}
```

### 가상 요소 선택자 (Pseudo-Elements) AFTER

선택자 ABC 요소의 내부 뒤에 내용을 삽입.

ABC::after (인라인 글자 요소)

```css
.box::after{
	content: "뒤!";
}
```