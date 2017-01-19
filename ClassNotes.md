# Notes from Lecture

## January 18, 2017

### Data Types

#### String

String object
string
“string literal”
`String myString = “Hello there!”;`

#### Variables

= is the assignment operator

Constant with “final”

#### Primitive Data Types

##### Numeric types

int, short, long, etc

Table on pg 71

In Java all numeric types are signed

##### char

chars are not strings

chars are created with single quotes ‘ ‘
##### Booleans

true or false

##### Expressions

An expression is a combination of one or more operators and operands that usually perform a calculation (p75)

`2 + 2`

Arithmetic operators: + - * / %

Unary operators: + -    ++ --

Thing to remember: Java is strongly typed

##### Coversions

Assignment conversion: int to double and are generally implicit

Promotion: happens automatically in the process of evaluating an expression…

``` java
int count = 10;
float sum = 32.4;
float average = sum / count;
```

Casting: an explicit conversion done by the programmer 

P84 tables of both widening and narrowing conversions

Widening conversion is converting from a type with a smaller range of values to a wider range of values

Narrowing conversion are the opposite


