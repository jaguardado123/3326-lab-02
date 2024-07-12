# Lab Assignment 02

In this lab you will practice writing Java code to input user data, declare variables, use simple arithmetic, and output different data types.

Same as Lab Assignment 01, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the src/ directory and name our class accordingly and remember to make it **public**.

```java
public class MagicNumber {

	// Your main() method goes here.
}
```

Next, **create your main() method inside the MagicNubmer class**. It should be the same as in Lab Assignment 01. Try writing the main() method without looking at your notes. Writing your main class and method should come to you as natural as in C++.

Now let the fun begin!

## Getting user input

To get user input in Java you must first import the **Scanner** class from the `java.util` package. Importing packages in Java must be done at the start of your code.

```java
import java.util.Scanner;

// Your code should start here.
```

Next, you must create a Scanner object inside of your main() method. This object will be used to get all of your user input regardless of their data type.

Creating an object in Java is done the same as in C++.

```java
// Inside main() method.
Scanner scanner = new Scanner(System.in);
```

But how do we user the scanner object to get user input?

Scanner has many built-in methods read user input depending on the type of data we're expecting (ex: String, int, double, etc.).

| **Method** | **Description** |
| ---- | ---- |
| nextBoolean() | Reads a <code style="color : darkorange">boolean</code> value from the user |
| nextByte() | Reads a <code style="color : darkorange">byte</code> value from the user |
| nextDouble() | Reads a <code style="color : darkorange">double</code> value from the user |
| nextFloat() | Reads a <code style="color : darkorange">float</code> value from the user |
| nextInt() | Reads an <code style="color : darkorange">int</code> value from the user |
| nextLine() | Reads a <code style="color : darkorange">String</code> value from the user |
| nextShort() | Reads a <code style="color : darkorange">short</code> value from the user |

The code snippet below shows how to input a float from the user.

```java
// Inside main() method.
float num;
num = scanner.nextFloat();
```

For more information on the Scanner class and how it's used visit: https://www.w3schools.com/java/java_user_input.asp

## Declaring variables & arithmetic operations

Exactly the same as C++. Only strings start with a capital 'S'.

## Outputting different data types

Java's print()/println() method is caple of outputting all data types: String, short, int, float, double, boolean, etc.

But, what if you want to output multiple data types in the same print()/println() method?

Simply seperate them with the summation operator '+'.

```java
System.out.print("hello" + 5 + true + 7.2);
// or
System.out.println("hello" + 5 + true + 7.2);
```

Easy peasy!

## Your program

Calculate a person's magic number using simple arithmetic operators in Java. A person's magic number is calculated by multiplying the month of their birth by the year of their birth, and taking the modulus of that result and the day of their birth. The equation is:

**magicNumber = (month * year) % day**

Write a program that will ask the user for their month of birth, day of birth, and year of birth and then output their magic number.

```
Welcome to Magic Number Calculator!
Your month of birth: 7
Your day of birth: 4
Your year of birth: 1776

Your magic number is 0.
```

## Submit your assignment

To submit your lab assignment click on the source control icon (3 circles with 2 lines) on your leftside navbar. Next, click on the '+' symbol next to "Changes" to stage your changes. Lastly, add a commit message (ex: "First commit") and click "Commit" then "Push" or "Sync Changes". And you're done!
