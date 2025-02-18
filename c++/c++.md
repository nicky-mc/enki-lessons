**C++ Basics**

**Introduction**

C++ is a powerful, high-performance programming language that extends the C programming language with object-oriented, generic, and functional programming features. It is widely used in system/software development, game development, embedded systems, and competitive programming.

This document provides a basic introduction to C++ syntax and fundamental concepts.

**Table of Contents**

•[Hello, World!](file:///index.html#hello-world)

•[Basic Syntax](file:///index.html#basic-syntax)

•[Data Types](file:///index.html#data-types)

•[Variables and Constants](file:///index.html#variables-and-constants)

•[Operators](file:///index.html#operators)

•[Control Flow Statements](file:///index.html#control-flow-statements)

•[Conditional Statements](file:///index.html#conditional-statements)

•[Loops](file:///index.html#loops)

•[Functions](file:///index.html#functions)

•[Pointers](file:///index.html#pointers)

•[Classes and Objects](file:///index.html#classes-and-objects)

•[Conclusion](file:///index.html#conclusion)

**Hello, World!**

The first step in learning C++ is writing a simple program that prints "Hello, World!" to the console.

#include   _// Include the input-output stream library_

int main() {

    std::cout << "Hello, World!" << std::endl; _// Print message to console_

    return 0; _// Indicate successful execution_

}

**Explanation:**

•#include : Includes the input-output stream library.

•int main() {}: The main function where program execution begins.

•std::cout: Outputs data to the console.

•std::endl: Moves the cursor to a new line.

•return 0;: Indicates successful program termination.

**Basic Syntax**

C++ syntax follows a structured approach:

1.**Every statement ends with a semicolon (;).**

2.**Code blocks are enclosed in {} (curly braces).**

3.**C++ is case-sensitive (Variable and variable are different).**

4.**Whitespace (spaces, tabs, and newlines) is ignored but should be used for readability.**

**Data Types**

C++ supports various data types, including:

**Data Type****Description****Example**

intInteger numbersint x = 10;

floatFloating-point numbers (single precision)float pi = 3.14;

doubleFloating-point numbers (double precision)double price = 99.99;

charSingle characterchar grade = 'A';

boolBoolean (true or false)bool isCPlusPlusFun = true;

stringSequence of characters (needs header)std::string name = "Alice";

**Variables and Constants**

**Declaring Variables:**

int age = 25;

double salary = 50000.75;

char letter = 'C';

**Constants:**

Use const to define a variable whose value cannot be changed.

const double PI = 3.14159;

**Operators**

Operators allow us to perform operations on variables.

**Arithmetic Operators:**

**Operator****Description****Example**

+Additionx + y

\-Subtractionx - y

\*Multiplicationx \* y

/Divisionx / y

%Modulus (remainder)x % y

**Comparison Operators:**

**Operator****Description****Example**

\==Equal tox == y

!=Not equal tox != y

\>Greater thanx > y

\>=Greater than or equal tox >= y

<=Less than or equal tox <= y

**Control Flow Statements**

**Conditional Statements**

**if Statement:**

int num = 10;

if (num > 5) {

    std::cout << "Number is greater than 5" << std::endl;

}

**if-else Statement:**

int age = 18;

if (age >= 18) {

    std::cout << "You are an adult." << std::endl;

} else {

    std::cout << "You are a minor." << std::endl;

}

**switch Statement:**

char grade = 'B';

switch (grade) {

    case 'A':

        std::cout << "Excellent!" << std::endl;

        break;

    case 'B':

        std::cout << "Good job!" << std::endl;

        break;

    default:

        std::cout << "Try harder next time." << std::endl;

}

**Loops**

**for Loop:**

for (int i = 0; i < 5; i++) {

    std::cout << "Iteration " << i << std::endl;

}

**while Loop:**

int count = 0;

while (count < 5) {

    std::cout << "Count: " << count << std::endl;

    count++;

}

**do-while Loop:**

int number = 0;

do {

    std::cout << "Number: " << number << std::endl;

    number++;

} while (number < 5);

**Functions**

Functions allow code reuse.

#include

void greet() {

    std::cout << "Hello, User!" << std::endl;

}

int main() {

    greet(); _// Function call_

    return 0;

}

**Function with Parameters:**

void add(int a, int b) {

    std::cout << "Sum: " << a + b << std::endl;

}

int main() {

    add(5, 10);

    return 0;

}

**Function with Return Value:**

int square(int x) {

    return x \* x;

}

int main() {

    int result = square(4);

    std::cout << "Square: " << result << std::endl;

    return 0;

}

**Pointers**

Pointers store memory addresses.

int num = 10;

int\* ptr = # _// Pointer to num_

std::cout << "Address of num: " << ptr << std::endl;

std::cout << "Value of num using pointer: " << \*ptr << std::endl;

**Classes and Objects**

C++ supports object-oriented programming.

class Car {

public:

    std::string brand;

    int year;

    void showInfo() {

        std::cout << "Brand: " << brand << ", Year: " << year << std::endl;

    }

};

int main() {

    Car myCar;

    myCar.brand = "Toyota";

    myCar.year = 2022;

    myCar.showInfo();

    return 0;

}

**Conclusion**

This guide covered the basics of C++ syntax, variables, operators, control flow, functions, pointers, and classes. C++ is a vast language with many advanced topics like templates, polymorphism, and memory management, which you can explore further.

For more in-depth learning, check out:

•[C++ Documentation](https://cplusplus.com/)

•[C++ Reference](https://en.cppreference.com/)

Happy coding!