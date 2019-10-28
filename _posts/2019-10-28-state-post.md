---
title: "TIL(about state)"
date: 2019-10-28 17:24:00 -0400
categories: state
---



#### state값 바꾸는 올바른 예



```
handlePlus = () => {

  this.setState({ number: this.state.number + 1 });
  console.log(this.state.number);

 };
```



#### state값 바꾸는 틀린 예

```
handlePlus = () => {

  
  this.state = { number: this.state.number + 1 };
	console.log(this.state.number);

 };
```

<u>결과적으로 console창에 찍힌 number 값은 같지만</u>

<u>rerendering이 되지 않아 화면에 올바르게 출력되지 않음</u>

