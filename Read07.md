# Functions
In general, a function is a "subprogram" that can be called by code external (or internal in the case of recursion) to the function. Like the program itself, a function consists of a series of statements called the function body. Values can be passed to a function, and the function will return a value.

In JavaScript, functions are first-class objects, because they can have properties and methods like any other object. What sets them apart from other things is that functions can be called. In short, they are functional objects.

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

#### Example
```
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```
## Expressions and operators
### Operators

JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

  - Assignment operators
  - Comparison operators
  - Arithmetic operators
  - Bitwise operators
  - Logical operators
  - String operators
  - Conditional (ternary) operator
  - Comma operator
  - Unary operators
  - Relational operators

### Operator precedence

The precedence of operators determines the order they are applied when evaluating an expression. You can override operator precedence by using parentheses.

The following table describes the precedence of operators, from highest to lowest.


Operator type | Individual operators
--- | ---
member | . []
call / create instance | () new
negation/increment | ! ~ - + ++ -- typeof void delete
multiply/divide | * / %
addition/subtraction | + -
bitwise shift | << >> >>>
relational | < <= > >= in instanceof
equality | == != === !==
bitwise-and | &
bitwise-xor	| ^
bitwise-or	|\|
logical-and	| &&
logical-or	|\|\|
conditional	| ?:
assignment	| = += -= *= /= %= <<= >>= >>>= &= ^= \|= &&= \|\|= ??=
comma	| ,