
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







































