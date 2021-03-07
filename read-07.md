# Comparison And Logical Operators

- _Comparison operators_ — operators that compare values and return true or false. The operators include: >, <, >=, <=, ===, and !==.

- _Logical operators_ — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: &&, ||, and !.

## Comparison Operators

You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

1. Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
2. Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
3. Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
4. Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
5. Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
6. Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

## Logical Operators

Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.

There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.

1. && (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
2. || (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
**EX**var isTrue = ('yellow' === 'green') && (4 >= 4);

## The For Loop
The for loop has the following **syntax**:

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

- Statement 1 is executed (one time) before the execution of the code block.

- Statement 2 defines the condition for executing the code block.

- Statement 3 is executed (every time) after the code block has been executed.

## The Do/While Loop

The do/while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

**Syntax**:
do {
  // code block to be executed
}
while (condition);
