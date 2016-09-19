# ccs-project-template
CCS Project Template

#Topics
- [Data Types](#data-types)
  - [Strings](#strings)
  - [Booleans](#booleans)
  - [Integers](#integers)
- [Variables](#variables)
- [Functions](#functions)
  - [Function Statement](#function-statement)
  - [Function Expression](#function-expression)
- [Conditions](#conditions)
  - [Comparison and Logical Operators](comparison-and-logical-operators)
  - [If Else Statements](#if-else)
  - [Switch](#switch)
- [jQuery Basics](#jquery-basics)
  - [Selectors](#selectors)
  - [Events](#events)


##Data Types
A data type defines the structure of data that will be stored in an object (variable) of that type. A variable is a named instance of that data type. JS variables can hold many data types such as numbers, strings, arrays, objects and more. 


###Strings
Used for storing and manipulating text
```javascript
"Kikko"
"Kikko Paradela"
"Hello" + "world"
```

###Booleans
Used for representing one of two values: true or false
```javascript
10 > 9
10 === 10
```


###Integers
Used for storing numbers
```javascript
10
3.14
4*10
```

##Variables
Containers for storing data values
```javascript
var student = "Kikko";
var age = 18;
var student = false;
```


##Functions
Block of code designed to perform a particular task. There are two ways we can create a function:

###Function Statement
```javascript
// Define the function
function sayHello() {
  console.log("Hello world!")
}

// Call function
sayHello(); // Prints: Hello World!
```

###Function Expression
```javascript
var sayHello = function() {
  console.log("Hello world!")
}

sayHello(); // Prints: Hello World!
```

###Arguments
```javascript
function sayHello(student) {
  console.log("Hello " + student)
}

sayHello("Kikko"); // Prints: Hello Kikko
```

You can also use multiple arguments
```javascript
function sayHello(student, yourName) {
  console.log("Hello " + student + "! My name is " + yourName + ".");
}

sayHello("Shaq", "Kikko"); // Prints: Hello Shaq! My name is Kikko.
```


##Conditions
Block of code designed to perform a particular task


###Comparison and Logical Operators
Block of code designed to perform a particular task

| Operantor | Description |
| --- | :--- |
| == | equal to |
| === | equal value and equal type |
| != | not equal |
| !== | not equal value or not equal type |
| > | greater than |
| < | less than |
| >= | greater than or equal to	 |
| <= | less than or equal to |


###Switch
Block of code designed to perform a particular task
```javascript
function sayHello() {
  console.log("Hello world!")
  // Returns: Hello World
}
```


###If Else
Block of code designed to perform a particular task
```javascript
function sayHello() {
  console.log("Hello world!")
  // Returns: Hello World
}
```


##jQuery Basics

###Selectors
```javascript
$("p")      // Finds the p element
$(".box")   // Finds element(s) with a box class
$("#shaq")  // Finds element with the shaq id name

```
###Events
```javascript
```


###Load your JS file(s) into your HTML
```html
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <h1>Hello World!</h1>
    <script type='text/javascript' src='scripts/script.js'></script>
  </body>
</html>
```
