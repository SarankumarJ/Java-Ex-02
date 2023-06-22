# EX-02 Java program to compare two numbers
## Aim:
To write a java program to compare two numbers.

## Procedure:
### Step 1:
Import the required packages

### Step 2:
Get two inputs from the user

### Step 3:
Compare them using comparative operator.

### Step 4:
If first number is greater display first number is greater.

### Step 5:
If second number is greater then display first number is lesser.

### Step 6:
If Both numbers are equal then display both are equal.

### Program:-
#### Developed By : Sarankumar J
#### Register Number : 212221230087
```java
import java.util.Scanner;
public class Compare {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num1,num2;
        System.out.print("Enter Two numbers: ");
        num1=sc.nextInt();
        num2=sc.nextInt();
        if(num1>num2)
        {
            System.out.println(num1+" is greater than "+num2);
        }
        else if(num1<num2)
        {
            System.out.println(num1+" is smaller than "+num2);
        }
        else
        {
            System.out.println(num1+" and "+num2+" are equal");
        }
    }
}
```
## Output:
![image](https://github.com/SarankumarJ/Java-Ex-02/assets/94778101/f2cbd433-4707-4809-b3bf-1d4678cbd4af)

## Result:-
A java program to compare two numbers has been executed successfully.
