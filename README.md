# Lab 02 -- Chapter 01

## Define the following trms:
* object, - What's created from a class
* class, - A code base for objects
* instance, - What's created from a specific class
* method, - A peice of code from a class that will affect the instance it's used on.
* signature, - A method's name and it's parameters. 
* parameter, - An input request from a method.
* type, - Defines the different inputs a parameter can use. Ex. Int for whole numbers, String for words or sentences, etc.
* state, - Every attribute and it's value of a specific class.
* source code, - The code that makes up a class
* return value, - Determines what a method returns after it's called.
* compiler - Converts code into something the computer can understand

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 - Int
* "hello" - String
* 101 - Int
* -1 - Int
* true - Boolean
* "33" - String
* 3.1415 - Float

## What would you have to do to add a new field, for example one called name, to a circle object?
In the part of the class where the attributes are defined, I would add "private String name;", then add a way to change the name:
public void changeName (String newName)
{
	name = newName;
}
## Write the header for a method named send that has one parameter of type String, and does not return a value.
void send(String send1);
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
int average(int num1, int num2);
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
Object. The class is Book.
## Can an object have several different classes? Discuss.
A class can make an object that uses code from several different classes. That means that an object can technically be made up of different classes, but the computer only sees it as being made up of one class that happens to call other classes.