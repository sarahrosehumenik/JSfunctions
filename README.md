# Javascript Functions
![](https://miro.medium.com/max/600/0*IdTcxUwLw77wSkUi.jpg)

## Objective: 
- We will be able to Declare and call a JavaScript function.

## 📖 JavaScript recap before diving into JavaScript functions 

### Data Types! 
- What are Javascript Data Types? Lets refresh! 

- primative data types: 
Number, String, Boolean, NULL, Undefined and Symbol

- non-primative data types:
Objects! An object can hold a collection of data. 

### ❓ What data type is an array and why? An array may look like:
    let array = [“hi”, true, 123, “im one data type of many in this array”]
    
  <details>	
    <summary>Answer...</summary>
    <p><strong> Object! An array lets you store multiple values in a single variable. </strong></p>
  </details><br>
  
 - Strech review: javascript methods, javascript objects and control flow! 




## Road Map 

1. What is a function?
2. Why use a function?
3. Defining and calling a function

### Strech content:
 4. Parameters
 5. Scope

## ‼️ questions check point! 

⬇️ Okaaaay lets gooo ⬇️


## What is a function?
### - A function is a reusable block of code written to preform a single purpose

Examples:

```js
// Get player's choice of board size (S for small, M for medium, L for large)
 function getBoardSize() {
   const validChoices = ['S', 'M', 'L'];
   let size;
   while (!validChoices.includes(size)) {
     size = prompt('Enter the board size (S)mall, (M)edium or (L)arge: ').toUpperCase();
   }
   return size;
 }
``` 
 
 - If the user enters "M" in the prompt, the return on the function will be "M". We now can use that information anywhere that is needed and is stored in our function. 

```js
 function getPointsScored(elapsedTime) {
   if (elapsedTime < 30) {
     return 100;
   } else if (elapsedTime < 60) {
     return 75;
   } else {
     return 25;
   }
 }
 
 const points = getPointsScored(time);
 ```
 
 ❓ If time = 25 how many points will the function return?
  <details>	
    <summary>Answer...</summary>
    <p><strong> 100!  </strong></p>
  </details><br>
 

final thoughts: 

- functions are the primary building blocks of programs
- the code in a function does not execute until the function is called, however the code is checked for syntax errors when the script file is loaded. 
- programming languages also include built in functions! for example <code>  .toUpperCase()  </code> as seen in the first example. 

 ## Okay i get what a function is, but why? 
 
 
 
 
