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

first:with this function we will get a return on screen.

second:with this function we can see result on console to check whether its right.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

function sum(a, b) {
return a + b;
}
The return value will depend on the value we,
put in the variable but in oder to display it we have to use function.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
   function sum(a+b) {
   return a + b;
   }

let first=sum
sum(12,24,35)

Ans,Nan.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

Ans;function sayHello(name) {
let name=Arya
alert{`Hello${name}}
}

sayHello(name) 6. What will be the output of the function below and why?

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

showMessage();
```

Ans;It will print "Hello,John"

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

alert(userName); // "John"

showMessage(); // undefined

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
   let add = (a, b) => a + b;  
   let mul =(a,b)=>a\*b;
   let sub =(a,b)=>a-b;

9. Can function declaration be a Anonymous Function? Explain
   Ans;Yes,function declaration can be made anonymous by removing the function name like function add(numA,numB) {return numA+numB} add(10,21) can be written as function(numA,numB) {return numA+numB}
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with???

"get???" ??? return a value,
"calc???" ??? calculate something,
"create???" ??? create something,
"check???" ??? check something and return a boolean, etc.
```

UnderScores
Dashes
NoSeparation
CamelCase,
userName
