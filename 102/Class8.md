
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

# Expressions and operators

Some types of Expressions and Operators are listed below

- Assignment

- Comparison

- Arithmetic

-bitwise

- logical

- string

- ternary

An expression is valid unti of code that resolves to a value. The are two types:

 Assinging values have side effects and the other type purely evalutes.

`x = 7`

`x =` assigns values and 7 is the expression it evalutes to.

`3 + 4`
3 + 4 is technically an evalution because the expression uses the + operator to add 3 and 4 together and produces a value, 7.

However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

## Assignment Operators

- Assignment	`x = f()`	Meaning `x = f()`

- Addition assignment	`x += f()` Meaning: `x = x + f()`

- Subtraction assignment	`x -= f()` Meaning:	`x = x - f()`

- Multiplication assignment	`x *= f()`  Meaning:	`x = x * f()`

- Division assignment	`x /= f()` Meaning:	`x = x / f()`

- Remainder assignment	`x %= f()` Meaning:	`x = x % f()`

- Exponentiation assignment	`x **= f()` Meaning:	`x = x ** f()`

- Left shift assignment	`x <<= f()`  Meaning:	`x = x << f()`

- Right shift assignment	`x >>= f()`  Meaning:	`x = x >> f()`

-Unsigned right shift assignment	`x >>>= f()`  Meaning:	`x = x >>> f()`

## Comparison operators

A comparison operator compares its operands and returns a logical value based on wether the comparison is true.

The opreands can be numerical, string, logical, or object values. If the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. Two exceptions to type conversion within comparisons invole the `====` and `!==` operators. These operators do not attempt to convert the operands to compatible types.

[Lecture and passcode:  nV16=#0Vpm ](https://zoom.us/rec/share/30i8VSDFex30amWsM9bFrGv2zOzW6j7ZEKpGZiQvGp8ikVC_gGH3yyXJlRP_JEpz.WNdNIkcS9huguZqI)

[Back to home page](../README.md)