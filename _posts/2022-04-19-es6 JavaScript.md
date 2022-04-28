---
layout: single
title: 자바스크립트 es6문법
categories: React
tag: [react, js]
toc: true
author_profile: false
sidebar:
  nav: "docs"
---

# 자바스크립트 es6문법

```js
// 1. object shorthand assignment 
let name = "noona";
let age = 17;

let person={
	name: name,
	age: age
};

console.log(person);
```


근데 이것을

```js
//key와 value의 값이 같을 경우

let name = "noona";
let age = 17;

let person={
	name,
	age
};

console.log(person);
```

이렇게 생략이 가능하다

```js
//2.Destructuring

let person ={
  name:"noona",
  age: 20
}

let name = person.name;
let age = person['age'];

// 여기를 객체로 써놓고 내가 갖고 오고 싶은 key 값을 써주는 거야.
//person이라는 객체에서 name 이라는 key 값을 분해하고 age 라는 key 값을 분해한다.
// 그것을 let 으로 선언한다.

let person ={
  name:"noona",
  age: 20
}

let {name, age} = person
```



