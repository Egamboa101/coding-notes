# Data Types

- String "String" // You can use backticks (`), double quotations ("), or single quotations (') interchangebly
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

# Arithmetic Operators

[Easy cheatsheet](https://www.w3schools.com/js/js_operators.asp)

# Functions

To define but not invoke:

function functionName(){
//...insert function steps
}

New ES6 syntax

//when there's a parameter in the parenthesis you're telling the function to do something with that. When defining the function you generally don't list a defined variable in the parenthesis.
const functionName = (x) => {

}


To invoke 
functionName(insert variable)


If you want your function to give you something back you use the return statement.

#Comparing Different Values

The equality operator is (==) and the strict equality operator is (===).

If the values being compared are not of the same type, the equality operator will perform a type conversion, and then evaluate the values. However, the strict equality operator will compare both the data type and value as-is, without converting one type to the other.

Examples

3 == '3' returns true because JavaScript performs type conversion from string to number. 3 === '3' returns false because the types are different and type conversion is not performed.

Note: In JavaScript, you can determine the type of a variable or a value with the typeof operator, as follows:

typeof 3
typeof '3'
typeof 3 returns the string number, and typeof '3' returns the string string.

Comparison with the Inequality Operator
- The inequality operator (!=) is the opposite of the equality operator. It means not equal and returns false where equality would return true and vice versa. Will convert data types of values while comparing.

Comparison with the Strict Inequality Operator
- The strict inequality operator (!==) is the logical opposite of the strict equality operator. It means "Strictly Not Equal" and returns false where strict equality would return true and vice versa. The strict inequality operator will not convert data types.

Comparison with the Greater Than Operator
- The greater than operator (>) compares the values of two numbers. If the number to the left is greater than the number to the right, it returns true. Otherwise, it returns false. Will convert data types of values while comparing.

Comparison with the Greater Than Or Equal To Operator
- The greater than or equal to operator (>=) compares the values of two numbers. If the number to the left is greater than or equal to the number to the right, it returns true. Otherwise, it returns false. Will convert data types of values while comparing.

- Comparison with the Less Than Operator
The less than operator (<) compares the values of two numbers. If the number to the left is less than the number to the right, it returns true. Otherwise, it returns false. Will convert data types of values while comparing.

Comparison with the Less Than Or Equal To Operator
- The less than or equal to operator (<=) compares the values of two numbers. If the number to the left is less than or equal to the number to the right, it returns true. If the number on the left is greater than the number on the right, it returns false. Will convert data types of values while comparing.

Comparisons with the Logical And Operator

Sometimes you will need to test more than one thing at a time. The logical and operator (&&) returns true if and only if the operands to the left and right of it are true.

The same effect could be achieved by nesting an if statement inside another if:

if (num > 5) {
  if (num < 10) {
    return "Yes";
  }
}
return "No";
will only return Yes if num is greater than 5 and less than 10. The same logic can be written as:

if (num > 5 && num < 10) {
  return "Yes";
}
return "No";

Comparisons with the Logical Or Operator
The logical or operator (||) returns true if either of the operands is true. Otherwise, it returns false.

The logical or operator is composed of two pipe symbols: (||). This can typically be found between your Backspace and Enter keys.

EXAMPLE:
if (num > 10 || num < 5) {
  return "No";
}
return "Yes";
