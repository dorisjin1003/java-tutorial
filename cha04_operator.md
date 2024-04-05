### Chapter 04 Operator

## Arithmetic operators
![image](https://github.com/dorisjin1003/java-tutorial/assets/158774060/ef2318cd-0dcd-4db9-a891-90ac5e913486)


## Assignment operators

1. Classification of assignment operators:

Basic assignment operator =
Compound assignment operators +=, -=, *=, /=, %=, etc. One important one is +=; the usage of others follows the same principle.

2. Characteristics of assignment operators:

Compound assignment operators perform type conversion.

byte b = 2; b+=3; b++;


## Relational operators
The result of relational operators is always a Boolean type, which means it's either true or false.


## Logical operators
Used to combine multiple conditions (multiple relational expressions), the final result is also a boolean value.

* a&b: & is called logical AND: Rule: When both a and b are true, the result is true; otherwise, it is false.
* a&&b: && is called short-circuit AND: Rule: When both a and b are true, the result is true; otherwise, it is false.
* a|b: | is called logical OR: Rule: When either a or b is true, the result is true; otherwise, it is false.
* a||b: || is called short-circuit OR: Rule: When either a or b is true, the result is true; otherwise, it is false.
* !a: Called negation or NOT operation. When a is true, the result is false; when a is false, the result is true.
* a^b: Called logical XOR. When a and b are different, the result is true; otherwise, it is false.

## Ternary operator
Basic syntax: 

# Operation rules:

If the condition expression is true, the result after the operation is expression1;
If the condition expression is false, the result after the operation is expression2;

# Usage details:
Expression1 and expression2 should be of the type that can be assigned to the receiving variable (or can be automatically converted).
The ternary operator can be converted into an if-else statement.

# Operator precedence: 
* Operators have different precedence levels, which determine the order of operations in an expression. Operators in the upper rows always have higher precedence than those in the lower rows.
* Only unary operators and assignment operators are evaluated from right to left.
* ![image](https://github.com/dorisjin1003/java-tutorial/assets/158774060/0a858f9a-655f-4cf1-9813-4852ba28a587)



## Rules and conventions for naming identifiers
# Naming rules for identifiers:

* Consist of 26 English letters (both uppercase and lowercase), digits 0-9, or the dollar sign $.

* Cannot start with a digit.

* Cannot use keywords or reserved words, but can contain them.

* Java strictly distinguishes between uppercase and lowercase letters, with no length limit.

* Identifiers cannot contain spaces. For example, int a b = 90; is not valid.
