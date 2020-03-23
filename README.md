# Assignment: Types

## Overview

>Understand all the different primitive types in JavaScript

### Learning Objectives

-[] Understand the different types in JavaScript 
-[] Uses the defaults effectively 
-[] Creates new strings by concatenation 
-[] Convert a string to a float 
-[] Convert a string to an int 
-[] Recognize an array literals 
-[] Recognize an object literal

### Requirements

1. List the different types with an example of a value
- Numbers: numbers w/ or w/o decimals; ex: 3 or 3.00
- Strings: characters within quotes; ex: "hello" or "3"
- Booleans: ex: true or false
- Arrays: an ordered list; ex: [1, 2, 3] or ["dog","cat","fish] or [{},{},{}]
- Objects: properties written as a key:value pair;  ex: 
{hair:blonde, weight:185, american:true}; Null is also an object type. Stands for nothing.
- Undefined: a variable w/o a value; var person;



2. Explain what happens when you add a string and a number? 
- When adding a string to a number, the interpreter views the number as a string and joins them. ex: "1" + 1 = "11"

3. How do you convert a string to a number? 
- The function parseInt(x) will convert a string into a number. 

4. What is the difference between a float and an int? 
- they are both types of numerical data. ints or integers is a number without a decimal place. float or floating point number has decimal places.

4a. Give an example of why you would want to use each one.
- Floats are used when you want to be more precise but it also takes more work for the computer to figure out binary problems, like float values, than it does for the computer to work in integers

5. Give an example of adding "Hello" and "World" together to get "Hello World". 
- console.log("Hello "+"World")

6. Provide and example of an array literal. 
- A list of 0 or more expressions, which represent an array element and can be specified by its order
- let pets = ["dog", "cat", "fish", "parrot"]

7. Provide an example of an object literal.
- a list of zero or more pairs of keys and their value that are enclosed in curly braces {}
- let peron = {name:"John", age:32, student: true}

