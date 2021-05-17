1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage = function (marks, total) {
  return (marks * 100) / total;
}
let percentage = (marks, total) => {
  return (marks * 100) / total;
}

let percentage = (marks, total) => (marks * 100) / total;

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

// Function Expression

```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

// Function Expression

```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

// Function Expression Arrow Function

```

```js
let percentage = (marks, total) => (marks * 100) / total;

// Function Expression

```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Ans: An Expression is anything that results into a value. A function definition  is an expression     in   JavaScript because it results into what we want from that particular function.

```js
let add = function (a, b) {
  return a +b;
}  // Function Expression
```
4. Why is a function call an expression in JavaScript?
Ans: Function call is also an expression because it always results into a value.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // VALID 5
five = add; // VALID 
five = five(10, 11); // valid 21
five = function () {
  return 'Hello';
}; // VALID 
```

6. What is the difference between function definition and function call? Explain with an example.

Ans: Difining a function means giving the steps that the function will follow whenever it is executed. On the other hand Fuction call is the execution of those defined steps. 

```js 
function add(a, b) {
 return a + b;
} // This is a function definition

add(12, 14) // This a function Call/execution

```


7. What is the similarities between function definition and function call?

Ans: Functions Definition as well as the function call, both are expessions in JavaScript. 

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // It is a valid piece of code as function is also an object.
```

9. What is higher order function explain with an example.

Ans: A function that accepts a function definition as an argument is known as Higher order function.
```js
function add (a, b) {
  return a + b; 
}
function average (a, b) {
  return add(a, b) / 2;
} // This is a HOF
``` 

10. Explain what is callback function. Why you can pass a function inside a function?

Ans: Whenever we pass a function definition inside another function the function becomes a higher order function and the function that we pass as parameter to the HOF is known as callback function.
We can Pass a function inside another function because function is an expression in javascript.