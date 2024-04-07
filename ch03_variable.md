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

## FloatDetail.java
* Similar to integer types, Java floating-point types also have fixed ranges and field lengths, unaffected by the specific operating system.

* In Java, floating-point constants (specific values) default to double type. To declare a float constant, 'f' or 'F' must be appended after the value.

* There are two forms of floating-point constants:
- Decimal form: such as 5.12, 512.0f, .512 (must have a decimal point).
- Scientific notation: such as 5.12e2 (5.12 * 10^2), 5.12E-2 (5.12 / 10^2).

* Generally, double type should be used because it is more precise than float type. For example: double num9 = 2.1234567851; float num10 = 2.1234567851F;

* Floating-point number pitfalls: Comparing 2.7 and 8.1/3.


## Char type
Character type can represent a single character, and the character type is char. Char occupies two bytes (can store Chinese characters). Multiple characters are represented using the String data type.



## CharDetail.java
* Character constants are enclosed in single quotes ('').

* In Java, escape characters can be used to represent special characters after them. For example: char c3 = '\n'; represents the newline character.

* In Java, the essence of char is an integer, and when output, it is the character corresponding to the Unicode code.


## Boolean type
* The boolean type allows data to have only two values: true and false. There is no null value allowed for boolean types.

* A boolean type occupies 1 byte of memory.



### Primitive Data Type Conversion

## Automatic type conversion
* Automatic Promotion: When multiple data types are mixed in an operation, the system automatically converts all data to the type with the largest capacity before performing the calculation.

* Assignment Compatibility: Assigning a larger-capacity data type to a smaller-capacity one will result in an error. Conversely, assigning a smaller-capacity data type to a larger-capacity one will result in automatic type conversion.

* No Automatic Conversion between (byte, short) and char: There is no automatic conversion between byte, short, and char. However, byte, short, and char can all be used in calculations, and they are first converted to int when performing calculations.

* Boolean Not Participating: Boolean type does not participate in type conversion.

* Automatic Promotion Principle: The result of an expression is automatically promoted to the largest type among the operands involved.


## Type casting
* Inverse Process of Automatic Conversion: Explicit type conversion is the reverse process of automatic conversion, where a larger-capacity data type is converted to a smaller-capacity one.

* Syntax: To perform explicit type conversion, you need to use the cast operator (), followed by the target data type. For example, (int) doubleValue will explicitly convert a double value to an integer.

* Potential Loss of Precision or Overflow: Explicit type conversion may lead to loss of precision or overflow if the value being converted cannot be represented accurately in the target data type. It's essential to be cautious when performing explicit type conversion to avoid unintended consequences.

* Use with char Type: While char type can store constant values from int, it cannot store variable values from int directly. Therefore, explicit type casting is required when assigning int variables to char variables.





### Converting between primitive data types and String type
## Intro
From primitive type to String type:

Syntax: Simply concatenate the value of the primitive type with an empty string "".

From String type to primitive data type:

Syntax: Use the parseXX method of the corresponding wrapper class of the primitive type.
