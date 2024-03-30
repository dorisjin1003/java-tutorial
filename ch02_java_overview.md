# Java Overview

## Java's Important Characteristics

* ava language is object-oriented (OOP).

* Java language is robust. Java's strong typing mechanism, exception handling, and automatic garbage collection are important guarantees of Java program robustness.

* Java language is platform-independent. Compiled .class files can run on multiple systems, a feature known as platform independence.

* Java language is interpreted.
  
  Interpreted languages: JavaScript, PHP, Java. Compiled languages: C/C++.

  The difference is that in interpreted languages, the compiled code cannot be directly executed by the machine and requires an interpreter to execute, whereas in compiled languages, the compiled code can be directly executed by the machine.


## JDK, JRE
### JDK Introduction

The full name of JDK is Java Development Kit, which is a set of tools for Java development. JDK consists of JRE (Java Runtime Environment) plus Java development tools such as java, javac, javadoc, javap, etc. It is intended for use by Java developers.

### JRE Introduction

JRE stands for Java Runtime Environment, which includes JVM (Java Virtual Machine) and Java's core class library. It comprises the Java Virtual Machine (JVM) and the core class library required by Java programs. If you want to run a developed Java program, you only need to install JRE on the computer.



## Java Development Steps

1. Write Java code in a file with the extension ".java", for example, "Hello.java".
2. Compile the Java file using the "javac" command to generate a ".class" file.
3. Run the generated class file using the "java" command.


## Hints

* Java source files have the extension ".java". The basic component of a source file is a class, such as the "Hello" class in this example.

* The entry point for executing a Java application is the "main" method. It has a fixed syntax: "public static void main(String[] args)".

* Java language strictly distinguishes between uppercase and lowercase letters.

* A source file can have at most one public class. There is no limit to the number of other classes. Each class corresponds to one "class" file.

* If a source file contains a public class, the file name must be named after that class!

* A source file can have at most one public class. There is no limit to the number of other classes. You can also write the main method in a non-public class and then specify to run the non-public class, so the entry method is the non-public "main" method.


## Java Escape Characters

In the console, pressing the tab key can achieve command completion.
* \t: Represents a tab, providing alignment functionality.
* \n: Represents a newline character.
* \\ : Represents a backslash character.
* \" : Represents a double quote character.
* \' : Represents a single quote character.
* \r: Represents a carriage return. System.out.println("timerring\r Beijing"); Note: Carriage return does not result in a newline.



## Java Code Conventions

Class and method comments should be written in Javadoc format.

Non-JavaDoc comments are often for maintainers of the code, focusing on explaining why the code is written that way, how to modify it, and any important considerations.

Use tab for indentation, defaulting to moving the entire block to the right. Use Shift+Tab to move the entire block to the left.

Operators and "=" should have a space on each side.

Source files should use UTF-8 encoding.

Line width should not exceed 80 characters.

Code style preferences for continuation lines and line endings (!) recommend line endings style.





