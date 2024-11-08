# primitive Data Type


## String 

string are used to store text value there are different  ways to declare a string

1) double quotes
2) single quotes
3) back ticks


>
```javascript
let doubleQuote = "Avishek";
let singleQuote = 'Avishek';
let backTick - `Avishek`;
```


The Main difference between Double Quote and single Quote you can use single quote in double quote string

example

```javascript

const string =  'it's avishek'  //will throw an error
const string = "it's avishek" // will not throw an error
```


with the help of back tick we can use variables in our inside of string 

example

```javascript
const name = 'avishek';
const string =  `my name is ${name}`;
```

with the help of backtick you can use variables in your code which can show thing dynamically `dynamic means data is coming from outside and not static or other word for static is  HardCoded `



## Escape Characters

with the help of escape Character we can all three string type  same type of string in any value

example

```javascript
const string  = "Hello my name is \"avishek\" "; //this will not throw any  errors
```

## Numbers

The number data type of Number will represent well , Numbers!!

However there are Four type of Numbers   Octal , hexadecimals , and binary numbers 

examples

```javascript
let intNr = 1;
let decNr = 1.5;
let expNr = 0o10; // decimal version would be 8;
let hexNr =  0x3E8; // decimal version would be 1000
let binNr = 0b101 // decimal version would be 5
```

## BigInt

Long story short it store big number  


## Boolean

true and false nothing else 

```javascript
let bool1 = false;
let bool2 = true;
```



## undefined

when a variable is not defined it set to be undefined

```javaScript
const name;
console.log(name); //undefined
```

## null

null is something we intentionally put

```javascript
let name = null;
console.log(name); //null
```

the difference between null and undefined  

> undefined Automatically assigned when a variable is declared but not given a value. where null is A value that represents an intentional absence or emptiness.


## type of 


type of help to find out type of any thing

example

```javascript
const name = 'avishek`;

console.log(typeof(name))  // string

```


# JavaScript Operators

JavaScript operators are used for different operations like arithmetic, comparison, logical operations, and more. Here’s a breakdown:

## 1. Arithmetic Operators

Used for mathematical operations.

| Operator | Description               | Example        | Result |
|----------|---------------------------|----------------|--------|
| `+`      | Addition                  | `5 + 2`       | `7`    |
| `-`      | Subtraction               | `5 - 2`       | `3`    |
| `*`      | Multiplication            | `5 * 2`       | `10`   |
| `/`      | Division                  | `5 / 2`       | `2.5`  |
| `%`      | Modulus (Remainder)       | `5 % 2`       | `1`    |
| `**`     | Exponentiation (Power)    | `5 ** 2`      | `25`   |
| `++`     | Increment (Adds 1)        | `let x = 5; x++` | `6`|
| `--`     | Decrement (Subtracts 1)   | `let x = 5; x--` | `4`|

## 2. Assignment Operators

Used to assign values to variables.

| Operator | Description               | Example       | Equivalent to |
|----------|---------------------------|---------------|---------------|
| `=`      | Assignment                | `x = 5`      | `x = 5`       |
| `+=`     | Addition assignment       | `x += 5`     | `x = x + 5`   |
| `-=`     | Subtraction assignment    | `x -= 5`     | `x = x - 5`   |
| `*=`     | Multiplication assignment | `x *= 5`     | `x = x * 5`   |
| `/=`     | Division assignment       | `x /= 5`     | `x = x / 5`   |
| `%=`     | Modulus assignment        | `x %= 5`     | `x = x % 5`   |
| `**=`    | Exponentiation assignment | `x **= 5`    | `x = x ** 5`  |

## 3. Comparison Operators

Used to compare two values, returning `true` or `false`.

| Operator | Description             | Example      | Result      |
|----------|-------------------------|--------------|-------------|
| `==`     | Equal to                | `5 == '5'`  | `true`      |
| `===`    | Strict equal to         | `5 === '5'` | `false`     |
| `!=`     | Not equal to            | `5 != '5'`  | `false`     |
| `!==`    | Strict not equal to     | `5 !== '5'` | `true`      |
| `>`      | Greater than            | `5 > 3`     | `true`      |
| `<`      | Less than               | `5 < 3`     | `false`     |
| `>=`     | Greater than or equal   | `5 >= 5`    | `true`      |
| `<=`     | Less than or equal      | `5 <= 3`    | `false`     |

## 4. Logical Operators

Used to perform logical operations.

| Operator | Description         | Example             | Result     |
|----------|---------------------|---------------------|------------|
| `&&`     | Logical AND         | `true && false`    | `false`    |
| `||`     | Logical OR          | `true || false`    | `true`     |
| `!`      | Logical NOT         | `!true`            | `false`    |

## 5. Bitwise Operators

Operate on 32-bit binary numbers.

| Operator | Description       | Example    | Result |
|----------|-------------------|------------|--------|
| `&`      | AND               | `5 & 1`   | `1`    |
| `|`      | OR                | `5 | 1`   | `5`    |
| `^`      | XOR               | `5 ^ 1`   | `4`    |
| `~`      | NOT               | `~5`      | `-6`   |
| `<<`     | Left shift        | `5 << 1`  | `10`   |
| `>>`     | Right shift       | `5 >> 1`  | `2`    |
| `>>>`    | Zero-fill right shift | `5 >>> 1` | `2` |

## 6. Ternary Operator

Shorthand for an `if-else` statement.

| Syntax               | Example                | Result      |
|----------------------|------------------------|-------------|
| `condition ? exprIfTrue : exprIfFalse` | `5 > 3 ? "Yes" : "No"` | `"Yes"` |

## 7. Type Operators

Check or change types of variables.

| Operator   | Description         | Example             | Result          |
|------------|---------------------|---------------------|-----------------|
| `typeof`   | Type of a variable  | `typeof 42`        | `"number"`      |
| `instanceof` | Checks instance   | `obj instanceof Array` | `true` for arrays |

---





