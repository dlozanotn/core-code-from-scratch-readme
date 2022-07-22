


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



# Wednesday 19 of July of 2022
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




</HTML>