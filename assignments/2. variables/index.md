1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
//variable
```

2. Find the error if any
```js
  var productcost = 3.45;
  //space between productcost
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //right
  'Hello World" //wrong
  "Hello World' //wrong
  'Hello World' //right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; //valid
var 1girl; //invalid
var woman3; //valid
var -girl; //invalid
var blackDog; //valid
var 42; //invalid
var $42; //valid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
let value=(amount- 80);
alert(value);
// Define a new variable and store the value that is 200 more then the value of amount.
let value=(amount + 200);
alert(value);
// Define a new variable and store the value that is 4 times the value of amount.
let value=(amount *4);
alert(value);
// Define a new variable and store the reminder when the value of amount is  divided by 21.
let value=(amount/21);
alert(value);
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if (johnage > markage){
    alert("john is older than mark");
} else {
    alert("mark is older than john");
}
// Check who is younger
if (johnage < markage){
    alert("john is younger than mark");
} else {
    alert("mark is younger than john");
}
// Check if their age is equal
if (johnage == markage){
    alert("john age is equal  mark age");
} else {
    alert("mark and john age are not equal");
}
// Create a new variable and assign the age of john to new variable.
let johnname = johnage;
alert(johnname);
// Check if john is equal to or greater then mark.
if (johnage >= markage){
    alert("john age is equal to greater than   mark age");
} else {
    alert("mark age is equal to or greater than johnage");
}
// Check if john is less then or equal to mark.
if (johnage <= markage){
    alert("mark age is equal to or greater than johnage");
} else {
    alert("john age is not equal to less than   mark age");
}

// Calculate the average age of john and mark and assign to a new variable.
let avgage=(johnAge+markAge)/2;
alert(avgage);
```