


<HTML>

<h1 style='color: #7C278D;'>DAVID LOZANO</h1>


# core-code-from-scratch-readme
Works of the course


![David Lozano](images/header-nueva-paginasin-fondo.png)

# Tuesday 19 of July of 2022

## Interpreted And Compiled Programming Languages
<br>

compiled languages are those that communicate directly with the cpu, and need to be compiled so that they can be interpreted to binary code and communicate directly with the computer.

interpreted languages are those that can be understood both by us and the computer, since they are run by commands.

compiled languages: C, C++, 

interpreted languages: PHP, Javascript

Hybrid: Java, Python



## Is Java compiled or interpreted, or both?,
<br>

Both, because  a java program is first compiled into bytecode which JRE can understand. ByteCode is then interpreted by the JVM making it as interpreted language.

Learn about the basics of programming and start knowing Javascript.
<br>
<br>

## Week subtopics 
<br>

| Preguntas    🧐       | Respuestas  🤭                                                             |
| ----------------- | ------------------------------------------------------------------ |
| What does programming look like? | Programming is an activity that makes us feel alive, and shows that we are intelligent beings. Programming is not a mechanical activity. |
| What really is programming? | Programming is the process of creating a set of instructions that tell a computer how to perform some kind of task. |
| What is a program? | A computer program or computer program is a sequence of instructions, written to perform a specific task on a computer.  |
| How a computer run a program? |  Instruction by instruction until it ends. |
| Algorithmic operations | Operators are symbols that represent an action to be performed with the numbers or elements before or after them. |
| Sequential | Also known as sequential structure, it is one in which one instruction or action follows another in sequence.|
| Conditional | A conditional, as its name indicates, is a condition to discern between one option or another, and in the mental process it is normally manifested with an "If"; for example: If (it is going to rain), take the umbrella. |
| Iterative |  The operations or instructions are the same but the data being processed may change during the execution of the cycle. |
| Basic elements of programming | Common language, Flowcharts, Pseudocode, Programming languages, Programming languages. |
| Instruction set | a program is nothing more than a set of statements that are executed to perform a certain task. |
| Variables | In programming, a variable consists of a space in the storage system (main memory of a computer) and a symbolic name (an identifier) that is associated with that space. |
| Output | In computing, the output corresponds to the data provided by a computer after processing the information it has received.|
| Wat is javascript? | JavaScript is an interpreted programming language, a dialect of the ECMAScript standard. |
| What is an interpreted language? |is defined as object-oriented, prototype-based, imperative, weakly typed and dynamic.|
| HTMl basics | Hypertext Markup Language (HTML) is the code used to structure and display a web page and its contents. |
| Javascript Hello World | Console.log('Hello World...') |
| Variables in Javascript | Var, Const, let> |
| Basic HTML structure | The basic structure of a web page consists of <html>, <head> and <body> tags. |

## Pseudocode 
<br>

 1.Starting point: START
  2.Input: READ, GET
  3.Output: PRINT
  4.Math: +, -, *, /
  5.Assignation: <--
  6.Initialize:  SET, INIT
  7.Add one: INCREMENT
  8.End point: END
  
  
**SOLUTION**
  
  1. START
  2. Amount of dollar <-- GET
  3. BTCprice <-- GET FROM[(https://www.coinbase.com/es-LA/converter/btc/usd)]
  4. total dollar <-- Amount of dollar * BTCprice
  5. PRINT Total dollar (result of convert bitcoin to dollar)
  6. END



## Core Challenges Mission Statement 

<br>
I'm David Lozano, I'm a web designer, I've worked with wordpress, figma, html and css, in agencies in USA; but what I want to learn is to program, to be a frontend, or full stack, and I want to work in companies where I can develop and in the future, create my own web applications.

I am a curious, resilient, self-taught and self-directed person, and I believe that you can always learn something new every day.💻 

<br>



# Wednesday 20 of July of 2022
<br>

## 1.Your date of birth in the matrix? exercise
<br>

28 04 1985 convert to binary

First 28   

| 32 | 16| 8| 4|2 | 1|
|:-------------------:|---|---|---|---|---|
| 0 | 1 | 1| 1 | 0 | 0

## 28 = 011100 <br>

Second 4
 
 | 8 | 4| 2| 1|
|:-------------------:|---|---|---|
| 0 | 1 | 0| 0 | 

## 4 = 0100

Third 1985

| 2048 | 1024| 512| 256| 128 |64 | 32 | 16| 8 | 4 | 2 | 1|
|:-------------------:|---|---|---|---|---|---|---|---|---|---|---|
| 0 | 1 | 1| 1 | 1 | 1 | 0 | 0 | 0| 0 | 0| 1|

## 1985 = 011111000001
<br>

**Solution**

<br>

## 28= 011100

## 4= 0100

## 1985= 011111000001 

<br>


## 2.MIPS exercise 
<br>

1. **Create a program that adds any two given numbers provided by the user:**

```
.data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              add $t2, $t0, $t1
              
              li $v0, 1
              move $a0, $t2
              syscall
```






2.  **Create a program that displays your name:**
 
 ```
 .data
        message: .asciiz "\nDavid Lozano Tenorio\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall

```
<br>


# Thursday 21 of July of 2022
<br>

# Print special numbers

## Description

In this exercise you must use an iterative flow control to be able to print all the even numbers in the range of numbers from 0 to 100. Remember that you should not print each number, you should use a flow control structure to perform the exercise.

Help

0.For <br>
1.While <br>
2.do While <br>
3.Even number<br>
4.Reminder Operator

<br>

## FOR
<br>

```javascript

let str = '';
for (let i = 0; i <= 100; i=i+2) {
    str = str + i;
}
console.log(str);

```
## WHILE
<br>

```javascript

var x = 0;
while (x <= 100){
    console.log(x);
    x += 2;
}



```

## DO WHILE
<br>

```javascript

let result = '';
let i = 0;

do {
  i = i + 2;
  result = result + i;
} while (i < 100);

console.log(result);



```

# Bad code
## Description
<br>
The code shown below is not working in the right way, as a task you must find the error made by the developer who programmed this code and correct it, for this exercise you must explain what the error is and place the correct code

```javascript

var cond = false;

if ((cond === true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}

```


# Bad code2
## Description
<br>
The code shown below is not working in the right way, as a task you must find the error made by the developer who programmed this code and correct it, for this exercise you must explain what the error is and place the correct code

```javascript

const  n = 100;

if (n == 100) {
  console.log("¡Este es un número especial!");
} else if (n < 1000 || n % 10 == 0) {
 console.log('Este número es casi especial');
} else {
  console.log('Sólo un número normal');
}

```
<br>
<br>


# Monday 25 of July of 2022
<br>

# IF..ELSE

The if statement executes a statement if a specified condition is [truthy
](https://developer.mozilla.org/en-US/docs/Glossary/Truthy). If the condition is [falsy](https://developer.mozilla.org/en-US/docs/Glossary/Falsy), another statement in the optional else clause will be executed.

```javascript

const  n = 100;

function testNum(a) {
  let result;
  if (a > -6) {
    result = 'positive';
  } else {
    result = 'NOT positive';
  }
  return result;
}

console.log(testNum(-5));
// expected output: "NOT positive"

```

# FOR

The for statement creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement (usually a [block statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block)) to be executed in the loop.

```javascript

let str = '';

for (let i = 0; i < 9; i++) {
  str = str + i;
}

console.log(str);
// expected output: "012345678"

```

# WHILE

The while statement creates a loop that executes a specified statement as long as the test condition evaluates to true. The condition is evaluated before executing the statement.

```javascript

let n = 0;

while (n < 3) {
  n++;
}

console.log(n);
// expected output: 3

```

# FUNCTION DECLARATION

The function declaration (function statement) defines a function with the specified parameters.

You can also define functions using the [Function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function) constructor and a [function expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function).

```javascript

function calcRectArea(width, height) {
  return width * height;
}

console.log(calcRectArea(5, 6));
// expected output: 30

```

# Tuesday 26 of July of 2022
<br>

# Excersices CodeWars

Multiply exercise

```javascript

function multiply(a, b){
  return (a * b)
  console.log(multiply)
}


```


ASCII Total exercise

```javascript

function uniTotal(str) {
  let total = 0;
  for (let i = 0, length = str.length; i < length; i++) {
    total += str[i].charCodeAt();
  }
  return total;
}


```
Char From ASCII Value exercise

```javascript

function getChar(a){
  // ...
  return  String.fromCharCode(a);
}


```

Binary Addition exercise

```javascript

function addBinary(a, b) {
  return (a + b).toString(2);
}



```

Student's Final Grade exercise
```javascript

function finalGrade(exam, projects) {
  if (exam > 90 || projects > 10) return 100;
  if (exam > 75 && projects >= 5) return 90;
  if (exam > 50 && projects >= 2) return 75;
  return 0;
}


```

# Thursday  28 of July of 2022
<br>

# 1.Remove All Exclamation Marks From The End Of Sentence exercise<br>
<br>

```javascript

function remove(string) {
  return string.replace(/!+$/, '');
}

```



# 2.Vowel Remover exercise <br>
<br>

```javascript

function shortcut(string) {
  return string.replace(/[aeiou]/g, '');
}


```


# 3.Rock Paper Scissors! exercise<br>
<br>

```javascript

const rps = (p1, p2) => {
  let rules = { rock: 'scissors', paper: 'rock', scissors: 'paper' };
  if (p1 === p2) return 'Draw!';
  if (p2 === rules[p1]) {
    return 'Player 1 won!';
  }
  return 'Player 2 won!';
};


```




# 4.Persistent Bugger exercise
<br>

```javascript

function persistence(num) {
  let times = 0;
  num = num.toString();
  while (num.length > 1) {
    times++;
    num = num
      .split('')
      .map((a) => Number(a))
      .reduce((a, b) => a * b)
      .toString();
  }
  return times;
}


```











</HTML>