# Ex.No:2(A)  STATIC METHOD

## AIM:
To create a java program for calculate cube of a number using static method.

## ALGORITHM :
1.  Start : Begin the process of calculating the cube of a number.
2.	Declare a variable to store input : Declare an integer variable n to hold the number whose cube will be calculated.
3.	Create a Scanner object : Create a Scanner object (sc) to read the input from the user.
4.	Read input from the user : Prompt the user to input an integer value. The input value is stored in the variable n.
5.	Call the cubecal function : Call the function cubecal(n) which computes the cube of the number by performing n * n * n.
6.	Store the result : Store the result of the cubecal function in an integer variable result.
7.	Output the result :
8.	Print the cube of the number using System.out.println("Cube is: " + result);.
9.	End the program.




## PROGRAM:
 ```
Program to implement a Static method using Java
Developed by: KARTHIKEYAN R
RegisterNumber: 212222240046 
```

## Sourcecode.java:
```
import java.util.Scanner;

public class CubeCalculator {

    public static int calculateCube(int number) {
        return number * number * number;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int number = scanner.nextInt();
        int cube = calculateCube(number);
        System.out.println("Cube is: "+ cube);
    }
}
```

## OUTPUT:
![449770138-ebc0884e-1875-4be6-9f67-669cdbb70fd3](https://github.com/user-attachments/assets/b1b5c1aa-35c6-4ce7-9f9b-ca5d1ebcccc0)

## RESULT:
Thus the java program for calculate cube of a number using static method has been executed successfully.

