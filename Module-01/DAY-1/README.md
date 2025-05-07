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
Developed by: Hanshika Varthini R
RegisterNumber: 212223240046

class Student{
    String name;
    String address;
    int rollno;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();   
        obj.name="John";
        obj.address="Chennai";
        obj.rollno=10;
        System.out.println(obj.name+" "+obj.address+" "+obj.rollno);
    }   
}
```

## OUTPUT:

![Screenshot 2025-05-07 134821](https://github.com/user-attachments/assets/47ba58b0-ed4e-4ee5-bc28-4e39268126ee)


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
