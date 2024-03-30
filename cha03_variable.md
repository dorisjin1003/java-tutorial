#### chapter 03 Variable

### Data Types
Java data types are divided into two major categories: primitive data types and reference types.

1. Primitive data types consist of eight types:

* Numeric types [byte, short, int, long, float, double]
* char
* boolean

2. Reference types include classes, interfaces, and arrays.

## Integer type
Integer constants (specific values) in Java default to int type. To declare a long constant, 'l' or 'L' must be appended after the value.

## Float type
A brief explanation about the representation of floating-point numbers in computers: 
Floating-point numbers consist of three components: the sign bit, the exponent, and the significand (also known as the mantissa). 


The significand part may lose precision, resulting in accuracy loss (decimal numbers are all approximate values).

# FloatDetail.java
* Similar to integer types, Java floating-point types also have fixed ranges and field lengths, unaffected by the specific operating system.

* In Java, floating-point constants (specific values) default to double type. To declare a float constant, 'f' or 'F' must be appended after the value.

* There are two forms of floating-point constants:
- Decimal form: such as 5.12, 512.0f, .512 (must have a decimal point).
- Scientific notation: such as 5.12e2 (5.12 * 10^2), 5.12E-2 (5.12 / 10^2).

* Generally, double type should be used because it is more precise than float type. For example: double num9 = 2.1234567851; float num10 = 2.1234567851F;

* Floating-point number pitfalls: Comparing 2.7 and 8.1/3.


## Char type
# CharDetail.java
* Character constants are enclosed in single quotes ('').

* In Java, escape characters can be used to represent special characters after them. For example: char c3 = '\n'; represents the newline character.

* In Java, the essence of char is an integer, and when output, it is the character corresponding to the Unicode code.


## Boolean type
* The boolean type allows data to have only two values: true and false. There is no null value allowed for boolean types.

* A boolean type occupies 1 byte of memory.




### Primitive Data Type Conversion



