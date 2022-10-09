# Report
To Report Daily Activity
Date :-26/9/22
                                 C# Net Basics
  Basic Structure of C#:
                 understand the Basic Structure of the C# Program using a Console Application.

  Methods and Properties of Console Application:
                 There are many methods and Properties are available in the Console class.
  Data Types :
                i gone through different Data Types and their uses.
 
  Literals :    Gone through literals,The fixed values are called Literals in C#. Here 'Literal' is a value that is used
                by the variables.

  Type Casting :
                Here we have two types of type casting. 1.Implicit
                                                        2.explicit
                 In 'Implicit' Type conversion, the smaller types are converted to larger data types and hence, there is no 
                 loss of data during the conversion.
                 In 'Explicit' Type casting, The larger data types can be converted into smaller datatype. 
                     Ex : original value is 1.23 whereas the converted value is 1.
  Variables :  
                I Gone through different kinds of variables a class can have and their behavior.
                 1. Non-Static/Instance Variable
                 2. Static Variable
                 3. Constant Variable
                 4. Readonly Variable
 Operators : 
               Operators in C# are symbols that are used to perform operations on operands. For example, consider the expression
               2 + 3 = 5, here 2 and 3 are operands and + and = are called operators.
               Gone through Different Kinds of operators.
                 1. Arithmetic Operators
                 2. Relational Operators
                 3. Logical Operators
                 4. Bitwise Operators
                 5. Assignment Operators
                 6. Unary Operators or
                 7. Ternary Operator or Conditional Operator
  
 Control Flow Statements :
                The Control Flow Statements are useful to write better and more complex programs.
                gone through different types of Control Statements.
                 1. Selection Statements or Branching Statements: (Examples: if-else, switch case, nested if-else, if-else ladder)
                 2. Iteration Statements or Looping Statements: (Examples: while loop, do-while loop, for-loop, and foreach loop)
                 3. Jumping Statements: (Examples: break, continue, return, goto)

 If-Else Statements :
                Here, the block of statements executes only when the condition is true. And if the condition is false, then it will
                skip the execution of the statements. Using else block is optional in C#.

  Switch Statements :
                 When there are several options and we have to choose only one option from the available options 
                 depending on a single condition then we need to go for a switch statement.The default block in the 
                 switch statement is optional.
  Nested Switch Statements :
                 Whenever we create a switch statement inside another switch statement, then it is said to be a nested 
                 switch statement and this is allowed in C#. 
     DATE :-27/9/22
                                        Week 2
                                 C# Net Basics
  Basic Stru          2 types of loops they are.
           1. Counter Loop
           2. Conditionak loop
        gone through various types of loops like :
           1. for loop
           2.for each
           3.While and Do While
Break Statement :
        the break is a keyword. By using the break statement, we can terminate either the loop body or the switch body.
 
Continue Statement :
         By using the continue keyword, we can skip the statement execution from the loop body. 

Goto Statement :
         The Goto Statement in C# is used to transfer the control to the labeled statement in the program.
Functions :
         Basically, there are two types of Functions in C#. 
          1. Built-in Functions :these are default functions providede in C#.
          2. User-Defined Functions :The User-defined functions in C# are the functions that are created by the programmer so
                                  that he/she can use it many times
          
Call By Value  :
        In .NET Framework, by default, all the objects are called by value, not called by reference. 
Call by Reference :
        C# provides a ref keyword to pass argument as reference-type. It passes reference of arguments to the function rather 
        than copy of original value. 

Recursion : recursion is a process in which a function calls itself repeatedly until some specified condition has been satisfied.

String : the string is an object of the String class that represents a sequence of characters. We can perform many operations on strings such 
         as concatenation, comparison, getting substring, search, trim, replacement, etc.

Static Keyword :
         they most probably answer you that the static keyword is used in Factory Design Pattern, Singleton Design Pattern as well as used for data sharing, etc.
        
Static vs Non-Static Members :
         The members (Variables, Constructors, and Methods) which are created by using the static modifier are called static members rest of all are called non-static members.
         the members which require an instance of a class for both initialization and execution are known as non-static members.
         
28\9\22
           Object Oriented Programming (OOPs) in C#
Class :    A class is simply a user-defined data type that represents both state and behavior.

Objects : 
          It is an instance of a class. A class is brought live by creating objects. An object can be considered as a thing
          that can perform activities.

Constructor  :
          It is a special method present inside a class responsible for initializing the variables of that class. We will come
          to this point later part of this article.
          There are five types of constructors available. they are

          1.Default or Parameter Less Constructor
          2.Parameterized Constructor
          3.Copy Constructor
          4.Static Constructor
          5.Private Constructor

Inheritance :
          Inheritance in C# is a mechanism of consuming the members that are defined in one class from another class.
   
Polymorphism :
          polymorphism means “many forms” .
Method Overloading : this can be done with same Method name but different Parameters

29/9/22
                     Master in OOps

Class and Object : 
             Understanding class and objects in C# is very important for you as a developer. 

Google Meet: by subramaniyanvg at 11.30 am

 
Constructors :
             It is a special method present inside a class responsible for initializing the variables of that class.

Properties : In order to encapsulate and protect the data members (i.e. fields or variables) of a class, we use properties in C#.
             The Properties in C# are used as a mechanism to set and get the values of data members of a class outside of that class.

Methods :   A method is a code block that contains a series of statements. A program causes the statements to be executed by calling 
            the method and specifying any required method arguments
           
30/9/22
                           OOPs
Garbage Collector :
            Garbage Collector is nothing but, it is a feature provided by CLR which helps us to clean or destroy unused 
            managed objects. Cleaning or destroying those unused managed objects basically reclaim the memory.

Access Specifiers :
            Private : When we declare a type member (variable, property, method, constructor, etc) as private, then we can
                     access that member within the class only.
            Public : When we declare a type member (variable, property, method, constructor, etc) as public, then we can access
                     that member from anywhere.
            Protected : protected members are available within the parent class (i.e. the containing type) as well as to the 
                        child/derived classes (classes derived from the containing type). 
            Internal : available anywhere within the containing assembly. It’s a compile-time error to access an internal member
                       from outside the containing assembly.
            Protected Internal : Protected Internal Members in C# can be accessed anywhere within the same assembly i.e. in which
                                 it is declared or from within a derived class from another assembly.
            Private Protected : The private protected members are accessible within the class and within the derived class of the
                                 same assembly but cannot be accessed from another assembly.

Abstraction:  process of defining a class by providing necessary details to call the object operations (i.e. methods) by hiding its
            implementation details

Inheretance : he members defined in one class can be consumed from another class by establishing a parent/child relationship between
              the classes.
Polymorphism : Polymorphism is a concept by which we can perform a single task in different ways.

Struct and Classes :
             Struct is a value type and class is a reference type so whatever differences hold for reference type and value types hold
             for struct and classes too.

Interface: Interface members are public by default and no explicit access modifiers are allowed.Can contains declaration not implementation.

3/10/22
                             Master In OOps
polymorphism : gone little bit deep into polymorphism and different types of implementations. they are,
             1.Method Overloading
             2.Operator Overloading
             3.Method Overriding
             4.Method Hiding

interface : he Interface in C# is a fully un-implemented class used for declaring a set of methods of an object. So, we
            can define an interface as a pure abstract class which allows us to define only abstract methods.
            gone through how to implementit in bank.


Abstraction : 
            Abstract Method: A method without a body is known as an abstract method.
            Abstract Class: A class that contains any abstract members in it is known as an abstract class.

Static Class :
           The class which is created by using the static modifier is called a static class in C#. A static class can contain
           only static members. It is not possible to create an instance of a static class.

partial Class :

           we can physically split the content of the class into different files but even physically they are divided but 
           logically it is one single unit only.

4/10/22
                               Master Class C#

Today i did Programming on Static methods, Abstraction ,Polymorphism, Extension Methods ,Interface.
  
Google meet by Ankit Yadav from 3.00 pm-4.00 pm 
  
cultural activies from 6.00pm - 7.00pm

6/10/22
Properties : 
             i gone through how to use properties and where to use. about getters and setters.
             
      A Property in C# is a member of a class that is used to set and get the data from a data field (i.e. variable) of a class.
       Getters and Setters : Add security to fields Encapsulation. They are accessors found within Properties.
          Get Accessor: Used t return property value.
          Set Accessor: Used to assign a new value.

Exception Handling:
    An Exception is a class in C# which is responsible for abnormal termination of the program when runtime errors occur while running the program

    Types of Errors : When we write and execute our code in the .NET framework then there is a possibility of two types of error occurrences.

    Compilation Errors :The error that occurs in a program at the time of compilation is known as a compilation error (compile-time error).
                        These errors occur due to syntactical mistakes in the program.
    Runtime Errors : The compiler will never check the logic, the compiler will only check the syntaxes. So, the compiler will identify 
                     the syntax error, but not the logical error. 

   To implement the try-catch implementation, the .NET framework provides three keywords. They are as follows:
   1.Try :The try keyword establishes a block in which we need to write the exception causing and its related statements.
   2.Catch :The catch block is used to catch the exception that is thrown from its corresponding try block.
   3.finally:The keyword finally establishes a block that definitely executes the statements placed in it irrespective of
     whether any exception has occurred or not.
Enum :
   An enum is a special "class" that represents a group of constants (unchangeable/read-only variables).
   To create an enum, use the enum keyword (instead of class or interface), and separate the enum items with a comma.

07-10-2022

  Given PPT presention on OOps Concept.
  Doubt clarification by @Ramesh Kumar.
  go through C# Totorials.












