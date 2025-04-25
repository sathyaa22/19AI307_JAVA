# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address' and Integer variable 'rollno'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Declare an int variable "rollno" and initialize it with "10"
7.	Define the 'main' class named "Main"
8.	Create an object 'obj' of the 'Student' class
9.	Print the value of 'name' and 'address' and 'rollno' variables of the 'obj' object
10.	End


## PROGRAM:

```
Program to implement a class & objects using Java
Developed by: SATHYAA R
RegisterNumber: 212223100052
```

## Sourcecode.java:

```
class Student
{
    String name="John";
    String address="Chennai";
    int rollno=10;
}
public class Main 
{
    public static void main(String[] args) 
    {
        Student obj= new Student();   
        obj.name="John";
        obj.address="Chennai";
        obj.rollno=10;
        System.out.println(obj.name+" "+obj.address+" "+obj.rollno);
    }   
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/3426112b-6726-49b3-80a6-cd4d759bfd51)


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' and Integer variable 'rollno' was created successfully.
