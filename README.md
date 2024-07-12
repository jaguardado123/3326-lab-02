# Lab Assignment 02

In this lab you will practice writing Java code to declare variables and output different data types.

Same as Lab Assignment 01, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the src/ directory and name our class accordingly and remember to make it **public**.

```java
public class MixMatch {

	// Your main() method goes here.
}
```

Next, **create your main() method inside the MixMatch class**. It should be the same as in Lab Assignment 01. Try writing the main() method without looking at your notes. Writing your main class and method should come to you as natural as in C++.

Now let the fun begin!

## Declaring variables & arithmetic operations

Exactly the same as C++. Only strings start with a capital 'S'.

**dataType** **identifier** = **literalValue**;

or

**dataType** **identifier**;

Remember the rules: 
* Don't start with numbers.
* Don't include spaces.
* Don't include special characters, except '_'.
* Don't start with a capital letter, those are reserved for classes.

For more information about variables in Java visit: https://www.w3schools.com/java/java_variables.asp and https://www.w3schools.com/java/java_data_types.asp 

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

**Mix & Match Data Types**

Declare 8 variables of type String, char, short, int, long, float, double, and boolean and initialize them with a literal value. Next, output the stored value next to its type description using the same print()/println() method.

**Example:**
```java
short num = 7;
System.out.println(num + " <- Int: Stores whole numbers from -2,147,483,648 to 2,147,483,647");
```
Finally, output all of the variables of similar type using the same print()/println() method.

**Example:**
```
All text data types: Hello, A.
```

## Submit your assignment

To submit your lab assignment click on the source control icon (3 circles with 2 lines) on your leftside navbar. Next, click on the '+' symbol next to "Changes" to stage your changes. Lastly, add a commit message (ex: "First commit") and click "Commit" then "Push" or "Sync Changes". And you're done!
