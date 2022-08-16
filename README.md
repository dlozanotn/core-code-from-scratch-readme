


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
};


```

# Monday   01 of Agust of 2022
<br>

# 1.Who likes it ?<br>
<br>

```javascript

function likes(names) {
  if(Array.isArray(names)){
   
   return names.length > 3 ? names.slice(0,2).join(', ') + ' and ' + (names.length - 2) +' others like this'
        : names.length === 3 ? names.slice(0,2).join(', ') + ' and ' + names[2] + ' like this'
        : names.length === 2 ? names.join(' and ') + ' like this'
        : names.length === 1 ? names[0] + ' likes this' : 'no one likes this'
  } else {
    throw 'params must be a array.'
  }
}
```

# 2.Bit Counting exercise<br>
<br>

```javascript

var countBits = function(n) {
   // make an array with the bit result
   const base = (n).toString(2).split('');
   
   // make a sum with the array and make the index a Number
   const result = base.reduce((sum, num) => sum + Number(num), 0);
   
   return result;
};

```

# 3.Your Order, Please exercise<br>
<br>

```javascript

function order(words){
  let arr = words.split(' ')
  let r = []

  arr.forEach(word=>{
    let x = word.split('')
    let num = x.find(el=>parseInt(el))
    r.push([word,parseInt(num)]) 
  })

  r.sort((a,b)=>a[1]-b[1]).map(x=> x.splice(1,1))
  return r.join(' ')
}


```

#  *Martes 02-08-22*

## *1. Ejercicio - simple de latín de cerdo*
<br>

- **Descripción:** Mueva la primera letra de cada palabra al final de la misma, luego agregue "ay" al final de la palabra. Deje los signos de puntuación intactos.

- **Ejemplo:**
  - pigIt('Pig latin is cool'); // igPay atinlay siay oolcay
  - pigIt('Hello world !');     // elloHay orldway !

- **Solución:**
```javascript
function pigIt(str){
  return str.replace(/(\w)(\w*)(\s|$)/g, '$2$1ay$3');
}
```


## *2. Ejercicio - conteo de duplicados*

- **Descripción:** Escriba una función que devuelva el recuento de caracteres alfabéticos y dígitos numéricos distintos que no distinguen entre mayúsculas y minúsculas que aparecen más de una vez en la cadena de entrada. Se puede suponer que la cadena de entrada contiene solo letras (tanto mayúsculas como minúsculas) y dígitos numéricos.

- **Ejemplo:**

  - "abcde" -> 0 # no characters repeats more than once
  - "aabbcde" -> 2 # 'a' and 'b'
  - "aabBcde" -> 2 # 'a' occurs twice and 'b' twice (`b` and `B`)
  - "indivisibility" -> 1 # 'i' occurs six times
  - "Indivisibilities" -> 2 # 'i' occurs seven times and 's' occurs twice
  - "aA11" -> 2 # 'a' and '1'
  - "ABBA" -> 2 # 'A' and 'B' each occur twice

- **Solución:**
```javascript
function duplicateCount(text) {
  return text
    .toLowerCase()
    .split('')
    .filter((char, i, arr) => {
      return arr.indexOf(char) !== i && arr.lastIndexOf(char) === i;
    }).length;
}
```

## *3. Ejercicio - decodificar el código Morse*

- **Descripción:** En este kata tienes que escribir un decodificador de código Morse simple. Si bien el código Morse ahora es reemplazado en su mayoría por los canales de comunicación de voz y datos digitales, todavía se usa en algunas aplicaciones en todo el mundo. El código Morse codifica cada carácter como una secuencia de "puntos" y "guiones". Por ejemplo, la letra A se codifica como ·−, la letra Q se codifica como −−·− y el dígito 1 se codifica como ·−−−−. El código Morse no distingue entre mayúsculas y minúsculas, tradicionalmente se utilizan letras mayúsculas. Cuando el mensaje está escrito en código Morse, se utiliza un solo espacio para separar los códigos de caracteres y 3 espacios para separar palabras. Por ejemplo, el mensaje HEY JUDE en código Morse es ···· · −·−−   ·−−− ··− −·· ·.
- NOTA: Los espacios adicionales antes o después del código no tienen significado y deben ignorarse.
 Además de letras, dígitos y algunos signos de puntuación, hay algunos códigos de servicio especiales, el más notorio de ellos es la señal de socorro internacional SOS (que fue emitida por primera vez por Titanic), que está codificada como ···−−−···. Estos códigos especiales se tratan como caracteres especiales únicos y, por lo general, se transmiten como palabras separadas Su tarea es implementar una función que tome el código morse como entrada y devuelva una cadena descifrada legible por humanos.

- **Ejemplo:**

  - decodeMorse('.... . -.--   .--- ..- -.. .')
//should return "HEY JUDE"

- **Solución:**
```javascript
decodeMorse = function (morseCode) {
  return morseCode
    .split(' ')
    .map((word) => MORSE_CODE[word] || ' ')
    .join('')
    .replace(/  /g, ' ')
    .trim();
};
```
# *Miércoles 03-08-22*

## *1. Ejercicio - Parentesis válidos*

- **Descripción:** Escribe una función que tome una cadena de paréntesis y determine si el orden de los paréntesis es válido. La función debe devolver verdadero si la cadena es válida y falso si no es válida.

- **Ejemplo:**
  - "()"              =>  true
  - ")(()))"          =>  false
  - "("               =>  false
  - "(())((()())())"  =>  true

- Restricciones 
  - 0 <= entrada.longitud <= 100

- **Solución:**
```javascript
function validParentheses(parens) {
  let valid = 0;
  for (let i = 0; i < parens.length; i++) {
    if (parens[i] === ')') valid--;
    if (parens[i] === '(') valid++;
    if (valid < 0) return false;
  }
  return valid == 0;
}
```


## *2. Ejercicio - Convertir cadena en caso de camello*

- **Descripción:** Complete el método/función para que convierta las palabras delimitadas por guiones/guiones bajos en mayúsculas y minúsculas. La primera palabra dentro de la salida debe estar en mayúsculas solo si la palabra original estaba en mayúsculas (conocido como Upper Camel Case, también conocido como caso Pascal).

- **Ejemplo:**
  - "the-stealth-warrior" gets converted to "theStealthWarrior"
  - "The_Stealth_Warrior" gets converted to "TheStealthWarrior"

- **Solución:**

```javascript
function toCamelCase(str){
  let resultado = '';
  let pos = str.length;
  for(let i = 0; i < pos; i++){
    if(i != 0 && (str[i - 1] === '_' || str[i - 1] === '-')) {
      resultado += str[i].toUpperCase();
    } else if (str[i] != '-' && str[i] != '_') {
      resultado += str[i];
    }
  }
  return resultado;
}
```


## *3. Ejercicio - único en orden*

- **Descripción:** Implemente la función unique_in_order que toma como argumento una secuencia y devuelve una lista de elementos sin ningún elemento con el mismo valor uno al lado del otro y conservando el orden original de los elementos.

- **Ejemplo:**
  - uniqueInOrder('AAAABBBCCDAABBB') == ['A', 'B', 'C', 'D', 'A', 'B']
  - uniqueInOrder('ABBCcAD')         == ['A', 'B', 'C', 'c', 'A', 'D']
  - uniqueInOrder([1,2,2,3,3])       == [1,2,3]

- **Solución:**
```javascript
function uniqueInOrder(iterable) {
  let result = [];
  let last;
  for (let i = 0; i < iterable.length; i++) {
    if (iterable[i] !== last) {
      last = iterable[i];
      result.push(last);
    }
  }
  return result;
}
```
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy

#  *Jueves 04-08-22*

## *1. Ejercicio - Plegar una matriz*

- **Descripción:** En este kata, debe escribir un método que doble una matriz determinada de números enteros por el medio x veces.

- **Ejemplo:**
  - Fold 1-times:
  - [1,2,3,4,5] -> [6,6,3]

  - A little visualization (NOT for the algorithm but for the idea of folding):

  - Step 1         Step 2        Step 3       Step 4       Step5
  -                    5/           5|         5\          
  -                   4/            4|          4\      
  -                   1 2 3 4 5      1 2 3/         1 2 3|       1 2 3\       6 6 3
  -                   ----*----      ----*          ----*        ----*        ----*


  - Fold 2-times:
  - [1,2,3,4,5] -> [9,6]
  
- **Solución:**

```javascript
function foldArray(a, n) {
  const r = [],
    c = a.slice();
  while (c.length) r.push(c.pop() + (c.shift() || 0));
  return n - 1 ? foldArray(r, n - 1) : r;
}
```

## *2. Ejercicio - Cifrar esto!*

- **Descripción:** ¡Cifra esto! ¡Quieres crear mensajes secretos que puedan ser descifrados por Descifrar esto! kata. Aquí están las condiciones: 
- Su mensaje es una cadena que contiene palabras separadas por espacios. 
- Debe encriptar cada palabra en el mensaje usando las siguientes reglas: 
  - La primera letra debe convertirse a su código ASCII. 
  - La segunda letra debe ser intercambiada con la última letra 
- Manteniéndolo simple: no hay caracteres especiales en la entrada.

- **Ejemplo:**
  - encryptThis("Hello") === "72olle"
  - encryptThis("good") === "103doo"
  - encryptThis("hello world") === "104olle 119drlo"

- **Solución:**

```javascript
function encryptedWord(word) {
  if (word.length == 1) return word.charCodeAt();
  if (word.length == 2) return `${word.charCodeAt(0)}${word[1]}`;
  return `${word.charCodeAt(0)}${word[word.length - 1]}${word.slice(
    2,
    word.length - 1
  )}${word[1]}`;
}
var encryptThis = function (text) {
  return text.split(' ').map(encryptedWord).join(' ');
};
```

## *3. Completar el 1er Core Challenge*

- Completado
  - Me llamo David Lozano, soy de México, y soy un amante del diseño, la web, la tecnologia, animes, videojuegos, peliculas, en resumen un geek,  Soy diseñor web, en la parte del Frontend, y y queiro completar mi camino con javascript y react, y ser full stack, para crear aplicaciones que sorprendan. soy una persona curiosa, y quesiempre le gusta aprender algo nuevo cada día, soy autodidacta y apasionado.


# *Lunes 08-08-22*

## *1. Ejercicio - Es hora de ponerse al día ⏱️ o hacer trabajo extra ⭐*

- Completado


## *2. Ejercicio - Más información sobre bucle for*

- Completado

## *3. Ejercicio - Siga este video de filtro de matriz de JavaScript*

- Video --> [Javascript Array Filter](https://www.youtube.com/watch?v=4_iT6EGkQfk)

- Completado

## *4. Ejercicio - Siga este video JavaScript Array Reduce*

- Video --> [Javascript Array Reduce](https://www.youtube.com/watch?v=g1C40tDP0Bk)

- Completado

## *5. Ejercicio - Siga este video de JavaScript Array Map*

- Video --> [Javascript Array Map](https://www.youtube.com/watch?v=G3BS3sh3D8Q)

- Completado

#  *Martes 09-08-22*

## *1. Ejercicio - Es hora de ponerse al día ⏱️ o hacer trabajo extra ⭐*

- Completado

## *2. Ejercicio - Mire este video de expresiones regulares (RegEx)*

- Video --> [Expresiones Regulares](https://www.youtube.com/watch?v=sXQxhojSdZM)

- Completado

## *3. Ejercicio - Leer expresiones regulares - documentación de MDN*

- Documentación --> [Expresiones Regulares MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Regular_Expressions)

- Completado

## *4. Ejercicio - Aprende sobre Replace() en este video*

- Video --> [Método Replace()](https://www.youtube.com/watch?v=ZYPqPoijCAQ&t=176s)

- Completado

## *5. Ejercicio - Leer Replace() - documentación de MDN*

- Documentación --> [Método Replace() MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/String/replace)

- Completado

## *6. Ejercicio - Compruebe Regexr, una herramienta para probar sus expresiones regulares*

- Herramienta --> [Regexr](https://regexr.com/)

- Completado

## *7. Ejercicio - Un video completo de Expresiones Regulares*

- Video --> [Expresiones regulares Completo](https://www.youtube.com/watch?v=rhzKDrUiJVk)

- Completado

# *Miércoles 10-08-22*

## *1. Ejercicio - Es hora de ponerse al día ⏱️ o hacer trabajo extra ⭐ *

- Completado

#  *Jueves 11-08-22*

## *1. Ejercicio - ✨Completa tu 2do Core Challenge. Este es uno de los requisitos para la certificación, donde impulsará su marca profesional de desarrollo. *

- Completado
  - Perfil de linkedin --> [David Lozano Tenorio](https://www.linkedin.com/in/dlozanotn/)


#  *Lunes  15-08-22*

## *1. Ejercicio - Es hora de ponerse al día ⏱️ o hacer trabajo extra ⭐*

- Completado





</HTML>