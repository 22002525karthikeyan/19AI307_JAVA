# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
Program to implement a Smallest Element in an Array
Developed by: KARTHIKEYAN R
RegisterNumber: 212222240046
```

## Sourcecode.java:
```
import java.util.*;
public class main
{
    public static void main(String[] args)
    {
        int n,i,j,temp=0;
        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();
        int[] arr = new int[n];
        for(i=0;i<n;i++)
        {
            arr[i] = sc.nextInt();
        }
        System.out.print("Second largest element = ");
        for(i=0;i<n;i++)
        {
            for(j=i+1;j<n;j++)
            {
                if(arr[i] < arr[j])
                {
                    temp = arr[i];
                    arr[i] =arr[j];
                    arr[j] = temp;
                }
            }
        }
        System.out.print(arr[1]);
        
    }
}
```

## OUTPUT:


![image](https://github.com/user-attachments/assets/8f27cc49-4186-4d13-a6df-51c2ff352a00)


## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




