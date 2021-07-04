# 함수
특정 동작(기능)을 수행하는 일부 코드의 집합(부분)

## function

```jsx
//함수 선언
function helloFunc() {
	//실행 코드
console.log(1234);
}

//함수 호출
helloFunc(); //1234
```

명령들을 감싸고 있는 집합이라고 할 수 있다.

```jsx
function returnFunc() {
	return 123;
}

let a = returnFunc();
console.log(a); // 123
```

```jsx
// 함수 선언!
function sum(a,b) { // a와 b는 매개변수(Parameters)
	return a + b;
}

// 재사용!
let a = sum(1, 2); // 1과 2는 인수(Arguments)
let b = sum(7, 12);
let c = sum(2, 4);

console.log(a,b,c); // 3, 19, 6
```