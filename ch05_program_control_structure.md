### Introduction to Program Flow Control:
1. Sequential Control
2. Branch Control
3. Loop Control

## If Branch



## Switch Branch
1. The data type of the expression should match the type of the constants following each case, or it should be a type that can be automatically converted to a type that can be compared with each other. For example, if the input is a character and the constant is an integer.

2. The return value of the expression in a switch statement must be: (byte, short, int, char, enum, String).

3. The values in case clauses must be constants and cannot be variables.

4. The default clause is optional; it is executed when no matching case is found.

5. The break statement is used to exit the switch block after executing a case branch. If break is not used, the program will continue to execute sequentially until the end of the switch block, unless it encounters a break statement.


## for loop control

for (loop variable initialization; loop condition; loop variable iteration){
    loop operations (multiple statements can be used);
}

## while loop control

while (loop condition){
  loop body (statement);
  loop variable iteration;
}

## do.while loop control
do {
  loop body (statement);
  loop variable iteration;
} while (loop condition);

## Jump Control Statement - break
* The break statement is used to terminate the execution of a statement block, typically used in switch or loops (for, while, do-while).

* When the break statement appears within nested statement blocks, you can specify which level of statement block to terminate by using a label. If no break is specified, it defaults to exiting the nearest loop body.

 ![image](https://github.com/dorisjin1003/java-tutorial/assets/158774060/4b4800ce-7835-4aac-8516-74c37ff5e640)

 ## Jump Control Statements - continue
* The continue statement is used to terminate the current iteration of a loop and continue with the next iteration.

* When the continue statement appears within nested loops, you can specify which loop to skip by using a label. The rules for using labels are the same as mentioned before.

 ## Jump Control Statement - return
 The return statement is used in methods to exit the current method.
