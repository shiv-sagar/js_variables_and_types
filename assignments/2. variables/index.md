1. In code below "Mark" is a string. What is name?


```js
var name = "Mark";


name is the name of variable where value of type "string" is  stored and var is the reserved keyword used by js to declare variable.
```

2. Find the error if any

```js
  var product cost = 3.45;

there shouldn't be any empty space in varible name and using camel casing while naming a variable is a good practice.


```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"     Right
  'Hello World"     Wrong
  "Hello World'     Wrong
  'Hello World'     Wrong
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;                   VALID
var 1girl;                 INVALID
var woman3;                VALID
var -girl;                 INVALID
var blackDog;              VALID
var 42;                    INVALID 
var $42;                   INVALID
var userName;              VALID
var x, y, z;               VALID
var x = 5, y = 6, z = 7;   VALID
var x = 5 + 10 + 2;        VALID        
var user = "Tyrion"; "Arya"; "John"; INVALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less than the value of amount.

let substract80 = amount - 80;

// Define a new variable and store the value that is 200 more than the value of amount.

let add200 = amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.

let into4 = amount * 4;

// Define a new variable and store the reminder when the value of amount is  divided by 21.

let remainder = amount % 21;

```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"

user = "Sam";

// Define a variable with name user with value "Irfan"

let name = "Irfan";

let number = 21;
// Reassign the value of number to 60

number = 60;

// Define another variable called number with the value of 100

let number = 100;

const username = "Admin";
// Reassign the value of username to "Arya"

username = "Arya";


// Define a variable called usernae with value "John"

let username = "John";

```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark

var checkOld = johnAge < markAge ? console.log("Mark is older") : console.log("John is older");
// Check who is younger

var checkYoung = johnAge < markAge ? console.log("John is younger") : console.log("Mark is younger")

// Check if their age is equal

var checkEqual = (johnAge === markAge) ? console.log("age is equal") : console.log("age is not euqal");

// Create a new variable and assign the age of john to new variable.

let shivsagar = johnAge;

// Check if john is equal to or greater then mark.

let check = johnAge >= markAge ? alert("John's age is equal to or greater than mark") : alert("John's age is not equal to or greater than mark");

// Check if john is less then or equal to mark.

var lessOrEqual = johnAge <= markAge ? alert("John's age is less than or equal to mark's age") : alert("John's age is not less than or equal to mark's age");

// Calculate the average age of john and mark and assign to a new variable.

let averageAge = (johnAge + markAge) / 2;


```
