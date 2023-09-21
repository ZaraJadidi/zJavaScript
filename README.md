
# What is JavaScript?
<br>
<br>
It is one of the most popular programming languages that makes websites dynamic and interactive. With JavaScript, we can also create mobile apps and games, process data, and much more!
<br>
<br>
console.log():
<br>
The console is part of the web browser and allows you to log messages, run JavaScript code, and see errors and warnings.It is used to generate output to the console.
<br>
<br>
Script:
<br>
we can add JavaScript code in an HTML document using the script tag.
In HTML:
<br>

```
<body>
    <script>
      console.log("JavaScript in HTML");
    </script>
</body>
```
<br>
<br>
<br>
alert():
<br> 
It is Used to display mesage.
<br>
<br>
<br>
Comments :
<br>
<br>
Comments are explanatory statements that you can include in a program to benefit the person reading your code.A single-line comment starts with //:
<br>
You can also create multi-line comments.They start with /* and end with */, making everything in between a comment.
<br>
<br>
<br>
<br>

## Calculation 
<br>
<br>
Multiplication:
<br>
Multiplication is done using an asterisk symbol * :
<br>
console.log(1*2)
<br>
<br>
Division :
<br>
Division is done using a slash:
<br>
console.log(42/7);
<br>
<br>
Exponentiation:
<br>
Two asterisks ** are used to raise a number to the power of another, which is called exponentiation.
<br>
console.log(x**y);
<br>
<br>
Remainder:
<br>
It is used to calculate the remainder of a division.
<br>
console.log(x % y );
<br>
<br>
Increment:
<br>
Sometimes we need to repeatedly add 1 to a variable.For example, when counting attempts in a game, or the number of clicks on a web page.This can be done using the increment (++) operator:
<br>

```
let count = 0;
count++;
console.log(count);
```
<br>
<br>
Decrement:
<br>
the decrement (--) operator can be used to subtract 1 from a variable.
<br>
The postfix form returns the original value of the variable, and only then increments/decrements it.
<br>

```
let x = 5;
console.log(x++);//5
console.log(x);//6
```

<br>
<br>

## Variables
to define a variable u can use : let , var , const 
<br>
<br>
assignment operator: to assign a value to an operator. we have = , += ( addition assignment operator :
<br>

let x = 15;
x+=5; // x = x+5;
x-=5; // x = x-5;
x*=5; // x = x*5;
x/=5; // x = x/5;
x%=5; // x = x%5;

) 
<br>
<br>
input :
let balance = parseInt(readLine(), 10);
let withdraw = parseInt(readLine(), 10);
<br>
<br>
<br>
What mistake i made and What i learned?!<br>
Spaces are important.
<br>

```
let country = readLine();
let capital = readLine();

//complete the code
console.log(`Country: ${country}, Capital: ${capital}`);
```
<br>
<br>

```
if (condition) {
    // block of code
}
```
<br>
<br>

 your program needs to perform some action only if the given condition is true. And this is where the if statement comes in.You can use any expression that can be evaluated as true or false for your if statement.
 <br>

 ```

let answer = "Maybe";
if(answer == "Yes!"){
    console.log("You are tough!")
}
```
<br>
<br>

```
${player}
```
<br>
<br>
<br>
 else statement : The code inside the else statement will be executed only if the condition is false.
<br>
<br>

```
let score = 98;

if(score >=100){
  console.log("Level Completed!");
} else {
  console.log("Try again!");
}
```
<br>
<br>
<br>
else if statement : There will be times when you want to test multiple conditions. That is where the else if block comes in. It's written between if and else statements.
<br>
<br>

```
let time = 15;

if (time < 10) {
  console.log("Good morning");
} else if (time < 20) {
  console.log("Good day");
} else {
  console.log("Good evening");
}
```
<br>
<br>
<br>
switch statement : The switch expression is evaluated once. The value of the expression is compared with the values of each case, and if there’s a match, that block of code is executed.You can achieve the same result with multiple if else statements, but the switch statement is more effective in such situations and makes the code more readable.
<br>
<br>

```
let choice = 1;

switch(choice){
  case 1://match!
    console.log("Sports");
    break;
  case 2:
    console.log("Business");
    break;
  case 3:
    console.log("Technology");
    break;
}
```
<br>
<br>
<br>
The default keyword : 
Often there will be no match, but we still need the program to do some action. For this, we use the default keyword, which specifies the code to run if there’s no case match.
<br>

```
let color ="yellow";

switch(color) {
  case "blue": 
    console.log("This is blue.");
    break;
  case "red": 
    console.log("This is red.");
    break;
  default: 
    console.log("Color not found.");
}
```
<br>
<br>
<br>
Ternary operator : Conditional, or ternary, operators assign a value to a variable, based on some condition. This operator is frequently used as an alternative to an if else statement.
<br>
<br>

```
variable = (condition) ? value1: value2
```
<br>

```
let age = 42;
let isAdult = (age < 18) ? "Too young": "Old enough";
console.log(isAdult);
```
<br>
<br>
<br>
Loops 


Loops allow you to run the same code multiple times.
<br>
<br>
for:
<br>
<br>
```
for (initializer; condition; final-expression) {
    // code to run
}
```
<br>

```
for (let i = 1; i <= 10; i++) {
    console.log(i);
}
```
<br>
<br>


while 

<br>
<br>
The while loop is another way to create loops.It runs as long as the condition is true.

```
while(condition) {
  //code to run
}
```
<br>
<br>
<br>
do...while
<br>
<br>
This loop will execute the code block once, before checking if the condition is true, and then it will repeat the loop as long as the condition is true.The condition is tested after the first iteration, that's why the code inside it is executed once. The while loop with the same conditions will not output anything in this case.

<br>
<br>

```
let i=5;
do {  
    console.log(i);
    i++;  
}
while (i<5);
```
<br>
<br>
<br>
The break statement : The break statement allows you to exit a loop prematurely, based on the given condition.This can be useful, for example, to exit a loop when the user enters a specific number, or taps on a specific button.

<br>
<br>

```
for(let i=0; i<10;i++) {
  if(i==3) {
    break;
  }
  console.log(i);
}
```
<br>
<br>
<br>
continue  : The continue statement is used to skip an iteration of the loop and continue from the next one.This can be useful, for example, to skip some particular elements in the loop:
<br>

```
for(let i=0;i<10;i++) {
  if(i == 5) {
    continue;
  }
  console.log(i);
}
```

<br>
<br>
<br>
Functions :
<br>
<br>
A function is a block of code designed to perform a particular task.For example, our app can have functions like login(), logout(), convert(), etc.The purpose of a function is to create it once and call it multiple times when needed to perform particular tasks.
To define a function, use the function keyword, followed by a name, followed by a set of parentheses ().


<br>
<br>

Parameters :
<br>
Functions can have parameters.The parameters are defined in the parentheses and can be used like variables in the function.

```
function login(user) {
   console.log("Hi, "+user);
}
```
<br>
To call it :

```

login("james");
login("bob");
```
<br>

```
function login(user) {
  console.log("Hi, "+user);
}
let myUser = "Bob";
login(myUser);
```
<br>
<br>
<br>
Returning from functions
<br>
<br>
The methods we have seen so far output their result.In some cases, we do not need to output the result but need to assign it to a variable, to work with it in our program.The return statement ends the function execution, which means that everything after it inside the function will be ignored - the program just goes on from the scope of the function.

```
function add(x,y){
  return x+y;
}

let result = add(5,6);
console.log(result);
```
<br>
<br>
<br>
JavaScript Objects
<br>
JavaScript variables are containers for data values. Objects are variables too, but they can contain many values. JavaScript objects are containers for named values.

```
var person = {
 name: "John", age: 31, 
 favColor: "green", height: 183
};
```
<br>
In reference to an object, color, height, weight, and name are all examples of properties.
<br>
<br>
<br>

Object Properties : You can access object properties in two ways.

<br>
<br>

```
objectName.propertyName
//or
objectName['propertyName']
```
<br>

```
var person = {
 name: "John", age: 31, 
 favColor: "green", height: 183
};
var x = person.age;
var y = person['age'];
```
<br>
<br>
Length : JavaScript's built-in length property is used to count the number of characters in a property or string.
<br>
<br>

```
var course = {name: "JS", lessons: 41};
document.write(course.name.length);
```
<br>
<br>
Object Methods :
<br>
An object method is a property that contains a function definition.document.write() outputs data. The write() function is actually a method of the document object.Methods are functions that are stored as object properties.


<br>
<br>

```
objectName.methodName()
```

<br>
Use the following syntax to create an object method:

```
methodName = function() { code lines }
```
<br>
<br>
Access an object method using the following syntax:

```
objectName.methodName()
```
<br>
<br>
The Object Constructor
<br>
<br>
 we need to set an "object type" that can be used to create a number of objects of a single type. The standard way to create an "object type" is to use an object constructor function

```
function person(name, age, color) {
  this.name = name;
  this.age = age;
  this.favColor = color;
}
```
<br>
The this keyword refers to the current object.Note that this is not a variable. It is a keyword, and its value cannot be changed.
<br>
<br>
Once you have an object constructor, you can use the new keyword to create new objects of the same type.

```
var p1 = new person("John", 42, "green");
var p2 = new person("Amy", 21, "red");

document.write(p1.age); // Outputs 42
document.write(p2.name); // Outputs "Amy"
```
<br>
<br>
<br>
Methods : Methods are functions that are stored as object properties. 
















































