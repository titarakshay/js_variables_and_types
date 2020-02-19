## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

   ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
    ```js
    let val1=Number(prompt("enter first number",0));
    let val2=Number(prompt("enter second number",0));
    alert("which operation you want to  1.add 2.multiply 3.sub 4.div ..Enter it");
    let operation = prompt("enter which operation want to do", '');
    if (operation=="add"){
    alert(val1+val2);
    }else if(operation=="multiply"){
    alert(val1*val2);
    }else if(operation=="sub"){
      if(val1>val2){
        alert(val1-val2);
      }else{
        alert("val2 is greater than val1")
      }
    }else if(operation=="div"){
        if(val1>val2){
        alert(val1/val2);
        }else{
        alert("val2 is greater than val1")
      }
    }else{
    alert("Enter valid operation")
    }
    ```



2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
var firstName = 'John';
var status = prompt("enter john is single or not");

if(status=="single"){
  console.log("john is single");
}else{
  console.log("john is married");
}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
let val1=Number(prompt("enter a val1 integer",0));
let val2=Number(prompt("enter a val2 integer",0));
let large;
if (large = (val1>val2)){
alert(val1);
}else{
alert(val2);
}
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
let val1 = Number(prompt("enter a val1",0));
let val2 = Number(prompt("enter a val2",0));
let val3 = Number(prompt("enter a val3",0));
let multiply=(val1*val2*val3);
alert(multiply);
if (multiply>=0){
alert("+")
}else{
alert("-")
}
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
let val1=Number(prompt("enter a number",0));
switch(val1){
case 1:
alert (`${val1} is equal to 1`);
break;
case 2:
alert (`${val1} is equal to 2`);
break;
case 3:
alert (`${val1} is equal to 3`);
break;
case 4:
alert (`${val1} is equal to 4`);
break;
case 5:
alert (`${val1} is equal to 5`);
break;
case 6:
alert (`${val1} is equal to 6`);
break;
case 7:
alert (`${val1} is equal to 7`);
break;
case 8:
alert (`${val1} is equal to 8`);
break;
case 9:
alert (`${val1} is equal to 9`);
break;
default:
alert("Please try again...")
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
let marks = Number(prompt("enter your marks in range0-100",0));
switch(marks<=100){
case (marks >90):
alert('AA');
break;
case(marks<=90  && marks >80):
alert('AB');
break;
case(marks<=80  && marks >70):
alert('BB');
break;
case(marks<=70  && marks >60):
alert('BC');
break;
case(marks<=60  && marks >50):
alert('CC');
break;
case(marks<=50  && marks >40):
alert('CD');
break;
case(marks<=40  && marks >30):
alert('DD');
break;
case(marks <=30):
alert('FF');
break;
}
```
