# Multiple Value 

multiple value can store more then 1 thing in it like array and object



```javascript

const array = [1,'hi',3,false];

// this is the array and we can store multiple value in it
```




## Array 

Array can store multiple value at one with different data types

to create an array we can use 

```javascript

const array = [1,2,3,4,5];

// this is the array and we can store multiple value in it
```


you can store array with const and can change value but , the value will change but it will show type error

```javascript
const arr = [1,2,3,];
 arr[0] = 4;

console.log(arr);

//  [ 4, 2, 3 ]
```



## Accessing an Array

we can access array by indexing we don't need to define index when we initialize an array it come out of its own but we can access it 


```javascript
let array = [1,2,3,4];

console.lof(array[0]);

// 1

```

## overwriting elements


in the same way we can over write an element but changing its value


```javascript
let array = [1,2,3,4];

array[0] = 5;

console.log(array);  //5,2,3,4
```


but this is the not a correct way to change an array


## built-int length property


length property can help to find out the length of a array


```javascript

let arr = [1,2,3];

console.log("length of array = ", arr.length);  //3

```


this is to remember that length of array will be 3 but to access the last element of array
we need to 
```javascript
let arr = [1,2,3];

console.log(arr[arr.length -1]);

//output will be 3
```

this is because the index will start from 0 but so  1,2,3  indexes will be 0,1,2  and th length will be 3 so to access we need to do -1 , Got it!



we can also assign empty array in array


```javascript
let arr = [1,2,3];

arr[5] = 5;

console.log( arr);

// [ 1, 2, 3, <2 empty items>, 5 ]
```

### Practice exercise

1) create an array to use as your shopping list with 3 items "Milk" ,"Bread" ,"Apple"
2) check your length in the console
3) update bread to banana
4) output your entre list to console


### Answer
>
 ```javascript
let shopping_list  = ["Milk", "bread", "Apples"];

console.log(shopping_list.length);


shopping_list[1] = "Banana";

console.log(shopping_list);


//3
// [ 'Milk', 'Banana', 'Apples' ]
```


## push method 


we can use push method to add a string or any data value to an array 

example

```javascript

let shopping_list  = ["Milk", "bread", "Apples"];

console.log(shopping_list);

console.log( "length of shopping_list before using push", shopping_list.length);
shopping_list.push("orange");

console.log(shopping_list);
console.log( "length of shopping_list after using push", shopping_list.length);


/* [ 'Milk', 'bread', 'Apples' ]
length of shopping_list before using push 3
[ 'Milk', 'bread', 'Apples', 'orange' ]
length of shopping_list after using push 4
*/

// btw its multiline comment '
```


## splice method 


we use this when we need to put certain value in the middle of array of in indexes



1) 
```javascript
let shapes =  ['circle','square', 'triangle']


shapes.splice(2,0, "diamond");

console.log(shapes)

//[ 'circle', 'square', 'diamond', 'triangle' ]

```

2) 
```javascript
let shapes =  ['circle','square', 'triangle']


shapes.splice(2,2, "diamond");

console.log(shapes)

//[ 'circle', 'square', 'diamond' ]
```

I have given two example in the first one we are defining  we are using splice(2,0) 2 means at what index and 0 means which i want to replace with in the first example i don't want to replace with anything so i put 0  and we get all the value and none replace in the 2 example i am putting 2,2 that means "diamond " will replace with 'triangle' which is on 2 index 


## concat method


To add 2 array we can use concat method for example


```javascript

let a = [1,2,3,4,];
let b = [5,6,7,8,];

let c = a.concat(b);

console.log(c);

/*
[
  1, 2, 3, 4,
  5, 6, 7, 8
]
*/
```

# deleting an array

## pop method

To delete a last element of array we can use pop method to delete it


```javascript 

let a = [1,2,3,4,];

a.pop();

console.log(a);

//[ 1, 2, 3 ]
```

## shift method 

we can use shift method to delete the first element of an array

```javascript
let a = [1,2,3,4,];

a.shift();

console.log(a);


// [ 2, 3, 4 ]
```

## splice method to delete certain elements

```javascript
let a = [1,2,3,4,];
a.splice(1,2);

console.log(a);

// [ 1, 4 ]

```


## delete method 


we can use delete to delete certain element to undefined


```javascript
let a = [1,2,3,4,];
delete a[1];

console.log(a);

/// [ 1, <1 empty item>, 3, 4 ]
```



# object


object is Multi value data type just like array but instead of assigning the value we can assign the description , for example when we use array index are already present but in object we need to assign the value , type of array is also object


```javascript
let dog = {
    name: "tommy",
    weight: 2.5,
    color: 'brown'
};

// this is an object
```


> we can update value of object as same as  we do for array






