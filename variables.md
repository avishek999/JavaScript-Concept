# Variables

Variables can help store data for to use later on for example

there are three type of variables

1) const 
2) let
3) var


cost variable has  to be declared before it is used and it can't be changed once it is declared.

var  variable can be declared anywhere in the code and it can be changed anytime.

let  variable can be declared  anywhere in the code and it can be changed once it is declared.


> var and let is diffrent  from const in one thing that is var and let can be redeclared but const can't be
 but main difference between  var and let is that var is function scoped and let is block scoped. meaning  that if you declare a variable with var inside a function it will be accessible from the whole function but  if you declare a variable with let inside a function it will be accessible only inside that block.

 ```javascript
const name = "avishek"; 
name = "avi" // will  throww an error

let name = "avishek";
name = "avi" // will not throw an error

var name = "avishek";
name = "avi" // will not throw an error
```





