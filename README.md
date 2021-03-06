# Method-overloading-and-Method-overriding

## Method Overloading
If a class has multiple methods having same name but different in parameters, it is known as Method Overloading.

If we have to perform only one operation, having same name of the methods increases the readability of the program.

Suppose you have to perform addition of the given numbers but there can be any number of arguments, if you write the method such as a(int,int) for two parameters, and b(int,int,int) for three parameters then it may be difficult for you as well as other programmers to understand the behavior of the method because its name differs.

Advantage of method overloading
* Method overloading increases the readability of the program.

### Different ways to overload the method
There are two ways to overload the method in java:

* By changing number of arguments
* By changing the data type

## Method Overriding in Java

If subclass (child class) has the same method as declared in the parent class, it is known as method overriding in Java.

In other words, If a subclass provides the specific implementation of the method that has been declared by one of its parent class, it is known as method overriding.

### Usage of Method Overriding
* Method overriding is used to provide the specific implementation of a method which is already provided by its superclass.
* Method overriding is used for runtime polymorphism
### Rules for Java Method Overriding
* The method must have the same name as in the parent class
* The method must have the same parameter as in the parent class.
* There must be an IS-A relationship (inheritance).
