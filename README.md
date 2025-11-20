# Javascript


1. #### What's is Javascript?
- Javascript is a programming language that make our website more interactive
- Javascript is OOP(Object-Oriented Programming) Language build around a prototype model
- Javascript was created by Brendan Eich and first releast in 1995

2. #### Javascript Variable
- Variable Declaration(JS have 3 different types to declare the variable)
  - var ```var variableName;```
  - let ```let variableName;```
  - const ```const variableName;```
- Variable Name Rules
  - Snake Casing ```snake_casing```
  - Camel Casing ```variableName```
  - Pascal Casing ```VariableName```
  - Scream Snake Casing ```VARIABLE_NAME```
- Hosting
  - Hosting are the way JS move our variable and function declaration on top of the scope(just work for __var__ declaration not assign variable)
- Variable scope 
  - Global Scope
  - Block Scope
  - Function Scope

3. #### Data Type
  - String
  - Number
  - BigInt
  - Boolean
  - Undefined
  - Null
  - Object(An object is a data type in JavaScript that stores data as key–value pairs.)
    - Object Prototype
      - An Object Prototype is a template (or blueprint) that other objects can inherit properties and methods from.
    - Prototypal Inheritance
      - The Prototypal Inheritance is a feature in javascript used to add methods and properties in objects. It is a method by which an object can inherit the properties and methods of another object

4. #### Type Casting
   - Implicit Type Casting
     - EX:
       ```
       let a = 123 // number
       let b = a + "" // string
       ```
   - Explicit Type Casting
       - EX:
       ```
       let a = "123" //string
       let b = Number(a) // Number(123)
       ```
5. #### Data Structure
   - Keyed Collections
     - Map
     - Weak Map
     - Set
     - Weak Set
   - Structured data
     - JSON
   - Indexed collections
     - Array
       - Array is a special type of object that store multiple values in a variable
     - Typed Array
       - Typed Array is special kind of array used to store only 1 specific data type

6. #### Equality Comparisons
  - ```==```
  - ```===```
  - ```Object.is(value, value)```
7. #### Loops and Iterations
  - For
    ```
      for(let i = 0; i < 10; i ++){
        console.log(i);
      }
    // 1 2 3 4 5 6 7 8 9 10
    ```
  - While
    ```
      let i = 0;
    
      while(i < 10){
        console.log(i)
        i++
      }
    // 1 2 3 4 5 6 7 8 9 10
    ```
  - Do While
    ```
      let i = 0;
    
      do {
        console.log(i);
        i++;
      } while(i < 10)
    // 1 2 3 4 5 6 7 8 9 10
    ```
  - For...of(loop through Array)
    ```
      let a = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

      for(let i of a){
        console.log(i);
      }
    // 1 2 3 4 5 6 7 8 9 10
    ```
  - For...in(Loop in Object to get key-value pair)
    ```
      let object = {
        a: 1,
        b: 2,
        c: 3
      }
      
      for (let key in object) {
        console.log(key + ": " + object[key]);
      }
    // a: 1, b: 2, c: 3
    ```
  - Break/Continue
    ```
      for (let i = 1; i <= 10; i++) {
        if (i === 5) {
          continue; // skip number 5
        }
        if (i === 8) {
          break; // stop the loop when i = 8
        }
        console.log(i);
      }
      // 1 2 3 4 6 7
    ```
      
8. Controll Flow
  - Conditional statements
    - if...else
      ```
        if(trueConditional){
          // Execute this code block
        } else {
          // Execute this code block
        }
      ```
    - switch
      ```
        switch (expression) {
          case value1:
            //Statements executed when the result of expression matches value1
            break;
          case value2:
            //Statements executed when the result of expression matches value2
            break;
          ...
          case valueN:
            //Statements executed when the result of expression matches valueN
            break;
          default:
            //Statements executed when none of the values match the value of the expression
            break;
        }
      ```
  - Exception Handling
  - ! Try catch only handle Runtime Error not Parsetime Error
    - try/catch/finally
      ```
      try {
        // Code that may cause an error
      } catch (error) {
        // Code to handle the error
      } finally {
        // Code that always runs, no matter what
      }
      ```
    - Throw Statement
      - The Throw Statement throws a user-defined exception. Execution of the current function will stop(the statements after throw won't be executed).
    - Error Object *****

9. Expressions and Operators
  - Conditional operators```condition ? val_for_true : val_for_false```
  - Comma operators
    - Comma operator ```,``` are operater let you evaluate multiple expressions in one statement
  - Unary Operators
    - Unari operator is an operator that works on only one operand (one value)
    ```
    +
    -
    ++
    --
    !
    ```
  - Assignment Operators ```=```
    - Assignment Operator used to assign a value to a variable
  - Comparison Operators ```<, >, <=, >=, ==, ===, !=, !==```
    - Comparison operators compare two values and return true or false
  - Arithmetic operators ``` +, -, *, **, /, %, ++, --```
    - Arithmetic operators perform mathematical calculations on numbers
  - Bitwise operators
  - Logical Operators
  - BigInt Operators
  - String Operators

10. Function
    - 

