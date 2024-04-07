### Introduction to Program Flow Control:
1. Sequential Control
2. Branch Control
3. Loop Control

## If Branch
The if statement is a fundamental control flow statement in Java used for decision-making. It allows you to execute a block of code conditionally based on whether a given condition evaluates to true or false. 
```
import java.util.Scanner;
public class IfExercise01 {
class If_01 {
    public static void main(String[] args){
        //应该定义一个Scanner 对象
        Scanner myScanner = new Scanner(System.in); 
        System.out.println("input age: ");
        // 用age来接收
        int age = myScanner.nextInt();
        if(age > 18) {
            System.out.println("buy ticket");
        } else {//双分支
            System.out.println("no ticket");
        }
        System.out.println("process continue");
    }
}
class If_02 {
    public static void main(String[] args){
        double t1 = 20.0;
        double t2 = 15.0;
        if(t1 > 10.0 && t2 <20.0) {
            System.out.println("the sum is = " + t1 + t2);
        } 
    }
}

class If_03 {
    public static void main(String[] args){
       int a1 = 15;
       int a2 = 30;
        if((a1 + a2) % 3 ==0 && (a1 + a2) % 5 ==0) {
            System.out.println("两个数的和可以既被3又被5整除");
        } else {
            System.out.println("两个数的和不能既被3又被5整除");
        }
    }
}

class If_04 {
    public static void main(String[] args){
        Scanner myScanner = new Scanner(System.in); 
        System.out.println("请输入年份");
        int year = myScanner.nextInt();
        if( (year % 4 == 00 && year % 100 !=0) || year % 400 == 00) {  //注意这里不是|
            System.out.println("是闰年");
        } else {
            System.out.println("不是闰年");
        }
    }
}

}
```

## Switch Branch
1. The data type of the expression should match the type of the constants following each case, or it should be a type that can be automatically converted to a type that can be compared with each other. For example, if the input is a character and the constant is an integer.

2. The return value of the expression in a switch statement must be: (byte, short, int, char, enum, String).

3. The values in case clauses must be constants and cannot be variables.

4. The default clause is optional; it is executed when no matching case is found.

5. The break statement is used to exit the switch block after executing a case branch. If break is not used, the program will continue to execute sequentially until the end of the switch block, unless it encounters a break statement.


## for loop control
```
for(loop variable initialization; loop condition; loop variable iteration){
    loop operations (multiple statements can be used);
}
```

## while loop control
```
while (loop condition){
    loop body (statement);
    loop variable iteration;
}
```

## do.while loop control
```
do {
    loop body (statement);
    loop variable iteration;
} while (loop condition);
```


## Jump Control Statement - break
* The break statement is used to terminate the execution of a statement block, typically used in switch or loops (for, while, do-while).

* When the break statement appears within nested statement blocks, you can specify which level of statement block to terminate by using a label. If no break is specified, it defaults to exiting the nearest loop body.

 ![image](https://github.com/dorisjin1003/java-tutorial/assets/158774060/4b4800ce-7835-4aac-8516-74c37ff5e640)

 ## Jump Control Statements - continue
* The continue statement is used to terminate the current iteration of a loop and continue with the next iteration.

* When the continue statement appears within nested loops, you can specify which loop to skip by using a label. The rules for using labels are the same as mentioned before.

 ## Jump Control Statement - return
 The return statement is used in methods to exit the current method.
