# Basics of Java

In this chapter, we will know basics of java, like variables, datatypes, types of datatypes, identifiers, keywords, Oprators.

- Keywords
- Identifiers
- Variables
- Datatypes
- Oprators
- Comments

## Keywords

Keywords or Reserved words are the words in a language that are used for some internal process or represent some predefined actions. These words are therefore not allowed to use as variable names or objects. If we do we will get a compile-time error.

__Ex:__
    abstract, assert, boolean, break, byte, case, catch, char, class continue, default, do, double, else, enum, extends, final, float, for, if, implements import, instanceof, int interface, long, native, new null, package, private, protected, public, return, short, static strictfp, super, switch, this, synchronized, this, throw, throws, transient, try, void, volatile, while

Note: The keywords const and goto are reserved, even they are not currently in use. true, false and null look like keywords, but in actual they are literals. However they still can’t be used as identifiers in a program.

## Identifiers

In programming languages, identifiers are used for identification purposes. In Java, an identifier can be a class name, method name, variable name, or label.

- The only allowed characters for identifiers are all alphanumeric characters([A-Z],[a-z],[0-9]), ‘$‘(dollar sign) and ‘_‘ (underscore).For example “geek@” is not a valid java identifier as it contain ‘@’ special character.

- Identifiers should not start with digits([0-9]). For example “123geeks” is a not a valid java identifier.

- Java identifiers are case-sensitive.

- There is no limit on the length of the identifier but it is advisable to use an optimum length of 4 – 15 letters only.

- Reserved Words can’t be used as an identifier. For example “int while = 20;” is an invalid statement as while is a reserved word. There are 53 reserved words in Java.

        // Valid itentifier 
        MyVariable
        MYVARIABLE
        myvariable
        x
        i
        x1
        i1
        _myvariable
        $myvariable
        sum_of_array
        geeks123
    
        // Invalid identifier
        My Variable
        123geeks
        a+c
        variable-2
        sum_&_difference

## Variables

Variables are just like a container, allocate by the JVM in the memory. In which we can store our data. 

    // here 'value' is a variable
    int value = 10;


## DataTypes

Datatypes refers the type and size of data. Data types are different sizes and values that can be stored in the variable that is made as per convenience and circumstances to cover up all test cases. Also, let us cover up other important ailments that there are majorly two types of languages that are as follows:

- First, one is a Statically typed language where each variable and expression type is already known at compile time. Once a variable is declared to be of a certain data type, it cannot hold values of other data types. For example C, C++, Java.

- The other is Dynamically typed languages. These languages can receive different data types over time. For example Ruby, Python

        // 'int' is a type of Data
        int value = 10;


### Types of Datatypes

There are two types of datatypes. One is primitive and second is non-primitive datatypes.

#### Primitive DataTypes

| Type      | Size      |
------------|-----------|
| boolean   |   1 bit   |
| byte      |   4 bit   |
| short     |   8 bit   |
| char      |   16 bit  |
| int       |   32 bit  |
| long      |   64 bit  |
| float     |   32 bit  |
| double    |   64 bit  |


#### Non Primitive Datatype

Such as Array, String, Other Object etc.

## Oprators

Java provides many types of operators which can be used according to the need. They are classified based on the functionality they provide. Some of the types are:

| Type                  | Sign                  |
|-----------------------|-----------------------|
| Arithmetic Operators  | +, -, /, *            |
| Unary Operators       | -, +, --, ++          |
| Assignment Operator   | =, /= *=, +=, -=, %=  |
| Relational Operators  | ==, !=, <, >, <=, >=  |
| Logical Operators     | &&, ||, !             |
| Ternary Operator      | ? :                   |
| Bitwise Operators     | &, |, ^, ~            |
| Shift Operators       |  >>, <<, >>>          |
| instance of operator  | instanceof            |
-------------------------------------------------

## Comments

Comments are usefull for documantation perpose. Commented line in code ignored by the complier. 

    -> Single Line comment
    // This is a comment

    -> Multiline comment
    /* 
        This 
        is 
        multiline
        comment
    */    