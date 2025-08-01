# Javascript
Javascript adds interactivity and dynamic functionality to the webpage. 

## Data type:
1. **Number**: 
   A Number represents both integers and floating-point values. Examples of integers include 7, 19, and 90. Examples of floating point numbers include 3.14 and 5.2. A floating point number is a number with a decimal point.
2. String:
   A String is a sequence of characters, or text, enclosed in quotes
   
   ```js
   "Yugal"
   ```
4. Boolean:
   A Boolean represents one of two possible values: true or false.
5. Undefined and Null:
   undefined means a variable has been declared but hasn't been given a value yet. null means the variable has been intentionally set to "nothing" and does not hold any value
6. Object:
   An Object is a more complex data type that can hold collections of key-value pairs. Let's break this down. The key (also called a property name), is like a label for the data, whereas the value, is the actual data you want to store. Here    is an example:
   ```js
    let book = {
    title: "The Great Gatsby",
    author: "F. Scott Fitzgerald",
    year: 1925
    };
   ```
   Each key-value pair in an object is called a property. So we can say that this book object has three properties.
7. Symbol:
   A Symbol is a special type of value in JavaScript that is always unique and cannot be changed. It's often used to create unique labels or identifiers for properties:
   ```js
   // Creating two symbols
    const symbol1 = Symbol('mySymbol');
    const symbol2 = Symbol('mySymbol');
    console.log(symbol1 === symbol2); // Outputs: false
   ```
8. BigInt:
   BigInt is used for very large numbers that exceed the limit of the Number type:
   ```js
   const bigNumber = 1234567890123456789012345678901234567890n;
    console.log(bigNumber);
    // Outputs: 1234567890123456789012345678901234567890n
   ```
   we create a BigInt by adding n at the end of a very large number.

## Variable:
  Variables are the containers for storing data that you can access and modify throughout the program.
  Things to consider while naming a variable:
  1. Your variable names should describe what the data represents.
  2. Variables in JavaScript must begin with a letter, an underscore (_), or a dollar sign ($). They cannot start with a number.
  3. Variable names are case-sensitive, so it is better to use camelCase format.
  ### Ways to declare Variable:
1. Let:
   ```js
   let age = 22;
   ```
   Using let you can reassign the values to them without redeclaring it later. 
   
2. Const:
   You cannot reassign the values and is constant. This is used for configuration values or settings that shouldn't be changed accidentally. <br>
   *Const Values must be initialized at the time of declaration*

## Strings:
   A `string` is a sequence of characters used to represent text data. To create a string in JavaScript, you can use single quotes ('), or double quotes (").
   Immutability: When you create a string, you can't change its characters directly. 
   ```js
    let string = "Yugal is doing js";
   ```
  ### Concatenation in String: 
  Joining of the String
  1. Using '+' operation:
     
     ```js
       let greeting = 'Hello';
       greeting += ', Yugal!';
      
       // greeting is now the string Hello, John!

      ```
     
     *String is immutable but why did you add it here*
     Good point, it is immutable in the sense that entirely new values cannot be assigned but we can only append it by methods like concatenation.
  2. Using `concat' method: There is difference between method, functions and objects which we will study later.
     
     ```js
     let str1 = 'Yugal';
     let str2 = 'WebDev';
     let result = str1.concat(' ',str2);
     ```
     
## Console.log:
   It is used to log data and display the output in the browser console. It is commonly used by developers for debugging and inspecting values or expressions in their code during development. 
   ```js
   let name = "Yugal is doing js";
   console.log(name);
   ```

## Roles of semicolons in JS:
   Just as a period (.) marks the end of a sentence in English, a semicolon signifies the end of an executable line of code. This allows the JavaScript engine to distinguish between separate commands. But, without considering this much in mind , since JS has Automatic Semicolon Insertion (ASI) , it is not compulsion to use as in C, C++ and Java. 
*But explicitly using them improves code clarity and helps prevent erros that may arise from unexpected ASI behaviot*

## Comments in JavaScript:
It is for your own use, so that you can re-read the code, or add note to it without the JS engine recognizing it.
```js
//This is a comment
```

   
     
   
   

   
   
