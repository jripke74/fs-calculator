# fs-calculator

In this workshop, you will review your knowledge of functions by building a calculator.

Step 1
In this workshop, you will review how to work with functions by building a calculator app.

In the previous lecture videos, you learned how to declare functions like this:

Example Code
// regular function
function myFunction() {

}

// arrow function
const myArrowFunction = () => {

}
Start by creating a function called addTwoAndSeven.

You can choose to use the regular function syntax or the arrow function syntax.

Step 2
One of concepts you learned in the previous lecture videos was how to return values from a function.

Here is a reminder of how to return a value from a function:

Example Code
function myFunction() {
  return "Hello World";
}
Inside your addTwoAndSeven function, return the sum of 2 and 7.

Step 3
In the previous lecture videos, you learned how to call (invoke) a function. Calling a function means to execute the code inside the function.

Here is a reminder of how to call a function:

Example Code
function myFunction() {
  return "Hello World";
}

// function call
myFunction();
Add a console.log statement, and inside it, call the addTwoAndSeven function.

You should now see the sum of 2 and 7 logged to the console.

Step 4
Now, it is time to add another function.

Declare a function called addThreeAndFour that returns the sum of 3 and 4.

Then call the addThreeAndFour function inside a console.log to see the result.

Step 5
Even though the functions work as expected, there is a lot of repetition in your code.

Since you are building a calculator, you don't want to have to create a function for every possible combination of numbers you want to add together.

It would be better to create a single reusable function that can add any two numbers together.

Remove all of the code you have written so far.

In the next step, you will review how to work with parameters and arguments in functions.

Step 6
In the previous lecture videos, you learned how to work with function parameters.

A function parameter is a variable that is defined in the function's declaration and acts as a placeholder.

Here is an example of a function that has a parameter:

Example Code
// The parameter is `name`
function greetUser(name) {
  return `Hello, ${name}!`;
}
Declare a function called calculateSum that takes two parameters, num1 and num2.

Step 7
Inside your calculateSum function, you will need to return the sum of the two parameters.

Step 8
The advantage of functions is that they can be called with different arguments, allowing you to reuse the same code with various values.

Here are some example function calls with different string arguments:

Example Code
// function definition
function greetUser(name) {
  console.log(`Hello ${name}!`);
}

// function calls
greetUser("John"); // "Hello John!"
greetUser("Jane"); // "Hello Jane!"
Add a console.log that calls the calculateSum function with the arguments 2 and 5.

Step 9 Passed
To further test out your calculateSum function, you will need to call it with different arguments.

Add another console.log that calls the calculateSum function with the arguments 10 and 10.

Below that console.log, add another console.log that calls the calculateSum function with the arguments 5 and 5.