# Lab 02 -- Chapter 01

## Define the following trms:
* object, - state or behavior (instance) of a class
* class, - A code base that defines how to create an object
* instance, - Specific realization of any object
* method, - A collection of statements, in a class, used to manipulate (mutators) or access information (accessors) from an object of that class (Behaves like a function in mathematics)
* signature (or heading), - Name of a method and it's parameter type. ex. This signature changes the size of the instance "box" of class "Box" and does not give an output
---
void changeSize(Box box)
---
* parameter, - An input of the method. ex. "box" is the parameter in the example above.
* type, - Defines what values the parameter is allowed to be. Ex. Int for whole numbers, String for words or sentences, etc.
* state, - Set of values describing an object.
* source code, - Collection of commands that compiles to create an executable program.
* return value, - Output of a method
* compiler - Converts source code into machine language (allows the computer to read the instructions)

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
