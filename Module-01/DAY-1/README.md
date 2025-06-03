# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
Program to implement a class & objects using Java
Developed by: KARTHIKEYAN R
RegisterNumber:  212222240046

```

## Sourcecode.java:
class Student
{
    String name;
    String address;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();        
        obj.name="John";
        obj.address="Chennai";
        System.out.println(obj.name+" "+obj.address);
    }
}

## OUTPUT:
![449768060-5de6ba68-d94e-4d8d-85b0-5c17baa7689c](https://github.com/user-attachments/assets/cb098ad0-a783-4e5f-8b71-1a6aab5ac59e)

## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
