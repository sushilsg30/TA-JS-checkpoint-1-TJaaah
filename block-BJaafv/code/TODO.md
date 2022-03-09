1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}

```
2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`. // first = a + b; second =a +b;/undefined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why? //this some is not defined

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why? // we can use function as expression.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.//not solved.

6. What will be the output of the function below and why? // `Hello John ` // function used already defined userName.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // `John`

showMessage(); // `Hello, John` 

alert(userName); // `John`
```

8. What is a Anonymous Function give example of three functions. // In anonymous function when we define a variable that name of function is not necessary we remove that and function become anonymous.It is only possible in function expression.
```js
const addNumbers = function(a,b) {
  return a + b;
}
const multiplyNumbers = function(a,b) {
  return a * b;
}
const sayHello = function(name) {
  return `Hello ${name}`;
}
```

9. Can function declaration be a Anonymous Function? Explain // No it is not possible in function declration.// no variable.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that. // 

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value, //getValue
"calc…" – calculate something, calcAdd
"create…" – create something, // createId
"check…" – check something and return a boolean, etc. //checkValue
```
