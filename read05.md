# Expressions and operators

### Expressions 

Anything that evaluates to a value is called an expression.

An expression is any valid set of literals, variables, operators, and expressions that evaluates to a single value. The value may be a number, a string, or a logical value. Conceptually, there are two types of expressions: those that assign a value to a variable, and those that simply have a value.

JavaScript has the following expression categories:

1. Arithmetic: evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.)
2. String: evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.)
3. Logical: evaluates to true or false. (Often involves logical operators.)
4. Primary expressions: Basic keywords and general expressions in JavaScript.
5. Left-hand-side expressions: Left values are the destination of an assignment.

## Primary expressions

Basic keywords and general expressions in JavaScript.

### this
Use the this keyword to refer to the current object. In general, this refers to the calling object in a method. Use this either with the dot or the bracket notation

Example:

1. this.name
2. this.displayName()

## Left-hand-side expressions
Left values are the destination of an assignment.

### new
You can use the new operator to create an instance of a user-defined object type or of one of the built-in object types.

Example

new constructor[([arguments])]

### super
The super keyword is used to call functions on an object's parent. It is useful with classes to call the parent constructor.

Example

super([arguments]); // calls the parent constructor.
super.functionOnParent([arguments]);

# operators

JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

* Assignment operators
* Comparison operators
* Arithmetic operators
* Bitwise operators
* Logical operators
* String operators
* Conditional (ternary) operator
* Comma operator
* Unary operators
* Relational operators

## Assignment operators


Name | Shorthand operator | Meaning
------------ | -------------
Assignment|	x = y	|x = y
Addition assignment |	x += y |	x = x + y
Subtraction assignment |	x -= y|	x = x - y
Multiplication assignment|	x *= y|	x = x * y
Division assignment|	x /= y|	x = x / y
Remainder assignment	|x %= y	|x = x % y
Exponentiation assignment	|x **= y|	x = x ** y
Left shift assignment |	x <<= y	| x = x << y
Right shift assignment |	x >>= y	| x = x >> y
Unsigned right shift assignment |	x >>>= y| 	x = x >>> y
Bitwise AND assignment |	x &= y	| x = x & y
Bitwise XOR assignment | 	x ^= y |	x = x ^ y

## Comparison operators
Operator|	Description	| Examples returning true
------------ | -------------
Strict not equal (!==) |	Returns true if the operands are of the same type but not equal, or are of different type.|	var1 !== "3" 3 !== '3'
Greater than (>)|	Returns true if the left operand is greater than the right operand.|	var2 > var1 "12" > 2
Greater than or equal (>=) |	Returns true if the left operand is greater than or equal to the right operand.|	var2 >= var1 var1 >= 3
Less than (<)	|Returns true if the left operand is less than the right operand.|	var1 < var2 "2" < 12
Less than or equal (<=)	|Returns true if the left operand is less than or equal to the right operand.	|var1 <= var2 var2 <= 5
Equal (==) |	Returns true if the operands are equal.	|3 == var1      "3" == var1                                                            3 == '3'
Not equal (!=)|	Returns true if the operands are not equal.	| var1 != 4    var2 != "3"
Strict equal (===)| 	Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.|3 === var1


## Arithmetic operators
Operator|	Description	| Examples 
------------ | -------------
Remainder (%)	Binary operator.| Returns the integer remainder of dividing the two operands.|	12 % 5 returns 2.
Increment (++)	Unary operator.| Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one.|	If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.
Decrement (--)	Unary operator.| Subtracts one from its operand. The return value is analogous to that for the increment operator.	|If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2.
Unary negation (-)	Unary operator.| Returns the negation of its operand.|	If x is 3, then -x returns -3.
Unary plus (+)	Unary operator.| Attempts to convert the operand to a number, if it is not already.	| +"3" returns 3. +true returns 1.
Exponentiation operator (**)|	Calculates the base to the exponent power, that is, base^exponent|	2 ** 3 returns 8. 10 ** -1 returns 0.1.


[Read more about the  Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#operators)

# Loops and iteration

The statements for loops provided in JavaScript are:

* for statement
* do...while statement
* while statement
* labeled statement
* break statement
* continue statement
* for...in statement
* for...of statement

## for statement

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

![for](https://cdn-media-1.freecodecamp.org/images/1*XJvkwoG4BLFnx6tpfzPZQQ.jpeg)

![for](https://eecs.oregonstate.edu/ecampus-video/CS161/template/chapter_5/chapter5_images/5_17.png)

## while statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

![while](https://www.bookofnetwork.com/images/javascript-images/JS_while-syntx_24Feb17_1743.png)

example shows incrementing variable counter 5 times using while loop.
Also, shown below is output for every iteration of the loop.

![while](https://www.bookofnetwork.com/images/javascript-images/JS_While-loop-example_20Sep16_1243.png)

[Read more about Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)