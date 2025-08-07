# Logical_Operators
## Aim
To understand and implement logical operators in C++ and analyze how they work in decision-making statements.

## Apparatus
Computer or Laptop
C++ Compiler (g++ or any standard C++ compiler)
Text Editor or IDE (VS Code, Code::Blocks, etc.)
Theory
Logical operators are used to combine multiple conditions and return either true (1) or false (0) based on the result of the conditions. They are mostly used in if, else if, while, and other control flow statements. C++ supports three basic logical operators: AND (&&), OR (||), and NOT (!).

## 1. Logical AND (&&)
The logical AND operator returns true if both conditions are true, otherwise returns false. It is commonly used when multiple conditions must be satisfied simultaneously.

Truth Table:

| Condition A |	Condition B |	A && B |
| ----------- | ----------- | ------ |
| true (1) |	true (1) |	true (1) |
| true (1) | false (0) |	false (0) |
| false (0) |	true (1) |	false (0) |
| false (0) |	false (0)	| false (0) |
## 2. Logical OR (||)
The logical OR operator returns true if at least one condition is true. It is used when you need any one of the conditions to be satisfied.

Truth Table:

| Condition A |	Condition B	| `A || B` |
| ----------- | ----------- | ------ |
| true (1) |	true (1) |	true (1) |
| true (1) |	false (0) |	true (1) |
| false (0) |	true (1) |	true (1) |
| false (0) |	false (0) |	false (0) |

## 3. Logical NOT (!)
The logical NOT operator reverses the logical state of a condition. If a condition is true, !condition becomes false, and if the condition is false, !condition becomes true.

Truth Table:

| Condition A |	!A |
| ----------- | -- |
| true (1) |	false (0) |
| false (0) |	true (1) |
## Importance of Logical Operators
They help in combining multiple relational conditions in decision-making.
They make programs efficient by reducing nested if statements.
They are essential for loops, conditional statements, and validating user input.
## Conclusion
This experiment helped understand the working of logical operators in C++. The AND (&&) operator ensures that all conditions must be true, the OR (||) operator allows any one of the conditions to be true, and the NOT (!) operator reverses the condition. Logical operators are fundamental in control flow and are used extensively in decision-making, validations, and looping structures in programming.
