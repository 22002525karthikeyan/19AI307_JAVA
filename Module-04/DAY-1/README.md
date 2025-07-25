# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End

## PROGRAM:
 ```
Program to implement a Constructor using Java
Developed by: KARTHIKEYAN R
RegisterNumber:  212222240046
```

## Sourcecode.java:
```
class Rectangle 
 { 
    int length;
    int width;
    Rectangle (int l, int w) 
    {  
        //Write your code here
        length=l;
        width=w;
    } 
    Rectangle (Rectangle obj) 
    { 
        //Write your code here
        this.length=obj.length;
        this.width=obj.width;
        
    } 
    int circumference () 
    { 
        //Write your code here
        return (length+width)*2+8;
    } 
} 
    //class to create Rectangle object and calculate area 
public class CopyConstructor 
{ 
    public static void main(String[] args) 
    { 
        Rectangle  firstRect = new Rectangle (5,6); 
        //Write your code here
        System.out.println("Area  of First Rectangle : "+firstRect.circumference());
        Rectangle secondRect = new Rectangle (firstRect);
        System.out.println("Area of First Second Rectangle : "+secondRect.circumference());
    } 
} 
```
## OUTPUT:

![449774918-c42bc52a-02d3-438d-88c8-c48ad745dac7](https://github.com/user-attachments/assets/c2844516-2941-49b3-af90-fc7827389015)


## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
