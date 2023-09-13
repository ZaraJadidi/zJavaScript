
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



































