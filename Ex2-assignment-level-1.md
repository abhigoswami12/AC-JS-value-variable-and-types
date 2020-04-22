## writeCode

Define 5 values of types number and string and store it in a variable.

```
// FEEDBACK: Question not clear. If what my understanding about the question is true, then the statement should be "Declare 5 values of types number and string, and store each of them in a variable".
```

## writeCode

- Declare a variable `user` and take the name using `prompt`. Display the value stored in `user` using `alert`.
```
var user = prompt('Enter your name');
alert(user);
```
- Now re-assign the value stored in the above example into a new variable `userName`. Log the value of both `user` and `userName` in console using `console.log`.

```
var userName = user;
console.log(`${user} and ${userName}`);
```
- Declare `age` and `gender` in the same line as `userName` i.e. declare multiple variables in one line.
```
var userName = user, age = 34, gender = "male";
```
- Now change the value of `user` to "John" and log the value of both `user` and `userName`.
```
user = 'John';
console.log(user);
console.log(userName);
```

## writeCode

Use `prompt` to take two numbers from user and store it in variable `numA` and `numB`. Create a third variable called `sum`, using `+` operator add numA and numB , store it in varible `sum` and using alert display `sum` in browser.
```
var numA = prompt('enter first number');
var numB = prompt('enter second number');
var sum = Number(numA) + Number(numB);
alert(sum);
```



## writeCode

Define 10 variables and store any kind of value in it. Like name, age etc
```
var a = 10;
var b = 20;
var sum = a+b;
var name = "Abhishek";
var isAdult = true;
var age = 27;
var gender = "male";
var address = "dharamshala";
var phone = 9205578146;
var friend = "Ashik"
```

## writeTextAnswer

- Declare variables with the name `break`, `class`, `const`, `for`, `else`, `if`, `import` and `return`. Explain in your own words what did you observe.
var break = 'yes';
var class = 'yes';
var const = 'yes';
var for = 'yes';
var else = 'yes';
var if = 'yes';
var import = 'yes';
var return = 'yes';
Explanation : All these variables name are predefined in Javascript and perform some specific task. We cannot declare them as variables.


## writeTextAnswer

- What is a truthy and falsey values.
Truthy values are values which upon evaluation gives boolean true, whereas falsey values upon evaluation gives boolean false.

## writeTextAnswer

- What are falsey values?
//FEEDBACK: SINCE WE HAVE ALREADY DEFINED WHAT FALSEY VALUES ARE, I FEEL THE QUESTION SHOULD BE "NAME ALL FALSEY VALUES."

The falsey values are : 0, null, undefined, NaN, false, "".

## writeCode

- Declare three variables `name,` `newUser` and `isAdmin`.
  - Assign your name as the value of `name`.
  - Reassign the value `newUser` to `name`.
  - Set the value of `isAdmin` to `true`.
  - Prompt the values of all the three variables.

  ```
  var name = "Abhishek";
  var newUser = name;
  var isAdmin = true;
  prompt (name);
  prompt (newUser);
  prompt (isAdmin);
  ```

## writeTextAnswer

What is the error in the given variable declaration:

```js
let user name = "John";
 There should be no space between a variable name and the second word of the variable name should be capital.So, the correct form will be : let userName = "John";
## writeQuiz

Q. What does the 'mkdir' command do?

- [x] "Welcome to JavaScript"
- [ ] 'Welcome to JavaScript"
- [ ] "Welcome to JavaScript'
- [ ] 'Welcome to JavaScript'

## writeTextAnswer

Find out the `valid` and `invalid` variables. In case of `invalid` declarations give reasons. Just below every line.

- let monk;//valid
- let 1stName;//invalid
    Variables should not start with numeric values.
- let places3;//valid
- let -name;//invalid
    Only special characters '_' and '$' is allowed as variable name.
- let bigPanther;//valid
- let 35;//invalid
    Cannot start with digit.
- let 43 = 30;//invalid
    Cannot start with digit.
- let \$48;//invalid
    Only special characters '_' and '$' is allowed as variable name.
- var \*gt = 350;//invalid
    Only special characters '_' and '$' is allowed as variable name.
- let userName;//valid
- let a, b, c;//valid
- let x = 3, y = 11, z = 13;//valid
- let x = 2 + 5 + 7;//valid
- let user = "Brienne of Tarth"; "Sansa Stark"; "Lyanna Mormont";//invalid
    Here, only the first string value will be assigned to user.

## writeCode

Follow instructions and write code. In case of an error write the error in your own words.

```js
var wiseMan = "Tyrion Lannister";
```

- Reassign the value of `wiseMan` to "Samwell Tarly"
- Declare a variable `userName` with value "Lysa Arryn"
- Declare a variable as `oddNumber` and assign a value `57`.
- Reassign the value of `oddNumber` to 61

wiseMen = "Samwell Tarly";
var userName = "Lysa Arryn";
var oddNumber = 57;
oddNumber = 61;

## writeCode

Using mathematical operations find the solutions. `(+, -, \*, / , etc.)`

```js
let amount = 4280;
```

- Declare a new variable `reducedAmount` . In it store the value that is 24 less than the value of amount.
- Declare another variable `addedAmount` . Its value should be 32 more than the value of amount.
- Declare a variable `multipleAmount` . Its value should be 7 times the value of amount.
- Declare a variable `dividedAmount` . It should store the resultant of amount divided by 57.

```
var reducedAmount = amount - 24;
var addedAmount = amount + 32;
var multipleAmount = amount * 7;
var dividedAmount = amount / 57;

```

## typeof-writeCode

What will be the output of the following

1. `typeof NaN`// "Number"
2. `typeof phone`//"undefined"
3. `typeof null`// "object"
4. `typeof undefined`//"undefined"
5. `typeof "abc"`// "string"
6. `typeof -0`// "number"
7. `typeof 4`// "number"

## Number Type Conversion-writeCode

Output of the following code

1. `Number("6")`//6
2. `Number("6.76")`//6.76
3. `Number(" 6.76 ")`
4. `Number(" 6 . 7 6 ")`//NaN
5. `Number(" ")`//0
6. `Number("")`//0
7. `Number("5+6")`//NaN
8. `Number(true)`//1
9. `Number(false)`//0
10. `Number("text")`//NaN

## String Type Conversion-writeCode

Output of the following code

1. `String(456)`//"456"
2. `String(1.25)`//"1.25"
3. `String(10+20)`//"30"
4. `String(true)`//"true"
5. `String(false)`//"false"
6. `String(NaN)`//"NaN"
7. `String("text")`//"text"
8. `String("This", "is", "text")`// "This"
9. `String["This", "is", "text"]`// undefined
10. `String{"This", "is", "text"}`// ERROR({} is not allowed.)
11. `String("This"+"is"+"text")`// 'thisistext'

## Boolean Type Conversion-writeCode

Output of the following code

1. `Boolean(1)`
true
2. `Boolean(0)`
false
3. `Boolean(-5)`
true
4. `Boolean(5-5)`
false
5. `Boolean(undefined)`
false
6. `Boolean(null)`
false
7. `Boolean(NaN)`
false
8. `Boolean("text")`
true
9. `Boolean(" ")`
true
10. `Boolean("")`
false

## Operators-writeCode

Output of the following line of code.

```js
20 > 5 && 5 < 20; //output : true
20 > 5 && 20 < 5; //output : false
NaN && NaN; //output : NaN
NaN && undefined; //output : NaN
undefined && " "; //output : undefined
"" && "Arya"; //output : ""
"Arya" && 5; //output : 5
10 && "Arya"; //output : "Arya"
" " && 10; //output : 10
NaN && undefined; //output : NaN
" " || 10; //output : " "
undefined || " "; //output : " "
10 || "Arya"; //output : 10
"" || "Arya"; //output : "Arya"
!undefined; //output : true
!null; //output : true
!20; //output : false
!0; //output : true
!NaN; //output : true
```
//FEEDBACK: LINE 261 & 267 ARE SAME.

## writeQuiz

What is the value of x?

```js
var a = 5,
  b = 10,
  c = "5";
var x = a + "5";
```

- [ ] 5
- [ ] 10
- [ ] 15
- [Ans ] 55

## Condition-writeCode

Write a program that asks the user his/her age and check for the following conditions :

- `if` the age is between 12-55 then print the message "You can participate in the marathon".
- `if` the age is between 4-11 then print the message " You are too young to participate in the marathon".
- `if` the age is less than 4 then print the message " Hey Kiddo! Can You Walk ?"
- `if` the age is greater than 55 then print the message " You are too old to participate in the marthon".

```
let age = prompt("Enter your age");
if (age > 12 && age < 55) {
  console.log('you can participate in the marathon.');
} else if (age > 4 && age < 11) {
    console.log('you are too young to participate in the marathon.');
} else if (age < 4) {
    console.log('Hey kiddo! Can you walk?');
} else {
  console.log('you are too old to participate in the marathon.');
}

```

## writeCode

Write a program that asks the user for the house name and check the following conditions :

- `if` house name is "stark" then print the message " Winter is coming"
- `if` house name is "lannister" then print the message " A lannister always pays his debt"
- `else` print the message " All men must die"
```
let houseName = prompt('Enter your house name');
if (houseName == "stark") {
  console.log('Winter is coming');
} else if (houseName == "lannister") {
  console.log('A lannister always pays his debt');
} else {
  console.log ('All men must die')
}
```

## writeCode

Write a program that asks the user for a number and check the following conditions :

- `if` the number is even print the message " number is even"
- `if` the number is odd print the message "number is odd"
```
var num = Number(prompt ('Enter any number'));
if (num % 2 == 0){
  console.log('number is even');
} else{
  console.log('number is odd');
}
```

### Convert the above code using `?` terniary operator
```
var num = Number(prompt ('Enter any number'));
var result = (num % 2 == 0)? "number is even" : "number is odd";
console.log(result);
```

## writeCode

1. Print the odd numbers from 9 through 1(both inclusive) using a for loop. There is no input involved.
```
for (i = 9; i > 0; i--) {
  if(i % 2 != 0) {
    console.log(i);
  }
}
```
2. Add numbers from 5 through 0(both inclusive) in descending order using a while loop. There is no input involved.
```
var sum = 0;
for (i = 5; i >= 0; i--) {
  sum = sum + i;
}
console.log(sum);
```
3. Program to calculate the sum of first n natural numbers(1,2,3...n are known as natural numbers). Prompt user to enter n(using prompt modal window) then based on input provided calculate and show result in alert modal window.
```
var n = prompt('Enter any natural number');
var sum = 0;
for (i = 1; i <= n; i++) {
  sum = sum + i;
}
console.log(sum);

```
4. Write a program to print from 1 to 10 but quit if multiple of 7 is encountered. There is no input involved.
```
for (i = 1; i<=10; i++) {
  if (i % 7 != 0) {
    console.log(i);
  } else {
    break;
  }
}
```

## writeCode

Complete the following code to make the output be 0 2 4 6 8 10?

```js
for (let j = 0; j <= 10; j = j + 2) console.log(j);
```
