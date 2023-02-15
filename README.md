# Master Java - Basic to Advanced

Hi, This is [Anuj Kumar](https://github.com/wtricks). In this course, I'll teach you [Java](https://www.java.com) from very `basic to Advanced` level. I'm assuming that either you're `begineer` or don't have knowledge of codings.

If you have no knowledge of codings, don't worry. I will start from very basic like `Intro to coding`.

## Intro to coding

`Codings` means "We writes some instructions for the computer so that computer can generate desired output according to our instructions".

But computer is just a machine, so it can not understand our language, we need to give instructions in machine langauge (Binary language). It is called low level language. Machine language are called Binarylanguage that is in the form of 0's and 1's.

👉 __Why a computer understand only Binary langauge (0's and 1's) ?__

Actually computer also does not understand 0's and 1's. It is just a machine, In a machine everything works beacuse of electric current. If a circuit has flow of current, it is called 'ON' (or true), then it is denoting from `1` and when the circuit has no flow of current, it is called 'OFF' (or false) and it is denoting with `0`. A computer CPU can have billions of circuits inside it and flow of current can be changed (processing) according to the instructions is given.

    # Some numbers reperenting in Binary language.

    0   -> 0
    1   -> 1
    2   -> 11
    6   -> 110
    10  -> 1010
    100 -> 1100100
    ...
    ...

    # Like numbers letters (a-z, A-Z) and other special symbols ( [(*&^%$#@!></\{}>)] ) has also a defined meanings in Binary language.

    Hi -> 01001000 01101001
    ...
    ... 

In the above example, I have used [Text to Binary comverter](https://rapidtables.com/ascii-to-binary.html). You can try it to know more about binary language.

But remembering all the binary codes is very dificult of us. We can not give every instruction in binary language. In abive example we have seen that just writing two letters 'Hi', we need to write '01001000 01101001'. 

That is why, we need something that could translate our instructions into binary language (so computer could understand it). These translators are called compilers. Now if we have these compilers, we can write our instructions in english like language then compiler will compile it into computer unserstandable language.

Actually Using compilers too, We can not write our instructions directly into english like language, beacuase if you do this then the compiler will not understand, whatever you are writing. Now if the compiler does not understand, then how will it convert our instructions into binary language. You have to follow compilers `predfined syntax`, so it can unserstand and then it can compiles our instructions.

    # If you directly using enlish langauge.
    # Will not work beacuse right now compiler also doesn't know about it.
    
    print 10 
    add 10 and 20

    # Use with compilers predefined syntax.
    # Here we are using its predefined syntax 'System.out.print'.
    # Will print ' HELLO WORLD '.

    System.out.print(" HELLO WORLD ");

Like our own languages ex. Hindi, English, we follow its predefined syntax. Same works in compilers. 

In this course, We are learning Java that's why we will use Java Compiler. Every compliler has its own syntax, pros and cons. Whatever the complier you are going to use, you have to follow its predefined syntaxs.

## Intro to Java
Java is one of most popular and widly used programming language. It is a object oriented. Java syntax are similar to C/C++. But is does not not support low level funtionallity like `pointer`. Java is used in all kinds of applications (Android is Java based), desktop applications, web applications, client-server applications, and many more.

## Short histroy of Java.
Java was developed by `James Gosling` at `Sun Microsystems_inc` in the year `1995`, later acquired by `Oracle Corporation`. Initialy it is release as `JDK 1.0` in `1996`, after it many version comes and now the latest version of Java is `JAVA 19` in `September 2022`.

## Installation
Installation of Java is very easy. Just go its official site and download latest version of it.

## First Program of Java

Create a file named `Main.java`. Here `.java` is a extension of Java. You are writing a program in Java. Your file name must be match with your class name.

    public class Main {
        public static void main(String[] args) {
            System.out.print("Hello World");
        }
    }

To run this program run `javac Main.java`, this will compile your code into Java Byte code. If there no error ocuured, then run `java Main` command to run your program. here `Main` is your file name.