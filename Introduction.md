# Introduction to sintax

## The using Keyword
The first statement in any C# program is
~~~c#
using System;
~~~
The using keyword is used for including the namespaces in the program. A program can include multiple using statements.

## The class Keyword
The class keyword is used for declaring a class.

## Comments in C#
Comments are used for explaining code. Compilers ignore the comment entries. The multiline comments in C# programs start with /* and terminates with the characters */ as shown below
~~~c#
/* This program demonstrates
The basic syntax of C# programming 
Language */
~~~
Single-line comments are indicated by the '//' symbol. For example,
~~~c#
}//end class Rectangle
~~~

## Member Variables
Variables are attributes or data members of a class, used for storing data. In the preceding program, the Rectangle class has two member variables named length and width.

## Member Functions
Functions are set of statements that perform a specific task. The member functions of a class are declared within the class. Our sample class Rectangle contains three member functions: AcceptDetails, GetArea and Display.

## Instantiating a Class
In the preceding program, the class ExecuteRectangle contains the Main() method and instantiates the Rectangle class.

## Identifiers
An identifier is a name used to identify a class, variable, function, or any other user-defined item. The basic rules for naming classes in C# are as follows −

- A name must begin with a letter that could be followed by a sequence of letters, digits (0 - 9) or underscore. The first character in an identifier cannot be a digit.

- It must not contain any embedded space or symbol such as? - + ! @ # % ^ & * ( ) [ ] { } . ; : " ' / and \. However, an underscore ( _ ) can be used.

- It should not be a C# keyword.

## C# Keywords
Keywords are reserved words predefined to the C# compiler. These keywords cannot be used as identifiers. However, if you want to use these keywords as identifiers, you may prefix the keyword with the @ character.

In C#, some identifiers have special meaning in context of code, such as get and set are called contextual keywords.