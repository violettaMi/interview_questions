# Design/Patterns

## OOP

1. Explain the difference between public, protected and private methods
self (receiver)

1. What is OOP? What are the 3 principles of OOP and their meaning?
Object-oriented programming (OOP) is a programming paradigm that uses objects and their interactions to design applications and computer programs.

1. What is Encapsulation?
The encapsulation hides the implementation details of a class from other objects. 

1. What is Polymorphism?
 The polymorphism is the process of using an operator or function in different ways for different data input.
 
1. What is Inheritance?
The inheritance is a way to form new classes using classes that have already been defined.

1. Abstraction 
The abstraction is simplifying complex reality by modeling classes appropriate to the problem.

1. What is a Class?
A class is a template for an object, that describes the state and behavior that the objects of the class all share.

1. What is an Object?
An object is a combination of data and methods.

1. What is the main difference between a `class` and an `object`?
 
1. Explain the term Constructor.
 It is automatically called when an object is created. 
 
1. Ruby constructor overloading
Constructor overloading is the ability to have multiple types of constructors in a class. 
  
1. What is the `super` keyword?
 The super method calls the constructor of the parent class. 
 The super method calls a method of the same name in the parent's class.
 
1. What is the to_s Method into classes?
 Any class you define should have a to_s instance method to return a string representation of the object.
 
 1. What is method overriding?
 Though you can add new functionality in a derived class, 
 but sometimes you would like to change the behavior of already defined method in a parent class.
 You can do so simply by keeping the method name same and overriding the functionality of the method
 
 1. What is Operator Overloading?
 Ruby permits operator overloading, allowing one to define how an operator( +, -, /, *, **, %) shall be used in a particular program.
 
 1. Create Object Using Allocate
 Box.allocate   => #<Box:0x00007ffd86821668>
 Box.new(10, 20)   => #<Box:0x00007ffd8684d560 @width=10, @height=20>