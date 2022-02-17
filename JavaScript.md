# Data Types

- String "String"
- Number 3423423
- Array [123, text, ]
- Boolean (True/False)
- Object {
  name: "Marcus",
  age: 27,
  spouse: {  
   }
  }

If I want to see if something is working then use console.log() to test and see the results of the code.

Variable names can't start with a number or have spaces in them.

# Declare Data Types

- let name = "Marcus";
  let keyword means you can change the data
  or
- const age = 27;
  const keyword means you can't change the data

Old way to declare used var, which is equivalent to "let" essentially.

Declare a Read-Only Variable with the const Keyword

- You should always name variables you don't want to reassign using the const keyword. This helps when you accidentally attempt to reassign a variable that is meant to stay constant.
- A common practice when naming constants is to use all uppercase letters, with words separated by an underscore.

Create Decimal Numbers with JavaScript

- We can store decimal numbers in variables too. Decimal numbers are sometimes referred to as floating point numbers or floats.

Finding a Remainder in JavaScript

- The remainder operator % gives the remainder of the division of two numbers.
  Example

      5 % 2 = 1 because
      Math.floor(5 / 2) = 2 (Quotient)
      2 * 2 = 4
      5 - 4 = 1 (Remainder)

  Usage
  In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by 2.

Compound Assignment With Augmented Operators
There are operators which do both a mathematical operation and assignment in one step; One such operator is the += operator.

    `let myVar = 1;
    myVar += 5;
    console.log(myVar);`
    6 would be displayed in the console.

Like the += operator, -= subtracts a number from a variable.
The \*= operator multiplies a variable by a number.
The /= operator divides a variable by another number.
