# MDN Control

The control Flow is the order in which the computer executes statementsin a script. 

Code is run in order from first line in the file to the last line, unless the computer runs across the structures that change the control flow such as conditionals and loops.

For example, imagine a scipt used to validate user data from a webpage form. The script submits validated data, but if the user, leaves a required field empty, the script prompts them to fill it in. This is done with an if...else code. This makes different code execute depending on wether the form is complete or not.

`if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}`

JS includes many control structures like

- Loops

- Conditionals

- Functions


## Loops

A loop is a sequence of instruction that is continually repeated until a certaiin condition is met. An example would be like scrubbing a dish over and over again until it is clean.

### For loop

Syntax:

`for (statement 1; statement 2; statement 3) {
  execute code block
}`

- Statement 1 is executed once before the code block is run.

- Statement 2 defines the condition needed to execute the code block.

- Statement 3 is executed every time the code block is run.

Example of real code

`for (let i = 0; i < 10; i++) {
  console.log(i);
}`

- This loop will print numbers 0-9, will stop when condition is met (i = 10)

- Statement 1 sets the variable for the loop (let i = 0).

- Statement 2 sets the loop condition (i < 10).

- Statement 3 increases the value of i (i++) each time the code block is run.

- This loop will print numbers 0-9, will stop when condition is met (i = 10)

### While loop

Syntax

`while (condition) {
  execute code block
}`

- The code block will continue to loop as long as the condition is true.

Example of real code:

`let i = 0;
while (i < 5) {
  console.log(i);
  i++;
}`

This loop will print number 0-4, will stop when condition becomes false (i >=5)

For the above example, the syntax is as follows:

The code block will continue to run as long as the variable (i) is less than 5.

## Functions

Js is defined with the **function** keyword, follow by name, followed by paraentheses`()`.

Functions names can be anything and the same thing applies to variables.

Function Syntax

The code to be executed, by the function, is placed inside curly brackets: {}

`function name(parameter1, parameter2, parameter3) {
  // code to be executed
}`

Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.


### Function Invocation

The code inside the function will execute when "something" calls the function

- When an event occurs (when a user clicks a button)

- When it is called from JavaScript code

- Automatically (self calls)

### Function Return

Return Syntax

Calculate the product of two numbers, and return the result:

let x = myFunction(4, 3);   // Function is called, return value will end up in x

`function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}`
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller"

So the console will read:

12

We use functions so we can reuse the same code for one action over and over again. You can also use the same code many times with different arguement to get different results.

### Functions Used as Variable 

Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

Syntax:

Instead of using a variable to store the return value of a function:

`let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";`

- You can use the function directly, as a variable value:

`let text = "The temperature is " + toCelsius(77) + " Celsius";`

#### Local Variables

Variables declared within a JavaScript function, become LOCAL to the function.

Local variables can only be accessed from within the function.

Syntax

`code here can NOT use carName`

`function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}`

`code here can NOT use carName`


## Excercise

 Pick up a shirt. Find the left sleeve. Put the left arm in the left sleeve. Find the head hole. Put your head in the head hole. Find the right sleeve. Put the right are in the right sleeve. Slide the rest of the shirt down the torrso.


[Lecture and passcode: 7T0s781LZC ](https://zoom.us/rec/share/tzjaW-3mtwadGFMKG8Ld-Bw-8b3Hr9blYM-le5HXLcMhGfdYZh5xEMRsxxV_cio._2Cx3FwTCih-4aFR)

[Back to home page](../README.md)