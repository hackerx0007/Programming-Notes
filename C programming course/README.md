<p align="center">
    <img align="center" src="https://github.com/hackerx0007/Programming-Notes/blob/main/C%20programming%20course/c_programming-removebg-preview.png" width="200" />
</p>
<div align="center"><img src="https://github.com/hackerx0007/Programming-Notes/blob/main/C%20programming%20course/c_programming-removebg-preview.png"  width="50" height="50"/>&nbsp; Welcome to C Programming Notes &nbsp; <img src="https://github.com/hackerx0007/Programming-Notes/blob/main/C%20programming%20course/c_programming-removebg-preview.png" alt="Technologist" width="50" height="50"/> </div>


### What is a Program?

A **program** is a set of instructions written in a specific programming language that tells a computer how to perform a task or solve a problem. These instructions are executed step by step by the computer's processor. In simple terms, a program is like a recipe that guides the computer to do something useful, such as displaying information, solving mathematical problems, or managing files.

Key points:
- A program is made up of code.
- It follows a specific sequence of instructions.
- It can be written in various programming languages like C, Python, Java, etc.
- A computer executes the program to perform tasks. 

### What is a Programming Language?

A **programming language** is a formal language used to write code that provides instructions for a computer to follow. It enables developers to communicate with machines and control their behavior to perform specific tasks. Programming languages have syntax and rules, and examples include C, Python, Java, and JavaScript.

Key points:
- It allows humans to write code for computers.
- Each language has its own syntax and structure.
- Used to create software, websites, and other applications.
### Types of Programming Languages (With Detailed Explanation and Examples)

#### 1. **Procedural Programming**
   - **What it is:** Procedural programming is a programming paradigm that uses a step-by-step approach to break down tasks into functions or procedures. Each function performs a specific task and can be reused throughout the program.
   - **Example:** C, Pascal, Fortran.

   ```c
   // Example in C
   #include <stdio.h>

   void greet() {
       printf("Hello, World!\n");
   }

   int main() {
       greet();  // calling the greet function
       return 0;
   }
   ```

   - **Key Features:** 
     - Focuses on functions and procedures.
     - Step-by-step execution.

---

#### 2. **Object-Oriented Programming (OOP)**
   - **What it is:** OOP organizes code into objects and classes. Objects are instances of classes, which can contain both data (attributes) and functions (methods) that operate on the data.
   - **Example:** C++, Java, Python.

   ```cpp
   // Example in C++
   #include <iostream>
   using namespace std;

   class Car {
   public:
       string brand;
       void showBrand() {
           cout << "Car Brand: " << brand << endl;
       }
   };

   int main() {
       Car myCar;
       myCar.brand = "Toyota";
       myCar.showBrand();  // calling method on object
       return 0;
   }
   ```

   - **Key Features:**
     - Focuses on objects and classes.
     - Concepts like inheritance, encapsulation, and polymorphism.

---

#### 3. **Functional Programming**
   - **What it is:** Functional programming treats computation as the evaluation of mathematical functions. It avoids changing state and mutable data.
   - **Example:** Haskell, Lisp, Scala.

   ```haskell
   -- Example in Haskell
   square x = x * x

   main = print (square 5)  -- Output: 25
   ```

   - **Key Features:**
     - Emphasizes immutability.
     - Functions are first-class citizens.

---

#### 4. **Logic Programming**
   - **What it is:** Logic programming is based on formal logic. Programs consist of facts and rules, and the system tries to infer conclusions based on them.
   - **Example:** Prolog.

   ```prolog
   % Example in Prolog
   parent(tom, jerry).
   parent(jerry, spike).

   grandparent(X, Y) :- parent(X, Z), parent(Z, Y).

   % Query: grandparent(tom, spike). -> true
   ```

   - **Key Features:**
     - Focuses on what should be achieved, rather than how.
     - Based on facts and rules.

---

#### 5. **Scripting Languages**
   - **What it is:** Scripting languages are used for automating tasks. These languages are often interpreted, meaning the code is executed line by line rather than being compiled.
   - **Example:** JavaScript, Python, PHP.

   ```javascript
   // Example in JavaScript
   function greet() {
       console.log("Hello, World!");
   }

   greet();  // calling the function
   ```

   - **Key Features:**
     - Easy to write and execute.
     - Often used for web development and automation.

---

#### 6. **Markup Languages**
   - **What it is:** While not strictly programming languages, markup languages are used to define the structure and presentation of data.
   - **Example:** HTML, XML.

   ```html
   <!-- Example in HTML -->
   <html>
     <head>
       <title>My Web Page</title>
     </head>
     <body>
       <h1>Hello, World!</h1>
     </body>
   </html>
   ```

   - **Key Features:**
     - Defines structure rather than logic.
     - Used in web design and data representation.

---


### Why Learn C Programming?

1. **Foundation for Other Languages**
   - **Explanation:** C is the basis for many modern languages like C++, Java, and Python.
   - **Benefit:** It provides a strong foundation that makes learning other languages easier.

2. **Understanding Computer Basics**
   - **Explanation:** C helps you understand low-level operations like memory management and pointers.
   - **Benefit:** Gives insight into how computers work internally.

3. **Performance and Efficiency**
   - **Explanation:** C is known for its speed and efficient use of resources.
   - **Benefit:** Ideal for high-performance applications and system-level programming.

4. **System Programming**
   - **Explanation:** C is widely used for developing operating systems and embedded systems.
   - **Benefit:** Opens opportunities in system programming and hardware-related projects.

5. **Large Ecosystem**
   - **Explanation:** C has a vast number of libraries and tools.
   - **Benefit:** Offers extensive resources for various types of development.

6. **Career Opportunities**
   - **Explanation:** Many industries and companies use C for critical software and systems.
   - **Benefit:** Enhances job prospects in various tech fields.

Learning C programming provides a strong foundation, enhances understanding of computer systems, and opens doors to many career opportunities.

### It can be compiled various computer platforms like : windows , linux , Mac

### Facts About C Programming

1. **Developed by Dennis Ritchie**
   - **Fact:** C was developed in the early 1970s by Dennis Ritchie at Bell Labs.
   - **Significance:** It was designed as an evolution of the B programming language.

2. **Foundational Language**
   - **Fact:** C serves as the foundation for many programming languages, including C++, C#, and Objective-C.
   - **Significance:** It has influenced the syntax and structure of many modern languages.

3. **Standardized Language**
   - **Fact:** C was standardized by the American National Standards Institute (ANSI) in 1989, resulting in ANSI C.
   - **Significance:** This standardization ensured consistent implementation across different platforms.

4. **Low-Level Operations**
   - **Fact:** C provides low-level access to memory through pointers and direct memory manipulation.
   - **Significance:** Allows programmers to interact closely with hardware and system resources.

5. **Wide Usage**
   - **Fact:** C is widely used in system programming, embedded systems, operating systems (like Unix), and application development.
   - **Significance:** Its versatility and performance make it a popular choice for critical software.

6. **Portable and Efficient**
   - **Fact:** Programs written in C can be compiled and run on various hardware and operating systems with minimal modifications.
   - **Significance:** Ensures portability and efficiency in diverse computing environments.

7. **Rich Library Support**
   - **Fact:** C has a rich set of standard libraries that provide a wide range of functions for input/output, string manipulation, and mathematical operations.
   - **Significance:** Enhances programming productivity by providing ready-to-use functions.

8. **Procedural Paradigm**
   - **Fact:** C follows the procedural programming paradigm, focusing on functions and structured programming.
   - **Significance:** Encourages organized and modular code.

9. **Legacy and Influence**
   - **Fact:** C has significantly influenced the development of other programming languages and remains relevant in modern programming.
   - **Significance:** Its principles and practices are foundational to many current technologies.

These facts highlight the importance, history, and characteristics of C programming, showcasing its impact and relevance in the programming world.

### Setting Up a C Programming Environment

#### 1. **Install a Compiler**

   - **Windows:**
     - **Option 1:** Install [MinGW](http://www.mingw.org/), which provides the GCC compiler for Windows.
       - Download the installer from the MinGW website.
       - During installation, select the `gcc-g++` and `gcc-` packages.
       - Add the MinGW `bin` directory to your system's PATH environment variable.
     - **Option 2:** Install [Microsoft Visual Studio](https://visualstudio.microsoft.com/) and use its built-in compiler.

   - **macOS:**
     - **Option 1:** Install [Xcode](https://developer.apple.com/xcode/) from the Mac App Store.
       - After installation, open Terminal and run `xcode-select --install` to install the command-line tools.
     - **Option 2:** Install [Homebrew](https://brew.sh/) and use it to install GCC with `brew install gcc`.

   - **Linux:**
     - Open Terminal and install GCC using your package manager.
       - For Debian-based systems (e.g., Ubuntu): `sudo apt-get install build-essential`
       - For Red Hat-based systems (e.g., Fedora): `sudo dnf install gcc`

#### 2. **Install an Integrated Development Environment (IDE)**

   - **Windows:**
     - **Option 1:** Use [Code::Blocks](http://www.codeblocks.org/) for a free and open-source IDE.
     - **Option 2:** Use [Dev-C++](https://sourceforge.net/projects/orwelldevcpp/) for another free option.

   - **macOS:**
     - **Option 1:** Use [Xcode](https://developer.apple.com/xcode/) for a full-featured IDE.
     - **Option 2:** Use [Visual Studio Code](https://code.visualstudio.com/) with C/C++ extensions for a lightweight option.

   - **Linux:**
     - **Option 1:** Use [Geany](https://www.geany.org/) or [KDevelop](https://www.kdevelop.org/) for a lightweight IDE.
     - **Option 2:** Use [Visual Studio Code](https://code.visualstudio.com/) with C/C++ extensions.

#### 3. **Set Up a Text Editor (Optional)**

   - **Text Editors:**
     - **Visual Studio Code** with C/C++ extensions.
     - **Sublime Text** with C/C++ plugins.
     - **Notepad++** on Windows.



This setup will get you ready to start programming in C by providing you with the necessary tools and environment.


### First C Program: "Hello, World!"

Here's a simple C program that prints "Hello, World!" to the console. This program demonstrates the basic structure of a C program.

```c
#include <stdio.h>  // Preprocessor directive to include the standard input/output library

int main() {  // Main function - execution starts here
    printf("Hello, World!\n");  // Print "Hello, World!" to the console
    return 0;  // Return 0 to indicate successful execution
}
```

### Explanation

- **`#include <stdio.h>`**: This line includes the standard input/output library, which is necessary for using the `printf` function.
- **`int main()`**: The `main` function is the entry point of the program. The execution of the program starts from here.
- **`printf("Hello, World!\n");`**: This line prints the string "Hello, World!" to the console. The `\n` adds a newline at the end.
- **`return 0;`**: This statement ends the `main` function and returns 0 to indicate that the program executed successfully.

### Running the Program

1. **Save the Code**: Save the code in a file named `hello.c`.
2. **Compile the Code**:
   - Open a terminal or command prompt.
   - Navigate to the directory where `hello.c` is saved.
   - Compile the program using:
     - `gcc hello.c -o hello` (for GCC)
     - `clang hello.c -o hello` (for Clang)
3. **Run the Executable**:
   - On Unix-like systems: `./hello`
   - On Windows: `hello.exe`

This will display "Hello, World!" on the console.   ```

### Components of a C Program

A C program typically consists of several key components:

1. **Preprocessor Directives**
   - **Description:** Lines that begin with `#` and are processed by the preprocessor before compilation.
   - **Example:** `#include <stdio.h>` (includes the standard input/output library).

2. **Main Function**
   - **Description:** The entry point of a C program. Execution starts here.
   - **Syntax:** `int main() { /* code */ return 0; }`
   - **Example:** 
     ```c
     int main() {
         // code here
         return 0;
     }
     ```

3. **Function Definitions**
   - **Description:** Blocks of code that perform specific tasks. Functions can be called from the main function or other functions.
   - **Syntax:** `return_type function_name(parameters) { /* code */ }`
   - **Example:**
     ```c
     void greet() {
         printf("Hello, World!\n");
     }
     ```

4. **Variable Declarations**
   - **Description:** Statements that define variables and their types. They must be declared before use.
   - **Syntax:** `type variable_name;`
   - **Example:** `int age;`

5. **Statements and Expressions**
   - **Description:** Instructions that perform operations or control the flow of execution.
   - **Syntax:** `statement;`
   - **Example:** `printf("Hello, World!\n");`

6. **Comments**
   - **Description:** Non-executable text used to explain code. Comments are ignored by the compiler.
   - **Syntax:** Single-line (`// comment`) or multi-line (`/* comment */`)
   - **Example:**
     ```c
     // This is a single-line comment
     /*
       This is a multi-line comment
     */
     ```

7. **Header Files**
   - **Description:** Files that contain declarations for functions and macros used in the program.
   - **Example:** `<stdio.h>` for input/output functions.

8. **Libraries**
   - **Description:** Collections of pre-written code that provide functionalities like mathematical operations, file handling, etc.
   - **Example:** The Standard Library (`stdlib.h`, `math.h`).

### Example C Program with Components

```c
#include <stdio.h>  // Preprocessor Directive

// Function Definition
void greet() {
    printf("Hello, World!\n");
}

int main() {  // Main Function
    int number = 5;  // Variable Declaration and Initialization
    greet();  // Function Call
    printf("Number: %d\n", number);  // Statement
    return 0;  // Return Statement
}
```

- **Preprocessor Directive:** `#include <stdio.h>`
- **Function Definition:** `void greet()`
- **Main Function:** `int main()`
- **Variable Declaration:** `int number = 5;`
- **Statements:** `greet();` and `printf("Number: %d\n", number);`
- **Comments:** (none in the example, but you can add them to explain code)

### Explanation of the Code

```c
#include <stdio.h>
int main() {
    /* MY first program */
    printf("Hallo world ");
    return 0;
}
```

#### 1. **Preprocessor Directive**
   ```c
   #include <stdio.h>
   ```
   - **Purpose:** This line tells the compiler to include the standard input/output library before compiling the program. The `stdio.h` header file contains declarations for input and output functions, such as `printf`.

#### 2. **Main Function**
   ```c
   int main() {
   ```
   - **Purpose:** This is the entry point of the program. The execution of the program starts from this function. `int` indicates that the function returns an integer value.

#### 3. **Comment**
   ```c
   /* MY first program */
   ```
   - **Purpose:** This is a multi-line comment. It is ignored by the compiler and is used to provide information or notes within the code. In this case, it notes that this is the programmer's first program.

#### 4. **Function Call**
   ```c
   printf("Hallo world ");
   ```
   - **Purpose:** This line uses the `printf` function from the `stdio.h` library to print the text "Hallo world " to the console. The `printf` function is used for outputting data to the standard output (usually the terminal or console).

#### 5. **Return Statement**
   ```c
   return 0;
   ```
   - **Purpose:** This statement ends the `main` function and returns 0 to the operating system. Returning 0 typically indicates that the program executed successfully.

### Summary

- **`#include <stdio.h>`**: Includes the standard I/O library for input and output functions.
- **`int main()`**: Defines the main function where program execution starts.
- **`/* MY first program */`**: A comment explaining that this is the first program.
- **`printf("Hallo world ");`**: Prints "Hallo world " to the console.
- **`return 0;`**: Ends the program and returns 0, indicating success.

This code demonstrates the basic structure of a C program, including how to include libraries, define a main function, use comments, print output, and return a value.

### What is Syntax?

**Syntax** refers to the set of rules and structure that govern the formation of statements and expressions in a programming language. It defines how symbols, keywords, and operators should be arranged to create valid code.

#### Key Points About Syntax

1. **Rules for Writing Code**
   - **Description:** Syntax dictates how code must be written to be understood by the compiler or interpreter.
   - **Example:** In C, every statement must end with a semicolon (`;`).

2. **Structure and Format**
   - **Description:** Syntax includes the correct arrangement of elements like keywords, operators, and punctuation.
   - **Example:** The `if` statement in C requires parentheses around the condition and curly braces around the block of code.
     ```c
     if (condition) {
         // code to execute
     }
     ```

3. **Error Detection**
   - **Description:** Syntax errors occur when code does not follow the rules of the language, leading to compilation or runtime errors.
   - **Example:** Forgetting a semicolon at the end of a statement in C will result in a syntax error.

4. **Language-Specific**
   - **Description:** Each programming language has its own syntax rules.
   - **Example:** The syntax for declaring a variable in C is `type variable_name;`, whereas in Python, it is simply `variable_name = value`.

#### Examples of Syntax in C

1. **Variable Declaration**
   ```c
   int age;  // Correct syntax for declaring an integer variable
   ```

2. **Function Definition**
   ```c
   void greet() {
       printf("Hello, World!\n");
   }
   ```

3. **Conditional Statement**
   ```c
   if (age > 18) {
       printf("Adult\n");
   } else {
       printf("Minor\n");
   }
   ```

4. **Loop Statement**
   ```c
   for (int i = 0; i < 5; i++) {
       printf("%d\n", i);
   }
   ```

In summary, syntax defines how code should be structured and written in a programming language to ensure it is correctly interpreted and executed by the compiler or interpreter.

### What is a Token in Programming?

A **token** in programming is a basic, individual unit of syntax that the compiler or interpreter uses to understand and process the code. Tokens are the building blocks of programming languages and are typically classified into several categories.

#### Types of Tokens

1. **Keywords**
   - **Description:** Reserved words in a programming language that have special meaning and cannot be used as identifiers (e.g., variable names).
   - **Examples:** `int`, `return`, `if`, `else`, `while` in C.

   ```c
   int main() {  // 'int' and 'main' are keywords
       return 0;
   }
   ```

2. **Identifiers**
   - **Description:** Names given to variables, functions, arrays, etc., that are defined by the programmer.
   - **Examples:** `age`, `sum`, `calculateTotal`.

   ```c
   int age = 25;  // 'age' is an identifier
   ```

3. **Constants**
   - **Description:** Literal values that are used directly in the code.
   - **Examples:** Numeric constants (e.g., `100`, `3.14`), string constants (e.g., `"Hello, World!"`).

   ```c
   int x = 100;  // '100' is a numeric constant
   ```

4. **Operators**
   - **Description:** Symbols that represent operations to be performed on operands.
   - **Examples:** `+`, `-`, `*`, `/`, `==`, `!=`.

   ```c
   int sum = a + b;  // '+' is an operator
   ```

5. **Punctuation (Separators)**
   - **Description:** Symbols used to separate or terminate statements and expressions.
   - **Examples:** `;` (semicolon), `{}`, `()`, `,` (comma).

   ```c
   printf("Hello, World!\n");  // ';' is a punctuation mark
   ```

6. **Comments**
   - **Description:** Text in the code that is ignored by the compiler but is useful for documentation and explanation.
   - **Examples:** `//` (single-line comment), `/* */` (multi-line comment).

   ```c
   // This is a single-line comment
   /* This is a 
      multi-line comment */
   ```

#### Example in C

Here's a simple C program with tokens highlighted:

```c
#include <stdio.h>  // #include, <stdio.h>, and // are tokens

int main() {  // int, main, (), {}, and ; are tokens
    int age = 25;  // int, age, =, 25, and ; are tokens
    printf("Age: %d\n", age);  // printf, "Age: %d\n", age, and ; are tokens
    return 0;  // return, 0, and ; are tokens
}
```

In this example:
- **Keywords:** `int`, `return`
- **Identifiers:** `main`, `age`
- **Constants:** `25`, `"Age: %d\n"`
- **Operators:** `=`, `,`
- **Punctuation:** `;`, `{}`, `()`

Tokens are essential for the syntax analysis phase of compilation, where the compiler breaks down code into meaningful components to generate executable instructions.

### Rules of Tokens in Programming

Tokens are fundamental components of programming languages and must adhere to specific rules to be correctly recognized and processed by the compiler or interpreter. Here are some general rules for tokens:

#### 1. **Keywords**
   - **Rule:** Keywords are reserved words that have predefined meanings in the language and cannot be used as identifiers (e.g., variable names).
   - **Example:** In C, `int`, `return`, `if`, and `while` are keywords.
   - **Rule:** Keywords must be spelled exactly as defined in the language specification.

#### 2. **Identifiers**
   - **Rule:** Identifiers are names used to identify variables, functions, arrays, etc.
   - **Rules:**
     - Must start with a letter (A-Z or a-z) or an underscore (_).
     - Can be followed by letters, digits (0-9), or underscores.
     - Must not be a keyword.
   - **Example:** `variable1`, `sum_total`, `_counter`.

#### 3. **Constants**
   - **Rule:** Constants represent fixed values used directly in the code.
   - **Rules:**
     - **Integer Constants:** Must be a sequence of digits (e.g., `100`, `-45`).
     - **Floating-Point Constants:** Must include a decimal point (e.g., `3.14`, `-0.001`).
     - **String Constants:** Must be enclosed in double quotes (e.g., `"Hello, World!"`).
   - **Example:** `42`, `3.14`, `"example"`

#### 4. **Operators**
   - **Rule:** Operators perform operations on operands.
   - **Rules:**
     - **Arithmetic Operators:** `+`, `-`, `*`, `/`, `%`
     - **Relational Operators:** `==`, `!=`, `>`, `<`, `>=`, `<=`
     - **Logical Operators:** `&&`, `||`, `!`
     - **Assignment Operators:** `=`, `+=`, `-=`, `*=`, `/=`
   - **Example:** `a + b`, `x == y`

#### 5. **Punctuation (Separators)**
   - **Rule:** Punctuation marks separate or terminate statements and expressions.
   - **Rules:**
     - **Semicolon (`;`):** Used to terminate statements.
     - **Commas (`,`):** Used to separate items in a list.
     - **Braces (`{}`, `[]`):** Used to define blocks of code or arrays.
     - **Parentheses (`()`):** Used to group expressions or parameters.
   - **Example:** `int main() { return 0; }`

#### 6. **Comments**
   - **Rule:** Comments are used for documentation and are ignored by the compiler.
   - **Rules:**
     - **Single-Line Comments:** Begin with `//` and continue to the end of the line.
     - **Multi-Line Comments:** Enclosed between `/*` and `*/`.
   - **Example:**
     ```c
     // This is a single-line comment
     /* This is a
        multi-line comment */
     ```

#### General Syntax Rules

- **Case Sensitivity:** Most programming languages, including C, are case-sensitive. `Variable`, `variable`, and `VARIABLE` are considered different identifiers.
- **No Spaces in Identifiers:** Identifiers cannot contain spaces. Use underscores (`_`) or camel case to separate words (e.g., `my_variable` or `myVariable`).
- **No Special Characters:** Identifiers typically cannot contain special characters other than underscores.

Understanding these rules ensures that your code is syntactically correct and can be successfully compiled or interpreted.

### What is a String in C?

In C programming, a **string** is a sequence of characters terminated by a null character (`'\0'`). Strings are used to represent text and are stored as arrays of characters.

#### Basic Concepts

1. **Declaration and Initialization**
   - Strings are declared as arrays of characters.
   - A string literal is automatically terminated by a null character.

   ```c
   char str1[] = "Hello, World!";  // String initialization with automatic null termination
   char str2[20] = "Hello";        // String initialization with space for up to 19 characters + null terminator
   ```

2. **Accessing Characters in a String**
   - Characters in a string can be accessed using array notation.

   ```c
   char str[] = "Hello";
   char firstChar = str[0];  // 'H'
   ```

3. **String Length**
   - The length of a string is the number of characters before the null terminator.

   ```c
   #include <stdio.h>
   #include <string.h>  // For strlen function

   int main() {
       char str[] = "Hello, World!";
       int length = strlen(str);  // strlen function returns the length of the string
       printf("Length of the string: %d\n", length);
       return 0;
   }
   ```

4. **String Operations**
   - Common string operations include copying, concatenation, and comparison. These are provided by standard library functions in `<string.h>`.

   ```c
   #include <stdio.h>
   #include <string.h>

   int main() {
       char str1[20] = "Hello";
       char str2[] = "World";

       // String concatenation
       strcat(str1, " ");
       strcat(str1, str2);  // str1 is now "Hello World"

       // String comparison
       int result = strcmp(str1, "Hello World");  // result is 0 if strings are equal

       printf("Concatenated string: %s\n", str1);
       printf("Comparison result: %d\n", result);
       return 0;
   }
   ```

#### Important Points

- **Null Terminator:** Every C string ends with a null terminator (`'\0'`). This terminator is essential for marking the end of the string and is automatically added when using string literals.
- **Array Size:** When declaring a string, ensure there is enough space for the null terminator.
- **String Functions:** Functions from `<string.h>` such as `strlen()`, `strcpy()`, `strcat()`, and `strcmp()` are used to perform various operations on strings.

Strings are fundamental in C for handling text and performing various text-based operations.

In C programming, a **data type** is a classification that specifies which type of data can be stored and manipulated within a program. Data types define the nature of the data and the operations that can be performed on it.

In C programming, data types can be broadly categorized into several types. Each type defines the kind of data it can hold and the operations that can be performed on it. Here’s a detailed overview:

### 1. **Basic Data Types**

#### **Integer Types**
   - **`int`**: Stores integer values (e.g., `-10`, `0`, `25`).
     - **Size:** Typically 4 bytes (32 bits).
     - **Range:** Depends on the system but usually `-2,147,483,648` to `2,147,483,647`.
   - **`short`**: Stores smaller integer values.
     - **Size:** Typically 2 bytes (16 bits).
     - **Range:** Usually `-32,768` to `32,767`.
   - **`long`**: Stores larger integer values.
     - **Size:** Typically 4 bytes (32 bits) or 8 bytes (64 bits) depending on the system.
     - **Range:** Depends on size (e.g., `-2,147,483,648` to `2,147,483,647` for 32-bit).
   - **`long long`**: Stores very large integer values.
     - **Size:** Typically 8 bytes (64 bits).
     - **Range:** Usually `-9,223,372,036,854,775,808` to `9,223,372,036,854,775,807`.

#### **Floating-Point Types**
   - **`float`**: Stores single-precision floating-point numbers.
     - **Size:** Typically 4 bytes (32 bits).
     - **Range:** Approximately `1.5 × 10^−45` to `3.4 × 10^38` with 6-9 decimal digits of precision.
   - **`double`**: Stores double-precision floating-point numbers.
     - **Size:** Typically 8 bytes (64 bits).
     - **Range:** Approximately `5.0 × 10^−324` to `1.7 × 10^308` with 15-17 decimal digits of precision.
   - **`long double`**: Stores extended-precision floating-point numbers.
     - **Size:** Typically 10 bytes (80 bits) or more.
     - **Range and Precision:** Greater than `double`, but varies by implementation.

#### **Character Type**
   - **`char`**: Stores a single character.
     - **Size:** Typically 1 byte (8 bits).
     - **Range:** `-128` to `127` for `signed char`, or `0` to `255` for `unsigned char`.

### 2. **Derived Data Types**

#### **Arrays**
   - **Description:** Collection of elements of the same type.
   - **Example:**
     ```c
     int numbers[5] = {1, 2, 3, 4, 5};
     ```

#### **Pointers**
   - **Description:** Variables that store memory addresses of other variables.
   - **Example:**
     ```c
     int *ptr;
     int value = 10;
     ptr = &value;  // ptr now holds the address of value
     ```

#### **Structures**
   - **Description:** User-defined data types that group different types of variables.
   - **Example:**
     ```c
     struct Person {
         char name[50];
         int age;
     };
     ```

#### **Unions**
   - **Description:** Similar to structures but only one member can hold a value at a time.
   - **Example:**
     ```c
     union Data {
         int i;
         float f;
         char str[20];
     };
     ```

#### **Enumer

#### **Enumerations (enum)**
   - **Description:** User-defined type that consists of a set of named integer constants.
   - **Example:**
     ```c
     enum Day { Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday };
     enum Day today = Wednesday;
     ```

### 3. **Void Type**

   - **Description:** Represents the absence of a type. Used for functions that do not return a value and for pointers to indicate that they can point to any data type.
   - **Example:**
     ```c
     void printMessage() {
         printf("Hello, World!\n");
     }
     ```

### Summary

1. **Basic Data Types:**
   - **Integer Types:** `int`, `short`, `long`, `long long`
   - **Floating-Point Types:** `float`, `double`, `long double`
   - **Character Type:** `char`

2. **Derived Data Types:**
   - **Arrays**
   - **Pointers**
   - **Structures (`struct`)**
   - **Unions (`union`)**
   - **Enumerations (`enum`)**

3. **Void Type:**
   - **`void`** – No specific type

Each data type serves a specific purpose and is chosen based on the needs of the program, such as the type of data being handled and the operations to be performed.

### Basic Data Types

1. **Integer Types**
   - **Description:** Used to store whole numbers.
   - **Examples:**
     - `int` – Stores integer values (e.g., `-10`, `0`, `25`).
     - `short` – Stores smaller integer values (typically 16 bits).
     - `long` – Stores larger integer values (typically 32 or 64 bits).
     - `long long` – Stores very large integer values (typically 64 bits).

   ```c
   int age = 30;
   short height = 160;
   long population = 7800000000L;
   long long distance = 123456789012345LL;
   ```

2. **Floating-Point Types**
   - **Description:** Used to store numbers with fractional parts.
   - **Examples:**
     - `float` – Stores single-precision floating-point numbers (typically 32 bits).
     - `double` – Stores double-precision floating-point numbers (typically 64 bits).
     - `long double` – Stores extended-precision floating-point numbers (typically 80 bits).

   ```c
   float pi = 3.14f;
   double e = 2.718281828459;
   long double largeNumber = 1.2345678901234567890L;
   ```

3. **Character Type**
   - **Description:** Used to store single characters.
   - **Example:**
     - `char` – Stores a single character (e.g., `'a'`, `'1'`, `'%'`).

   ```c
   char letter = 'A';
   ```

4. **Void Type**
   - **Description:** Represents the absence of data type. It is used for functions that do not return a value and for pointers to indicate that they can point to any data type.
   - **Examples:**
     - `void` – Used in functions that do not return a value.

   ```c
   void printMessage() {
       printf("Hello, World!\n");
   }
   ```

### Type Modifiers

Type modifiers are used to alter the properties of basic data types.

- **`signed`** – Indicates that the variable can hold both positive and negative values.
- **`unsigned`** – Indicates that the variable can only hold non-negative values.
- **`short`** – Indicates a smaller range of values.
- **`long`** – Indicates a larger range of values.

```c
unsigned int positiveNumber = 100;
signed int negativeNumber = -50;
long long veryLargeNumber = 9876543210LL;
```

### Example

Here is a C program that demonstrates different data types:

```c
#include <stdio.h>

int main() {
    int age = 25;
    float height = 5.9f;
    double weight = 70.55;
    char grade = 'A';

    printf("Age: %d\n", age);
    printf("Height: %.1f\n", height);
    printf("Weight: %.2f\n", weight);
    printf("Grade: %c\n", grade);

    return 0;
}
```

### Summary

- **Integer Types:** Used for whole numbers.
- **Floating-Point Types:** Used for numbers with fractions.
- **Character Type:** Used for single characters.
- **Void Type:** Indicates no data or unspecified data type.

Understanding data types is crucial for effective memory management and for performing correct operations in C programming.

```c
#include <stdio.h>
#include <conio.h>

void main(){
    int num1, num2, result;
    num1= 2;
    num2= 4;
    result = num1 + num2;
    printf("Result : ");
    printf("%d", result);
}

```

### What is a Variable in C?

A **variable** in C is a named location in memory that is used to store data. The data stored in a variable can be changed during program execution. Each variable has a specific **data type** that determines the type of data it can store, such as integers, floating-point numbers, characters, etc.

### Syntax for Declaring Variables

To declare a variable in C, you need to specify its **data type** followed by its **name** (identifier):

```c
data_type variable_name;
```

For example:

```c
int age;      // Declaring an integer variable
float height; // Declaring a floating-point variable
char grade;   // Declaring a character variable
```

### Variable Initialization

You can also assign a value to a variable at the time of declaration:

```c
int age = 25;
float height = 5.9;
char grade = 'A';
```

### Types of Variables in C

1. **Local Variables**
   - **Description:** Declared inside a function or block and can only be used within that function or block.
   - **Example:**
     ```c
     void myFunction() {
         int localVar = 10;  // Local variable
         printf("%d", localVar);
     }
     ```

2. **Global Variables**
   - **Description:** Declared outside of all functions and can be accessed by any function within the program.
   - **Example:**
     ```c
     int globalVar = 100;  // Global variable

     void myFunction() {
         printf("%d", globalVar);  // Accessing global variable
     }
     ```

3. **Static Variables**
   - **Description:** Declared with the `static` keyword. Retains its value between function calls and is initialized only once.
   - **Example:**
     ```c
     void myFunction() {
         static int counter = 0;  // Static variable
         counter++;
         printf("%d", counter);
     }
     ```

4. **Automatic Variables**
   - **Description:** By default, variables declared inside a function are automatic variables, meaning their lifetime is limited to the function.
   - **Example:**
     ```c
     void myFunction() {
         int autoVar = 10;  // Automatic variable
         printf("%d", autoVar);
     }
     ```

5. **Extern Variables**
   - **Description:** Declared with the `extern` keyword to indicate that the variable is defined in another file or later in the same file.
   - **Example:**
     ```c
     extern int externalVar;  // Declaration of extern variable
     ```

### Example Program with Variables

```c
#include <stdio.h>

int globalVar = 100;  // Global variable

void display() {
    static int staticVar = 1;  // Static variable
    int localVar = 10;         // Local variable
    staticVar++;               // Static variable retains its value
    printf("Local: %d, Static: %d, Global: %d\n", localVar, staticVar, globalVar);
}

int main() {
    display();
    display();  // Static variable retains its incremented value
    return 0;
}
```

### Variable Naming Rules
1. **Must start with a letter or underscore (`_`).**
2. **Cannot use C keywords** like `int`, `float`, `if`, `else`.
3. **No spaces or special characters** except underscores.

### Summary of Variables in C

- **Local Variables**: Declared inside a function or block, accessible only within that scope.
- **Global Variables**: Declared outside of all functions, accessible by all functions.
- **Static Variables**: Retain their value between function calls and have a local scope.
- **Automatic Variables**: Declared within functions, their lifetime ends when the function ends.
- **Extern Variables**: Declared but not defined in the current scope, used to reference a variable in another file.

Variables are a fundamental part of programming in C as they allow you to store and manipulate data throughout your program.

### What is a Storage Class in C?

A **storage class** in C defines the **scope, lifetime, and visibility** of variables and functions. It tells the compiler where to store a variable, how long the variable should exist, and who can access it. 

### Types of Storage Classes in C

There are four primary storage classes in C:

1. **Automatic (`auto`)**
2. **External (`extern`)**
3. **Static (`static`)**
4. **Register (`register`)**

---

### 1. **Automatic (`auto`)**

- **Scope**: Local to the block or function in which it is defined.
- **Lifetime**: Exists until the function/block in which it is defined completes execution.
- **Default storage class** for variables declared inside a function.
- **Keyword**: `auto` (optional because it is the default).

#### Example:
```c
void myFunction() {
    auto int x = 10;  // 'x' is an automatic variable
    printf("%d", x);
}
```
In this case, `x` is local to `myFunction`, and its storage is automatically managed by the compiler.

---

### 2. **External (`extern`)**

- **Scope**: Global, accessible across different files.
- **Lifetime**: The entire duration of the program’s execution.
- Used when a variable or function is **defined in one file** and **used in another**.
- **Keyword**: `extern`

#### Example:
File 1 (`file1.c`):
```c
int globalVar = 10;  // Global variable definition
```

File 2 (`file2.c`):
```c
extern int globalVar;  // Referencing the global variable from file1
void myFunction() {
    printf("%d", globalVar);  // Accessing the global variable
}
```
`extern` tells the compiler that the variable is defined elsewhere (in another file).

---

### 3. **Static (`static`)**

- **Scope**: If declared inside a function, it's local to the function. If declared globally, it’s local to the file.
- **Lifetime**: Retains its value between function calls or persists throughout the program when declared globally.
- **Keyword**: `static`

#### Example 1 (Local Static):
```c
void myFunction() {
    static int count = 0;  // 'count' retains its value between calls
    count++;
    printf("%d", count);
}

int main() {
    myFunction();  // Output: 1
    myFunction();  // Output: 2 (value is retained)
}
```

#### Example 2 (Global Static):
```c
static int globalVar = 10;  // This variable is accessible only within this file
```
In both cases, the `static` keyword makes the variable retain its value.

---

### 4. **Register (`register`)**

- **Scope**: Local to the block or function where it is declared.
- **Lifetime**: Exists until the block or function completes execution.
- Suggests that the variable be stored in a **register** instead of RAM, making access faster (but it's up to the compiler to decide).
- **Keyword**: `register`

#### Example:
```c
void myFunction() {
    register int counter = 0;  // Request to store 'counter' in a register
    for (int i = 0; i < 10; i++) {
        counter++;
    }
}
```
`register` is often used for variables that are frequently accessed, like loop counters.

---

### Summary of Storage Classes

| Storage Class | Scope          | Lifetime             | Keyword   | Used For |
|---------------|----------------|----------------------|-----------|----------|
| **auto**      | Local          | Until block/function ends | `auto` (optional) | Local variables |
| **extern**    | Global         | Entire program        | `extern`  | Sharing variables/functions across files |
| **static**    | Local or File  | Retains value across calls (if local), entire program (if global) | `static` | Persistent local variables or file-local globals |
| **register**  | Local          | Until block/function ends | `register` | Faster access (request) |

Storage classes control how variables are stored, where they can be accessed from, and how long they persist in memory.

### `printf()` and `scanf()` Functions in C

The functions `printf()` and `scanf()` are used for **input** and **output** in C. Both functions work with **format strings** and **argument lists** to display or read values of different types.

---

### 1. **`printf()` Function**

- **Purpose**: Used to print output to the console.
- **Syntax**: 
  ```c
  printf("format string", argument_list);
  ```
- **Example**:
  ```c
  int age = 25;
  printf("Age: %d\n", age);  // Output: Age: 25
  ```

- **`format string`**: A string containing text to be displayed and placeholders (format specifiers) for variables.
- **`argument_list`**: The variables or values that are substituted in place of the format specifiers in the format string.

---

### 2. **`scanf()` Function**

- **Purpose**: Used to read input from the user.
- **Syntax**:
  ```c
  scanf("format string", argument_list);
  ```
- **Example**:
  ```c
  int age;
  scanf("%d", &age);  // Reads an integer and stores it in the variable 'age'
  ```

- **`format string`**: A string containing format specifiers that define the type of data to be read.
- **`argument_list`**: The addresses of variables where the input data will be stored. For `scanf()`, you need to pass **pointers** (use the `&` symbol before the variable name).

---

### Format Specifiers

A **format specifier** tells `printf()` or `scanf()` the type of data that is being handled (e.g., integer, float, character). Each specifier starts with a `%` symbol followed by a character that represents the data type.

#### Common Format Specifiers:

| Format Specifier | Data Type        | Description                        |
|------------------|------------------|------------------------------------|
| `%d` or `%i`     | Integer          | Decimal integer                    |
| `%f`             | Float/Double     | Floating-point number              |
| `%c`             | Character        | Single character                   |
| `%s`             | String           | Sequence of characters             |
| `%lf`            | Double           | Double precision floating-point    |
| `%u`             | Unsigned Integer | Unsigned decimal number            |
| `%x` or `%X`     | Hexadecimal      | Hexadecimal representation of an integer |
| `%o`             | Octal            | Octal representation of an integer |
| `%p`             | Pointer          | Memory address                     |

#### Example of Using `printf()`:
```c
int num = 10;
float pi = 3.14;
char letter = 'A';

printf("Integer: %d\n", num);     // Output: Integer: 10
printf("Float: %.2f\n", pi);      // Output: Float: 3.14
printf("Character: %c\n", letter);// Output: Character: A
```

#### Example of Using `scanf()`:
```c
int num;
float pi;
char letter;

scanf("%d", &num);   // Reading an integer
scanf("%f", &pi);    // Reading a float
scanf(" %c", &letter); // Reading a character (space before %c to consume any leftover newline)

printf("Num: %d, Pi: %.2f, Letter: %c\n", num, pi, letter);
```

---

### Detailed Explanation of Format Specifiers:

1. **Integer Format Specifier (`%d` or `%i`)**:
   - Used for printing or reading integers.
   - Example:
     ```c
     int num = 100;
     printf("Value: %d", num);  // Output: Value: 100
     ```

2. **Floating-point Format Specifier (`%f` or `%lf`)**:
   - Used for printing or reading floating-point numbers (e.g., decimals).
   - `%f` is used for `float`, and `%lf` is used for `double`.
   - Example:
     ```c
     float num = 3.14;
     printf("Value: %.2f", num);  // Output: Value: 3.14
     ```

3. **Character Format Specifier (`%c`)**:
   - Used for printing or reading a single character.
   - Example:
     ```c
     char ch = 'A';
     printf("Character: %c", ch);  // Output: Character: A
     ```

4. **String Format Specifier (`%s`)**:
   - Used for printing or reading a string of characters.
   - Example:
     ```c
     char name[] = "John";
     printf("Name: %s", name);  // Output: Name: John
     ```

5. **Unsigned Integer Format Specifier (`%u`)**:
   - Used for printing or reading unsigned integers (non-negative values).
   - Example:
     ```c
     unsigned int num = 300;
     printf("Unsigned Value: %u", num);  // Output: Unsigned Value: 300
     ```

---

### Summary:

- **`printf()`** is used to print output, while **`scanf()`** is used to read input.
- Both functions use **format strings** and **argument lists** to specify the data types to be printed or read.
- **Format specifiers** in the format string tell the functions how to interpret the data (e.g., `%d` for integers, `%f` for floats).

Format specifiers are essential for properly handling different data types in C programs.


### This is Simple Code Of calculates the area of a rectangle by taking two inputs

```c
#include <stdio.h>

int main() {
    int base, height, area;
    // Input base
    printf("Enter the base: ");
    scanf("%d", &base);
    // Input height
    printf("Enter the height: ");
    scanf("%d", &height);
    // Calculate area
    area = base * height;
    // Output the result
    printf("The area of the rectangle is: %d", area);
    return 0;
}

```

### Constants in C

In C, **constants** are fixed values that cannot be changed during the execution of a program. They are defined in the code and used to represent data that remains the same throughout the program. Constants can be of various types such as integers, floating-point numbers, characters, and strings.

### Types of Constants in C

1. **Integer Constants**
2. **Floating-point Constants**
3. **Character Constants**
4. **String Constants**
5. **Symbolic Constants**

---

### 1. **Integer Constants**

An **integer constant** is a whole number without a fractional part.

- **Example**:
  ```c
  int a = 10;  // 10 is an integer constant
  ```

---

### 2. **Floating-point Constants**

A **floating-point constant** is a number with a fractional part (decimals).

- **Example**:
  ```c
  float pi = 3.14;  // 3.14 is a floating-point constant
  ```

---

### 3. **Character Constants**

A **character constant** represents a single character enclosed in single quotes (`'`).

- **Example**:
  ```c
  char grade = 'A';  // 'A' is a character constant
  ```

---

### 4. **String Constants**

A **string constant** is a sequence of characters enclosed in double quotes (`"`).

- **Example**:
  ```c
  char name[] = "John";  // "John" is a string constant
  ```

---

### 5. **Symbolic Constants**

A **symbolic constant** is a name given to constant values, typically defined using the `#define` preprocessor directive or the `const` keyword.

#### Using `#define`:
- **Example**:
  ```c
  #define PI 3.14159  // PI is a symbolic constant
  int main() {
      float area = PI * 2 * 2;  // Using the symbolic constant
      printf("Area: %.2f\n", area);
      return 0;
  }
  ```

#### Using `const`:
- **Example**:
  ```c
  const int MAX = 100;  // MAX is a constant integer
  int main() {
      printf("Max value: %d\n", MAX);
      return 0;
  }
  ```

---

### Example Code with Different Constants:

```c
#include <stdio.h>

#define PI 3.14159  // Symbolic constant

int main() {
    const int MAX = 100;  // Constant integer
    int radius = 5;
    float area;

    // Integer constant
    int age = 25;  

    // Floating-point constant
    area = PI * radius * radius;

    // Character constant
    char grade = 'A';

    // String constant
    char name[] = "Alice";

    // Printing constants
    printf("Age: %d\n", age);                  // Output: Age: 25
    printf("Area of circle: %.2f\n", area);    // Output: Area of circle: 78.54
    printf("Grade: %c\n", grade);              // Output: Grade: A
    printf("Name: %s\n", name);                // Output: Name: Alice
    printf("Max value: %d\n", MAX);            // Output: Max value: 100

    return 0;
}
```

### Summary of Constants:

- **Integer Constants**: Whole numbers without decimal points.
- **Floating-point Constants**: Numbers with decimal points.
- **Character Constants**: Single characters enclosed in single quotes.
- **String Constants**: Sequences of characters enclosed in double quotes.
- **Symbolic Constants**: Named constants defined using `#define` or `const`.

Constants in C help in making code more readable and easier to maintain by providing a way to use fixed values that cannot be modified during program execution.

### What is an Operator in C?

An **operator** in C is a symbol that tells the compiler to perform a specific mathematical, logical, or relational operation on one or more operands. Operators are used in expressions to manipulate data and variables.

### Types of Operators in C

1. **Arithmetic Operators**
2. **Relational Operators**
3. **Logical Operators**
4. **Bitwise Operators**
5. **Assignment Operators**
6. **Unary Operators**
7. **Conditional (Ternary) Operator**
8. **Comma Operator**
9. **Sizeof Operator**
10. **Pointer Operators**
11. **Special Operators**

---

### 1. **Arithmetic Operators**

These operators are used to perform basic arithmetic operations like addition, subtraction, multiplication, division, and modulus.

- **Operators**: `+`, `-`, `*`, `/`, `%`
- **Example**:
  ```c
  int a = 10, b = 5;
  int sum = a + b;        // Addition
  int diff = a - b;       // Subtraction
  int prod = a * b;       // Multiplication
  int quot = a / b;       // Division
  int mod = a % b;        // Modulus (remainder)
  ```

---

### 2. **Relational Operators**

Relational operators are used to compare two values. They return either true (1) or false (0).

- **Operators**: `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Example**:
  ```c
  int x = 10, y = 20;
  int isEqual = (x == y);   // False (0)
  int isNotEqual = (x != y); // True (1)
  int isGreater = (x > y);  // False (0)
  ```

---

### 3. **Logical Operators**

Logical operators are used to combine two or more conditions or to negate a condition.

- **Operators**: `&&` (AND), `||` (OR), `!` (NOT)
- **Example**:
  ```c
  int a = 10, b = 5, c = 10;
  int result1 = (a == c) && (b < c);  // True (1)
  int result2 = (a == c) || (b > c);  // True (1)
  int result3 = !(a > b);             // False (0)
  ```

---

### 4. **Bitwise Operators**

Bitwise operators perform operations on the individual bits of integers.

- **Operators**: `&` (AND), `|` (OR), `^` (XOR), `~` (NOT), `<<` (Left Shift), `>>` (Right Shift)
- **Example**:
  ```c
  int a = 5;  // Binary: 0101
  int b = 9;  // Binary: 1001

  int and = a & b;  // AND: 0001 (1)
  int or = a | b;   // OR: 1101 (13)
  int xor = a ^ b;  // XOR: 1100 (12)
  int not = ~a;     // NOT: 1010 (two's complement)
  int lshift = a << 1;  // Left Shift: 1010 (10)
  int rshift = b >> 1;  // Right Shift: 0100 (4)
  ```

---

### 5. **Assignment Operators**

Assignment operators are used to assign values to variables.

- **Operators**: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `<<=`, `>>=`, `&=`, `^=`, `|=`
- **Example**:
  ```c
  int a = 10;
  a += 5;  // a = a + 5 (a becomes 15)
  a *= 2;  // a = a * 2 (a becomes 30)
  ```

---

### 6. **Unary Operators**

Unary operators operate on a single operand to perform various operations like incrementing/decrementing a value, negating an expression, or testing the size of a data type.

- **Operators**: `++`, `--`, `-`, `+`, `!`, `~`
- **Example**:
  ```c
  int x = 10;
  int y = ++x;  // Pre-increment (x becomes 11, y is 11)
  int z = x--;  // Post-decrement (x becomes 10, z is 11)
  ```

---

### 7. **Conditional (Ternary) Operator**

The conditional operator is a shorthand for an if-else statement and has the form `? :`.

- **Operator**: `? :`
- **Example**:
  ```c
  int a = 10, b = 20;
  int max = (a > b) ? a : b;  // max is 20
  ```

---

### 8. **Comma Operator**

The comma operator allows multiple expressions to be evaluated in a single statement, with the last expression being the result.

- **Operator**: `,`
- **Example**:
  ```c
  int a, b, c;
  c = (a = 1, b = 2, a + b);  // a becomes 1, b becomes 2, c becomes 3
  ```

---

### 9. **Sizeof Operator**

The `sizeof` operator returns the size, in bytes, of its operand.

- **Operator**: `sizeof`
- **Example**:
  ```c
  int a = 10;
  int size = sizeof(a);  // Size of int (typically 4 bytes)
  ```

---

### 10. **Pointer Operators**

Pointer operators are used to work with pointers.

- **Operators**: `*` (Dereference), `&` (Address-of)
- **Example**:
  ```c
  int a = 10;
  int *p = &a;  // p points to the address of a
  int value = *p;  // value is the value at the address p (value becomes 10)
  ```

---

### 11. **Special Operators**

- **Comma (` , `) Operator**: Used to separate expressions.
- **Member Access Operators**: `.` (dot) and `->` (arrow)
- **Example**:
  ```c
  struct Point {
      int x, y;
  };

  struct Point p = {1, 2};
  int xCoord = p.x;  // Accessing member 'x' using the dot operator
  ```

---

### Example Code with Various Operators:

```c
#include <stdio.h>

int main() {
    int a = 10, b = 20;
    int sum, diff, prod, quot, mod;
    int isEqual, isNotEqual, isGreater;
    int and, or, xor, not;
    int result;

    // Arithmetic Operators
    sum = a + b;
    diff = a - b;
    prod = a * b;
    quot = a / b;
    mod = a % b;

    // Relational Operators
    isEqual = (a == b);
    isNotEqual = (a != b);
    isGreater = (a > b);

    // Logical Operators
    result = (a == 10) && (b == 20);
    result = (a == 10) || (b == 15);
    result = !(a == 15);

    // Bitwise Operators
    and = a & b;
    or = a | b;
    xor = a ^ b;
    not = ~a;

    // Assignment Operators
    a += 5;
    b *= 2;

    // Unary Operators
    ++a;
    --b;

    // Conditional (Ternary) Operator
    result = (a > b) ? a : b;

    // Sizeof Operator
    int size = sizeof(a);

    printf("Sum: %d, Difference: %d, Product: %d, Quotient: %d, Modulus: %d\n", sum, diff, prod, quot, mod);
    printf("Is Equal: %d, Is Not Equal: %d, Is Greater: %d\n", isEqual, isNotEqual, isGreater);
    printf("Bitwise AND: %d, OR: %d, XOR: %d, NOT: %d\n", and, or, xor, not);
    printf("Size of a: %d bytes\n", size);

    return 0;
}
```

### Summary of Operators:

- **Arithmetic Operators**: Perform mathematical operations.
- **Relational Operators**: Compare values.
- **Logical Operators**: Combine or negate conditions.
- **Bitwise Operators**: Perform operations on individual bits.
- **Assignment Operators**: Assign values to variables.
- **Unary Operators**: Operate on a single operand.
- **Conditional (Ternary) Operator**: Shorten conditional statements.
- **Sizeof Operator**: Get the size of a data type or variable.
- **Pointer Operators**: Work with pointers and addresses.

Operators are essential in C programming for manipulating data, controlling flow, and performing various calculations.

