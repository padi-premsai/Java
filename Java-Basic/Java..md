# What is Java ?
Java is a popular programming language that was developed by Sun Microsystems (now owned by Oracle Corporation) in the mid-1990s. It is known for its simplicity, portability, and versatility, and is widely used for developing a variety of applications, including desktop software, mobile apps, web applications, and enterprise systems.
- Java is an object-oriented programming language, which means it focuses on creating and manipulating objects to perform tasks.
- It follows the "**write once, run anywhere**" principle, which means that Java programs can run on any device or platform that has a Java Virtual Machine (JVM) installed. This makes Java highly portable.
- Java programs are compiled into bytecode, which is a platform-independent representation of the code. This bytecode is then executed by the JVM.
- Java provides a rich set of libraries and frameworks that simplify common programming tasks, such as input/output operations, networking, database connectivity, and user interface development.
- Java programs are organized into classes, which are the building blocks of Java applications. Each class contains data (variables) and methods (functions) that define its behavior.
- Java supports multithreading, allowing programs to execute multiple tasks concurrently, which is particularly useful for handling tasks that require parallel processing or responsiveness.
- Java has a strong emphasis on security, with features like automatic memory management (garbage collection) and built-in mechanisms for handling exceptions, which help prevent common programming errors and enhance application robustness.

Overall, Java is widely used in the software industry due to its platform independence, extensive library support, and robustness. It is a great choice for developing a wide range of applications, from small utility programs to large-scale enterprise systems.

==Java was originally developed by James Gosling, Patrick Naughton, Chris Warth, Ed Frank, and Mike Sheridan at Sun Microsystems in the mid-1990s. The project was led by **James Gosling**, who is often referred to as the "**father of Java**". Since then, Java has been further developed and maintained by Oracle Corporation, which acquired Sun Microsystems in 2010.==

### Here are some basic rules and syntax in Java:
- **Java is case-sensitive:** This means that uppercase and lowercase letters are considered distinct. For example, "`myName`" and "`myname`" are treated as different variables.
- **Class names:** In Java, class names should start with an uppercase letter and follow the camel case convention. For example, "`MyClass`" or "`StudentRecord`".
- **Main method:** Every Java program must have a main method, which serves as the entry point for the program. 
The syntax for the main method is as follows:
    ```
    public static void main(String[] args) {
        // Program statements go here
    }
    ```
- **Statements and Blocks:** Java code is written in statements, which end with a semicolon `(;)`. Multiple statements can be grouped together in a block using curly braces (`{ }`). 
For example:
    ```
    int x = 1; // single statement
    
    if (x > 0) { // block
        System.out.println(x + " is positive");
        System.out.println("x = " +  x);
    }
    ```
- In Java, file extensions are used to identify the type of files and their associated content. The most common file extension used for Java source code files is `.java`.
### Data Types

In Java, there are several built-in data types that determine the kind of values that can be stored in variables. Here are the commonly used data types:

1. **Primitive Data Types:**

   - `byte`: Represents a 1-byte integer value. Range: -128 to 127.
   - `short`: Represents a 2-byte integer value. Range: -32,768 to 32,767.
   - `int`: Represents a 4-byte integer value. Range: -2,147,483,648 to 2,147,483,647.
   - `long`: Represents an 8-byte integer value. Range: -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807.
   - `float`: Represents a 4-byte floating-point value. Range: approximately ±1.4e-45 to ±3.4e+38. Should be suffixed with 'f'.
   - `double`: Represents an 8-byte floating-point value. Range: approximately ±4.9e-324 to ±1.8e+308.
   - `boolean`: Represents a boolean value (`true` or `false`).
   - `char`: Represents a single character value. Range: 0 to 65,535 or '\u0000' to '\uffff'.

2. **Reference Data Types:**

   - `String`: Represents a sequence of characters.
   - `Arrays`: Represents a collection of elements of the same type.

It's important to note that the size and range of the primitive data types may vary depending on the underlying system architecture. Additionally, Java also supports the concept of "`Wrapper Classes`" that allow you to use primitive types as objects.

Here's an example of variable declarations using different data types:

```java
int age = 25;
double pi = 3.14;
boolean isStudent = true;
char grade = 'A';
String name = "John";```

---

**Conclusion**
In this document, we explored basic info about `JAVA`.

---

Thank you for reading!