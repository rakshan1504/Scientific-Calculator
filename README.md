# Advanced-Scientific-Calculator-CPP
An Advanced Scientific Calculator Tool using C++ Language. It includes all major functions a calculator uses, apart for them, we have included a number of other innovatively designed functions.

## Basis
The purpose of creation of this calculator tool is to simplify calculations for people, at least, on our level.

## Advantages
This gives us a better understanding of creating programming tools, and will be amongst our first projects in these programming languages as well.

## Includes
- Basic Mathematical operators (Addition, Subtraction, Multiplication, Division, etc.)
- Trigonometric Operators (Sin, Cos, Tan, Cot, Cosec, Sec)
- Scientific Calculator Operators (Power, Factorial, Reciprocal, Logarithm, Log10, Exponential function, Square Root, etc.)
- Unit Converters (CGS to SI and vice-versa, Degree to Radians and vice versa, etc.)
- Additional Functions (Rounding off, Greatest/Smallest Integer, Absolute Value, Negative of a Rational Number, Remainder after Division, etc.)
- Innovatively Created Operations (Taylor Series Calculator, Fibonacci Sequence Calculator, Permutations, Combinations, Impedance Calculation, Phase angle calculation, etc.)

# Implementation

## Basic Mathematical Operators
- Addition
  - Implementation using simple a+b commands by defining a and b as int/float data types.
- Subtraction
  - Implementation using simple a-b commands by defining a and b as int/float data types.
- Multiplication
  - Implementation using simple a*b commands by defining a and b as int/float data types.
- Division
  - Implementation using simple a/b commands by defining a and b as int/float data types.

## Trigonometric Operators
- Sine function (sin x)
  - Implementation using <math.h> library. The input will be only in Radians(float data type).
- Cosine function (cos x)
  - Implementation using <math.h> library. The input will be only in Radians(float data type).
- Tangent function (tan x)
  - Implementation using <math.h> library. The input will be only in Radians(float data type).
Cotangent(cot x), Cosecant(cosec x) and Secant(sec x) functions can be implemented similarly by using the commands 1/tan x, 1/sin x, 1/cos x respectively.

- Inverse Trigonometric Functions:
These can be calculated using asin x, acos x, atan x, etc., functions.

## Scientific Calculator Operators
- Power Function
  - Implementation using <math.h> library using the  pow(x,n) function. Exponential Function can also be implemented using the above technique.
- Factorial
  - The function will be user defined, and will be implemented using loops.
- Square Root
  - Implementation using <math.h> library using the sqrt(x) function.
- Reciprocal
  - Implementing using putting value equivalent to 1/x.
- Logarithm(ln)
  - Implementation using <bits/c++.h>  or <math.h>library using log(x) function. Similarly, log10 can also be implemented by log10(x) function.

## Unit Converters
- Radians to degrees and Degrees to Radians
  - This will be implemented by defining a function that uses the fact that 1 Degree is equivalent to π/180 radians.
- CGS to SI and SI to CGS
  - Basic conversion factor between all basic CGS and SI Units is that
    - 1 kg(SI) = 1000 g(CGS)
    - 1  m(SI) = 100 cm(CGS)
    - 1 s(SI) = 1 s(CGS)
These can be assigned easily.

## Additional Functions
- Rounding off
  - Implemented using round() function using <cmath> library for float database.
- Greatest/Smallest Integer
  - Implemented using nested loops and arrays.
- Absolute Value
  - Implemented using the abs() function. Alternatively, if else statements can be used.
- Negative of a Rational Number
  - Implemented by assigning the variable a value that is negative of its own.
- Remainder after division
  - Implemented by using ‘%’ (Modulus) function. We can print the remainder of the division.

## Innovatively Designed Functions
- Taylor Series Calculator(exemplified using 𝑒^𝑥)
  - Implemented using loops and defining the Taylor series for the given exponential function.
- Fibonacci Sequence Calculator 
  - Implemented using for loops and user-defined functions, following the Fibonacci Sequence Principle that the nth term is the sum of the (n-1)th and the (n-2)th terms.
- Permutations and Combinations
  - Implemented using the formulae for P&C using the factorial function for calculating factorials.
- Impedance Calculation 
  - Implemented using sqrt() and pow() functions. Where impedance is given by:
                          Z = √(𝑹^𝟐+𝑿^𝟐 )
- Phase angle calculation
  - Implemented using arctan function defined by <math.h> library, and using the relation:
〖𝐭𝐚𝐧〗^(−𝟏)⁡〖𝑿/𝑹〗 = Phase Angle (ф)  or 〖𝐜𝐨𝐬〗^(−𝟏)⁡〖𝑹/𝒁〗 = Phase Angle(ф)	[Where X = |𝑿_𝑳−𝑿_𝒄|]
