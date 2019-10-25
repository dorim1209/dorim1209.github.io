---
title: "TIL(about Arrow Function)"
date: 2019-10-25 11:06:00 -0400
categories: Arrow_Function
---

`ES5`

function add(a, b) {
return a + b;
}

function multiply(a, b) {
return a \* b;
}

<hr/>

`ES6`

const add = (a, b) => {
return a + b;
};

const multiply = (a, b) => {
return a \* b;
};

const multiply = (a, b) => a \* b;

const square = a => a \* a; //인자가 하나일 경우 괄호를 생략도 가능합니다.

const logging = () => console.log("logging..."); //인자가 하나도 없을 경우는 괄호를 꼭 해야합니다.
