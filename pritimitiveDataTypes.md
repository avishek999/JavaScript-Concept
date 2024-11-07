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




