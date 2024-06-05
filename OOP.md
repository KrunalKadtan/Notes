# Table Of Content

1. **[Revision Of C](#revision-of-c)**
    -
    - [Pointers in C](#pointers-in-c)
        -
        - [What is a Pointer?](#what-is-a-pointer)
        - [Why Use Pointers?](#why-use-pointers)
        - [Basic Syntax](#basic-syntax)
        - [Example : Using Pointers](#example--using-pointers)
        - [Important Concepts](#important-concepts)

    - [Dynamic Memory Allocation](#dynamic-memory-allocation)
        -
        - [Functions for Dynamic Memory Allocation](#functions-for-dynamic-memory-allocation)
        - [Using `malloc`](#using-malloc)
        - [Using `calloc`](#using-calloc)
        - [Using `realloc`](#using-realloc)

    - [File Managment](#file-managment)
        -
        - [Basic File Operations](#basic-file-operations)
        - [Opening and Closing a File](#opening-and-closing-a-file)
        - [Writing to a File](#writing-to-a-file)
        - [Reading from a File](#reading-from-a-file)

2. [Concepts of OOP](#concepts-of-oop)
    -
    - [Introduction to OOP](#introduction-to-oop)
        -
        - [Key Concepts of OOP](#key-concepts-of-oop)
        - [Example in C++](#example-in-c)
        - [Explanation of the Example](#explanation-of-the-example)
        - [Inheritance and Polymorphism Example](#inheritance-and-polymorphism-example)

    - [Procedural Vs. Object-Oriented Programming](#procedural-vs-object-oriented-programming)
        -
        - [Procedural Programming](#procedural-programming)
        - [Object-Oriented Programming](#object-oriented-programming)
        - [Comparison](#comparison)
        - [Example to Illustrate the Differences](#example-to-illustrate-the-differences)
        - [Strengths and Weaknesses](#strengths-and-weaknesses)
        - [When to Use](#when-to-use)

    - [Principles of OOP](#principles-of-oop)
        -
        - [1. Encapsulation](#1-encapsulation)
        - [2. Abstraction](#2-abstraction)
        - [3. Inheritance](#3-inheritance)
        - [4. Polymorphism](#4-polymorphism)

    - [Benefits & Applications of OOP](#benefits--applications-of-oop)
        -
        - [Benefits of OOP](#benefits-of-oop)
        - [Applications of OOP](#applications-of-oop)
        - [Benefits & Applications](#benefits--applications)

3. [C++ Basics](#c-basics)
    -
    - [Overview](#overview)
        -
        - [Introduction to C++](#introduction-to-c)
        - [Basic Syntax and Structure](#basic-syntax-and-structure)
        - [Key Concepts](#key-concepts)
        - [Input/Output](#inputoutput)
        - [Example Program](#example-program)

    - [Program Structure](#program-structure)
        -
        - [Basic Structure of a C++ Program](#basic-structure-of-a-c-program)
        - [Example Program](#example-program-1)
        - [Detailed Explanation](#detailed-explanation)
        - [Additional Components in C++ Program Structure](#additional-components-in-c-program-structure)
        - [Example Program with Classes](#example-program-with-classes)

    - [Namespace](#namespace)
        -
        - [Introduction to Namespaces](#introduction-to-namespaces)
        - [Key Points about Namespaces](#key-points-about-namespaces)
        - [Example with Multiple Namespaces](#example-with-multiple-namespaces)
        - [Avoiding Name Conflicts](#avoiding-name-conflicts)

    - [Identifiers](#identifiers)
        -
        - [Rules for Identifiers](#rules-for-identifiers)
        - [Best Practices for Naming Identifiers](#best-practices-for-naming-identifiers)
        - [Examples of Valid and Invalid Identifiers](#examples-of-valid-and-invalid-identifiers)
        - [Example Program](#example-program-2)

    - [Variables](#variables)
        -
        - [Declaring and Initializing Variables](#declaring-and-initializing-variables)
        - [Basic Data Types](#basic-data-types)
        - [Example Program](#example-program-3)
        - [Variable Scope](#variable-scope)
        - [Variable Types](#variable-types)
        - [Example Program with Scope](#example-program-with-scope)
        
    - [Constants](#constants)
        -
        - [Defining Constants](#defining-constants)
        - [1. Using the `const` Keyword](#1-using-the-const-keyword)
        - [2. Using the `#define` Preprocessor Directive](#2-using-the-define-preprocessor-directive)
        - [3. Using `constexpr` (C++11 and Later)](#3-using-constexpr-c11-and-later)
        - [Differences Between `const`, `#define`, and `constexpr`](#differences-between-const-define-and-constexpr)
        - [Example with Class Constants](#example-with-class-constants)

    - [Enum](#enum)
        -
        - [Basic Syntax of `enum`](#basic-syntax-of-enum)
        - [Example of an Enumeration](#example-of-an-enumeration)
        - [Key Points about Enums](#key-points-about-enums)
        - [Example Programs](#example-programs)

    - [Operators](#operators)
        -
        - [Types of Operators](#types-of-operators)
        - [1. Arithmetic Operators](#1-arithmetic-operators)
        - [2. Relational Operators](#2-relational-operators)
        - [3. Logical Operators](#3-logical-operators)
        - [4. Bitwise Operators](#4-bitwise-operators)
        - [5. Assignment Operators](#5-assignment-operators)
        - [6. Increment and Decrement Operators](#6-increment-and-decrement-operators)
        - [7. Conditional (Ternary) Operator](#7-conditional-ternary-operator)
        - [8. Comma Operator](#8-comma-operator)
        - [9. Type Cast Operator](#9-string-manipulation)
        - [10. Sizeof Operator](#10-input-and-output)

    - [Typecasting](#typecasting)
        -
        - [Types of Typecasting](#types-of-typecasting)
        - [1. Implicit Typecasting (Automatic Type Conversion)](#1-implicit-typecasting-automatic-type-conversion)
        - [2. Explicit Typecasting (Manual Type Conversion)](#2-explicit-typecasting-manual-type-conversion)

    - [Control Structures](#control-structures)
        -
        - [1. Conditional Statements](#1-conditional-statements)
        - [2. Loops](#2-loops)
        - [3. Jump Statements](#3-jump-statements)


4. [C++ Functions](#c-functions)
    -
    - [Simple Functions](#simple-functions)
        -
        - [Defining a Function](#defining-a-function)
        - [Example of a Simple Function](#example-of-a-simple-function)
        - [Function with No Parameters and No Return Value](#function-with-no-parameters-and-no-return-value)
        - [Function with Parameters and No Return Value](#function-with-parameters-and-no-return-value)
        - [Function with No Parameters and a Return Value](#function-with-no-parameters-and-a-return-value)
        - [Function Overloading](#function-overloading)

    - [Call & Return By Reference](#call--return-by-reference)
        -
        - [Call by Value](#call-by-value)
        - [Call by Reference](#call-by-reference)
        - [Returning by Reference](#returning-by-reference)
        - [Important Points](#important-points)
        - [Example with Arrays](#example-with-arrays)

    - [Inline Functions](#inline-functions)
        -
        - [Defining Inline Functions](#defining-inline-functions)
        - [Example of an Inline Function](#example-of-an-inline-function)
        - [Inline Functions in Classes](#inline-functions-in-classes)
        - [Advantages of Inline Functions](#advantages-of-inline-functions)
        - [Limitations and Considerations](#limitations-and-considerations)
        - [Example with Inline Keyword](#example-with-inline-keyword)

    - [Macro Vs. Inline Functions](#macro-vs-inline-functions)
        -
        - [Macros](#macros)
        - [Inline Functions](#inline-functions-1)
        - [Comparison](#comparison-1)

    - [Overloading Of Functions](#overloading-of-functions)
        -
        - [Key Points of Function Overloading](#key-points-of-function-overloading)
        - [Example of Function Overloading](#example-of-function-overloading)
        - [Overloading with Different Number of Parameters](#overloading-with-different-number-of-parameters)
        - [Overloading with Different Parameter Types](#overloading-with-different-parameter-types)
        - [Rules and Best Practices](#rules-and-best-practices)
        - [Example with Class Methods](#example-with-class-methods)

    - [Default Arguments](#default-arguments)
        -
        - [Syntax](#syntax)
        - [Example of Default Arguments](#example-of-default-arguments)
        - [Rules for Default Arguments](#rules-for-default-arguments)
        - [Example with Class Methods](#example-with-class-methods-1)

    - [Friend Functions](#friend-functions)
        -
        - [Key Points about Friend Functions](#key-points-about-friend-functions)
        - [Example of a Friend Function](#example-of-a-friend-function)
        - [Why Use Friend Functions?](#why-use-friend-functions)
        - [Example of Friend Function for Operator Overloading](#example-of-friend-function-for-operator-overloading)

5. [Objects & Classes](#objects--classes)
    -
    - [Basics Of Object & Class in C++](#basics-of-object--class-in-c)
        -
        - [What is a Class?](#what-is-a-class)
        - [What is an Object?](#what-is-an-object)
        - [Members of a Class](#members-of-a-class)
        - [Constructors and Destructors](#constructors-and-destructors)

    - [Private & Public Members](#private--public-members)
        -
        - [Access Specifiers in C++](#access-specifiers-in-c)
        - [Public Members](#public-members)
        - [Private Members](#private-members)
        - [Why Use Private Members?](#why-use-private-members)
        - [Example: Combining Public and Private Members](#example-combining-public-and-private-members)

    - [Static Data & Function Members](#static-data--function-members)
        -
        - [Static Data Members](#static-data-members)
        - [Static Member Functions](#static-member-functions)
        - [Combined Example : Static Data Members and Static Member Functions](#combined-example--static-data-members-and-static-member-functions)

    - [Constructors & Their Types](#constructors--their-types)
        -
        - [Types of Constructors](#types-of-constructors)
        - [1. Default Constructor](#1-default-constructor)
        - [2. Parameterized Constructor](#2-parameterized-constructor)
        - [3. Copy Constructor](#3-copy-constructor)
        - [4. Move Constructor (C++11)](#4-move-constructor-c11)
        - [5. Delegating Constructor (C++11)](#5-delegating-constructor-c11)

    - [Destructors](#destructors)
        -
        - [Key Features of Destructors](#key-features-of-destructors)
        - [Example of a Destructor](#example-of-a-destructor)
        - [When Destructors Are Called](#when-destructors-are-called)
        - [Example: Object Going Out of Scope](#example-object-going-out-of-scope)
        - [Example: Explicitly Deleting Objects](#example-explicitly-deleting-objects)
        - [Example: Destructor in Inheritance](#example-destructor-in-inheritance)
        - [Best Practices for Destructors](#best-practices-for-destructors)

    - [Operator Overloading](#operator-overloading)
        -
        - [Key Points about Operator Overloading](#key-points-about-operator-overloading)
        - [Types of Operators That Can Be Overloaded](#types-of-operators-that-can-be-overloaded)
        - [Example : Overloading Arithmetic Operators](#example--overloading-arithmetic-operators)
        - [Example : Overloading the `<<` Operator](#example--overloading-the--operator)
        - [Example : Overloading the Subscript Operator `[]`](#example--overloading-the-subscript-operator-)

    - [Type Conversion](#type-conversion)
        -
        - [Types of Type Conversion](#types-of-type-conversion)
        - [1. Implicit Conversion (Automatic)](#1-implicit-conversion-automatic)
        - [2. Explicit Conversion (Casting)](#2-explicit-conversion-casting)
        - [3. User-Defined Conversion](#3-user-defined-conversion)

6. [Inheritance](#inheritance)
    -
    - [Concept Of Inheritance](#concept-of-inheritance)
        -
        - [Key Concepts of Inheritance](#key-concepts-of-inheritance)
        - [Types of Inheritance](#types-of-inheritance)
        - [Syntax of Inheritance](#syntax-of-inheritance)
        - [Example: Single Inheritance](#example-single-inheritance)
        - [Access Specifiers and Inheritance](#access-specifiers-and-inheritance)
        - [Example: Access Specifiers](#example-access-specifiers)
        - [Example: Multiple Inheritance](#example-multiple-inheritance)
        - [Virtual Inheritance](#virtual-inheritance)

    - [Types Of Inheritance](#types-of-inheritance)
        -
        - [1. Single Inheritance](#1-single-inheritance)
        - [2. Multiple Inheritance](#2-multiple-inheritance)
        - [3. Multilevel Inheritance](#3-multilevel-inheritance)
        - [4. Hierarchical Inheritance](#4-hierarchical-inheritance)
        - [5. Hybrid Inheritance](#5-hybrid-inheritance)

    - [Protected Members](#protected-members)
        -
        - [Key Points about `protected` Members](#key-points-about-protected-members)
        - [Syntax](#syntax-1)
        - [Example of `protected` Members](#example-of-protected-members)
        - [Explanation](#explanation)
        - [Advantages of `protected` Members](#advantages-of-protected-members)

    - [Overriding](#overriding)
        -
        - [Key Points about Method Overriding](#key-points-about-method-overriding)
        - [Syntax](#syntax-2)
        - [Example of Method Overriding](#example-of-method-overriding)
        - [Explanation](#explanation-1)
        - [Virtual Destructors](#virtual-destructors)

    - [Virtual Base Class](#virtual-base-class)
        -
        - [Diamond Problem](#diamond-problem)
        - [Using Virtual Base Classes](#using-virtual-base-classes)
        - [Syntax](#syntax-3)
        - [Example with Virtual Inheritance](#example-with-virtual-inheritance)
        - [Explanation](#explanation-2)
        - [Virtual Inheritance in Depth](#virtual-inheritance-in-depth)

7. [Polymorphism](#polymorphism)
    -
    - [Pointers in C++](#pointers-in-c-1)
        -
        - [Key Concepts of Pointers](#key-concepts-of-pointers)
        - [Pointer Declaration](#pointer-declaration)
        - [Pointer Initialization](#pointer-initialization)
        - [Dereferencing](#dereferencing)
        - [Example: Basic Pointer Usage](#example-basic-pointer-usage)
        - [Output](#output)
        - [Pointer Arithmetic](#pointer-arithmetic)
        - [Advanced Concepts](#advanced-concepts)
        - [Functions and Pointers](#functions-and-pointers)
        - [Dynamic Memory Allocation](#dynamic-memory-allocation-1)

    - [Pointers & Objects](#pointers--objects)
        -
        - [Key Concepts](#key-concepts-1)
        - [Object Pointers](#object-pointers)
        - [Dynamic Allocation of Objects](#dynamic-allocation-of-objects)
        - [Accessing Members](#accessing-members)
        - [Passing Objects to Functions](#passing-objects-to-functions)
        - [Array of Objects](#array-of-objects)
        - [Example: Linked List Using Pointers and Objects](#example-linked-list-using-pointers-and-objects)

    - [This Pointer](#this-pointer)
        -
        - [Key Points](#key-points)
        - [Example](#example)
        - [Output](#output-1)
        - [Detailed Explanation](#detailed-explanation-1)
        - [Common Uses of `this` Pointer](#common-uses-of-this-pointer)

    - [Virtual & Pure Virtual Functions](#virtual--pure-virtual-functions)
        -
        - [Virtual Functions](#virtual-functions)
        - [Example: Virtual Functions](#example-virtual-functions)
        - [Output](#output-2)
        - [Pure Virtual Functions](#pure-virtual-functions)
        - [Example: Pure Virtual Functions](#example-pure-virtual-functions)
        - [Output](#output-3)
        - [Detailed Explanation](#detailed-explanation-2)
        - [Abstract Classes](#abstract-classes)

    - [Implementing Polymorphism](#implementing-polymorphism)
        -
        - [Run-time Polymorphism](#run-time-polymorphism)
        - [Example: Run-time Polymorphism](#example-run-time-polymorphism)
        - [Output](#output-4)
        - [Explanation](#explanation-3)
        - [Compile-time Polymorphism](#compile-time-polymorphism)

8. [I/O Files & Templates](#io-files--templates)
    -
    - [C++ Stream Classes](#c-stream-classes)
        -
        - [Stream Class Hierarchy](#stream-class-hierarchy)
        - [Key Stream Classes](#key-stream-classes)
        - [Basic Input and Output with Streams](#basic-input-and-output-with-streams)
        - [File I/O with Streams](#file-io-with-streams)
        - [String Streams](#string-streams)

    - [Unformatted & Formatted I/O](#unformatted--formatted-io)
        -
        - [Unformatted I/O](#unformatted-io)
        - [Formatted I/O](#formatted-io)
        - [Manipulators](#manipulators)

    - [Manipulators](#manipulators-1)
        -
        - [Commonly Used Manipulators](#commonly-used-manipulators)
        - [Summary of Common Manipulators](#summary-of-common-manipulators)
        - [Example Usage](#example-usage)
        - [Output](#output-5)

    - [File Management Functions](#file-management-functions)
        -
        - [Key File Stream Classes](#key-file-stream-classes)
        - [Basic File Operations](#basic-file-operations-1)
        - [Writing to a File](#writing-to-a-file-2)
        - [Reading from a File](#reading-from-a-file-2)
        - [File Modes](#file-modes)
        - [Additional File Management Functions](#additional-file-management-functions)

    - [File Modes](#file-modes-1)
        -
        - [Common File Modes](#common-file-modes)
        - [Combining File Modes](#combining-file-modes)
        - [Examples](#examples)
        - [Summary of File Modes](#summary-of-file-modes)
        - [Combining File Modes](#combining-file-modes-1)

    - [Templates](#templates)
        -
        - [Function Templates](#function-templates)
        - [Class Templates](#class-templates)
        - [Template Specialization](#template-specialization)
        - [Class Template Specialization](#class-template-specialization)
        - [Template Parameters](#template-parameters)

    - [Exception Handling & Standard Template Library](#exception-handling--standard-template-library)
        -
        - [Exception Handling in C++](#exception-handling-in-c)
        - [Standard Template Library (STL)](#standard-template-library-stl)
        - [Example: Using `map`](#example-using-map)
        - [Example: Using `set`](#example-using-set)

9. [Introduction to Python Programming](#introduction-to-python-programming)
    -
    - [The Basic Elements of Python](#the-basic-elements-of-python)
        -
        - [1. Variables and Data Types](#1-variables-and-data-types)
        - [2. Basic Operators](#2-basic-operators)
        - [3. Control Structures](#3-control-structures)
        - [4. Functions](#4-functions)
        - [5. Lists](#5-lists)
        - [6. Tuples](#6-tuples)
        - [7. Dictionaries](#7-dictionaries)
        - [8. Sets](#8-sets)
        - [9. String Manipulation](#9-string-manipulation)
        - [10. Input and Output](#10-input-and-output)
        - [11. Exception Handling](#11-exception-handling)

    - [Branching Programs](#branching-programs)
        -
        - [Basic Conditional Statements](#basic-conditional-statements)
        - [Nested Conditional Statements](#nested-conditional-statements)
        - [Logical Operators](#logical-operators-1)
        - [Examples of Branching Programs](#examples-of-branching-programs)

    - [Control Structures](#control-structures-1)
        -
        - [1. Conditional Statements](#1-conditional-statements-1)
        - [2. Loops](#2-loops-1)
        - [3. Branching Statements](#3-branching-statements)
        - [4. Functions](#4-functions-1)
        - [5. List Comprehensions](#5-list-comprehensions)
        - [6. Dictionary Comprehensions](#6-dictionary-comprehensions)
        - [Examples](#examples-1)

    - [Strings & Input](#strings--input)
        -
        - [1. String Basics](#1-string-basics)
        - [2. String Operations](#2-string-operations)
        - [3. String Methods](#3-string-methods)
        - [4. String Formatting](#4-string-formatting)
        - [5. Handling User Input](#5-handling-user-input)
        - [Examples](#examples-2)

    - [Iteration](#iteration)
        -
        - [1. `for` Loop](#1-for-loop)
        - [2. `while` Loop](#2-while-loop)
        - [3. Nested Loops](#3-nested-loops)
        - [4. Loop Control Statements](#4-loop-control-statements)
        - [5. List Comprehensions](#5-list-comprehensions-1)
        - [6. Dictionary Comprehensions](#6-dictionary-comprehensions-1)
        - [Examples](#examples-3)

    - [Functions & Scoping](#functions--scoping)
        -
        - [1. Functions](#1-functions)
        - [2. Scoping](#2-scoping)
        - [3. The `global` and `nonlocal` Keywords](#3-the-global-and-nonlocal-keywords)
        - [4. Anonymous (Lambda) Functions](#4-anonymous-lambda-functions)
        - [Examples](#examples-4)

    - [Specifications](#specifications)
        -
        - [1. Docstrings](#1-docstrings)
        - [2. Type Hints](#2-type-hints)
        - [3. Comments](#3-comments)
        - [4. Assertions](#4-assertions)
        - [5. Example](#5-example)

    - [Recursion](#recursion)
        -
        - [Key Concepts](#key-concepts-2)
        - [Basic Example](#basic-example)
        - [Recursive Functions](#recursive-functions)
        - [Practical Example](#practical-example)
        - [Handling Recursion Depth](#handling-recursion-depth)
        - [Recursion vs. Iteration](#recursion-vs-iteration)
        - [Tail Recursion](#tail-recursion)

    - [Global Variables](#global-variables)
        -
        - [Key Concepts](#key-concepts-3)
        - [Example](#example-2)
        - [Reading Global Variables](#reading-global-variables)
        - [Modifying Global Variables](#modifying-global-variables)
        - [Best Practices](#best-practices)
        - [Example of Using Global and Local Variables](#example-of-using-global-and-local-variables)
        - [Local vs. Global Variables](#local-vs-global-variables)
        - [Nested Functions and Global Variables](#nested-functions-and-global-variables)

    - [Strings](#strings)
        -
        - [Creating Strings](#creating-strings-1)
        - [String Operations](#string-operations)
        - [String Methods](#string-methods)
        - [Formatting Strings](#formatting-strings)
        - [Checking String Content](#checking-string-content)
        - [Escape Characters](#escape-characters)
        - [Raw Strings](#raw-strings)
        - [Examples](#examples-5)

    - [Tuples](#tuples)
        -
        - [Creating Tuples](#creating-tuples)
        - [Accessing Elements](#accessing-elements)
        - [Slicing](#slicing-1)
        - [Tuple Methods](#tuple-methods)
        - [Tuple Operations](#tuple-operations)
        - [Tuple Packing and Unpacking](#tuple-packing-and-unpacking)
        - [Nested Tuples](#nested-tuples)
        - [Tuple vs. List](#tuple-vs-list)
        - [Example : Using Tuples in Functions](#example--using-tuples-in-functions)
        - [Tuple Immutability](#tuple-immutability)
        - [Use Cases for Tuples](#use-cases-for-tuples)

    - [List](#list)
        -
        - [Creating Lists](#creating-lists)
        - [Accessing Elements](#accessing-elements-1)
        - [Modifying Lists](#modifying-lists)
        - [List Operations](#list-operations)
        - [List Methods](#list-methods)
        - [List Comprehensions](#list-comprehensions)
        - [Nested Lists](#nested-lists)
        - [Example : Using Lists](#example--using-lists)

#


# Revision Of C

## Pointers in C

### What is a Pointer?
- variable that stores the memory address of another variable
- a reference or a link to another variable.

### Why Use Pointers?
1. **Efficiency** : allow direct access to memory
2. **Dynamic Memory Allocation** : Pointers are used with functions like `malloc` to allocate memory dynamically.
3. **Array Handling** : Pointers can simplify the handling of arrays and strings.
4. **Functions** : Passing large structures to functions by reference (using pointers) is more efficient than passing by value.

### Basic Syntax
1. **Declaration** :
   ```c
   int *p;  // p is a pointer to an integer
   ```
2. **Initialization** :
   ```c
   int a = 10;
   int *p;
   p = &a;  // p now holds the address of a
   ```

### Example : Using Pointers

```c
#include <stdio.h>

int main() {
    int a = 10;      // an integer variable
    int *p;          // a pointer to an integer

    p = &a;          // p points to the address of a

    printf("Value of a: %d\n", a);          // prints 10
    printf("Address of a: %p\n", (void*)&a); // prints address of a
    printf("Value of p: %p\n", (void*)p);   // prints the same address as above
    printf("Value pointed to by p: %d\n", *p); // prints 10

    return 0;
}
```

### Important Concepts

1. **Pointer Arithmetic** :
   - You can perform arithmetic operations on pointers (e.g., `p++` to move to the next memory location).

2. **Null Pointer** :
   - A pointer that doesn't point to any memory location. It is often used for error handling.
   ```c
   int *p = NULL;
   ```

3. **Pointer to Pointer** :
   - You can have a pointer that points to another pointer.
   ```c
   int a = 10;
   int *p = &a;
   int **pp = &p;
   ```

4. **Function Pointers** :
   - Pointers can also point to functions, allowing dynamic function calls.
   ```c
   void (*func_ptr)() = myFunction;
   func_ptr();
   ```

## Dynamic Memory Allocation

Dynamic memory allocation allows to allocate memory during the runtime of the program.

### Functions for Dynamic Memory Allocation

1. **malloc** : Allocates a specified number of bytes and returns a pointer to the first byte of the allocated memory.
2. **calloc** : Allocates memory for an array of elements, initializes them to zero, and returns a pointer to the memory.
3. **realloc** : Changes the size of the previously allocated memory.
4. **free** : Deallocates previously allocated memory.

### Using `malloc`
The `malloc` function allocates a block of memory but does not initialize it.

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    int *p;
    p = (int *)malloc(5 * sizeof(int));  // Allocate memory for 5 integers

    if (p == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < 5; i++) {
        p[i] = i + 1;
        printf("%d ", p[i]);
    }

    free(p);  // Free the allocated memory

    return 0;
}
```

### Using `calloc`
The `calloc` function allocates memory for an array and initializes all elements to zero.

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    int *p;
    p = (int *)calloc(5, sizeof(int));  // Allocate and initialize memory for 5 integers

    if (p == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < 5; i++) {
        printf("%d ", p[i]);  // All elements are initialized to 0
    }

    free(p);  // Free the allocated memory

    return 0;
}
```

### Using `realloc`
The `realloc` function changes the size of the allocated memory block.

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    int *p;
    p = (int *)malloc(5 * sizeof(int));  // Allocate memory for 5 integers

    if (p == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < 5; i++) {
        p[i] = i + 1;
        printf("%d ", p[i]);
    }

    printf("\n");

    // Reallocate memory for 10 integers
    p = (int *)realloc(p, 10 * sizeof(int));

    if (p == NULL) {
        printf("Memory reallocation failed\n");
        return 1;
    }

    // Initialize the newly allocated memory
    for (int i = 5; i < 10; i++) {
        p[i] = i + 1;
    }

    // Use the reallocated memory
    for (int i = 0; i < 10; i++) {
        printf("%d ", p[i]);
    }

    free(p);  // Free the allocated memory

    return 0;
}
```

## File Managment

File management involves creating, opening, reading, writing, and closing files.

### Basic File Operations

1. **Opening a File** : Use `fopen()`
2. **Closing a File** : Use `fclose()`
3. **Reading from a File** : Use `fgetc()`, `fgets()`, `fread()`
4. **Writing to a File** : Use `fputc()`, `fputs()`, `fwrite()`

### Opening and Closing a File
To open a file, use the `fopen` function, which returns a pointer to a `FILE` object. You must specify the file name and the mode in which to open the file.

```c
FILE *fopen(const char *filename, const char *mode);
```

**Modes**:
- `"r"`: Open for reading (file must exist)
- `"w"`: Open for writing (creates a new file or truncates an existing one)
- `"a"`: Open for appending (creates a new file if it doesn't exist)
- `"r+"`: Open for reading and writing (file must exist)
- `"w+"`: Open for reading and writing (creates a new file or truncates an existing one)
- `"a+"`: Open for reading and appending (creates a new file if it doesn't exist)

Example :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "w");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }
    // Use the file
    fclose(file); // Close the file
    return 0;
}
```

### Writing to a File
You can write to a file using `fputc`, `fputs`, or `fwrite`.

**fputc** :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "w");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }

    fputc('A', file);  // Write a single character
    fclose(file);
    return 0;
}
```

**fputs** :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "w");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }

    fputs("Hello, World!", file);  // Write a string
    fclose(file);
    return 0;
}
```

**fwrite** :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "w");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }

    int numbers[] = {1, 2, 3, 4, 5};
    fwrite(numbers, sizeof(int), 5, file);  // Write an array of integers
    fclose(file);
    return 0;
}
```

### Reading from a File
You can read from a file using `fgetc`, `fgets`, or `fread`.

**fgetc** :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "r");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }

    int c;
    while ((c = fgetc(file)) != EOF) {
        putchar(c);  // Print each character
    }
    fclose(file);
    return 0;
}
```

**fgets** :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "r");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }

    char buffer[100];
    while (fgets(buffer, sizeof(buffer), file) != NULL) {
        printf("%s", buffer);  // Print each line
    }
    fclose(file);
    return 0;
}
```

**fread** :
```c
#include <stdio.h>

int main() {
    FILE *file = fopen("example.txt", "r");
    if (file == NULL) {
        printf("Could not open file\n");
        return 1;
    }

    int numbers[5];
    fread(numbers, sizeof(int), 5, file);  // Read an array of integers

    for (int i = 0; i < 5; i++) {
        printf("%d ", numbers[i]);  // Print each number
    }
    printf("\n");
    fclose(file);
    return 0;
}
```

# Concepts of OOP

## Introduction to OOP

allows for modular and organized code by bundling related properties and behaviors into individual objects.

### Key Concepts of OOP

1. **Class** : A blueprint for creating objects (a particular data structure), containing methods (functions) and attributes (data).

2. **Object** : An instance of a class. When a class is defined, no memory is allocated until an object of that class is created.

3. **Encapsulation** : Bundling the data (attributes) and methods (functions) that operate on the data into a single unit or class. It restricts direct access to some of an object's components, which can prevent the accidental modification of data.

4. **Abstraction** : Simplifying complex reality by modeling classes appropriate to the problem, and working at the most relevant level of inheritance.

5. **Inheritance** : A mechanism where a new class inherits the properties and behaviors of an existing class. It supports the concept of hierarchical classification.

6. **Polymorphism** : The ability to present the same interface for different underlying forms (data types). For example, a single function name might work with different types of arguments.

### Example in C++

```cpp
#include <iostream>
using namespace std;

// Definition of the class
class Animal {
private:
    string name;
    int age;

public:
    // Constructor
    Animal(string n, int a) : name(n), age(a) {}

    // Method to display animal details
    void display() {
        cout << "Name: " << name << ", Age: " << age << endl;
    }

    // Setter for age
    void setAge(int a) {
        if (a > 0) {
            age = a;
        }
    }

    // Getter for age
    int getAge() {
        return age;
    }
};

int main() {
    // Creating objects
    Animal cat("Whiskers", 3);
    Animal dog("Buddy", 5);

    // Using methods
    cat.display();
    dog.display();

    // Modifying and accessing private attribute via setter and getter
    cat.setAge(4);
    cout << "Updated Age of Cat: " << cat.getAge() << endl;

    return 0;
}
```

### Explanation of the Example

1. **Class Definition** : 
   - `class Animal` defines a class named `Animal`.
   - The `private` section declares private attributes `name` and `age`.
   - The `public` section contains a constructor, methods `display`, `setAge`, and `getAge`.

2. **Encapsulation** :
   - Private attributes `name` and `age` are encapsulated within the class. They can't be accessed directly outside the class.
   - The methods `setAge` and `getAge` allow controlled access to the `age` attribute.

3. **Constructor** :
   - `Animal(string n, int a) : name(n), age(a)` is a constructor that initializes `name` and `age` when an object is created.

4. **Object Creation** :
   - `Animal cat("Whiskers", 3);` creates an `Animal` object named `cat` with `name` "Whiskers" and `age` 3.

5. **Method Usage** :
   - `cat.display();` calls the `display` method for the `cat` object, printing its details.

### Inheritance and Polymorphism Example

```cpp
#include <iostream>
using namespace std;

// Base class
class Animal {
protected:
    string name;

public:
    Animal(string n) : name(n) {}

    virtual void makeSound() {
        cout << "Some generic animal sound" << endl;
    }
};

// Derived class
class Cat : public Animal {
public:
    Cat(string n) : Animal(n) {}

    void makeSound() override {
        cout << name << " says: Meow" << endl;
    }
};

// Another derived class
class Dog : public Animal {
public:
    Dog(string n) : Animal(n) {}

    void makeSound() override {
        cout << name << " says: Woof" << endl;
    }
};

int main() {
    Animal *animal1 = new Cat("Whiskers");
    Animal *animal2 = new Dog("Buddy");

    animal1->makeSound(); // Calls Cat's makeSound
    animal2->makeSound(); // Calls Dog's makeSound

    delete animal1;
    delete animal2;

    return 0;
}
```

### Explanation of the Inheritance and Polymorphism Example

1. **Inheritance** :
   - `class Cat : public Animal` means `Cat` is a derived class that inherits from the base class `Animal`.
   - `class Dog : public Animal` is another derived class inheriting from `Animal`.

2. **Polymorphism** :
   - `virtual void makeSound()` in the `Animal` class allows the method to be overridden in derived classes.
   - `animal1->makeSound()` and `animal2->makeSound()` demonstrate polymorphism. The correct method (`makeSound`) for the actual object type (`Cat` or `Dog`) is called, even though the pointer is of type `Animal`.

## Procedural Vs. Object-Oriented Programming

### Procedural Programming

**Definition** : Procedural programming is a programming based on the concept of procedure calls, where statements are structured into procedures (also known as routines, subroutines, or functions).

**Key Characteristics** :

1. **Focus on Functions** : The main focus is on functions (procedures) which operate on data.
2. **Linear Approach** : Programs are usually written in a top-down linear approach.
3. **Global Data** : Data is often stored in global variables and shared among functions.
4. **Modularity** : Functions can be reused across different parts of the program, but there is less emphasis on encapsulating data.
5. **Examples of Languages** : C, Pascal, Fortran.

### Object-Oriented Programming

**Definition** : Object-oriented programming is a programming based on the concept of "objects", which can contain data and methods to manipulate that data.

**Key Characteristics** :

1. **Focus on Objects** : The main focus is on objects, which combine data and functions.
2. **Encapsulation** : Data and methods are bundled together in classes, which helps in hiding the internal state and requiring all interaction to be performed through an object's methods.
3. **Inheritance** : Classes can inherit properties and behavior from other classes.
4. **Polymorphism** : Objects can be treated as instances of their parent class rather than their actual class.
5. **Abstraction** : Helps in dealing with complex systems by breaking them into smaller, manageable pieces.
6. **Examples of Languages** : C++, Java, Python, Ruby.

### Comparison

| Aspect | Procedural Programming | Object-Oriented Programming |
|--------|------------------------|-----------------------------|
| **Basic Unit** | Function | Object |
| **Data Handling** | Global data modified by functions | Encapsulated within objects |
| **Approach** | Top-down | Bottom-up |
| **Code Reusability** | Achieved via functions | Achieved via inheritance and polymorphism |
| **Modularity** | Functions provide modularity | Classes and objects provide modularity |
| **Data Security** | Less secure; data is exposed to the whole program | More secure; data is encapsulated and hidden |
| **Ease of Maintenance** | Can become difficult as the program size grows | Easier to manage due to encapsulation and modularity |
| **Examples** | C, Pascal, Fortran | C++, Java, Python |

### Example to Illustrate the Differences

#### Procedural Programming Example (C)

```c
#include <stdio.h>

// Function prototypes
void displayPerson(const char *name, int age);

int main() {
    const char *name = "Alice";
    int age = 30;

    displayPerson(name, age);

    return 0;
}

// Function to display person's details
void displayPerson(const char *name, int age) {
    printf("Name: %s, Age: %d\n", name, age);
}
```

#### Object-Oriented Programming Example (C++)

```cpp
#include <iostream>
using namespace std;

// Class definition
class Person {
private:
    string name;
    int age;

public:
    // Constructor
    Person(string n, int a) : name(n), age(a) {}

    // Method to display person's details
    void display() {
        cout << "Name: " << name << ", Age: " << age << endl;
    }
};

int main() {
    // Creating an object of Person
    Person person("Alice", 30);

    // Using the object's method
    person.display();

    return 0;
}
```

### Strengths and Weaknesses

**Procedural Programming** :

- **Strengths** :
  - Simplicity and ease of understanding for smaller programs.
  - Effective for straightforward, linear tasks.
  - Lower overhead compared to OOP.

- **Weaknesses** :
  - Scalability issues for large, complex programs.
  - Poor data security due to global variables.
  - Difficult to manage and maintain as codebase grows.

**Object-Oriented Programming** :

- **Strengths** :
  - Better suited for complex, large-scale applications.
  - Improved data security through encapsulation.
  - Easier maintenance and modification.
  - Enhanced code reuse through inheritance and polymorphism.

- **Weaknesses** :
  - More complex and can have a steeper learning curve.
  - Can introduce overhead in terms of performance and memory.

### When to Use

- **Procedural Programming** is suitable for:
  - Small, simple programs.
  - Performance-critical applications where overhead should be minimal.
  - Applications where object-oriented features are not necessary.

- **Object-Oriented Programming** is suitable for:
  - Large, complex applications requiring modularity.
  - Programs that need frequent updates and maintenance.
  - Projects where code reuse and scalability are important.

## Principles of OOP

The principles of Object-Oriented Programming (OOP) include :

1. **Encapsulation**
2. **Abstraction**
3. **Inheritance**
4. **Polymorphism**

### 1. Encapsulation

**Encapsulation** is the practice of bundling data (attributes) and methods (functions) that operate on the data into a single unit or class. It also involves restricting access to certain components, which can prevent the accidental modification of data.

- **Purpose** : To protect the internal state of an object and promote modularity.
- **Implementation** : Use access specifiers like `private`, `protected`, and `public` to control access to class members.

**Example**:

```cpp
#include <iostream>
using namespace std;

class Person {
private:
    string name;
    int age;

public:
    // Constructor
    Person(string n, int a) : name(n), age(a) {}

    // Public method to access private data
    void display() {
        cout << "Name: " << name << ", Age: " << age << endl;
    }

    // Getter for age
    int getAge() {
        return age;
    }

    // Setter for age
    void setAge(int a) {
        if (a > 0) {
            age = a;
        }
    }
};

int main() {
    Person person("Alice", 30);
    person.display();
    person.setAge(31);
    cout << "Updated Age: " << person.getAge() << endl;
    return 0;
}
```

### 2. Abstraction

**Abstraction** is the concept of hiding the complex implementation details and showing only the essential features of the object. It allows a programmer to focus on interactions at a higher level without worrying about the intricate details.

- **Purpose** : To simplify complex systems by modeling classes appropriate to the problem.
- **Implementation** : Use abstract classes and interfaces.

**Example** :

```cpp
#include <iostream>
using namespace std;

// Abstract base class
class Shape {
public:
    // Pure virtual function
    virtual void draw() = 0;
};

class Circle : public Shape {
public:
    void draw() override {
        cout << "Drawing Circle" << endl;
    }
};

class Rectangle : public Shape {
public:
    void draw() override {
        cout << "Drawing Rectangle" << endl;
    }
};

int main() {
    Circle circle;
    Rectangle rectangle;

    circle.draw();
    rectangle.draw();

    return 0;
}
```

### 3. Inheritance

**Inheritance** is the mechanism by which one class (derived class) inherits the properties and behaviors of another class (base class). This allows for hierarchical classification and reuse of code.

- **Purpose** : To promote code reuse and establish a natural hierarchy between classes.
- **Implementation** : Use the `: public` keyword to derive a class from a base class.

**Example** :

```cpp
#include <iostream>
using namespace std;

class Animal {
public:
    void eat() {
        cout << "Eating..." << endl;
    }
};

class Dog : public Animal {
public:
    void bark() {
        cout << "Barking..." << endl;
    }
};

int main() {
    Dog dog;
    dog.eat();  // Inherited method
    dog.bark(); // Derived class method

    return 0;
}
```

### 4. Polymorphism

**Polymorphism** is the ability of different classes to be treated as instances of the same class through inheritance. It allows methods to do different things based on the object it is acting upon, even if they share the same name.

- **Purpose** : To allow one interface to be used for a general class of actions.
- **Implementation** : Use function overriding and virtual functions.

**Example**:

```cpp
#include <iostream>
using namespace std;

class Animal {
public:
    virtual void sound() {
        cout << "Some generic animal sound" << endl;
    }
};

class Dog : public Animal {
public:
    void sound() override {
        cout << "Woof" << endl;
    }
};

class Cat : public Animal {
public:
    void sound() override {
        cout << "Meow" << endl;
    }
};

int main() {
    Animal* a;
    Dog dog;
    Cat cat;

    a = &dog;
    a->sound();  // Outputs: Woof

    a = &cat;
    a->sound();  // Outputs: Meow

    return 0;
}
```

- **Encapsulation** : Bundles data and methods, controls access.
- **Abstraction** : Hides complexity, shows only essential features.
- **Inheritance** : Enables a class to inherit properties and behaviors from another class.
- **Polymorphism** : Allows for methods to be used interchangeably between different object types, depending on the context.

## Benefits & Applications of OOP

### Benefits of OOP

1. **Modularity** :
   - **Benefit** : OOP encourages modular code, where classes are self-contained. This modularity makes it easier to manage, understand, and debug code.
   - **Example** : Each class in a library management system (like `Book`, `Member`, `Library`) can be developed independently.

2. **Code Reuse through Inheritance** :
   - **Benefit** : Classes can inherit properties and behaviors from existing classes, promoting code reuse and reducing redundancy.
   - **Example** : In a graphical application, a base class `Shape` can have derived classes like `Circle`, `Square`, and `Triangle` that reuse the common properties and methods.

3. **Encapsulation** :
   - **Benefit** : Encapsulation hides the internal state of objects and only exposes necessary parts through methods. This promotes data integrity and security.
   - **Example** : In a banking system, the `Account` class can hide the balance data and provide methods like `deposit` and `withdraw` to interact with the balance.

4. **Maintenance and Flexibility** :
   - **Benefit** : OOP makes it easier to update and maintain the existing code. Changes in one part of the system can be made with minimal impact on other parts.
   - **Example** : Updating the `display` method in a `Product` class in an e-commerce application will automatically update the way products are displayed throughout the system.

5. **Polymorphism** :
   - **Benefit** : Polymorphism allows objects to be treated as instances of their parent class rather than their actual class. It simplifies code and enhances flexibility.
   - **Example** : A function that accepts a `Shape` object can work with any derived class like `Circle` or `Rectangle`, making it easier to extend with new shapes.

6. **Extensibility** :
   - **Benefit** : OOP systems can be extended with new functionalities without affecting existing system operations.
   - **Example** : Adding a new payment method class (`PayPal`, `CreditCard`) to an e-commerce application without changing the existing code.

### Applications of OOP

1. **Software Development** :
   - **Application** : Development of desktop applications, web applications, and mobile applications.
   - **Example** : Developing a word processor, web browser, or mobile app using OOP principles to manage different components and features.

2. **Game Development** :
   - **Application** : Creating complex and interactive games.
   - **Example** : Using classes to represent game objects (like `Player`, `Enemy`, `Obstacle`) and their interactions in a game engine.

3. **Graphical User Interface (GUI) Applications** :
   - **Application** : Building applications with graphical user interfaces.
   - **Example** : A GUI application for photo editing, where different tools (crop, resize, filter) are implemented as classes.

4. **Simulation and Modeling** :
   - **Application** : Simulating real-world systems and processes.
   - **Example** : Developing a traffic simulation system where cars, traffic lights, and roads are represented as objects.

5. **Data Analysis and Machine Learning** :
   - **Application** : Implementing machine learning algorithms and data analysis tools.
   - **Example** : Using OOP to create classes for different machine learning models (like `LinearRegression`, `DecisionTree`) and data preprocessing methods.

6. **Embedded Systems** :
   - **Application** : Developing software for embedded systems and hardware devices.
   - **Example** : Using OOP to manage different components of an embedded system like sensors, actuators, and communication interfaces.

7. **Enterprise Applications** :
   - **Application** : Building large-scale business applications.
   - **Example** : Enterprise Resource Planning (ERP) systems, Customer Relationship Management (CRM) systems, where different modules (like `Sales`, `Inventory`, `HR`) are implemented as classes.

### Benefits & Applications

- **Benefits** :
  - Modularity
  - Code reuse through inheritance
  - Encapsulation
  - Maintenance and flexibility
  - Polymorphism
  - Extensibility

- **Applications** :
  - Software development (desktop, web, mobile)
  - Game development
  - GUI applications
  - Simulation and modeling
  - Data analysis and machine learning
  - Embedded systems
  - Enterprise applications

# C++ Basics

## Overview

### Introduction to C++

**C++** is a general-purpose programming language created by Bjarne Stroustrup as an extension of the C programming language.

It supports both procedural and object-oriented programming, making it a versatile language for various types of software development.

### Basic Syntax and Structure

```cpp
#include <iostream>  // Preprocessor directive to include the iostream library

int main() {  // Main function where program execution begins
    std::cout << "Hello, World!" << std::endl;  // Output to the console
    return 0;  // Indicate that the program ended successfully
}
```

### Key Concepts

1. **Data Types** :
   - **Basic Types** : `int`, `char`, `float`, `double`
   - **Derived Types** : Arrays, pointers, references
   - **User-Defined Types** : `struct`, `class`, `enum`

2. **Variables** :
   - Variables are containers for storing data values.
   - Example : `int age = 21;`

3. **Operators** :
   - Arithmetic Operators : `+`, `-`, `*`, `/`, `%`
   - Comparison Operators : `==`, `!=`, `>`, `<`, `>=`, `<=`
   - Logical Operators : `&&`, `||`, `!`
   - Assignment Operators : `=`, `+=`, `-=`, `*=`, `/=`

4. **Control Structures** :
   - **Conditional Statements** : `if`, `else if`, `else`, `switch`
   - **Loops** : `for`, `while`, `do-while`

5. **Functions** :
   - Functions are blocks of code that perform a specific task.
   - Syntax :
     ```cpp
     returnType functionName(parameters) {
         // function body
     }
     ```
   - Example :
     ```cpp
     int add(int a, int b) {
         return a + b;
     }
     ```

6. **Arrays** :
   - Arrays are collections of elements of the same type.
   - Example :
     ```cpp
     int numbers[5] = {1, 2, 3, 4, 5};
     ```

7. **Pointers** :
   - Pointers are variables that store the memory address of another variable.
   - Example :
     ```cpp
     int x = 10;
     int* p = &x;  // Pointer to x
     ```

8. **Classes and Objects** :
   - **Class** : A blueprint for creating objects (a particular data structure).
   - **Object** : An instance of a class.
   - Example :
     ```cpp
     class Car {
     public:
         string brand;
         string model;
         int year;

         void display() {
             cout << brand << " " << model << " " << year << endl;
         }
     };

     int main() {
         Car car1;
         car1.brand = "Toyota";
         car1.model = "Corolla";
         car1.year = 2020;
         car1.display();
         return 0;
     }
     ```

### Input/Output

- **Input** : Using `std::cin` to get user input.
  ```cpp
  int age;
  std::cout << "Enter your age: ";
  std::cin >> age;
  ```

- **Output** : Using `std::cout` to display output.
  ```cpp
  std::cout << "You entered: " << age << std::endl;
  ```

### Example Program

```cpp
#include <iostream>
using namespace std;

// Function declaration
int add(int a, int b) {
    return a + b;
}

int main() {
    // Variable declaration and initialization
    int num1, num2, sum;

    // User input
    cout << "Enter two numbers: ";
    cin >> num1 >> num2;

    // Function call
    sum = add(num1, num2);

    // Output the result
    cout << "Sum: " << sum << endl;

    return 0;
}
```

- **Basic Structure** : Understanding the main function and including headers.
- **Data Types** : Knowing basic, derived, and user-defined data types.
- **Variables and Operators** : Declaring variables and using operators for arithmetic, comparison, and logical operations.
- **Control Structures** : Using `if`, `switch`, `for`, `while`, and `do-while` for controlling the flow of the program.
- **Functions** : Writing reusable blocks of code.
- **Arrays and Pointers** : Working with collections of data and memory addresses.
- **Classes and Objects** : Encapsulating data and behavior using object-oriented principles.
- **Input/Output** : Using `std::cin` and `std::cout` for user interaction.

## Program Structure

The structure of a C++ program follows a specific order and convention to ensure the code is well-organized and readable.

### Basic Structure of a C++ Program

1. **Preprocessor Directives**
2. **Namespace Declaration**
3. **Function Prototypes (Optional)**
4. **Main Function**
5. **Function Definitions**

### Example Program

```cpp
#include <iostream>  // Preprocessor directive to include the standard input-output stream library

using namespace std;  // Namespace declaration

// Function prototype
void greet();

int main() {
    // Variable declaration and initialization
    int num1, num2, sum;

    // User input
    cout << "Enter two numbers: ";
    cin >> num1 >> num2;

    // Calculate sum
    sum = num1 + num2;

    // Output the result
    cout << "Sum: " << sum << endl;

    // Calling a user-defined function
    greet();

    return 0;  // Indicate successful program termination
}

// Function definition
void greet() {
    cout << "Hello, welcome to C++ programming!" << endl;
}
```

### Detailed Explanation

1. **Preprocessor Directives** :
   - Preprocessor directives are instructions to the preprocessor, which runs before the actual compilation process begins.
   - Commonly used to include standard or user-defined libraries using the `#include` directive.
   - Example : `#include <iostream>`

2. **Namespace Declaration** :
   - C++ uses namespaces to avoid name conflicts in large projects.
   - The `std` namespace is commonly used for the Standard Library.
   - Example : `using namespace std;`

3. **Function Prototypes** :
   - Function prototypes declare functions before they are used.
   - This informs the compiler about the function's return type and parameters.
   - Optional but useful for organization and readability, especially in larger programs.
   - Example : `void greet();`

4. **Main Function** :
   - The `main` function is the entry point of a C++ program where execution begins.
   - Every C++ program must have exactly one `main` function.
   - Example :
     ```cpp
     int main() {
         // Code to be executed
         return 0;
     }
     ```

5. **Function Definitions** :
   - Functions are defined with a return type, a name, and parameters (if any).
   - The function body contains the code to be executed when the function is called.
   - Example :
     ```cpp
     void greet() {
         cout << "Hello, welcome to C++ programming!" << endl;
     }
     ```

### Additional Components in C++ Program Structure

1. **Comments** :
   - Comments are used to explain the code and are ignored by the compiler.
   - Single-line comments : `// This is a comment`
   - Multi-line comments : `/* This is a multi-line comment */`

2. **Global Variables** :
   - Variables declared outside any function and accessible from any part of the program.
   - Example :
     ```cpp
     int globalVar = 10;  // Global variable
     ```

3. **Header Files** :
   - Header files contain declarations of functions, classes, and variables which can be used across multiple files.
   - Typically have a `.h` or `.hpp` extension.
   - Example:
     ```cpp
     // contents of myHeader.h
     void myFunction();
     ```

4. **Classes and Objects** :
   - In object-oriented programs, classes are used to define blueprints for objects.
   - Classes encapsulate data and functions that operate on the data.
   - Example :
     ```cpp
     class MyClass {
     public:
         int myVar;
         void myMethod() {
             cout << "Hello from MyClass!" << endl;
         }
     };
     ```

### Example Program with Classes

```cpp
#include <iostream>
using namespace std;

class Calculator {  // Class definition
public:
    int add(int a, int b) {  // Member function
        return a + b;
    }
};

int main() {
    Calculator calc;  // Creating an object of Calculator
    int num1, num2, sum;

    // User input
    cout << "Enter two numbers: ";
    cin >> num1 >> num2;

    // Using class method to calculate sum
    sum = calc.add(num1, num2);

    // Output the result
    cout << "Sum: " << sum << endl;

    return 0;
}
```

- **Preprocessor Directives** : Include necessary libraries.
- **Namespace Declaration** : Avoid name conflicts.
- **Function Prototypes** : Declare functions before use (optional but useful).
- **Main Function**: Entry point of the program.
- **Function Definitions** : Define the behavior of the functions.
- **Comments** : Explain the code.
- **Global Variables** : Define variables accessible throughout the program.
- **Classes and Objects** : Encapsulate data and functions using object-oriented principles.

## Namespace

- Namespaces in C++ are a way to group named entities like classes, objects, and functions under a single name.
- They are used to organize code and prevent name conflicts, especially in larger projects where multiple libraries might have functions or variables with the same name.

### Introduction to Namespaces

The `namespace` keyword is used to define a namespace. Here’s a simple example to illustrate the concept:

```cpp
#include <iostream>

namespace MyNamespace {
    void myFunction() {
        std::cout << "Hello from MyNamespace!" << std::endl;
    }
}

int main() {
    MyNamespace::myFunction();  // Accessing the function using the namespace
    return 0;
}
```

### Key Points about Namespaces

1. **Definition**:
   - Namespaces are defined using the `namespace` keyword.
   - Example:
     ```cpp
     namespace MyNamespace {
         // Declarations and definitions
     }
     ```

2. **Accessing Members**:
   - Members of a namespace are accessed using the scope resolution operator `::`.
   - Example:
     ```cpp
     MyNamespace::myFunction();
     ```

3. **Nested Namespaces**:
   - Namespaces can be nested inside other namespaces.
   - Example:
     ```cpp
     namespace OuterNamespace {
         namespace InnerNamespace {
             void innerFunction() {
                 std::cout << "Hello from InnerNamespace!" << std::endl;
             }
         }
     }

     int main() {
         OuterNamespace::InnerNamespace::innerFunction();
         return 0;
     }
     ```

4. **Using Directive**:
   - The `using` directive brings all members of a namespace into the current scope, eliminating the need to prefix them with the namespace name.
   - Example:
     ```cpp
     using namespace MyNamespace;
     
     int main() {
         myFunction();  // No need for MyNamespace:: prefix
         return 0;
     }
     ```

5. **Using Declaration**:
   - The `using` declaration brings specific members of a namespace into the current scope.
   - Example:
     ```cpp
     using MyNamespace::myFunction;
     
     int main() {
         myFunction();  // No need for MyNamespace:: prefix
         return 0;
     }
     ```

### Example with Multiple Namespaces

```cpp
#include <iostream>

namespace NamespaceA {
    void printMessage() {
        std::cout << "Hello from NamespaceA!" << std::endl;
    }
}

namespace NamespaceB {
    void printMessage() {
        std::cout << "Hello from NamespaceB!" << std::endl;
    }
}

int main() {
    NamespaceA::printMessage();  // Accessing printMessage from NamespaceA
    NamespaceB::printMessage();  // Accessing printMessage from NamespaceB

    using NamespaceA::printMessage;  // Bringing NamespaceA's printMessage into scope
    printMessage();  // Calls NamespaceA's printMessage

    return 0;
}
```

### Avoiding Name Conflicts

Namespaces are particularly useful for avoiding name conflicts. For example, if you have two libraries that both define a `log` function, you can place each `log` function in a different namespace to avoid conflicts:

```cpp
#include <iostream>

namespace LibraryA {
    void log() {
        std::cout << "Log from LibraryA" << std::endl;
    }
}

namespace LibraryB {
    void log() {
        std::cout << "Log from LibraryB" << std::endl;
    }
}

int main() {
    LibraryA::log();  // Calls log from LibraryA
    LibraryB::log();  // Calls log from LibraryB

    return 0;
}
```
- **Namespaces** group related functions, classes, and variables.
- **Scope Resolution Operator (`::`)** is used to access members of a namespace.
- **Nested Namespaces** allow hierarchical grouping of related functionality.
- **Using Directive** (`using namespace`) and **Using Declaration** (`using`) simplify access to namespace members.
- **Avoid Name Conflicts** by placing entities in different namespaces.

## Identifiers

- identifiers are names used to identify variables, functions, classes, objects, arrays, and other user-defined items.
- An identifier is a sequence of characters that can include letters, digits, and underscores.
- Identifiers are essential for giving meaningful names to the various elements in your program.

### Rules for Identifiers

1. **Start with a Letter or Underscore** :
   - Identifiers must begin with a letter (a-z, A-Z) or an underscore (_).
   - Subsequent characters can be letters, digits (0-9), or underscores.
   - Examples : `variableName`, `_temp`, `count1`

2. **Case Sensitivity** :
   - Identifiers in C++ are case-sensitive, meaning `Variable` and `variable` are considered different identifiers.

3. **No Reserved Keywords** :
   - Identifiers cannot be the same as C++ reserved keywords (e.g., `int`, `class`, `return`, etc.).
   - Example of reserved keywords : `if`, `else`, `while`, `for`, `switch`, `case`, `default`, `break`, `continue`, `return`, `struct`, `class`, `public`, `private`, `protected`, `virtual`, `const`, `void`, `static`, `using`, `namespace`, `new`, `delete`, `try`, `catch`, `throw`, `include`, `define`, `sizeof`, `typedef`, `typename`.

### Best Practices for Naming Identifiers

1. **Descriptive Names** :
   - Use descriptive names to make your code more readable and maintainable.
   - Example : Use `totalScore` instead of `ts`.

2. **Camel Case and Snake Case** :
   - Common naming conventions include camel case (`camelCaseExample`) and snake case (`snake_case_example`).
   - Camel case is often used for variable and function names.
   - Snake case is sometimes used for constants.

3. **Consistent Naming Conventions** :
   - Use consistent naming conventions throughout your code to maintain readability.
   - Example : If you use camel case for variable names, use it consistently.

4. **Avoid Single-Letter Names** :
   - Except for loop counters (`i`, `j`, `k`), avoid using single-letter names.
   - Example : Use `index` instead of `i` for a non-loop variable.

### Examples of Valid and Invalid Identifiers

**Valid Identifiers** :
```cpp
int age;
double totalAmount;
char firstLetter;
int _counter;
float averageScore1;
```

**Invalid Identifiers** :
```cpp
int 1stPlace;      // Cannot start with a digit
double total-amount; // Cannot contain hyphens
char class;        // Cannot use reserved keyword
int float;         // Cannot use reserved keyword
float total amount; // Cannot contain spaces
```

### Example Program

```cpp
#include <iostream>
using namespace std;

int main() {
    // Valid identifiers
    int age = 21;
    double totalAmount = 345.50;
    char firstLetter = 'A';
    int _counter = 0;
    float averageScore = 87.5;

    // Output the values
    cout << "Age: " << age << endl;
    cout << "Total Amount: $" << totalAmount << endl;
    cout << "First Letter: " << firstLetter << endl;
    cout << "Counter: " << _counter << endl;
    cout << "Average Score: " << averageScore << endl;

    return 0;
}
```

- **Identifiers** are names for variables, functions, classes, etc.
- **Rules**: Must start with a letter or underscore, case-sensitive, cannot use reserved keywords.
- **Best Practices**: Use descriptive names, consistent naming conventions, avoid single-letter names (except for loop counters).
- **Examples**: Provided examples of valid and invalid identifiers.

## Variables

- Variables are used to store data that your program can manipulate.
- Each variable has a specific type that determines the kind of data it can hold, such as integers, floating-point numbers, characters, etc.

### Declaring and Initializing Variables

1. **Declaration** :
   - To declare a variable, you specify its type followed by its name.
   - Syntax : `type variableName;`
   - Example :
     ```cpp
     int age;
     double salary;
     char grade;
     ```

2. **Initialization** :
   - You can initialize a variable at the time of declaration.
   - Syntax : `type variableName = value;`
   - Example :
     ```cpp
     int age = 21;
     double salary = 50000.50;
     char grade = 'A';
     ```

### Basic Data Types

- **int** : Stores integers (whole numbers).
  ```cpp
  int number = 10;
  ```

- **float** : Stores single-precision floating-point numbers.
  ```cpp
  float temperature = 36.6f;
  ```

- **double** : Stores double-precision floating-point numbers.
  ```cpp
  double pi = 3.14159;
  ```

- **char** : Stores single characters.
  ```cpp
  char initial = 'A';
  ```

- **bool** : Stores boolean values (`true` or `false`).
  ```cpp
  bool isValid = true;
  ```

### Example Program

```cpp
#include <iostream>
using namespace std;

int main() {
    // Variable declaration and initialization
    int age = 21;
    double salary = 50000.50;
    char grade = 'A';
    bool isEmployee = true;

    // Output the values
    cout << "Age: " << age << endl;
    cout << "Salary: $" << salary << endl;
    cout << "Grade: " << grade << endl;
    cout << "Is Employee: " << (isEmployee ? "Yes" : "No") << endl;

    return 0;
}
```

### Variable Scope

The scope of a variable is the region of the program where it can be accessed. There are three main types of scope in C++ :

1. **Local Scope** :
   - Variables declared inside a function or a block have local scope.
   - Example :
     ```cpp
     void myFunction() {
         int x = 10;  // Local variable
         cout << x << endl;
     }
     ```

2. **Global Scope** :
   - Variables declared outside all functions have global scope and can be accessed from any function.
   - Example :
     ```cpp
     int x = 10;  // Global variable

     void myFunction() {
         cout << x << endl;  // Accessing global variable
     }
     ```

3. **Class Scope** :
   - Variables declared inside a class are called member variables and have class scope.
   - Example :
     ```cpp
     class MyClass {
     public:
         int x;  // Member variable
         void display() {
             cout << x << endl;  // Accessing member variable
         }
     };
     ```

### Variable Types

- **Constant Variables** : Declared using the `const` keyword, their values cannot be changed after initialization.
  ```cpp
  const int MAX_AGE = 100;
  ```

- **Static Variables** : Retain their values between function calls and are initialized only once.
  ```cpp
  void myFunction() {
      static int count = 0;  // Static variable
      count++;
      cout << count << endl;
  }
  ```

### Example Program with Scope

```cpp
#include <iostream>
using namespace std;

int globalVar = 100;  // Global variable

void demoFunction() {
    static int staticVar = 0;  // Static variable
    int localVar = 10;         // Local variable

    cout << "Global Variable: " << globalVar << endl;
    cout << "Static Variable: " << ++staticVar << endl;
    cout << "Local Variable: " << localVar << endl;
}

int main() {
    demoFunction();
    demoFunction();  // Static variable retains its value

    return 0;
}
```

- **Declaration and Initialization** : Define the type and name, optionally assign a value.
- **Basic Data Types** : `int`, `float`, `double`, `char`, `bool`.
- **Variable Scope** : Local, global, and class scope.
- **Special Variables** : `const` for constants, `static` for static variables.
- **Best Practices** : Use meaningful names, maintain proper scope, initialize variables.

## Constants

- Constants are variables whose values cannot be changed once they are initialized.
- They are useful for values that need to remain constant throughout the program, providing clarity and preventing accidental modification.

### Defining Constants

1. **Using the `const` Keyword**
2. **Using the `#define` Preprocessor Directive**
3. **Using `constexpr` (C++11 and later)**

### 1. Using the `const` Keyword

- The `const` keyword is used to define constant variables.
- These variables must be initialized at the time of declaration.

```cpp
#include <iostream>
using namespace std;

int main() {
    const int MAX_AGE = 100;
    const double PI = 3.14159;
    const char GRADE = 'A';

    cout << "Max Age: " << MAX_AGE << endl;
    cout << "PI: " << PI << endl;
    cout << "Grade: " << GRADE << endl;

    // Uncommenting the following lines will cause a compilation error
    // MAX_AGE = 110;
    // PI = 3.14;

    return 0;
}
```

### 2. Using the `#define` Preprocessor Directive

The `#define` directive is used to define constant values. It is a preprocessor directive, which means the substitution happens before the actual compilation of the code.

```cpp
#include <iostream>
using namespace std;

#define MAX_AGE 100
#define PI 3.14159
#define GRADE 'A'

int main() {
    cout << "Max Age: " << MAX_AGE << endl;
    cout << "PI: " << PI << endl;
    cout << "Grade: " << GRADE << endl;

    // Uncommenting the following lines will not cause a compilation error but will lead to unexpected behavior
    // #define MAX_AGE 110
    // #define PI 3.14

    return 0;
}
```

### 3. Using `constexpr` (C++11 and Later)

- The `constexpr` keyword is used to define constants that are evaluated at compile-time.
- This can be more powerful than `const` because it ensures that the value is constant and allows for some compile-time optimizations.

```cpp
#include <iostream>
using namespace std;

constexpr int MAX_AGE = 100;
constexpr double PI = 3.14159;
constexpr char GRADE = 'A';

int main() {
    cout << "Max Age: " << MAX_AGE << endl;
    cout << "PI: " << PI << endl;
    cout << "Grade: " << GRADE << endl;

    // Uncommenting the following lines will cause a compilation error
    // MAX_AGE = 110;
    // PI = 3.14;

    return 0;
}
```

### Differences Between `const`, `#define`, and `constexpr`

- **`const`**:
  - Type-safe : The type is checked by the compiler.
  - Scoped : Follows the scope rules of C++.
  - Can be used with any data type.

- **`#define`** :
  - Not type-safe : The preprocessor simply replaces the defined name with the value.
  - No scope : It is globally replaced throughout the code.
  - Typically used for simple constant values.

- **`constexpr`** :
  - Ensures compile-time evaluation.
  - Type-safe : The type is checked by the compiler.
  - Scoped : Follows the scope rules of C++.
  - Introduced in C++11, more powerful for compile-time constants.

### Example with Class Constants

Constants can also be defined within classes using the `const` or `constexpr` keywords :

```cpp
#include <iostream>
using namespace std;

class Circle {
public:
    static constexpr double PI = 3.14159;
    double radius;

    Circle(double r) : radius(r) {}

    double getArea() const {
        return PI * radius * radius;
    }
};

int main() {
    Circle circle(5.0);
    cout << "Area of circle: " << circle.getArea() << endl;

    return 0;
}
```

- **Constants** are variables whose values cannot be changed once initialized.
- **`const` Keyword** : Defines constant variables, type-safe, and follows scope rules.
- **`#define` Directive** : Preprocessor directive, not type-safe, globally replaced.
- **`constexpr` Keyword** : Ensures compile-time evaluation, type-safe, introduced in C++11.
- **Class Constants** : Constants can be defined within classes using `const` or `constexpr`.

## Enum

- An `enum` (short for "enumeration") is a user-defined type that consists of a set of named integral constants.
- Enums are used to represent a collection of related values in a way that makes the code more readable and maintainable.
- They provide a way to define and group a set of constant values under a single type name.

### Basic Syntax of `enum`

```cpp
enum EnumName {
    ENUM_VALUE1,
    ENUM_VALUE2,
    ENUM_VALUE3,
    // ...
};
```

### Example of an Enumeration

```cpp
#include <iostream>
using namespace std;

enum Color {
    RED,
    GREEN,
    BLUE
};

int main() {
    Color myColor = RED;

    if (myColor == RED) {
        cout << "The color is red." << endl;
    }

    return 0;
}
```

### Key Points about Enums

1. **Default Values** :
   - By default, the values of the enumerators start from 0 and increase by 1.
   - In the above example, `RED` is 0, `GREEN` is 1, and `BLUE` is 2.

2. **Custom Values** :
   - You can assign custom values to enumerators.
   - Example :
     ```cpp
     enum Days {
         MONDAY = 1,
         TUESDAY,
         WEDNESDAY,
         THURSDAY = 10,
         FRIDAY,
         SATURDAY,
         SUNDAY
     };
     ```
     In this example, `MONDAY` is 1, `TUESDAY` is 2, `WEDNESDAY` is 3, `THURSDAY` is 10, `FRIDAY` is 11, `SATURDAY` is 12, and `SUNDAY` is 13.

3. **Scoped Enums (C++11 and later)** :
   - Scoped enums provide better type safety and avoid pollution of the global namespace.
   - Defined using the `enum class` keyword.
   - Example :
     ```cpp
     enum class Color {
         RED,
         GREEN,
         BLUE
     };

     int main() {
         Color myColor = Color::RED;

         if (myColor == Color::RED) {
             cout << "The color is red." << endl;
         }

         return 0;
     }
     ```
   - In scoped enums, enumerator names are accessed using the scope operator (`::`).

4. **Underlying Type** :
   - The underlying type of an enum can be specified explicitly.
   - Example :
     ```cpp
     enum class Color : char {
         RED = 'R',
         GREEN = 'G',
         BLUE = 'B'
     };
     ```

### Example Programs

#### Basic Enum Example

```cpp
#include <iostream>
using namespace std;

enum Direction {
    NORTH,
    EAST,
    SOUTH,
    WEST
};

int main() {
    Direction myDirection = SOUTH;

    switch (myDirection) {
        case NORTH:
            cout << "Going North" << endl;
            break;
        case EAST:
            cout << "Going East" << endl;
            break;
        case SOUTH:
            cout << "Going South" << endl;
            break;
        case WEST:
            cout << "Going West" << endl;
            break;
    }

    return 0;
}
```

#### Scoped Enum Example

```cpp
#include <iostream>
using namespace std;

enum class TrafficLight {
    RED,
    YELLOW,
    GREEN
};

int main() {
    TrafficLight light = TrafficLight::GREEN;

    switch (light) {
        case TrafficLight::RED:
            cout << "Stop!" << endl;
            break;
        case TrafficLight::YELLOW:
            cout << "Caution!" << endl;
            break;
        case TrafficLight::GREEN:
            cout << "Go!" << endl;
            break;
    }

    return 0;
}
```

- **Enums** : Define a set of named integral constants.
- **Basic Enums** : Use the `enum` keyword.
- **Default Values** : Start from 0 and increment by 1.
- **Custom Values** : Can be assigned to enumerators.
- **Scoped Enums (C++11)** : Use `enum class` for better type safety.
- **Underlying Type** : Can be specified for enums.

## Operators

Operators in C++ are symbols that perform operations on variables and values.

### Types of Operators

1. **Arithmetic Operators**
2. **Relational Operators**
3. **Logical Operators**
4. **Bitwise Operators**
5. **Assignment Operators**
6. **Increment and Decrement Operators**
7. **Conditional (Ternary) Operator**
8. **Comma Operator**
9. **Type Cast Operator**
10. **Sizeof Operator**

### 1. Arithmetic Operators

Arithmetic operators are used to perform mathematical operations.

- **Addition (`+`)**
  ```cpp
  int a = 10, b = 20;
  int sum = a + b;  // sum = 30
  ```

- **Subtraction (`-`)**
  ```cpp
  int diff = a - b;  // diff = -10
  ```

- **Multiplication (`*`)**
  ```cpp
  int prod = a * b;  // prod = 200
  ```

- **Division (`/`)**
  ```cpp
  int quotient = b / a;  // quotient = 2
  ```

- **Modulus (`%`)** (Remainder)
  ```cpp
  int remainder = b % a;  // remainder = 0
  ```

### 2. Relational Operators

Relational operators are used to compare two values.

- **Equal to (`==`)**
  ```cpp
  bool isEqual = (a == b);  // isEqual = false
  ```

- **Not equal to (`!=`)**
  ```cpp
  bool isNotEqual = (a != b);  // isNotEqual = true
  ```

- **Greater than (`>`)**
  ```cpp
  bool isGreater = (a > b);  // isGreater = false
  ```

- **Less than (`<`)**
  ```cpp
  bool isLess = (a < b);  // isLess = true
  ```

- **Greater than or equal to (`>=`)**
  ```cpp
  bool isGreaterOrEqual = (a >= b);  // isGreaterOrEqual = false
  ```

- **Less than or equal to (`<=`)**
  ```cpp
  bool isLessOrEqual = (a <= b);  // isLessOrEqual = true
  ```

### 3. Logical Operators

Logical operators are used to perform logical operations.

- **Logical AND (`&&`)**
  ```cpp
  bool result = (a < b && b > 0);  // result = true
  ```

- **Logical OR (`||`)**
  ```cpp
  bool result = (a > b || b > 0);  // result = true
  ```

- **Logical NOT (`!`)**
  ```cpp
  bool result = !(a > b);  // result = true
  ```

### 4. Bitwise Operators

Bitwise operators perform bit-level operations.

- **AND (`&`)**
  ```cpp
  int result = a & b;  // result = 0 (binary: 1010 & 10100 = 00000)
  ```

- **OR (`|`)**
  ```cpp
  int result = a | b;  // result = 30 (binary: 1010 | 10100 = 11110)
  ```

- **XOR (`^`)**
  ```cpp
  int result = a ^ b;  // result = 30 (binary: 1010 ^ 10100 = 11110)
  ```

- **NOT (`~`)**
  ```cpp
  int result = ~a;  // result = -11 (binary: ~1010 = 0101 in 2's complement form)
  ```

- **Left Shift (`<<`)**
  ```cpp
  int result = a << 1;  // result = 20 (binary: 1010 << 1 = 10100)
  ```

- **Right Shift (`>>`)**
  ```cpp
  int result = a >> 1;  // result = 5 (binary: 1010 >> 1 = 0101)
  ```

### 5. Assignment Operators

Assignment operators are used to assign values to variables.

- **Simple Assignment (`=`)**
  ```cpp
  int x = 10;
  ```

- **Add and Assign (`+=`)**
  ```cpp
  x += 5;  // x = x + 5; x = 15
  ```

- **Subtract and Assign (`-=`)**
  ```cpp
  x -= 3;  // x = x - 3; x = 12
  ```

- **Multiply and Assign (`*=`)**
  ```cpp
  x *= 2;  // x = x * 2; x = 24
  ```

- **Divide and Assign (`/=`)**
  ```cpp
  x /= 4;  // x = x / 4; x = 6
  ```

- **Modulus and Assign (`%=`)**
  ```cpp
  x %= 4;  // x = x % 4; x = 2
  ```

### 6. Increment and Decrement Operators

These operators are used to increase or decrease the value of a variable by one.

- **Increment (`++`)**
  ```cpp
  int y = 5;
  y++;  // y = 6
  ++y;  // y = 7
  ```

- **Decrement (`--`)**
  ```cpp
  y--;  // y = 6
  --y;  // y = 5
  ```

### 7. Conditional (Ternary) Operator

The ternary operator is a shorthand for the `if-else` statement.

- **Syntax** : `condition ? expression1 : expression2`
  ```cpp
  int a = 10, b = 20;
  int max = (a > b) ? a : b;  // max = 20
  ```

### 8. Comma Operator

- The comma operator is used to separate expressions.
- The value of the comma operator is the value of the last expression.

```cpp
int x, y;
x = (y = 3, y + 2);  // x = 5
```

### 9. Type Cast Operator

The type cast operator converts a variable from one type to another.

- **C-style Cast**
  ```cpp
  double pi = 3.14159;
  int intPi = (int)pi;  // intPi = 3
  ```

- **C++-style Cast**
  ```cpp
  int intPi = static_cast<int>(pi);  // intPi = 3
  ```

### 10. Sizeof Operator

The `sizeof` operator returns the size of a variable or data type in bytes.

```cpp
int x = 10;
cout << sizeof(x) << endl;  // Outputs the size of int in bytes
cout << sizeof(int) << endl;  // Outputs the size of int in bytes
```

- **Arithmetic Operators** : `+`, `-`, `*`, `/`, `%`
- **Relational Operators** : `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Logical Operators** : `&&`, `||`, `!`
- **Bitwise Operators** : `&`, `|`, `^`, `~`, `<<`, `>>`
- **Assignment Operators** : `=`, `+=`, `-=`, `*=`, `/=`, `%=`
- **Increment/Decrement** : `++`, `--`
- **Conditional Operator** : `? :`
- **Comma Operator** : `,`
- **Type Cast Operator** : `(type)`, `static_cast<type>(variable)`
- **Sizeof Operator** : `sizeof`

## Typecasting

- Typecasting in C++ is the process of converting one data type to another.
- There are different types of typecasting in C++, and understanding each type helps in writing clear and efficient code.

### Types of Typecasting

1. **Implicit Typecasting (Automatic Type Conversion)**
2. **Explicit Typecasting (Manual Type Conversion)**
   - C-style Cast
   - Function-style Cast
   - `static_cast`
   - `dynamic_cast`
   - `const_cast`
   - `reinterpret_cast`

### 1. Implicit Typecasting (Automatic Type Conversion)

Implicit typecasting is performed automatically by the compiler when a value of one data type is assigned to a variable of another compatible data type.

Example :
```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 42;
    double b = a;  // Implicit conversion from int to double

    cout << "a = " << a << endl;  // Output: a = 42
    cout << "b = " << b << endl;  // Output: b = 42.0

    return 0;
}
```

### 2. Explicit Typecasting (Manual Type Conversion)

- Explicit typecasting is performed manually by the programmer using casting operators.
- This is necessary when implicit type conversion is not possible or desired.

#### C-style Cast

Syntax : `(type)expression` or `type(expression)`

Example :
```cpp
#include <iostream>
using namespace std;

int main() {
    double pi = 3.14159;
    int intPi = (int)pi;  // C-style cast

    cout << "pi = " << pi << endl;  // Output: pi = 3.14159
    cout << "intPi = " << intPi << endl;  // Output: intPi = 3

    return 0;
}
```

#### Function-style Cast

Syntax : `type(expression)`

Example :
```cpp
#include <iostream>
using namespace std;

int main() {
    double pi = 3.14159;
    int intPi = int(pi);  // Function-style cast

    cout << "pi = " << pi << endl;  // Output: pi = 3.14159
    cout << "intPi = " << intPi << endl;  // Output: intPi = 3

    return 0;
}
```

#### `static_cast`

- `static_cast` is used for most type conversions that are well-defined and can be checked at compile time.
- It is safer than C-style cast.

Syntax : `static_cast<type>(expression)`

Example :
```cpp
#include <iostream>
using namespace std;

int main() {
    double pi = 3.14159;
    int intPi = static_cast<int>(pi);  // static_cast

    cout << "pi = " << pi << endl;  // Output: pi = 3.14159
    cout << "intPi = " << intPi << endl;  // Output: intPi = 3

    return 0;
}
```

#### `dynamic_cast`

- `dynamic_cast` is used for safely downcasting in inheritance hierarchies.
- It requires the presence of polymorphism, i.e., at least one virtual function in the base class.
- It performs runtime checks and can return `nullptr` if the cast is invalid.

Syntax : `dynamic_cast<type>(expression)`

Example :
```cpp
#include <iostream>
using namespace std;

class Base {
public:
    virtual void show() {
        cout << "Base class" << endl;
    }
};

class Derived : public Base {
public:
    void show() override {
        cout << "Derived class" << endl;
    }
};

int main() {
    Base* basePtr = new Derived;
    Derived* derivedPtr = dynamic_cast<Derived*>(basePtr);

    if (derivedPtr != nullptr) {
        derivedPtr->show();  // Output: Derived class
    } else {
        cout << "Invalid cast" << endl;
    }

    delete basePtr;
    return 0;
}
```

#### `const_cast`

`const_cast` is used to add or remove the `const` qualifier from a variable.

Syntax : `const_cast<type>(expression)`

Example :
```cpp
#include <iostream>
using namespace std;

void print(const int* value) {
    int* modifiableValue = const_cast<int*>(value);
    *modifiableValue = 100;
    cout << "Modified value: " << *value << endl;
}

int main() {
    const int num = 10;
    print(&num);  // Output: Modified value: 100

    return 0;
}
```

#### `reinterpret_cast`

- `reinterpret_cast` is used for low-level reinterpreting of bit patterns.
- It can cast any pointer type to any other pointer type.
- It is dangerous and should be used sparingly.

Syntax : `reinterpret_cast<type>(expression)`

Example :
```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 65;
    char* charPtr = reinterpret_cast<char*>(&num);

    cout << "num: " << num << endl;  // Output: num: 65
    cout << "charPtr: " << *charPtr << endl;  // Output: charPtr: A (ASCII code of 65)

    return 0;
}
```

- **Implicit Typecasting** : Automatic conversion performed by the compiler.
- **Explicit Typecasting** : Manual conversion using casting operators.
  - **C-style Cast** : `(type)expression`
  - **Function-style Cast** : `type(expression)`
  - **`static_cast`** : `static_cast<type>(expression)`, safe for well-defined conversions.
  - **`dynamic_cast`** : `dynamic_cast<type>(expression)`, used for safe downcasting in polymorphic hierarchies.
  - **`const_cast`** : `const_cast<type>(expression)`, used to add/remove `const`.
  - **`reinterpret_cast`** : `reinterpret_cast<type>(expression)`, used for low-level casting.

## Control Structures

- Control structures in C++ are constructs that control the flow of execution of the program.
- They allow you to specify conditions under which certain blocks of code should be executed or repeated.

1. **Conditional Statements**
   - `if`
   - `if-else`
   - `if-else if-else`
   - `switch`

2. **Loops**
   - `for`
   - `while`
   - `do-while`

3. **Jump Statements**
   - `break`
   - `continue`
   - `return`
   - `goto` (rarely used)

### 1. Conditional Statements

#### `if` Statement

The `if` statement executes a block of code if a specified condition is true.

```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 10;

    if (num > 5) {
        cout << "num is greater than 5" << endl;
    }

    return 0;
}
```

#### `if-else` Statement

The `if-else` statement executes one block of code if a condition is true and another block if the condition is false.

```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 10;

    if (num > 5) {
        cout << "num is greater than 5" << endl;
    } else {
        cout << "num is not greater than 5" << endl;
    }

    return 0;
}
```

#### `if-else if-else` Statement

The `if-else if-else` statement allows you to check multiple conditions.

```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 10;

    if (num > 10) {
        cout << "num is greater than 10" << endl;
    } else if (num == 10) {
        cout << "num is equal to 10" << endl;
    } else {
        cout << "num is less than 10" << endl;
    }

    return 0;
}
```

#### `switch` Statement

The `switch` statement allows you to execute one block of code among many based on the value of an expression.

```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 2;

    switch (num) {
        case 1:
            cout << "num is 1" << endl;
            break;
        case 2:
            cout << "num is 2" << endl;
            break;
        case 3:
            cout << "num is 3" << endl;
            break;
        default:
            cout << "num is not 1, 2, or 3" << endl;
            break;
    }

    return 0;
}
```

### 2. Loops

#### `for` Loop

The `for` loop is used when you know in advance how many times you want to execute a statement or a block of statements.

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i < 5; ++i) {
        cout << "i = " << i << endl;
    }

    return 0;
}
```

#### `while` Loop

The `while` loop executes a block of code as long as a specified condition is true.

```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 0;

    while (i < 5) {
        cout << "i = " << i << endl;
        ++i;
    }

    return 0;
}
```

#### `do-while` Loop

The `do-while` loop is similar to the `while` loop, but it guarantees that the loop body is executed at least once.

```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 0;

    do {
        cout << "i = " << i << endl;
        ++i;
    } while (i < 5);

    return 0;
}
```

### 3. Jump Statements

#### `break`

The `break` statement terminates the closest enclosing loop or `switch` statement.

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i < 5; ++i) {
        if (i == 3) {
            break;  // Exit the loop
        }
        cout << "i = " << i << endl;
    }

    return 0;
}
```

#### `continue`

The `continue` statement skips the remaining statements in the current iteration of the loop and proceeds to the next iteration.

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i < 5; ++i) {
        if (i == 3) {
            continue;  // Skip the rest of the loop body for this iteration
        }
        cout << "i = " << i << endl;
    }

    return 0;
}
```

#### `return`

The `return` statement exits a function and optionally returns a value to the function's caller.

```cpp
#include <iostream>
using namespace std;

int add(int a, int b) {
    return a + b;  // Exit the function and return the sum
}

int main() {
    int sum = add(5, 3);
    cout << "Sum = " << sum << endl;

    return 0;
}
```

#### `goto`

- The `goto` statement transfers control to the labeled statement.
- It is rarely used as it can make the code difficult to understand and maintain.

```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 0;

start:
    cout << "i = " << i << endl;
    ++i;

    if (i < 5) {
        goto start;  // Jump to the label 'start'
    }

    return 0;
}
```

- **Conditional Statements** :
  - `if`, `if-else`, `if-else if-else`, `switch`
- **Loops** :
  - `for`, `while`, `do-while`
- **Jump Statements** :
  - `break`, `continue`, `return`, `goto`

# C++ Functions

## Simple Functions

Functions in C++ allow you to encapsulate code into reusable blocks, making your programs more modular, easier to read, and easier to maintain.

### Defining a Function

A function definition in C++ has the following syntax:

```cpp
return_type function_name(parameter_list) {
    // body of the function
    // statements
}
```

- **return_type** : The type of value the function returns. Use `void` if the function does not return a value.
- **function_name** : The name of the function.
- **parameter_list** : A list of parameters the function takes (can be empty).

### Example of a Simple Function

Let's start with a simple example: a function to add two numbers.

#### Function Declaration (Prototype)

A function prototype declares the function and specifies its name, return type, and parameters. This is typically placed before the `main` function or in a header file.

```cpp
int add(int a, int b);
```

#### Function Definition

The function definition provides the actual implementation of the function.

```cpp
#include <iostream>
using namespace std;

// Function prototype
int add(int a, int b);

// Main function
int main() {
    int num1 = 10;
    int num2 = 20;
    
    // Calling the add function
    int sum = add(num1, num2);
    
    cout << "Sum: " << sum << endl;  // Output: Sum: 30
    
    return 0;
}

// Function definition
int add(int a, int b) {
    return a + b;
}
```

### Function with No Parameters and No Return Value

A function can also be defined without parameters and without returning a value. For example, a function to print a message.

```cpp
#include <iostream>
using namespace std;

// Function prototype
void printMessage();

// Main function
int main() {
    printMessage();  // Calling the printMessage function
    return 0;
}

// Function definition
void printMessage() {
    cout << "Hello, World!" << endl;
}
```

### Function with Parameters and No Return Value

A function can take parameters and not return any value. For example, a function to print a number.

```cpp
#include <iostream>
using namespace std;

// Function prototype
void printNumber(int num);

// Main function
int main() {
    int number = 42;
    printNumber(number);  // Calling the printNumber function
    return 0;
}

// Function definition
void printNumber(int num) {
    cout << "Number: " << num << endl;
}
```

### Function with No Parameters and a Return Value

A function can return a value without taking any parameters. For example, a function to get a fixed number.

```cpp
#include <iostream>
using namespace std;

// Function prototype
int getNumber();

// Main function
int main() {
    int number = getNumber();  // Calling the getNumber function
    cout << "Number: " << number << endl;  // Output: Number: 42
    return 0;
}

// Function definition
int getNumber() {
    return 42;
}
```

### Function Overloading

Function overloading allows you to define multiple functions with the same name but different parameter lists.

```cpp
#include <iostream>
using namespace std;

// Function prototypes
int add(int a, int b);
double add(double a, double b);

// Main function
int main() {
    cout << "Int sum: " << add(10, 20) << endl;  // Calls int add(int, int)
    cout << "Double sum: " << add(1.5, 2.5) << endl;  // Calls double add(double, double)
    return 0;
}

// Function definitions
int add(int a, int b) {
    return a + b;
}

double add(double a, double b) {
    return a + b;
}
```

- **Function Declaration (Prototype)** : Declares the function's return type, name, and parameters.
- **Function Definition** : Provides the actual implementation of the function.
- **Function Calling** : Invokes the function to perform its task.
- **Function Overloading** : Allows multiple functions with the same name but different parameters.

## Call & Return By Reference

- Functions can pass arguments in two main ways : by value and by reference.
- When passing by reference, the function can modify the actual parameter passed to it, unlike passing by value where only a copy of the argument is modified within the function.

### Call by Value

- When a function is called by value, a copy of the actual parameter is passed to the function.
- Changes made to the parameter inside the function do not affect the original value.

Example :
```cpp
#include <iostream>
using namespace std;

void modifyValue(int a) {
    a = 20;
}

int main() {
    int x = 10;
    modifyValue(x);
    cout << "x after modifyValue: " << x << endl;  // Output: x after modifyValue: 10
    return 0;
}
```

### Call by Reference

- When a function is called by reference, a reference to the actual parameter is passed to the function.
- Changes made to the parameter inside the function affect the original value.

Example :
```cpp
#include <iostream>
using namespace std;

void modifyValue(int &a) {  // Notice the & indicating a reference
    a = 20;
}

int main() {
    int x = 10;
    modifyValue(x);
    cout << "x after modifyValue: " << x << endl;  // Output: x after modifyValue: 20
    return 0;
}
```

### Returning by Reference

- When a function returns a reference, it returns a reference to a variable instead of a copy of the variable.
- This can be useful for allowing function calls to be lvalues and can be more efficient in some cases.

Example :
```cpp
#include <iostream>
using namespace std;

int& getReference(int &a) {
    return a;  // Return the reference to the caller
}

int main() {
    int x = 10;
    int &ref = getReference(x);  // Get a reference to x
    ref = 20;  // Modify the value through the reference
    cout << "x after getReference: " << x << endl;  // Output: x after getReference: 20
    return 0;
}
```

### Important Points

1. **Lifetime of Returned References** :
   - Be careful not to return references to local variables, as they will be destroyed when the function exits.
   
2. **Modifying Original Values** :
   - Using call by reference allows the function to modify the actual argument passed to it, which can be useful for functions that need to modify multiple values.

### Example with Arrays

Arrays are naturally passed by reference (actually, the pointer to the first element is passed), so changes made to the array inside a function will affect the original array.

Example :
```cpp
#include <iostream>
using namespace std;

void modifyArray(int arr[], int size) {
    for (int i = 0; i < size; ++i) {
        arr[i] *= 2;
    }
}

int main() {
    int arr[5] = {1, 2, 3, 4, 5};
    modifyArray(arr, 5);
    cout << "Array after modifyArray: ";
    for (int i = 0; i < 5; ++i) {
        cout << arr[i] << " ";  // Output: 2 4 6 8 10
    }
    cout << endl;
    return 0;
}
```

- **Call by Value** : Copies the actual parameter, changes do not affect the original.
- **Call by Reference** : Passes a reference to the actual parameter, changes affect the original.
- **Returning by Reference** : Returns a reference to a variable, allowing the caller to modify the original variable.

## Inline Functions

Inline functions in C++ are used to reduce the function call overhead by expanding the function's body at the point where the function is called, instead of performing a traditional function call.

### Defining Inline Functions

To declare a function as inline, use the `inline` keyword before the function definition.

```cpp
inline return_type function_name(parameter_list) {
    // function body
}
```

### Example of an Inline Function

```cpp
#include <iostream>
using namespace std;

inline int add(int a, int b) {
    return a + b;
}

int main() {
    int x = 10, y = 20;
    cout << "Sum: " << add(x, y) << endl;  // Output: Sum: 30
    return 0;
}
```

### Inline Functions in Classes

- Inline functions are often used in classes, especially for simple getter and setter methods.
- You can define these functions directly inside the class definition.

```cpp
#include <iostream>
using namespace std;

class Rectangle {
private:
    int width, height;

public:
    Rectangle(int w, int h) : width(w), height(h) {}

    // Inline function to calculate area
    inline int area() const {
        return width * height;
    }

    // Inline function to set width
    inline void setWidth(int w) {
        width = w;
    }

    // Inline function to set height
    inline void setHeight(int h) {
        height = h;
    }
};

int main() {
    Rectangle rect(10, 5);
    cout << "Area: " << rect.area() << endl;  // Output: Area: 50
    rect.setWidth(20);
    rect.setHeight(10);
    cout << "New Area: " << rect.area() << endl;  // Output: New Area: 200
    return 0;
}
```

### Advantages of Inline Functions

1. **Performance Improvement** : By expanding the function body at the call site, inline functions can eliminate the overhead associated with function calls.
2. **Readability** : Inline functions can make code more readable and maintainable compared to macros, as they provide type safety and proper scope handling.
3. **Small and Simple Functions** : Ideal for small and frequently called functions, such as getters, setters, and simple calculations.

### Limitations and Considerations

1. **Code Size Increase** : Inlining functions can lead to larger binary sizes because the function body is duplicated at each call site.
2. **Compiler Discretion** : The `inline` keyword is a request to the compiler, not a command. The compiler may choose to ignore the request if it deems inlining inappropriate (e.g., if the function is too complex or recursive).
3. **Recursive Functions** : Inline functions are generally not suitable for recursive functions as this could lead to excessive code expansion and potentially infinite recursion at compile time.

### Example with Inline Keyword

You can also use the `inline` keyword with functions defined outside the class definition.

```cpp
#include <iostream>
using namespace std;

class Rectangle {
private:
    int width, height;

public:
    Rectangle(int w, int h);
    inline int area() const;
    inline void setWidth(int w);
    inline void setHeight(int h);
};

// Constructor
Rectangle::Rectangle(int w, int h) : width(w), height(h) {}

// Inline function to calculate area
inline int Rectangle::area() const {
    return width * height;
}

// Inline function to set width
inline void Rectangle::setWidth(int w) {
    width = w;
}

// Inline function to set height
inline void Rectangle::setHeight(int h) {
    height = h;
}

int main() {
    Rectangle rect(10, 5);
    cout << "Area: " << rect.area() << endl;  // Output: Area: 50
    rect.setWidth(20);
    rect.setHeight(10);
    cout << "New Area: " << rect.area() << endl;  // Output: New Area: 200
    return 0;
}
```

- **Inline Function Declaration** : Use the `inline` keyword before the function definition.
- **Advantages** : Reduces function call overhead and can improve performance for small, frequently called functions.
- **Limitations** : Can lead to code bloat, and the compiler might ignore the inline request.
- **Best Use Cases** : Small functions, performance-critical sections, and class member functions.

## Macro Vs. Inline Functions

Macros and inline functions in C++ are both mechanisms for improving performance by reducing function call overhead.

### Macros

- Macros are preprocessor directives, defined using `#define`.
- The preprocessor replaces each occurrence of the macro with its definition before the compilation process begins.

#### Example of a Macro

```cpp
#include <iostream>
using namespace std;

#define SQUARE(x) ((x) * (x))

int main() {
    int num = 5;
    cout << "Square of " << num << " is " << SQUARE(num) << endl;  // Output: Square of 5 is 25
    return 0;
}
```

#### Advantages of Macros

1. **No Function Call Overhead** : Since macros are expanded inline by the preprocessor, they do not incur function call overhead.
2. **Simple and Fast** : Useful for simple constants and simple operations.

#### Disadvantages of Macros

1. **No Type Safety** : Macros are not type-checked by the compiler, which can lead to errors.
2. **No Scope** : Macros do not respect scope rules, potentially causing naming conflicts.
3. **Debugging Difficulty** : Errors in macros can be harder to debug because the preprocessor expands them before compilation.
4. **Potential Side Effects** : Macros can lead to unintended side effects, especially with complex expressions.

### Inline Functions

Inline functions are a feature of C++ where the compiler attempts to expand the function's code at each call site, similar to macros, but with better type safety and scope handling.

#### Example of an Inline Function

```cpp
#include <iostream>
using namespace std;

inline int square(int x) {
    return x * x;
}

int main() {
    int num = 5;
    cout << "Square of " << num << " is " << square(num) << endl;  // Output: Square of 5 is 25
    return 0;
}
```

#### Advantages of Inline Functions

1. **Type Safety** : Inline functions are checked by the compiler, ensuring type safety.
2. **Scope Handling** : Inline functions respect C++ scope rules, reducing naming conflicts.
3. **Ease of Debugging** : Inline functions are easier to debug compared to macros, as they are part of the normal compilation process.
4. **Optimization** : The compiler can optimize inline functions more effectively than macros.

#### Disadvantages of Inline Functions

1. **Compiler Discretion** : The compiler may ignore the inline request if it deems it inappropriate (e.g., if the function is too complex).
2. **Code Size Increase** : Excessive inlining can lead to code bloat, increasing the binary size.

### Comparison

| Feature              | Macros                             | Inline Functions                        |
|----------------------|------------------------------------|-----------------------------------------|
| Type Safety          | No                                 | Yes                                     |
| Scope                | No                                 | Yes                                     |
| Debugging            | Harder                             | Easier                                  |
| Functionality        | Simple text replacement            | Full function with type checking        |
| Compiler Optimization| No                                 | Yes                                     |
| Risk of Side Effects | High                               | Low                                     |
| Code Bloat           | Can be significant                 | Can be significant                      |

- **Macros** :
  - **Pros** : Simple and fast, no function call overhead, useful for constants.
  - **Cons** : No type safety, no scope, harder to debug, potential side effects.
  
- **Inline Functions** :
  - **Pros** : Type-safe, respects scope, easier to debug, can be optimized by the compiler.
  - **Cons** : Compiler may ignore inlining, excessive inlining can lead to code bloat.

## Overloading Of Functions

- Function overloading in C++ allows to define multiple functions with the same name but with different parameter lists (different type or number of parameters).
- This enables functions to handle different types of inputs with the same function name, enhancing code readability and reusability.

### Key Points of Function Overloading

1. **Same Function Name** : All overloaded functions must have the same name.
2. **Different Parameter Lists** : Overloaded functions must differ in the type, number, or order of parameters.
3. **Return Type** : The return type of the functions can be different, but it is not considered for function overloading. The compiler determines which function to call solely based on the parameter list.

### Example of Function Overloading

```cpp
#include <iostream>
using namespace std;

// Overloaded functions to add integers and doubles
int add(int a, int b) {
    return a + b;
}

double add(double a, double b) {
    return a + b;
}

int main() {
    int intResult = add(5, 3);           // Calls add(int, int)
    double doubleResult = add(5.5, 3.3); // Calls add(double, double)

    cout << "Sum of integers: " << intResult << endl;       // Output: Sum of integers: 8
    cout << "Sum of doubles: " << doubleResult << endl;     // Output: Sum of doubles: 8.8

    return 0;
}
```

### Overloading with Different Number of Parameters

You can also overload functions by varying the number of parameters:

```cpp
#include <iostream>
using namespace std;

// Function to calculate the area of a square
int area(int side) {
    return side * side;
}

// Function to calculate the area of a rectangle
int area(int length, int breadth) {
    return length * breadth;
}

int main() {
    cout << "Area of square: " << area(5) << endl;               // Output: Area of square: 25
    cout << "Area of rectangle: " << area(5, 10) << endl;        // Output: Area of rectangle: 50

    return 0;
}
```

### Overloading with Different Parameter Types

You can overload functions by changing the types of parameters:

```cpp
#include <iostream>
using namespace std;

// Function to print an integer
void print(int i) {
    cout << "Integer: " << i << endl;
}

// Function to print a double
void print(double f) {
    cout << "Double: " << f << endl;
}

// Function to print a string
void print(const string& s) {
    cout << "String: " << s << endl;
}

int main() {
    print(10);          // Calls print(int)
    print(10.5);        // Calls print(double)
    print("Hello");     // Calls print(const string&)

    return 0;
}
```

### Rules and Best Practices

1. **Parameter Differences** : Functions must differ in parameter type, number, or order. Overloading functions based only on return type is not allowed.
2. **Avoid Ambiguity** : Ensure that overloaded functions are not ambiguous. The compiler must clearly differentiate between them based on the argument types provided.
3. **Consistency** : Use overloading to provide consistent interfaces for similar operations with different types of data.

### Example with Class Methods

Function overloading is also common in classes, where methods with the same name can perform different tasks based on their parameters.

```cpp
#include <iostream>
using namespace std;

class Printer {
public:
    // Overloaded print methods
    void print(int i) {
        cout << "Printing int: " << i << endl;
    }

    void print(double f) {
        cout << "Printing double: " << f << endl;
    }

    void print(const string& s) {
        cout << "Printing string: " << s << endl;
    }
};

int main() {
    Printer p;
    p.print(10);          // Calls print(int)
    p.print(10.5);        // Calls print(double)
    p.print("Hello");     // Calls print(const string&)

    return 0;
}
```

- **Function Overloading** : Defining multiple functions with the same name but different parameters.
- **Different Parameter Lists** : Functions must differ in the type, number, or order of parameters.
- **Enhanced Readability** : Overloading improves code readability and reusability.
- **Class Methods** : Overloading is common in classes to provide multiple ways to interact with an object.

## Default Arguments

- Default arguments in C++ allow you to specify default values for one or more parameters in a function.
- When a function is called without providing arguments for those parameters, the default values are used.

### Syntax

The default values for parameters are specified in the function declaration:

```cpp
return_type function_name(parameter1 = default_value1, parameter2 = default_value2, ...);
```

### Example of Default Arguments

```cpp
#include <iostream>
using namespace std;

// Function with default arguments
void greet(string name = "Guest", string message = "Welcome!") {
    cout << "Hello, " << name << "! " << message << endl;
}

int main() {
    greet();                          // Uses default values for both parameters
    greet("Alice");                   // Uses default value for the second parameter
    greet("Bob", "Good to see you!"); // No default values used

    return 0;
}
```

Output:
```
Hello, Guest! Welcome!
Hello, Alice! Welcome!
Hello, Bob! Good to see you!
```

### Rules for Default Arguments

1. **Order Matters** : Once a parameter is given a default value, all subsequent parameters must also have default values.
   
   ```cpp
   // Correct
   void example(int x = 0, int y = 1);
   
   // Incorrect
   void example(int x = 0, int y); // Error: missing default argument for parameter 'y'
   ```

2. **Declaration** : Default arguments are typically specified in the function declaration, not in the definition. If the function is defined in a header file and implemented in a separate source file, the default arguments should be in the header file.

   ```cpp
   // Header file (example.h)
   void displayMessage(string text = "Hello", int times = 1);

   // Source file (example.cpp)
   #include "example.h"
   void displayMessage(string text, int times) {
       for (int i = 0; i < times; ++i) {
           cout << text << endl;
       }
   }
   ```

3. **Redefining Defaults** : If a function with default arguments is overloaded, the default values should be provided in only one declaration.

### Example with Class Methods

Default arguments are also commonly used in class constructors and member functions.

```cpp
#include <iostream>
using namespace std;

class Box {
private:
    int length, width, height;

public:
    // Constructor with default arguments
    Box(int l = 1, int w = 1, int h = 1) : length(l), width(w), height(h) {}

    // Member function with default arguments
    int volume(int scale = 1) const {
        return length * width * height * scale;
    }
};

int main() {
    Box box1;             // Uses default values for all dimensions
    Box box2(5, 3);       // Uses default value for height

    cout << "Volume of box1: " << box1.volume() << endl;           // Output: Volume of box1: 1
    cout << "Volume of box2: " << box2.volume() << endl;           // Output: Volume of box2: 15
    cout << "Volume of box2 scaled: " << box2.volume(2) << endl;   // Output: Volume of box2 scaled: 30

    return 0;
}
```

- **Default Arguments** : Allow specifying default values for function parameters.
- **Simplify Function Calls** : Default values make it easier to call functions without providing all arguments.
- **Declaration Location** : Typically specified in the function declaration, especially in header files.
- **Usage in Classes** : Commonly used in constructors and member functions to provide flexible initialization and operations.

## Friend Functions

- Friend functions in C++ are functions that are not members of a class but have access to the class's private and protected members.
- They are useful when you need to allow a non-member function to access the private data of a class.

### Key Points about Friend Functions

1. **Access** : Friend functions have the same access rights as member functions, meaning they can access private and protected members of the class.
2. **Declaration** : To declare a friend function, use the `friend` keyword inside the class.
3. **Definition** : Friend functions are defined outside the class just like normal functions.
4. **Non-Member Functions** : Although they have access to private members, friend functions are not member functions of the class.

### Example of a Friend Function

```cpp
#include <iostream>
using namespace std;

class Box {
private:
    double width;

public:
    // Constructor to initialize width
    Box(double w) : width(w) {}

    // Declaration of friend function
    friend void printWidth(const Box& b);
};

// Definition of friend function
void printWidth(const Box& b) {
    cout << "Width of box: " << b.width << endl;
}

int main() {
    Box box(10.5);
    printWidth(box);  // Output: Width of box: 10.5

    return 0;
}
```

In this example, `printWidth` is a friend function of the `Box` class, allowing it to access the private member `width`.

### Why Use Friend Functions?

1. **Operator Overloading** : Friend functions are commonly used to overload operators that need to access private data of a class.
2. **Non-Member Functions** : Sometimes a function logically belongs with a class but is not a member. Friend functions allow this function to access private data.
3. **Flexibility** : They provide more flexibility in how you can interact with the class’s private data.

### Example of Friend Function for Operator Overloading

Friend functions are particularly useful for overloading certain operators that require access to private data of both operands :

```cpp
#include <iostream>
using namespace std;

class Complex {
private:
    double real;
    double imag;

public:
    // Constructor to initialize the complex number
    Complex(double r = 0.0, double i = 0.0) : real(r), imag(i) {}

    // Declaration of friend function for overloading the + operator
    friend Complex operator+(const Complex& c1, const Complex& c2);

    // Function to display the complex number
    void display() const {
        cout << real << " + " << imag << "i" << endl;
    }
};

// Definition of friend function for overloading the + operator
Complex operator+(const Complex& c1, const Complex& c2) {
    return Complex(c1.real + c2.real, c1.imag + c2.imag);
}

int main() {
    Complex c1(3.0, 4.0), c2(1.5, 2.5);
    Complex c3 = c1 + c2;  // Calls the overloaded + operator

    c1.display();  // Output: 3 + 4i
    c2.display();  // Output: 1.5 + 2.5i
    c3.display();  // Output: 4.5 + 6.5i

    return 0;
}
```

In this example, the `operator+` is a friend function of the `Complex` class, allowing it to access the private members `real` and `imag`.

- **Friend Functions** : Allow non-member functions to access private and protected members of a class.
- **Declaration** : Use the `friend` keyword inside the class.
- **Usage** : Commonly used for operator overloading and when non-member functions need access to private data.
- **Flexibility** : Provide additional flexibility in class design and data access.

# Objects & Classes

## Basics Of Object & Class in C++

Objects and classes are fundamental concepts of Object-Oriented Programming (OOP).

### What is a Class?

- A class is a blueprint or template for creating objects.
- It defines a data structure and the functions (methods) that operate on the data.
- A class encapsulates data and functions that work on the data into a single unit.

#### Defining a Class

```cpp
#include <iostream>
using namespace std;

class Car {
public:
    string brand;
    string model;
    int year;

    // Method to display car details
    void displayDetails() {
        cout << "Brand: " << brand << ", Model: " << model << ", Year: " << year << endl;
    }
};
```

### What is an Object?

- An object is an instance of a class.
- When a class is defined, no memory is allocated until an object of that class is created.
- An object has a state (represented by the data members) and behavior (represented by the member functions or methods).

#### Creating an Object

To create an object, you declare it using the class name:

```cpp
int main() {
    Car myCar; // Create an object of class Car
    myCar.brand = "Toyota";
    myCar.model = "Corolla";
    myCar.year = 2020;

    myCar.displayDetails(); // Output: Brand: Toyota, Model: Corolla, Year: 2020

    return 0;
}
```

### Members of a Class

A class can have :

1. **Data Members** : Variables that hold data specific to the object.
2. **Member Functions (Methods)** : Functions that operate on the data members.

#### Access Specifiers

C++ classes use access specifiers to control the access level of their members :

1. **public** : Members are accessible from outside the class.
2. **private** : Members are accessible only within the class.
3. **protected** : Members are accessible within the class and by derived class.

#### Example with Access Specifiers

```cpp
#include <iostream>
using namespace std;

class Car {
private:
    string brand;
    string model;
    int year;

public:
    // Constructor
    Car(string b, string m, int y) : brand(b), model(m), year(y) {}

    // Method to display car details
    void displayDetails() {
        cout << "Brand: " << brand << ", Model: " << model << ", Year: " << year << endl;
    }
};

int main() {
    Car myCar("Toyota", "Corolla", 2020);
    myCar.displayDetails(); // Output: Brand: Toyota, Model: Corolla, Year: 2020

    return 0;
}
```

### Constructors and Destructors

- **Constructor** : A special member function that initializes objects of a class. It has the same name as the class and no return type.
- **Destructor** : A special member function that is invoked when an object is destroyed. It has the same name as the class preceded by a tilde (`~`).

#### Example with Constructor and Destructor

```cpp
#include <iostream>
using namespace std;

class Car {
private:
    string brand;
    string model;
    int year;

public:
    // Constructor
    Car(string b, string m, int y) : brand(b), model(m), year(y) {
        cout << "Car object created." << endl;
    }

    // Destructor
    ~Car() {
        cout << "Car object destroyed." << endl;
    }

    // Method to display car details
    void displayDetails() {
        cout << "Brand: " << brand << ", Model: " << model << ", Year: " << year << endl;
    }
};

int main() {
    Car myCar("Toyota", "Corolla", 2020);
    myCar.displayDetails(); // Output: Brand: Toyota, Model: Corolla, Year: 2020

    // Destructor will be called automatically when the object goes out of scope

    return 0;
}
```

- **Class** : A blueprint for creating objects, defining data members and methods.
- **Object** : An instance of a class, with a specific state and behavior.
- **Data Members** : Variables that store the state of the object.
- **Member Functions (Methods)** : Functions that define the behavior of the object.
- **Access Specifiers** : Control the accessibility of class members (`public`, `private`, `protected`).
- **Constructor** : Initializes objects of the class.
- **Destructor** : Cleans up when an object is destroyed.

## Private & Public Members

- private and public members of a class determine the accessibility of the class's data members and member functions.
- Understanding these access specifiers is crucial for designing robust and encapsulated classes.

### Access Specifiers in C++

1. **Public Members** : Accessible from anywhere in the program where the object is visible.
2. **Private Members** : Accessible only within the class itself and by friends of the class.

### Public Members

- Public members of a class can be accessed directly using the object of the class.
- This includes both data members and member functions declared with the `public` keyword.

#### Example of Public Members

```cpp
#include <iostream>
using namespace std;

class Car {
public:
    string brand;
    string model;
    int year;

    // Method to display car details
    void displayDetails() {
        cout << "Brand: " << brand << ", Model: " << model << ", Year: " << year << endl;
    }
};

int main() {
    Car myCar;
    myCar.brand = "Toyota";
    myCar.model = "Corolla";
    myCar.year = 2020;

    myCar.displayDetails(); // Output: Brand: Toyota, Model: Corolla, Year: 2020

    return 0;
}
```

In this example, `brand`, `model`, and `year` are public data members and can be accessed directly.

### Private Members

- Private members of a class cannot be accessed directly from outside the class.
- They can only be accessed by member functions of the class or by friends of the class.

#### Example of Private Members

```cpp
#include <iostream>
using namespace std;

class Car {
private:
    string brand;
    string model;
    int year;

public:
    // Constructor to initialize the car
    Car(string b, string m, int y) : brand(b), model(m), year(y) {}

    // Method to display car details
    void displayDetails() {
        cout << "Brand: " << brand << ", Model: " << model << ", Year: " << year << endl;
    }

    // Setter methods to modify private members
    void setBrand(string b) { brand = b; }
    void setModel(string m) { model = m; }
    void setYear(int y) { year = y; }
};

int main() {
    Car myCar("Toyota", "Corolla", 2020);

    // Cannot access private members directly
    // myCar.brand = "Honda"; // Error: 'brand' is private within this context

    // Use public methods to modify and access private members
    myCar.setBrand("Honda");
    myCar.displayDetails(); // Output: Brand: Honda, Model: Corolla, Year: 2020

    return 0;
}
```

In this example, `brand`, `model`, and `year` are private data members and cannot be accessed directly. Instead, public member functions are provided to modify and access these private members.

### Why Use Private Members?

1. **Encapsulation** : Private members help in encapsulating the data, meaning the internal representation of an object is hidden from the outside. Only the object's methods can access and modify its state.
2. **Control** : Private members provide control over how the data is accessed or modified, ensuring that the object's state remains consistent.
3. **Maintainability** : By hiding the details of the data representation, changes to the internal implementation do not affect code that uses the class.

### Example: Combining Public and Private Members

```cpp
#include <iostream>
using namespace std;

class Rectangle {
private:
    int length;
    int width;

public:
    // Constructor
    Rectangle(int l, int w) : length(l), width(w) {}

    // Public method to compute area
    int area() const {
        return length * width;
    }

    // Public method to display dimensions
    void displayDimensions() const {
        cout << "Length: " << length << ", Width: " << width << endl;
    }

    // Setter and getter for length
    void setLength(int l) { length = l; }
    int getLength() const { return length; }

    // Setter and getter for width
    void setWidth(int w) { width = w; }
    int getWidth() const { return width; }
};

int main() {
    Rectangle rect(10, 5);
    rect.displayDimensions(); // Output: Length: 10, Width: 5
    cout << "Area: " << rect.area() << endl; // Output: Area: 50

    // Modify dimensions using setters
    rect.setLength(15);
    rect.setWidth(7);
    rect.displayDimensions(); // Output: Length: 15, Width: 7
    cout << "Area: " << rect.area() << endl; // Output: Area: 105

    return 0;
}
```

In this example :
- `length` and `width` are private data members.
- Public methods `setLength`, `getLength`, `setWidth`, and `getWidth` are used to modify and access the private data members.
- The public method `area` computes the area of the rectangle.

- **Public Members** : Accessible from anywhere; typically used for methods that need to be called from outside the class.
- **Private Members** : Accessible only within the class; used for data members that should be hidden and protected from outside access.
- **Encapsulation** : Ensures that the internal state of an object is hidden and protected from unintended modifications.

## Static Data & Function Members

`static` data members and `static` member functions are part of a class but have unique properties that differentiate them from regular class members.

### Static Data Members

- A `static` data member is shared by all objects of the class.
- There is only one copy of a `static` data member, regardless of the number of objects created.
- It is used to store class-level data that is common to all objects of the class.

#### Characteristics of Static Data Members
1. **Shared among all objects** : Only one copy exists, and it is shared by all instances of the class.
2. **Class-level scope** : It can be accessed using the class name.
3. **Initialization** : Must be defined outside the class definition.

#### Example of Static Data Members

```cpp
#include <iostream>
using namespace std;

class Counter {
private:
    static int count; // Declaration of static data member

public:
    // Constructor increments count for each object created
    Counter() {
        count++;
    }

    // Static function to access the static data member
    static int getCount() {
        return count;
    }
};

// Definition of static data member
int Counter::count = 0;

int main() {
    Counter c1;
    Counter c2;
    Counter c3;

    // Accessing static data member using class name
    cout << "Number of objects created: " << Counter::getCount() << endl; // Output: 3

    return 0;
}
```

In this example :
- `count` is a static data member, keeping track of the number of `Counter` objects created.
- `getCount` is a static member function that returns the value of `count`.

### Static Member Functions

- A `static` member function can be called on the class itself, not on specific objects.
- It can only access static data members or other static member functions.

#### Characteristics of Static Member Functions
1. **Access** : Can be called using the class name or an object of the class.
2. **No `this` pointer** : Cannot access non-static members of the class because it does not operate on an instance of the class.

#### Example of Static Member Functions

```cpp
#include <iostream>
using namespace std;

class MathUtils {
public:
    // Static member function to add two numbers
    static int add(int a, int b) {
        return a + b;
    }

    // Static member function to multiply two numbers
    static int multiply(int a, int b) {
        return a * b;
    }
};

int main() {
    // Calling static member functions using the class name
    cout << "Sum: " << MathUtils::add(5, 3) << endl;       // Output: Sum: 8
    cout << "Product: " << MathUtils::multiply(5, 3) << endl; // Output: Product: 15

    return 0;
}
```

In this example :
- `add` and `multiply` are static member functions of the `MathUtils` class, performing basic arithmetic operations.

### Combined Example : Static Data Members and Static Member Functions

```cpp
#include <iostream>
using namespace std;

class Student {
private:
    static int totalStudents; // Static data member
    string name;

public:
    // Constructor increments totalStudents for each object created
    Student(string n) : name(n) {
        totalStudents++;
    }

    // Static member function to get the total number of students
    static int getTotalStudents() {
        return totalStudents;
    }

    // Function to display student name
    void display() const {
        cout << "Student Name: " << name << endl;
    }
};

// Definition of static data member
int Student::totalStudents = 0;

int main() {
    Student s1("Alice");
    Student s2("Bob");

    s1.display(); // Output: Student Name: Alice
    s2.display(); // Output: Student Name: Bob

    // Accessing static member function using class name
    cout << "Total Students: " << Student::getTotalStudents() << endl; // Output: Total Students: 2

    return 0;
}
```

In this example :
- `totalStudents` is a static data member that counts the number of `Student` objects created.
- `getTotalStudents` is a static member function that returns the total number of students.

- **Static Data Members** :
  - Shared by all objects of the class.
  - Only one copy exists, common to all instances.
  - Must be defined outside the class definition.

- **Static Member Functions** :
  - Can be called on the class itself, not on instances.
  - Can only access static data members and other static member functions.
  - Do not have access to the `this` pointer.

## Constructors & Their Types

- Constructors in C++ are special member functions that are used to initialize objects of a class.
- They have the same name as the class and do not have a return type.

### Types of Constructors

1. **Default Constructor**
2. **Parameterized Constructor**
3. **Copy Constructor**
4. **Move Constructor (C++11)**
5. **Delegating Constructor (C++11)**

### 1. Default Constructor

- A default constructor is a constructor that takes no arguments.
- If no constructors are explicitly defined, the compiler provides a default constructor.

#### Example of Default Constructor

```cpp
#include <iostream>
using namespace std;

class Box {
public:
    Box() { // Default constructor
        cout << "Default constructor called." << endl;
    }
};

int main() {
    Box box1; // Default constructor is called
    return 0;
}
```

### 2. Parameterized Constructor

- A parameterized constructor is a constructor that takes one or more arguments.
- It allows you to initialize objects with specific values when they are created.

#### Example of Parameterized Constructor

```cpp
#include <iostream>
using namespace std;

class Box {
private:
    double length;
    double width;
    double height;

public:
    Box(double l, double w, double h) : length(l), width(w), height(h) { // Parameterized constructor
        cout << "Parameterized constructor called." << endl;
    }

    void display() {
        cout << "Length: " << length << ", Width: " << width << ", Height: " << height << endl;
    }
};

int main() {
    Box box1(10.5, 7.5, 5.5); // Parameterized constructor is called
    box1.display(); // Output: Length: 10.5, Width: 7.5, Height: 5.5
    return 0;
}
```

### 3. Copy Constructor

- A copy constructor is a constructor that creates a new object as a copy of an existing object.
- It takes a reference to an object of the same class as an argument.

#### Example of Copy Constructor

```cpp
#include <iostream>
using namespace std;

class Box {
private:
    double length;
    double width;
    double height;

public:
    Box(double l, double w, double h) : length(l), width(w), height(h) { // Parameterized constructor
        cout << "Parameterized constructor called." << endl;
    }

    Box(const Box& other) { // Copy constructor
        length = other.length;
        width = other.width;
        height = other.height;
        cout << "Copy constructor called." << endl;
    }

    void display() {
        cout << "Length: " << length << ", Width: " << width << ", Height: " << height << endl;
    }
};

int main() {
    Box box1(10.5, 7.5, 5.5); // Parameterized constructor is called
    Box box2 = box1; // Copy constructor is called
    box2.display(); // Output: Length: 10.5, Width: 7.5, Height: 5.5
    return 0;
}
```

### 4. Move Constructor (C++11)

- A move constructor transfers the resources from one object to another without copying.
- It is used for the efficient transfer of resources, typically when an object is about to be destroyed.

#### Example of Move Constructor

```cpp
#include <iostream>
#include <utility> // For std::move
using namespace std;

class Box {
private:
    double* data;

public:
    // Constructor
    Box(double value) {
        data = new double(value);
        cout << "Constructor called." << endl;
    }

    // Move constructor
    Box(Box&& other) noexcept {
        data = other.data;
        other.data = nullptr;
        cout << "Move constructor called." << endl;
    }

    // Destructor
    ~Box() {
        delete data;
        cout << "Destructor called." << endl;
    }

    void display() {
        if (data != nullptr) {
            cout << "Data: " << *data << endl;
        } else {
            cout << "Data is nullptr." << endl;
        }
    }
};

int main() {
    Box box1(10.5); // Constructor is called
    Box box2 = std::move(box1); // Move constructor is called
    box2.display(); // Output: Data: 10.5
    box1.display(); // Output: Data is nullptr.
    return 0;
}
```

### 5. Delegating Constructor (C++11)

A delegating constructor allows a constructor to call another constructor in the same class.

#### Example of Delegating Constructor

```cpp
#include <iostream>
using namespace std;

class Box {
private:
    double length;
    double width;
    double height;

public:
    Box() : Box(0.0, 0.0, 0.0) { // Delegating constructor
        cout << "Default constructor called." << endl;
    }

    Box(double l, double w, double h) : length(l), width(w), height(h) { // Parameterized constructor
        cout << "Parameterized constructor called." << endl;
    }

    void display() {
        cout << "Length: " << length << ", Width: " << width << ", Height: " << height << endl;
    }
};

int main() {
    Box box1; // Default constructor is called, which delegates to the parameterized constructor
    box1.display(); // Output: Length: 0, Width: 0, Height: 0

    Box box2(10.5, 7.5, 5.5); // Parameterized constructor is called
    box2.display(); // Output: Length: 10.5, Width: 7.5, Height: 5.5
    return 0;
}
```

- **Default Constructor** : Initializes objects with default values.
- **Parameterized Constructor** : Initializes objects with specific values provided as arguments.
- **Copy Constructor** : Creates a new object as a copy of an existing object.
- **Move Constructor** : Efficiently transfers resources from a temporary object to a new object.
- **Delegating Constructor** : A constructor that calls another constructor in the same class to reuse code.

## Destructors

- A destructor in C++ is a special member function that is invoked automatically when an object goes out of scope or is explicitly deleted.
- Destructors are used to release resources that the object may have acquired during its lifetime, such as memory, file handles, or network connections.

### Key Features of Destructors

1. **Same Name as the Class** : The name of the destructor is the same as the class, preceded by a tilde (`~`).
2. **No Parameters** : Destructors do not take any parameters and do not return any values.
3. **One Destructor per Class** : Each class can have only one destructor.
4. **Automatic Invocation** : Destructors are called automatically when an object is destroyed, whether it goes out of scope, is explicitly deleted, or the program ends.

### Example of a Destructor

```cpp
#include <iostream>
using namespace std;

class Box {
private:
    double* length;

public:
    // Constructor
    Box(double l) {
        length = new double;
        *length = l;
        cout << "Constructor called. Length: " << *length << endl;
    }

    // Destructor
    ~Box() {
        delete length; // Release the allocated memory
        cout << "Destructor called. Memory released." << endl;
    }

    // Method to display length
    void display() {
        cout << "Length: " << *length << endl;
    }
};

int main() {
    Box box1(10.5); // Constructor is called
    box1.display(); // Output: Length: 10.5

    // Destructor will be called automatically when box1 goes out of scope

    return 0;
}
```

### When Destructors Are Called

1. **Object Goes Out of Scope** : When an object is created in a block (e.g., inside a function) and the block exits.
2. **Explicitly Deleted** : When `delete` is used on a dynamically allocated object.
3. **Program Ends** : When the program terminates, global and static objects are destroyed.
4. **Exception Handling** : When an exception is thrown and the stack unwinds, destructors for local objects are called.

### Example: Object Going Out of Scope

```cpp
#include <iostream>
using namespace std;

class Box {
public:
    Box() {
        cout << "Constructor called." << endl;
    }

    ~Box() {
        cout << "Destructor called." << endl;
    }
};

void createBox() {
    Box localBox; // Constructor is called here
} // Destructor is called when localBox goes out of scope

int main() {
    createBox(); // Calls createBox function
    return 0;
}
```

### Example: Explicitly Deleting Objects

```cpp
#include <iostream>
using namespace std;

class Box {
public:
    Box() {
        cout << "Constructor called." << endl;
    }

    ~Box() {
        cout << "Destructor called." << endl;
    }
};

int main() {
    Box* dynamicBox = new Box(); // Constructor is called
    delete dynamicBox; // Destructor is called
    return 0;
}
```

### Example: Destructor in Inheritance

When dealing with inheritance, destructors of derived classes and base classes are called in a specific order :

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    Base() {
        cout << "Base constructor called." << endl;
    }

    virtual ~Base() { // Use virtual destructor if the class is meant to be inherited from
        cout << "Base destructor called." << endl;
    }
};

class Derived : public Base {
public:
    Derived() {
        cout << "Derived constructor called." << endl;
    }

    ~Derived() {
        cout << "Derived destructor called." << endl;
    }
};

int main() {
    Base* basePtr = new Derived(); // Polymorphism: Base pointer to Derived object
    delete basePtr; // Correctly calls both Base and Derived destructors
    return 0;
}
```

### Best Practices for Destructors

1. **Virtual Destructors** : If you have a base class intended for polymorphism, make the destructor virtual to ensure the derived class's destructor is called.
2. **Resource Management** : Use destructors to release resources like memory, file handles, and network connections.
3. **Rule of Three** : If your class needs a custom destructor, it likely needs a custom copy constructor and copy assignment operator as well. This is known as the Rule of Three.
4. **Rule of Five** : In modern C++ (C++11 and later), if your class manages resources, also consider implementing the move constructor and move assignment operator, following the Rule of Five.

- **Destructor** : Special member function to clean up resources when an object is destroyed.
- **Naming** : Same as the class name, preceded by `~`.
- **Automatic Invocation** : Called when an object goes out of scope, is explicitly deleted, or when the program ends.
- **Inheritance** : Use virtual destructors in base classes intended for inheritance.

## Operator Overloading

- Operator overloading in C++ allows to redefine the behavior of operators for user-defined types (such as classes).
- This feature enhances the readability and usability of your classes by enabling operators to work with objects of your classes just as they do with fundamental data types.

### Key Points about Operator Overloading

1. **Syntax** : The keyword `operator` is followed by the operator to be overloaded.
2. **Member Function or Friend Function** : Operators can be overloaded as member functions or friend functions.
3. **Precedence and Associativity** : These properties of operators cannot be changed.
4. **Cannot Create New Operators** : You can only overload existing operators.

### Types of Operators That Can Be Overloaded

- **Arithmetic Operators** : `+`, `-`, `*`, `/`, `%`
- **Relational Operators** : `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical Operators** : `&&`, `||`, `!`
- **Bitwise Operators** : `&`, `|`, `^`, `~`, `<<`, `>>`
- **Assignment Operators** : `=`, `+=`, `-=`, `*=`, `/=`, `%=`
- **Increment/Decrement Operators** : `++`, `--`
- **Subscript Operator** : `[]`
- **Function Call Operator** : `()`
- **Dereference Operator** : `*`
- **Member Access Operators** : `->`, `.` (only `->` can be overloaded)

### Example : Overloading Arithmetic Operators

Let's start by overloading the `+` operator for a simple `Complex` class representing complex numbers.

#### Example of Overloading the `+` Operator

```cpp
#include <iostream>
using namespace std;

class Complex {
private:
    double real;
    double imag;

public:
    // Constructor
    Complex(double r = 0.0, double i = 0.0) : real(r), imag(i) {}

    // Overloading the + operator as a member function
    Complex operator+(const Complex& other) const {
        return Complex(real + other.real, imag + other.imag);
    }

    // Function to display the complex number
    void display() const {
        cout << real << " + " << imag << "i" << endl;
    }
};

int main() {
    Complex c1(3.0, 4.0);
    Complex c2(1.0, 2.0);
    Complex c3 = c1 + c2; // Using overloaded + operator

    c1.display(); // Output: 3 + 4i
    c2.display(); // Output: 1 + 2i
    c3.display(); // Output: 4 + 6i

    return 0;
}
```

### Example : Overloading the `<<` Operator

Overloading the `<<` operator allows you to use the `cout` stream to print objects of your class.

#### Example of Overloading the `<<` Operator

```cpp
#include <iostream>
using namespace std;

class Complex {
private:
    double real;
    double imag;

public:
    // Constructor
    Complex(double r = 0.0, double i = 0.0) : real(r), imag(i) {}

    // Overloading the << operator as a friend function
    friend ostream& operator<<(ostream& os, const Complex& c) {
        os << c.real << " + " << c.imag << "i";
        return os;
    }
};

int main() {
    Complex c1(3.0, 4.0);
    Complex c2(1.0, 2.0);

    cout << "Complex number 1: " << c1 << endl; // Output: 3 + 4i
    cout << "Complex number 2: " << c2 << endl; // Output: 1 + 2i

    return 0;
}
```

### Example : Overloading the Subscript Operator `[]`

Overloading the subscript operator allows you to access elements of a class that behaves like an array.

#### Example of Overloading the `[]` Operator

```cpp
#include <iostream>
using namespace std;

class Array {
private:
    int* arr;
    int size;

public:
    // Constructor
    Array(int s) : size(s) {
        arr = new int[size];
    }

    // Destructor
    ~Array() {
        delete[] arr;
    }

    // Overloading the [] operator
    int& operator[](int index) {
        if (index >= 0 && index < size) {
            return arr[index];
        } else {
            throw out_of_range("Index out of range");
        }
    }
};

int main() {
    Array array(5);

    // Using overloaded [] operator to set values
    for (int i = 0; i < 5; ++i) {
        array[i] = i * 10;
    }

    // Using overloaded [] operator to get values
    for (int i = 0; i < 5; ++i) {
        cout << array[i] << " "; // Output: 0 10 20 30 40
    }

    return 0;
}
```

- **Syntax** : Use the keyword `operator` followed by the operator to be overloaded.
- **Member Function** : If the left-hand operand is an object of the class.
- **Friend Function** : If the left-hand operand is not an object of the class or for operators that require more flexibility (like `<<` and `>>`).
- **Types of Operators** : Most operators can be overloaded, including arithmetic, relational, logical, bitwise, assignment, increment/decrement, subscript, function call, dereference, and member access operators.
- **Cannot Change Precedence** : Overloading operators does not change their precedence, associativity, or arity (number of operands).

## Type Conversion

- Type conversion in C++ refers to converting a value of one data type to another.
- This can be either implicit (automatic) or explicit (manual).

### Types of Type Conversion

1. **Implicit Conversion (Automatic)**
2. **Explicit Conversion (Casting)**
3. **User-Defined Conversion**

### 1. Implicit Conversion (Automatic)

- The compiler automatically converts one data type to another when it is safe and there is no risk of data loss.
- This is also known as "type promotion."

#### Example of Implicit Conversion

```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 42;
    double d = i; // int to double conversion
    cout << "Value of d: " << d << endl; // Output: 42

    double pi = 3.14;
    int x = pi; // double to int conversion (data loss)
    cout << "Value of x: " << x << endl; // Output: 3

    return 0;
}
```

### 2. Explicit Conversion (Casting)

- Explicit conversions are done using casting operators.
- C++ provides several ways to perform explicit type casting.

#### C-Style Casting

```cpp
#include <iostream>
using namespace std;

int main() {
    double d = 3.14;
    int i = (int)d; // C-style cast
    cout << "Value of i: " << i << endl; // Output: 3

    return 0;
}
```

#### C++ Casting Operators

- `static_cast`
- `dynamic_cast`
- `const_cast`
- `reinterpret_cast`

#### Example of `static_cast`

```cpp
#include <iostream>
using namespace std;

int main() {
    double d = 3.14;
    int i = static_cast<int>(d); // static_cast
    cout << "Value of i: " << i << endl; // Output: 3

    return 0;
}
```

### 3. User-Defined Conversion

- allows to define our own type conversions for user-defined types (classes).
- This can be done through conversion constructors and conversion functions.

#### Conversion Constructors

A conversion constructor is a single-argument constructor that allows conversion from a given type to the class type.

```cpp
#include <iostream>
using namespace std;

class Complex {
private:
    double real;
    double imag;

public:
    // Constructor
    Complex(double r = 0.0, double i = 0.0) : real(r), imag(i) {}

    // Conversion constructor
    Complex(int r) : real(r), imag(0.0) {
        cout << "Conversion constructor called." << endl;
    }

    void display() const {
        cout << real << " + " << imag << "i" << endl;
    }
};

int main() {
    Complex c1 = 7; // Conversion from int to Complex
    c1.display(); // Output: 7 + 0i

    return 0;
}
```

#### Conversion Functions

Conversion functions are member functions that convert an object of a class to another type.

```cpp
#include <iostream>
using namespace std;

class Complex {
private:
    double real;
    double imag;

public:
    // Constructor
    Complex(double r = 0.0, double i = 0.0) : real(r), imag(i) {}

    // Conversion function to double
    operator double() const {
        return real;
    }

    void display() const {
        cout << real << " + " << imag << "i" << endl;
    }
};

int main() {
    Complex c1(3.5, 2.5);
    double d = c1; // Conversion from Complex to double
    cout << "Value of d: " << d << endl; // Output: 3.5

    return 0;
}
```

- **Implicit Conversion** : Automatically performed by the compiler when safe.
- **Explicit Conversion (Casting)** : Performed manually using C-style casts or C++ casting operators like `static_cast`.
- **User-Defined Conversion** : Custom conversions defined in user-defined types (classes) using conversion constructors and conversion functions.

# Inheritance

## Concept Of Inheritance

- Inheritance is a fundamental concept in C++ and object-oriented programming (OOP) that allows a class (called the derived class) to inherit properties and behaviors (methods) from another class (called the base class).
- Inheritance promotes code reusability and establishes a hierarchical relationship between classes.

### Key Concepts of Inheritance

1. **Base Class (Parent Class)** : The class whose properties and behaviors are inherited.
2. **Derived Class (Child Class)** : The class that inherits from the base class.
3. **Access Specifiers** : Control the access level of the base class members in the derived class. The common access specifiers are `public`, `protected`, and `private`.

### Types of Inheritance

1. **Single Inheritance** : A derived class inherits from one base class.
2. **Multiple Inheritance** : A derived class inherits from more than one base class.
3. **Multilevel Inheritance** : A derived class is a base class for another derived class.
4. **Hierarchical Inheritance** : Multiple derived classes inherit from a single base class.
5. **Hybrid Inheritance** : A combination of two or more types of inheritance.

### Syntax of Inheritance

```cpp
class BaseClass {
    // Base class members
};

class DerivedClass : access_specifier BaseClass {
    // Derived class members
};
```

### Example: Single Inheritance

```cpp
#include <iostream>
using namespace std;

// Base class
class Animal {
public:
    void eat() {
        cout << "Eating..." << endl;
    }
};

// Derived class
class Dog : public Animal {
public:
    void bark() {
        cout << "Barking..." << endl;
    }
};

int main() {
    Dog myDog;
    myDog.eat();  // Inherited from Animal class
    myDog.bark(); // Specific to Dog class

    return 0;
}
```

### Access Specifiers and Inheritance

1. **Public Inheritance** : Public and protected members of the base class remain public and protected in the derived class.
2. **Protected Inheritance** : Public and protected members of the base class become protected in the derived class.
3. **Private Inheritance** : Public and protected members of the base class become private in the derived class.

### Example: Access Specifiers

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    int publicVar;
protected:
    int protectedVar;
private:
    int privateVar;
};

class DerivedPublic : public Base {
    // publicVar is public
    // protectedVar is protected
    // privateVar is not accessible
};

class DerivedProtected : protected Base {
    // publicVar is protected
    // protectedVar is protected
    // privateVar is not accessible
};

class DerivedPrivate : private Base {
    // publicVar is private
    // protectedVar is private
    // privateVar is not accessible
};

int main() {
    DerivedPublic dp;
    dp.publicVar = 5; // OK: publicVar is public in DerivedPublic

    // DerivedProtected and DerivedPrivate do not expose publicVar directly
    // dp.protectedVar and dp.privateVar are not accessible

    return 0;
}
```

### Example: Multiple Inheritance

In multiple inheritance, a derived class inherits from more than one base class.

```cpp
#include <iostream>
using namespace std;

class Base1 {
public:
    void display1() {
        cout << "Base1 display1" << endl;
    }
};

class Base2 {
public:
    void display2() {
        cout << "Base2 display2" << endl;
    }
};

class Derived : public Base1, public Base2 {
public:
    void display3() {
        cout << "Derived display3" << endl;
    }
};

int main() {
    Derived d;
    d.display1(); // From Base1
    d.display2(); // From Base2
    d.display3(); // From Derived

    return 0;
}
```

### Virtual Inheritance

Virtual inheritance is used to solve the diamond problem in multiple inheritance, where a derived class inherits from two classes that have a common base class.

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    void display() {
        cout << "Base display" << endl;
    }
};

class Derived1 : virtual public Base {};

class Derived2 : virtual public Base {};

class DerivedFinal : public Derived1, public Derived2 {};

int main() {
    DerivedFinal df;
    df.display(); // No ambiguity, Base::display is called

    return 0;
}
```

- **Inheritance** : Mechanism for one class to inherit properties and behaviors from another class.
- **Base Class** : The class being inherited from.
- **Derived Class** : The class that inherits from the base class.
- **Access Specifiers** : Control visibility of base class members in the derived class.
- **Single Inheritance** : One base class.
- **Multiple Inheritance** : More than one base class.
- **Multilevel Inheritance** : Inheritance chain involving multiple levels.
- **Hierarchical Inheritance** : Multiple derived classes from a single base class.
- **Hybrid Inheritance** : Combination of inheritance types.
- **Virtual Inheritance** : Solves the diamond problem in multiple inheritance.

## Types Of Inheritance

Inheritance is a key feature of object-oriented programming that allows a class to inherit properties and behaviors from another class.

### 1. Single Inheritance

Single inheritance occurs when a class (derived class) inherits from one base class.

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    void show() {
        cout << "Base class" << endl;
    }
};

class Derived : public Base {
public:
    void display() {
        cout << "Derived class" << endl;
    }
};

int main() {
    Derived obj;
    obj.show();    // Base class method
    obj.display(); // Derived class method
    return 0;
}
```

### 2. Multiple Inheritance

Multiple inheritance occurs when a class inherits from more than one base class.

```cpp
#include <iostream>
using namespace std;

class Base1 {
public:
    void show1() {
        cout << "Base1 class" << endl;
    }
};

class Base2 {
public:
    void show2() {
        cout << "Base2 class" << endl;
    }
};

class Derived : public Base1, public Base2 {
public:
    void display() {
        cout << "Derived class" << endl;
    }
};

int main() {
    Derived obj;
    obj.show1();   // Base1 class method
    obj.show2();   // Base2 class method
    obj.display(); // Derived class method
    return 0;
}
```

### 3. Multilevel Inheritance

Multilevel inheritance occurs when a class is derived from another derived class, forming a chain of inheritance.

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    void show() {
        cout << "Base class" << endl;
    }
};

class Intermediate : public Base {
public:
    void display() {
        cout << "Intermediate class" << endl;
    }
};

class Derived : public Intermediate {
public:
    void print() {
        cout << "Derived class" << endl;
    }
};

int main() {
    Derived obj;
    obj.show();    // Base class method
    obj.display(); // Intermediate class method
    obj.print();   // Derived class method
    return 0;
}
```

### 4. Hierarchical Inheritance

Hierarchical inheritance occurs when multiple classes inherit from a single base class.

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    void show() {
        cout << "Base class" << endl;
    }
};

class Derived1 : public Base {
public:
    void display1() {
        cout << "Derived1 class" << endl;
    }
};

class Derived2 : public Base {
public:
    void display2() {
        cout << "Derived2 class" << endl;
    }
};

int main() {
    Derived1 obj1;
    Derived2 obj2;

    obj1.show();     // Base class method
    obj1.display1(); // Derived1 class method

    obj2.show();     // Base class method
    obj2.display2(); // Derived2 class method
    return 0;
}
```

### 5. Hybrid Inheritance

- Hybrid inheritance is a combination of two or more types of inheritance.
- It can create complex inheritance structures.
- One common example is combining multiple and hierarchical inheritance to form a diamond shape, often solved using virtual inheritance to avoid ambiguity.

#### Diamond Problem Example

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    void show() {
        cout << "Base class" << endl;
    }
};

class Derived1 : virtual public Base {};

class Derived2 : virtual public Base {};

class DerivedFinal : public Derived1, public Derived2 {};

int main() {
    DerivedFinal obj;
    obj.show(); // No ambiguity due to virtual inheritance
    return 0;
}
```

- **Single Inheritance** : One derived class inherits from one base class.
- **Multiple Inheritance** : One derived class inherits from more than one base class.
- **Multilevel Inheritance** : A chain of inheritance where a class is derived from another derived class.
- **Hierarchical Inheritance** : Multiple derived classes inherit from a single base class.
- **Hybrid Inheritance** : A combination of different types of inheritance, such as multiple and hierarchical, potentially creating complex relationships.

## Protected Members

+ The `protected` access specifier allows class members (variables and functions) to be accessible within the same class, as well as in derived classes, but not from outside the class hierarchy.
- This makes `protected` a useful access level for designing class hierarchies where certain members should be shared with derived classes but not exposed to the outside world.

### Key Points about `protected` Members

- **Accessible in Base Class** : `protected` members can be accessed directly within the base class.
- **Accessible in Derived Classes** : `protected` members can be accessed directly within derived classes.
- **Not Accessible Outside** : `protected` members are not accessible from outside the class hierarchy.

### Syntax

```cpp
class Base {
protected:
    int protectedMember;
public:
    void setProtectedMember(int value) {
        protectedMember = value;
    }
};

class Derived : public Base {
public:
    void accessProtectedMember() {
        protectedMember = 10; // Accessing protected member in derived class
    }
};
```

### Example of `protected` Members

```cpp
#include <iostream>
using namespace std;

class Base {
protected:
    int protectedVar;

public:
    // Constructor
    Base() : protectedVar(0) {}

    // Member function to set the protected variable
    void setProtectedVar(int value) {
        protectedVar = value;
    }

    // Member function to display the protected variable
    void displayProtectedVar() const {
        cout << "Protected variable in Base: " << protectedVar << endl;
    }
};

class Derived : public Base {
public:
    // Member function to access and modify the protected variable
    void modifyProtectedVar(int value) {
        protectedVar = value; // Accessing protected member in derived class
    }

    // Member function to display the protected variable
    void displayDerivedVar() const {
        cout << "Protected variable in Derived: " << protectedVar << endl;
    }
};

int main() {
    Base baseObj;
    Derived derivedObj;

    // Accessing protected member through member function of Base class
    baseObj.setProtectedVar(5);
    baseObj.displayProtectedVar(); // Output: Protected variable in Base: 5

    // Accessing protected member through member function of Derived class
    derivedObj.modifyProtectedVar(10);
    derivedObj.displayDerivedVar(); // Output: Protected variable in Derived: 10

    // Direct access of protected member is not allowed
    // baseObj.protectedVar = 15; // Error: 'int Base::protectedVar' is protected within this context
    // derivedObj.protectedVar = 20; // Error: 'int Base::protectedVar' is protected within this context

    return 0;
}
```

### Explanation

- **Base Class** : The `Base` class has a `protected` member variable `protectedVar`. It also provides public member functions to set and display the value of `protectedVar`.
- **Derived Class** : The `Derived` class inherits from the `Base` class. It can access and modify the `protected` member variable `protectedVar` directly within its member functions.
- **Main Function** : In the `main` function, objects of `Base` and `Derived` classes are created. The `protected` member is accessed and modified using the member functions of these classes.

### Advantages of `protected` Members

- **Encapsulation** : Keeps data members protected from direct access while allowing derived classes to use them.
- **Controlled Access** : Provides a controlled way for derived classes to access and modify base class members without exposing them to the outside world.
- **Code Reusability** : Facilitates reusability by allowing derived classes to build on the functionality of the base class.

- **`protected` Members** : Accessible within the class itself and its derived classes.
- **Usage** : Useful for designing class hierarchies where derived classes need to access base class members without exposing them publicly.
- **Encapsulation** : Enhances encapsulation by hiding details from the outside world while sharing them within the class hierarchy.

## Overriding

- Overriding is a feature that allows a derived class to provide a specific implementation of a method that is already defined in its base class.
- This is a fundamental concept in object-oriented programming that supports polymorphism, allowing the behavior of a method to be determined at runtime based on the actual object type.

### Key Points about Method Overriding

1. **Base and Derived Class** : Method overriding involves a method in the base class and a method with the same signature in the derived class.
2. **Virtual Keyword** : The method in the base class must be declared with the `virtual` keyword to enable overriding.
3. **Same Signature** : The method in the derived class must have the same name, return type, and parameters as the method in the base class.
4. **Dynamic Binding** : Overriding enables dynamic binding, where the call to an overridden method is resolved at runtime based on the type of the object.

### Syntax

To override a method, declare the method in the base class as `virtual` and redefine it in the derived class.

```cpp
class Base {
public:
    virtual void show() {
        cout << "Base class show function" << endl;
    }
};

class Derived : public Base {
public:
    void show() override { // 'override' keyword is optional but recommended
        cout << "Derived class show function" << endl;
    }
};
```

### Example of Method Overriding

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    virtual void show() { // Virtual function
        cout << "Base class show function" << endl;
    }

    void display() {
        cout << "Base class display function" << endl;
    }
};

class Derived : public Base {
public:
    void show() override { // Overriding the base class method
        cout << "Derived class show function" << endl;
    }

    void display() { // Hiding the base class method
        cout << "Derived class display function" << endl;
    }
};

int main() {
    Base *bptr;
    Derived d;
    bptr = &d;

    // Virtual function, binded at runtime (Runtime polymorphism)
    bptr->show(); // Output: Derived class show function

    // Non-virtual function, binded at compile time
    bptr->display(); // Output: Base class display function

    return 0;
}
```

### Explanation

1. **Base Class** : The `Base` class has a virtual function `show()` and a regular function `display()`.
2. **Derived Class** : The `Derived` class overrides the `show()` function and hides the `display()` function.
3. **Main Function** : In the `main` function, a pointer to the `Base` class (`bptr`) is assigned the address of a `Derived` class object (`d`). 
    - When `bptr->show()` is called, the `show()` function in the `Derived` class is executed because `show()` is a virtual function and resolved at runtime.
    - When `bptr->display()` is called, the `display()` function in the `Base` class is executed because `display()` is not virtual and resolved at compile time.

### Virtual Destructors

When using inheritance and dynamic memory allocation, it is important to declare destructors as virtual to ensure proper resource cleanup.

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    virtual ~Base() { // Virtual destructor
        cout << "Base destructor called" << endl;
    }
};

class Derived : public Base {
public:
    ~Derived() {
        cout << "Derived destructor called" << endl;
    }
};

int main() {
    Base *bptr = new Derived();
    delete bptr; // Correctly calls both Base and Derived destructors
    return 0;
}
```

- **Method Overriding** : Allows a derived class to provide a specific implementation of a method defined in its base class.
- **Virtual Keyword** : The base class method must be declared with `virtual` to enable overriding.
- **Dynamic Binding** : Overriding enables runtime determination of method calls based on object type.
- **Virtual Destructors** : Ensure proper cleanup of resources in a class hierarchy.

## Virtual Base Class

- a virtual base class is used to solve the diamond problem in multiple inheritance, ensuring that only one instance of the base class is inherited by all derived classes.
- The diamond problem occurs when a class is derived from two classes that both inherit from a common base class, leading to ambiguity and redundancy.

### Diamond Problem

Consider the following example without using virtual inheritance:

```cpp
#include <iostream>
using namespace std;

class A {
public:
    void show() {
        cout << "Class A" << endl;
    }
};

class B : public A {
};

class C : public A {
};

class D : public B, public C {
};

int main() {
    D obj;
    obj.show(); // Ambiguity: which show() to call?
    return 0;
}
```

In this example, class `D` inherits from both `B` and `C`, which in turn both inherit from `A`. When `obj.show()` is called, it is ambiguous because `D` has two copies of `A`.

### Using Virtual Base Classes

- To resolve this ambiguity, we can use virtual inheritance.
- When a base class is inherited virtually, the derived classes share a single instance of the virtual base class.

### Syntax

```cpp
class Base {
    // Base class members
};

class Derived1 : virtual public Base {
    // Derived1 members
};

class Derived2 : virtual public Base {
    // Derived2 members
};

class FinalDerived : public Derived1, public Derived2 {
    // FinalDerived members
};
```

### Example with Virtual Inheritance

```cpp
#include <iostream>
using namespace std;

class A {
public:
    int value;
    A() : value(0) {}
    void show() {
        cout << "Class A, value: " << value << endl;
    }
};

class B : virtual public A {
};

class C : virtual public A {
};

class D : public B, public C {
};

int main() {
    D obj;
    obj.value = 10; // No ambiguity, only one instance of A
    obj.show(); // Correctly calls A::show()
    return 0;
}
```

### Explanation

1. **Virtual Inheritance** : Both `B` and `C` inherit from `A` using the `virtual` keyword. This ensures that only one instance of `A` is shared among `B` and `C`.
2. **Single Instance** : When `D` inherits from both `B` and `C`, it contains only one instance of `A`, eliminating the ambiguity and redundancy.
3. **Access Members** : Members of `A` can be accessed directly in `D` without ambiguity.

### Virtual Inheritance in Depth

#### Why Use Virtual Inheritance?

- **Avoid Redundancy** : Prevents multiple instances of the base class in the derived class hierarchy.
- **Eliminate Ambiguity** : Clarifies which base class member should be accessed when there are multiple inheritance paths.

#### Performance Considerations

- **Memory** : Virtual inheritance introduces some overhead in terms of memory and complexity because of the need to manage a single shared base class instance.
- **Speed** : Access to the virtual base class members may involve an additional level of indirection, potentially impacting performance.

#### Typical Use Cases

- **Complex Inheritance Hierarchies** : Virtual inheritance is especially useful in large systems with complex inheritance hierarchies where multiple inheritance is common.
- **Frameworks and Libraries** : Often used in frameworks and libraries where extensibility and reuse are important.

- **Virtual Base Class** : Used to ensure that only one instance of a base class is inherited by all derived classes in a multiple inheritance scenario.
- **Syntax** : Use the `virtual` keyword when inheriting the base class.
- **Solves Diamond Problem** : Prevents ambiguity and redundancy in class hierarchies.
- **Performance** : Introduces some overhead but necessary for complex inheritance structures.

# Polymorphism

## Pointers in C++

- Pointers in C++ are variables that store the memory address of another variable.
- They are a fundamental feature of the language, allowing for direct memory manipulation, dynamic memory allocation, and efficient array and data structure handling.

### Key Concepts of Pointers

1. **Pointer Declaration** : How to declare a pointer variable.
2. **Pointer Initialization** : How to assign an address to a pointer.
3. **Dereferencing** : How to access the value stored at the memory address a pointer points to.
4. **Pointer Arithmetic** : Performing operations on pointers, such as incrementing or decrementing to navigate through arrays.

### Pointer Declaration

A pointer is declared using the `*` operator.

```cpp
int *ptr;  // Declares a pointer to an integer
```

### Pointer Initialization

A pointer is initialized by assigning it the address of another variable using the address-of operator `&`.

```cpp
int var = 10;
int *ptr = &var;  // ptr now holds the address of var
```

### Dereferencing

Dereferencing a pointer means accessing the value at the memory address the pointer points to, using the `*` operator.

```cpp
int var = 10;
int *ptr = &var;
cout << *ptr << endl;  // Outputs: 10
```

### Example: Basic Pointer Usage

```cpp
#include <iostream>
using namespace std;

int main() {
    int var = 10;
    int *ptr = &var;

    cout << "Value of var: " << var << endl;
    cout << "Address of var: " << &var << endl;
    cout << "Pointer ptr stores address: " << ptr << endl;
    cout << "Value pointed to by ptr: " << *ptr << endl;

    return 0;
}
```

### Output

```
Value of var: 10
Address of var: 0x7ffee32b188c
Pointer ptr stores address: 0x7ffee32b188c
Value pointed to by ptr: 10
```

### Pointer Arithmetic

Pointers can be incremented or decremented to point to the next or previous memory location, respectively. This is particularly useful for navigating arrays.

```cpp
int arr[] = {10, 20, 30};
int *ptr = arr;

cout << *ptr << endl;      // Output: 10
cout << *(ptr + 1) << endl; // Output: 20
cout << *(ptr + 2) << endl; // Output: 30
```

### Advanced Concepts

#### Null Pointer

- A null pointer is a pointer that does not point to any valid memory location.
- It can be initialized using `nullptr` (or `NULL` in older C++).

```cpp
int *ptr = nullptr;
```

#### Void Pointer

- A void pointer (`void *`) can hold the address of any data type but cannot be dereferenced directly.
- It is often used for generic data storage and casting.

```cpp
void *ptr;
int x = 10;
ptr = &x;
// cout << *ptr; // Error: cannot dereference void pointer
```

#### Pointer to Pointer

A pointer to a pointer stores the address of another pointer, allowing for multiple levels of indirection.

```cpp
int x = 10;
int *ptr = &x;
int **pptr = &ptr;

cout << **pptr << endl; // Output: 10
```

### Functions and Pointers

Passing pointers to functions allows the function to modify the original variable.

```cpp
#include <iostream>
using namespace std;

void increment(int *ptr) {
    (*ptr)++;
}

int main() {
    int x = 10;
    increment(&x);
    cout << "Value of x after increment: " << x << endl; // Output: 11
    return 0;
}
```

### Dynamic Memory Allocation

Pointers are essential for dynamic memory allocation, which allows programs to request memory during runtime.

1. **Using `new` and `delete`**

```cpp
int *ptr = new int; // Allocate memory
*ptr = 10;
cout << *ptr << endl; // Output: 10
delete ptr; // Deallocate memory
```

2. **Allocating Arrays**

```cpp
int *arr = new int[5]; // Allocate memory for an array of 5 integers

for(int i = 0; i < 5; i++) {
    arr[i] = i + 1;
}

for(int i = 0; i < 5; i++) {
    cout << arr[i] << " "; // Output: 1 2 3 4 5
}

delete[] arr; // Deallocate memory
```

- **Pointers** : Variables that store memory addresses.
- **Declaration** : `type *pointerName;`
- **Initialization** : `pointerName = &variable;`
- **Dereferencing** : `*pointerName` to access the value.
- **Pointer Arithmetic** : Navigate through memory locations.
- **Advanced Concepts** : Null pointers, void pointers, pointers to pointers.
- **Dynamic Memory Allocation** : Using `new` and `delete` for runtime memory management.

## Pointers & Objects

- pointers can also be used with objects.
- This allows dynamic creation and manipulation of objects, passing objects to functions efficiently, and creating complex data structures like linked lists and trees.

### Key Concepts

1. **Object Pointers** : Declaring and using pointers to objects.
2. **Dynamic Allocation of Objects** : Creating objects dynamically using `new` and managing their lifecycle with `delete`.
3. **Accessing Members** : Using the arrow operator (`->`) to access members of an object through a pointer.
4. **Function Arguments** : Passing objects to functions by pointer.

### Object Pointers

#### Declaration

You can declare a pointer to an object just like you declare a pointer to a primitive type.

```cpp
class MyClass {
public:
    void display() {
        cout << "Display function called" << endl;
    }
};

int main() {
    MyClass obj;        // Normal object
    MyClass *ptr = &obj; // Pointer to object

    ptr->display();     // Accessing member using pointer
    return 0;
}
```

### Dynamic Allocation of Objects

You can dynamically allocate objects using the `new` operator and release the memory using the `delete` operator.

```cpp
class MyClass {
public:
    void display() {
        cout << "Display function called" << endl;
    }
};

int main() {
    MyClass *ptr = new MyClass; // Dynamically allocated object
    ptr->display();             // Accessing member using pointer

    delete ptr; // Deallocating memory
    return 0;
}
```

### Accessing Members

When you have a pointer to an object, you use the arrow operator (`->`) to access the object's members.

```cpp
class MyClass {
public:
    int value;
    void display() {
        cout << "Value: " << value << endl;
    }
};

int main() {
    MyClass obj;
    MyClass *ptr = &obj;

    ptr->value = 10; // Accessing and modifying member variable
    ptr->display();  // Calling member function
    return 0;
}
```

### Passing Objects to Functions

You can pass objects to functions using pointers, allowing the function to modify the original object.

```cpp
#include <iostream>
using namespace std;

class MyClass {
public:
    int value;
    void display() {
        cout << "Value: " << value << endl;
    }
};

void modify(MyClass *ptr) {
    ptr->value = 20;
}

int main() {
    MyClass obj;
    obj.value = 10;

    modify(&obj); // Passing object by pointer
    obj.display(); // Output: Value: 20

    return 0;
}
```

### Array of Objects

You can also create arrays of objects dynamically.

```cpp
#include <iostream>
using namespace std;

class MyClass {
public:
    int value;
    void display() {
        cout << "Value: " << value << endl;
    }
};

int main() {
    int n = 3;
    MyClass *arr = new MyClass[n]; // Dynamically allocated array of objects

    for (int i = 0; i < n; ++i) {
        arr[i].value = i + 1;
    }

    for (int i = 0; i < n; ++i) {
        arr[i].display();
    }

    delete[] arr; // Deallocating memory
    return 0;
}
```

### Example: Linked List Using Pointers and Objects

A linked list is a common data structure that can be implemented using pointers and objects.

```cpp
#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node *next;

    Node(int val) : data(val), next(nullptr) {}
};

class LinkedList {
public:
    Node *head;

    LinkedList() : head(nullptr) {}

    void insert(int val) {
        Node *newNode = new Node(val);
        newNode->next = head;
        head = newNode;
    }

    void display() {
        Node *current = head;
        while (current) {
            cout << current->data << " -> ";
            current = current->next;
        }
        cout << "NULL" << endl;
    }

    ~LinkedList() {
        Node *current = head;
        while (current) {
            Node *next = current->next;
            delete current;
            current = next;
        }
    }
};

int main() {
    LinkedList list;
    list.insert(1);
    list.insert(2);
    list.insert(3);

    list.display(); // Output: 3 -> 2 -> 1 -> NULL

    return 0;
}
```

- **Object Pointers** : Pointers can point to objects and are declared similarly to pointers to primitive types.
- **Dynamic Allocation** : Objects can be dynamically allocated using `new` and deallocated using `delete`.
- **Accessing Members** : Use the arrow operator (`->`) to access members of an object through a pointer.
- **Function Arguments** : Pass objects to functions by pointer to allow the function to modify the original object.
- **Array of Objects** : Dynamic arrays of objects can be created and managed using pointers.

## This Pointer

- The `this` pointer is a special pointer available to all non-static member functions in C++.
- It points to the object for which the member function is called.
- It is an implicit parameter to all non-static member functions and can be used to access the members of the object within the class.

### Key Points

1. **Implicit Pointer** : `this` is implicitly passed to all non-static member functions.
2. **Type** : `this` is a constant pointer (`MyClass* const this`).
3. **Usage** : Commonly used to refer to object members, resolve naming conflicts, and return the object itself.

### Example

Consider a simple class to illustrate the use of `this` pointer.

```cpp
#include <iostream>
using namespace std;

class MyClass {
private:
    int value;

public:
    // Constructor
    MyClass(int value) {
        this->value = value; // Using 'this' to distinguish between member variable and parameter
    }

    // Setter method
    void setValue(int value) {
        this->value = value; // Using 'this' to distinguish between member variable and parameter
    }

    // Getter method
    int getValue() const {
        return this->value; // Using 'this' to refer to the member variable
    }

    // Method to return the current object
    MyClass& increment() {
        this->value++;
        return *this; // Using 'this' to return the current object
    }
};

int main() {
    MyClass obj(10);
    cout << "Initial value: " << obj.getValue() << endl;

    obj.setValue(20);
    cout << "Updated value: " << obj.getValue() << endl;

    obj.increment().increment(); // Chaining member function calls
    cout << "Incremented value: " << obj.getValue() << endl;

    return 0;
}
```

### Output

```
Initial value: 10
Updated value: 20
Incremented value: 22
```

### Detailed Explanation

1. **Constructor** : In the constructor, `this->value` refers to the member variable `value`, while `value` refers to the constructor parameter. This disambiguation is necessary because both the parameter and the member variable have the same name.

2. **Setter Method** : Similarly, in the `setValue` method, `this->value` refers to the member variable, and `value` refers to the parameter. Using `this` helps avoid naming conflicts.

3. **Getter Method** : In the `getValue` method, `this->value` explicitly shows that we are returning the member variable `value`. Although `this` is not strictly necessary here, it can improve code clarity.

4. **Increment Method** : The `increment` method increments the `value` member variable and returns the current object using `*this`. This allows for method chaining, as shown in the `main` function with `obj.increment().increment()`.

### Common Uses of `this` Pointer

1. **Accessing Member Variables** : When the parameter name is the same as the member variable name.
2. **Returning Object from Method** : To allow method chaining by returning the current object.
3. **Passing Current Object** : To another function or method that requires a reference to the current object.

- **Implicit Pointer** : `this` is an implicit pointer to the current object.
- **Disambiguation** : Used to distinguish between member variables and parameters with the same name.
- **Method Chaining** : Facilitates method chaining by returning the current object.
- **Access Members** : Helps access object members within the class.

## Virtual & Pure Virtual Functions

Virtual and pure virtual functions are key features that enable polymorphism, allowing derived classes to override functions defined in base classes.

### Virtual Functions

- A virtual function is a member function in a base class that you can override in a derived class.
- The keyword `virtual` is used in the base class declaration to indicate that a function is virtual.

#### Key Points

1. **Allows Overriding** : Derived classes can provide a specific implementation.
2. **Polymorphism** : Enables calling the derived class's implementation through a base class pointer or reference.
3. **Runtime Determination** : The function to be called is determined at runtime.

### Example: Virtual Functions

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    virtual void display() {  // Virtual function
        cout << "Display from Base class" << endl;
    }
};

class Derived : public Base {
public:
    void display() override {  // Override virtual function
        cout << "Display from Derived class" << endl;
    }
};

int main() {
    Base *b;
    Derived d;
    b = &d;

    b->display();  // Calls Derived's display() because it is a virtual function

    return 0;
}
```

### Output

```
Display from Derived class
```

### Pure Virtual Functions

- A pure virtual function (or abstract function) is a virtual function that has no definition in the base class.
- It is declared by assigning `0` in its declaration. A class with at least one pure virtual function is an abstract class and cannot be instantiated.

#### Key Points

1. **Abstract Class** : A class with one or more pure virtual functions.
2. **No Implementation** : Pure virtual functions have no body in the base class.
3. **Must Override** : Derived classes must override pure virtual functions.

### Example: Pure Virtual Functions

```cpp
#include <iostream>
using namespace std;

class Base {
public:
    virtual void display() = 0;  // Pure virtual function
};

class Derived : public Base {
public:
    void display() override {  // Override pure virtual function
        cout << "Display from Derived class" << endl;
    }
};

int main() {
    // Base b; // Error: cannot declare variable 'b' to be of abstract type 'Base'
    Derived d;
    Base *b = &d;

    b->display();  // Calls Derived's display()

    return 0;
}
```

### Output

```
Display from Derived class
```

### Detailed Explanation

1. **Virtual Functions** :
   - Declared using the `virtual` keyword in the base class.
   - Can be overridden in any derived class.
   - Supports dynamic binding (resolved at runtime).

2. **Pure Virtual Functions** :
   - Declared by assigning `0` in the declaration (`virtual void display() = 0;`).
   - Makes the class abstract, meaning it cannot be instantiated.
   - Forces derived classes to provide an implementation.

### Abstract Classes

- An abstract class is a class that cannot be instantiated.
- It is intended to be a base class for other classes.
- Abstract classes contain at least one pure virtual function.

```cpp
class AbstractBase {
public:
    virtual void pureVirtualFunction() = 0;  // Pure virtual function
    void normalFunction() {
        cout << "Normal function in abstract base class" << endl;
    }
};
```

- **Virtual Functions** : Enable derived classes to override base class functions, supporting polymorphism and dynamic binding.
- **Pure Virtual Functions** : Declared with `= 0`, making the class abstract and forcing derived classes to implement the function.
- **Abstract Classes** : Cannot be instantiated and are used to define interfaces for other classes.

## Implementing Polymorphism

- Polymorphism is one of the core concepts of object-oriented programming (OOP).
- It allows objects to be treated as instances of their parent class rather than their actual class. The two main types of polymorphism in C++ are :

1. **Compile-time polymorphism (Static Binding)** : Achieved using function overloading and operator overloading.
2. **Run-time polymorphism (Dynamic Binding)** : Achieved using inheritance and virtual functions.

### Run-time Polymorphism

- Run-time polymorphism is implemented using virtual functions and pointers or references to base class objects.
- It allows a function to behave differently based on the object that is invoking it.

### Example: Run-time Polymorphism

Let's implement a simple example to demonstrate run-time polymorphism using inheritance and virtual functions.

```cpp
#include <iostream>
using namespace std;

// Base class
class Shape {
public:
    // Virtual function
    virtual void draw() {
        cout << "Drawing Shape" << endl;
    }

    // Virtual destructor
    virtual ~Shape() {}
};

// Derived class - Circle
class Circle : public Shape {
public:
    void draw() override {  // Override base class function
        cout << "Drawing Circle" << endl;
    }
};

// Derived class - Rectangle
class Rectangle : public Shape {
public:
    void draw() override {  // Override base class function
        cout << "Drawing Rectangle" << endl;
    }
};

// Function to demonstrate polymorphism
void demonstratePolymorphism(Shape* shape) {
    shape->draw();  // Call the overridden method
}

int main() {
    Shape* shape1 = new Circle();   // Pointer to base class holding derived class object
    Shape* shape2 = new Rectangle(); // Pointer to base class holding derived class object

    demonstratePolymorphism(shape1); // Output: Drawing Circle
    demonstratePolymorphism(shape2); // Output: Drawing Rectangle

    delete shape1;  // Clean up
    delete shape2;  // Clean up

    return 0;
}
```

### Output

```
Drawing Circle
Drawing Rectangle
```

### Explanation

1. **Virtual Function** : The `draw` function in the `Shape` class is declared as `virtual`. This allows derived classes to override it.
2. **Override** : The `Circle` and `Rectangle` classes override the `draw` function.
3. **Polymorphism** : The `demonstratePolymorphism` function takes a `Shape` pointer and calls `shape->draw()`. At runtime, the correct `draw` function is called based on the actual object type (`Circle` or `Rectangle`).

### Compile-time Polymorphism

Compile-time polymorphism is achieved through function overloading and operator overloading.

#### Function Overloading

```cpp
#include <iostream>
using namespace std;

class Print {
public:
    void display(int i) {
        cout << "Integer: " << i << endl;
    }

    void display(double f) {
        cout << "Float: " << f << endl;
    }

    void display(string s) {
        cout << "String: " << s << endl;
    }
};

int main() {
    Print obj;
    obj.display(5);         // Integer: 5
    obj.display(3.14);      // Float: 3.14
    obj.display("Hello");   // String: Hello

    return 0;
}
```

#### Operator Overloading

```cpp
#include <iostream>
using namespace std;

class Complex {
private:
    float real;
    float imag;

public:
    Complex() : real(0), imag(0) {}
    Complex(float r, float i) : real(r), imag(i) {}

    // Overload + operator
    Complex operator + (const Complex& obj) {
        Complex temp;
        temp.real = real + obj.real;
        temp.imag = imag + obj.imag;
        return temp;
    }

    void display() {
        cout << "Real: " << real << " Imag: " << imag << endl;
    }
};

int main() {
    Complex c1(3.3, 4.4);
    Complex c2(1.1, 2.2);
    Complex c3;

    c3 = c1 + c2;  // Add two objects

    c3.display();  // Real: 4.4 Imag: 6.6

    return 0;
}
```

- **Compile-time Polymorphism** : Achieved using function overloading and operator overloading.
- **Run-time Polymorphism** : Achieved using inheritance and virtual functions.
- **Virtual Functions** : Enable derived classes to override base class functions.
- **Polymorphic Behavior** : Allows calling derived class functions through base class pointers or references.

# I/O Files & Templates

## C++ Stream Classes

- C++ stream classes are part of the standard I/O library and are used for input and output operations.
- These classes provide a consistent interface for reading from and writing to different kinds of I/O devices, such as files, strings, and the console.
- The stream classes are defined in the `<iostream>` and `<fstream>` headers.

### Stream Class Hierarchy

The stream class hierarchy is built around several key classes, which can be divided into input and output streams :

- **Input Streams** : `istream`, `ifstream`, `istringstream`
- **Output Streams** : `ostream`, `ofstream`, `ostringstream`
- **Bidirectional Streams** : `iostream`, `fstream`, `stringstream`

### Key Stream Classes

1. **`istream`** : Base class for input streams.
2. **`ostream`** : Base class for output streams.
3. **`iostream`** : Base class for bidirectional streams.
4. **`ifstream`** : Derived from `istream`, used for file input.
5. **`ofstream`** : Derived from `ostream`, used for file output.
6. **`stringstream`** : Derived from `iostream`, used for string-based streams.

### Basic Input and Output with Streams

#### Console Input and Output

- The `cin` object is an instance of `istream` and is used for standard input (usually the keyboard).
- The `cout` object is an instance of `ostream` and is used for standard output (usually the screen).

```cpp
#include <iostream>
using namespace std;

int main() {
    int num;
    cout << "Enter a number: ";
    cin >> num;
    cout << "You entered: " << num << endl;
    return 0;
}
```

### File I/O with Streams

#### Reading from a File

To read from a file, you can use the `ifstream` class.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ifstream inputFile("example.txt"); // Open file for reading
    if (!inputFile) {
        cerr << "Unable to open file example.txt";
        return 1;
    }

    string line;
    while (getline(inputFile, line)) {
        cout << line << endl; // Output each line to the console
    }

    inputFile.close(); // Close the file
    return 0;
}
```

#### Writing to a File

To write to a file, you can use the `ofstream` class.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream outputFile("example.txt"); // Open file for writing
    if (!outputFile) {
        cerr << "Unable to open file example.txt";
        return 1;
    }

    outputFile << "Hello, world!" << endl; // Write to the file
    outputFile << "Writing to a file using ofstream." << endl;

    outputFile.close(); // Close the file
    return 0;
}
```

### String Streams

String streams allow you to use strings as if they were stream objects, which is useful for parsing and formatting strings.

#### Using `stringstream`

The `stringstream` class can be used to perform input and output operations on a string.

```cpp
#include <iostream>
#include <sstream>
using namespace std;

int main() {
    stringstream ss;
    ss << "123 456.78 ABC";
    
    int intVal;
    float floatVal;
    string strVal;

    ss >> intVal >> floatVal >> strVal;

    cout << "Integer: " << intVal << endl;
    cout << "Float: " << floatVal << endl;
    cout << "String: " << strVal << endl;

    return 0;
}
```

- **Input Streams (`istream`)** : Used for input operations.
- **Output Streams (`ostream`)** : Used for output operations.
- **File Streams (`ifstream`, `ofstream`)** : Used for file I/O.
- **String Streams (`stringstream`)** : Used for string-based I/O.

## Unformatted & Formatted I/O

C++ provides a variety of ways to perform input and output (I/O) operations. These can be broadly categorized into unformatted and formatted I/O.

### Unformatted I/O

- Unformatted I/O operations deal with raw data, without any formatting.
- These operations read or write data exactly as it is.
- The primary unformatted I/O functions in C++ are `get`, `getline`, `put`, and `write`.

#### Unformatted Input

- **`get()`** : Reads a single character from the input stream.
- **`getline()`** : Reads an entire line from the input stream until a newline character is encountered.

##### Example: `get()` and `getline()`

```cpp
#include <iostream>
using namespace std;

int main() {
    char ch;
    cout << "Enter a character: ";
    ch = cin.get();  // Reads a single character
    cout << "You entered: " << ch << endl;

    string line;
    cout << "Enter a line of text: ";
    cin.ignore();  // Ignore the leftover newline character from previous input
    getline(cin, line);  // Reads an entire line
    cout << "You entered: " << line << endl;

    return 0;
}
```

#### Unformatted Output

- **`put()`** : Writes a single character to the output stream.
- **`write()`** : Writes a block of data to the output stream.

##### Example: `put()` and `write()`

```cpp
#include <iostream>
using namespace std;

int main() {
    char ch = 'A';
    cout.put(ch);  // Writes a single character
    cout.put('\n');

    const char* str = "Hello, world!";
    cout.write(str, 13);  // Writes a block of data
    cout.put('\n');

    return 0;
}
```

### Formatted I/O

- Formatted I/O operations deal with data that is formatted in a human-readable way.
- These operations use the insertion (`<<`) and extraction (`>>`) operators for input and output.

#### Formatted Input

- **Extraction Operator (`>>`)** : Used to read formatted data from an input stream.

##### Example: Formatted Input

```cpp
#include <iostream>
using namespace std;

int main() {
    int num;
    float f;
    char str[20];

    cout << "Enter an integer: ";
    cin >> num;  // Reads an integer
    cout << "You entered: " << num << endl;

    cout << "Enter a floating-point number: ";
    cin >> f;  // Reads a float
    cout << "You entered: " << f << endl;

    cout << "Enter a string: ";
    cin >> str;  // Reads a string
    cout << "You entered: " << str << endl;

    return 0;
}
```

#### Formatted Output

- **Insertion Operator (`<<`)** : Used to write formatted data to an output stream.

##### Example: Formatted Output

```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 10;
    float f = 3.14;
    char str[] = "Hello";

    cout << "Integer: " << num << endl;  // Writes an integer
    cout << "Float: " << f << endl;  // Writes a float
    cout << "String: " << str << endl;  // Writes a string

    return 0;
}
```

### Manipulators

C++ provides several manipulators that can be used to format the output. Some common manipulators are `endl`, `setw`, `setprecision`, `fixed`, and `hex`.

##### Example: Using Manipulators

```cpp
#include <iostream>
#include <iomanip>  // Include header for manipulators
using namespace std;

int main() {
    int num = 255;
    float f = 123.456;

    cout << "Number in decimal: " << num << endl;
    cout << "Number in hex: " << hex << num << endl;

    cout << fixed << setprecision(2);  // Set precision for floating-point number
    cout << "Float with 2 decimal places: " << f << endl;

    cout << setw(10) << "Right aligned" << endl;  // Set width for output

    return 0;
}
```

- **Unformatted I/O** : Reads and writes raw data.
  - `get()`, `getline()`, `put()`, `write()`
- **Formatted I/O** : Reads and writes formatted data.
  - Extraction (`>>`) and insertion (`<<`) operators
- **Manipulators** : Provide additional control over formatting.
  - `endl`, `setw`, `setprecision`, `fixed`, `hex`

## Manipulators

- Manipulators are special functions that can be used to modify the input and output streams.
- They are typically used to format the output or to control the way data is read from an input stream.
- Manipulators can be used with the insertion (`<<`) and extraction (`>>`) operators.

### Commonly Used Manipulators

#### `endl`

The `endl` manipulator inserts a newline character into the output stream and flushes the buffer.

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, world!" << endl;
    cout << "This is a new line." << endl;
    return 0;
}
```

#### `setw`

- The `setw` manipulator sets the width of the next input or output field.
- It is included in the `<iomanip>` header.

```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    cout << setw(10) << "Hello" << endl;  // Output is right-aligned with a width of 10
    cout << setw(10) << "World" << endl;
    return 0;
}
```

#### `setprecision`

The `setprecision` manipulator sets the number of digits to be displayed for floating-point numbers.

```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    double pi = 3.141592653589793;
    cout << setprecision(5) << pi << endl;  // Outputs 3.1416
    cout << setprecision(10) << pi << endl; // Outputs 3.141592654
    return 0;
}
```

#### `fixed` and `scientific`

The `fixed` manipulator forces floating-point numbers to be displayed in fixed-point notation, while `scientific` forces them to be displayed in scientific notation.

```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    double num = 12345.6789;
    cout << fixed << num << endl;          // Outputs 12345.678900
    cout << scientific << num << endl;     // Outputs 1.234568e+04
    return 0;
}
```

#### `setfill`

The `setfill` manipulator sets the fill character used when padding a field to the specified width.

```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    cout << setfill('*') << setw(10) << "Hello" << endl;  // Outputs *****Hello
    cout << setfill('#') << setw(10) << "World" << endl;  // Outputs #####World
    return 0;
}
```

#### `boolalpha` and `noboolalpha`

- The `boolalpha` manipulator forces boolean values to be displayed as `true` or `false` instead of `1` or `0`.
- The `noboolalpha` manipulator reverses this effect.

```cpp
#include <iostream>
using namespace std;

int main() {
    bool flag = true;
    cout << boolalpha << flag << endl;     // Outputs true
    cout << noboolalpha << flag << endl;   // Outputs 1
    return 0;
}
```

#### `showpoint` and `noshowpoint`

- The `showpoint` manipulator forces floating-point numbers to always show the decimal point, even if there are no fractional digits.
- The `noshowpoint` manipulator reverses this effect.

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << showpoint << 100.0 << endl;    // Outputs 100.000
    cout << noshowpoint << 100.0 << endl;  // Outputs 100
    return 0;
}
```

### Summary of Common Manipulators

- **`endl`** : Inserts a newline and flushes the stream.
- **`setw`** : Sets the width for the next input/output operation.
- **`setprecision`** : Sets the precision for floating-point numbers.
- **`fixed`** : Forces floating-point numbers to use fixed-point notation.
- **`scientific`** : Forces floating-point numbers to use scientific notation.
- **`setfill`** : Sets the fill character for padding.
- **`boolalpha`** : Forces boolean values to be displayed as `true` or `false`.
- **`noboolalpha`** : Displays boolean values as `1` or `0`.
- **`showpoint`** : Forces the display of the decimal point for floating-point numbers.
- **`noshowpoint`** : Hides the decimal point if there are no fractional digits.

### Example Usage

```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    int num = 255;
    double pi = 3.14159;
    bool flag = true;

    cout << "Default boolean: " << flag << endl;
    cout << "Boolean with boolalpha: " << boolalpha << flag << endl;

    cout << "Number in hex: " << hex << num << endl;
    cout << "Number in decimal: " << dec << num << endl;

    cout << "Pi with setprecision(3): " << setprecision(3) << pi << endl;
    cout << "Pi with setprecision(5): " << setprecision(5) << pi << endl;

    cout << setfill('*') << setw(10) << "Hello" << endl;
    cout << setfill('#') << setw(10) << "World" << endl;

    return 0;
}
```

### Output

```
Default boolean: 1
Boolean with boolalpha: true
Number in hex: ff
Number in decimal: 255
Pi with setprecision(3): 3.14
Pi with setprecision(5): 3.1416
*****Hello
#####World
```

## File Management Functions

- File management involves performing operations like creating, reading, writing, and closing files.
- The `<fstream>` library provides classes and functions to handle file I/O operations.

### Key File Stream Classes

- **`ifstream`** : Input file stream (for reading from files).
- **`ofstream`** : Output file stream (for writing to files).
- **`fstream`** : File stream (for both reading from and writing to files).

### Basic File Operations

#### Opening and Closing Files

To perform any file operation, you must first open the file. After completing the operations, you should close the file.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    // Open a file for writing
    ofstream outFile("example.txt");
    if (!outFile) {
        cerr << "Unable to open file for writing";
        return 1;
    }
    outFile << "Hello, file!" << endl;
    outFile.close();  // Close the file

    // Open a file for reading
    ifstream inFile("example.txt");
    if (!inFile) {
        cerr << "Unable to open file for reading";
        return 1;
    }
    string line;
    while (getline(inFile, line)) {
        cout << line << endl;
    }
    inFile.close();  // Close the file

    return 0;
}
```

### Writing to a File

Use the `ofstream` class to write data to a file. 

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream outFile("example.txt");  // Open the file
    if (!outFile) {
        cerr << "Unable to open file for writing";
        return 1;
    }
    
    outFile << "This is an example of file writing." << endl;
    outFile << "Writing to a file using ofstream." << endl;
    
    outFile.close();  // Close the file
    return 0;
}
```

### Reading from a File

Use the `ifstream` class to read data from a file.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ifstream inFile("example.txt");  // Open the file
    if (!inFile) {
        cerr << "Unable to open file for reading";
        return 1;
    }
    
    string line;
    while (getline(inFile, line)) {  // Read line by line
        cout << line << endl;
    }
    
    inFile.close();  // Close the file
    return 0;
}
```

### File Modes

When opening a file, you can specify different modes that define the operations allowed on the file. Common modes include :

- **`ios::in`** : Open for reading.
- **`ios::out`** : Open for writing.
- **`ios::app`** : Append to the end of the file.
- **`ios::ate`** : Move to the end of the file on opening.
- **`ios::trunc`** : Truncate the file to zero length.
- **`ios::binary`** : Open in binary mode.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    // Open a file for reading and writing in binary mode
    fstream file("example.bin", ios::in | ios::out | ios::binary | ios::trunc);
    if (!file) {
        cerr << "Unable to open file";
        return 1;
    }
    
    // Write binary data to the file
    int num = 1234;
    file.write(reinterpret_cast<char*>(&num), sizeof(num));
    
    // Move to the beginning of the file
    file.seekg(0);
    
    // Read binary data from the file
    int readNum;
    file.read(reinterpret_cast<char*>(&readNum), sizeof(readNum));
    
    cout << "Read number: " << readNum << endl;
    
    file.close();  // Close the file
    return 0;
}
```

### Additional File Management Functions

#### Checking File Status

- **`is_open()`** : Checks if a file is open.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ifstream inFile("example.txt");
    if (inFile.is_open()) {
        cout << "File is open" << endl;
    } else {
        cout << "File is not open" << endl;
    }
    inFile.close();
    return 0;
}
```

#### File Position Functions

- **`tellg()`** : Returns the current get position.
- **`tellp()`** : Returns the current put position.
- **`seekg(pos)`** : Sets the get position to `pos`.
- **`seekp(pos)`** : Sets the put position to `pos`.

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    fstream file("example.txt", ios::in | ios::out | ios::trunc);
    file << "Hello, world!";
    
    // Get the current put position
    streampos pos = file.tellp();
    cout << "Current put position: " << pos << endl;
    
    // Move the get position to the beginning
    file.seekg(0);
    
    string str;
    file >> str;
    cout << "Read from file: " << str << endl;
    
    file.close();
    return 0;
}
```

- **Opening and Closing Files** : Use `ifstream` for reading, `ofstream` for writing, and `fstream` for both.
- **File Modes** : Specify how the file should be opened (e.g., read, write, append, binary).
- **Checking File Status** : Use `is_open()` to check if a file is open.
- **File Position Functions** : Use `tellg()`, `tellp()`, `seekg()`, and `seekp()` to manage file positions.

## File Modes

- File modes in C++ determine how a file is opened and what operations can be performed on it.
- They are specified using flags from the `ios` namespace, and they can be combined using the bitwise OR operator (`|`).

### Common File Modes

1. **`ios::in`** : Open for reading.
2. **`ios::out`** : Open for writing.
3. **`ios::app`** : Append to the end of the file.
4. **`ios::ate`** : Open and seek to the end of the file immediately after opening.
5. **`ios::trunc`** : Truncate the file to zero length if it already exists.
6. **`ios::binary`** : Open in binary mode (default is text mode).

### Combining File Modes

- You can combine file modes using the bitwise OR operator (`|`).
- For example, if you want to open a file for both reading and writing, you can combine `ios::in` and `ios::out`.

### Examples

#### Opening a File for Reading

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ifstream inputFile("example.txt", ios::in);
    if (!inputFile) {
        cerr << "Unable to open file for reading" << endl;
        return 1;
    }

    string line;
    while (getline(inputFile, line)) {
        cout << line << endl;
    }

    inputFile.close();
    return 0;
}
```

#### Opening a File for Writing

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream outputFile("example.txt", ios::out);
    if (!outputFile) {
        cerr << "Unable to open file for writing" << endl;
        return 1;
    }

    outputFile << "This is a line of text." << endl;
    outputFile.close();
    return 0;
}
```

#### Opening a File for Appending

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream outputFile("example.txt", ios::app);
    if (!outputFile) {
        cerr << "Unable to open file for appending" << endl;
        return 1;
    }

    outputFile << "This line will be appended." << endl;
    outputFile.close();
    return 0;
}
```

#### Opening a File in Binary Mode

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream outputFile("example.bin", ios::out | ios::binary);
    if (!outputFile) {
        cerr << "Unable to open file in binary mode" << endl;
        return 1;
    }

    int num = 12345;
    outputFile.write(reinterpret_cast<char*>(&num), sizeof(num));
    outputFile.close();
    return 0;
}
```

#### Opening a File for Both Reading and Writing

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    fstream file("example.txt", ios::in | ios::out);
    if (!file) {
        cerr << "Unable to open file for reading and writing" << endl;
        return 1;
    }

    string line;
    while (getline(file, line)) {
        cout << line << endl;
    }

    file.seekp(0, ios::end);
    file << "Appending to the same file." << endl;

    file.close();
    return 0;
}
```

#### Opening a File and Truncating It

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream outputFile("example.txt", ios::out | ios::trunc);
    if (!outputFile) {
        cerr << "Unable to open file and truncate it" << endl;
        return 1;
    }

    outputFile << "This will be the only content in the file." << endl;
    outputFile.close();
    return 0;
}
```

### Summary of File Modes

- **`ios::in`** : Opens the file for reading.
- **`ios::out`** : Opens the file for writing.
- **`ios::app`** : Opens the file for appending.
- **`ios::ate`** : Opens the file and seeks to the end.
- **`ios::trunc`** : Opens the file and truncates it to zero length.
- **`ios::binary`** : Opens the file in binary mode.

### Combining File Modes

- File modes can be combined using the bitwise OR operator (`|`) to create more complex file operations.
- For example, to open a file for both reading and writing in binary mode, you can use :

```cpp
fstream file("example.bin", ios::in | ios::out | ios::binary);
```

## Templates

- Templates in C++ allow you to write generic and reusable code.
- They enable you to define functions and classes that can operate with any data type, which makes your code more flexible and type-safe.

### Function Templates

- A function template defines a blueprint for a function that can work with any data type.
- Here’s how to define and use a function template :

#### Defining a Function Template

```cpp
#include <iostream>
using namespace std;

template <typename T>
T add(T a, T b) {
    return a + b;
}

int main() {
    cout << add(5, 3) << endl;          // Output: 8 (int)
    cout << add(5.5, 3.2) << endl;      // Output: 8.7 (double)
    return 0;
}
```

In this example :
- `template <typename T>` tells the compiler that `T` is a placeholder for any data type.
- `T add(T a, T b)` defines a function template where the data type `T` is used for the parameters and return type.
- The function `add` can then be called with different data types (e.g., `int`, `double`).

### Class Templates

- Class templates allow you to define a class that can work with any data type.
- Here’s how to define and use a class template :

#### Defining a Class Template

```cpp
#include <iostream>
using namespace std;

template <typename T>
class Container {
private:
    T value;
public:
    Container(T v) : value(v) {}
    void setValue(T v) { value = v; }
    T getValue() { return value; }
};

int main() {
    Container<int> intContainer(42);
    cout << intContainer.getValue() << endl; // Output: 42

    Container<string> stringContainer("Hello");
    cout << stringContainer.getValue() << endl; // Output: Hello

    return 0;
}
```

In this example :
- `template <typename T>` tells the compiler that `T` is a placeholder for any data type.
- `class Container` is defined as a template class that uses the data type `T`.
- `Container<int> intContainer(42);` creates an instance of `Container` with `int` as the data type.
- `Container<string> stringContainer("Hello");` creates an instance of `Container` with `string` as the data type.

### Template Specialization

- Sometimes, you might want to define a specific behavior for a particular data type.
- This is where template specialization comes in.

#### Function Template Specialization

```cpp
#include <iostream>
using namespace std;

template <typename T>
T max(T a, T b) {
    return (a > b) ? a : b;
}

// Specialization for const char*
template <>
const char* max<const char*>(const char* a, const char* b) {
    return (strcmp(a, b) > 0) ? a : b;
}

int main() {
    cout << max(10, 20) << endl;           // Output: 20 (int)
    cout << max(10.5, 20.5) << endl;       // Output: 20.5 (double)
    cout << max("apple", "banana") << endl; // Output: banana (const char*)

    return 0;
}
```

In this example :
- `template <> const char* max<const char*>(const char* a, const char* b)` is a specialization of the `max` function template for `const char*`.

### Class Template Specialization

```cpp
#include <iostream>
using namespace std;

template <typename T>
class Printer {
public:
    void print(T value) {
        cout << value << endl;
    }
};

// Specialization for char*
template <>
class Printer<char*> {
public:
    void print(char* value) {
        cout << "String: " << value << endl;
    }
};

int main() {
    Printer<int> intPrinter;
    intPrinter.print(42); // Output: 42

    Printer<char*> stringPrinter;
    stringPrinter.print("Hello"); // Output: String: Hello

    return 0;
}
```

In this example :
- `template <> class Printer<char*>` is a specialization of the `Printer` class template for `char*`.

### Template Parameters

Templates can accept non-type parameters as well. For example :

```cpp
#include <iostream>
using namespace std;

template <typename T, int size>
class Array {
private:
    T arr[size];
public:
    T& operator[](int index) {
        return arr[index];
    }
    int getSize() const {
        return size;
    }
};

int main() {
    Array<int, 5> intArray;
    for (int i = 0; i < intArray.getSize(); ++i) {
        intArray[i] = i * 2;
    }
    for (int i = 0; i < intArray.getSize(); ++i) {
        cout << intArray[i] << " "; // Output: 0 2 4 6 8
    }
    cout << endl;

    return 0;
}
```

In this example :
- `template <typename T, int size>` tells the compiler that `T` is a placeholder for any data type and `size` is a non-type parameter.
- `Array<int, 5> intArray;` creates an instance of `Array` with `int` as the data type and `5` as the size.

- **Function Templates** : Allow you to write generic functions.
- **Class Templates** : Allow you to write generic classes.
- **Template Specialization** : Define specific behavior for particular data types.
- **Template Parameters** : Templates can accept both type and non-type parameters.

## Exception Handling & Standard Template Library

### Exception Handling in C++

- Exception handling in C++ is a mechanism to handle runtime errors, allowing the program to continue executing or terminate gracefully.
- It uses three keywords : `try`, `catch`, and `throw`.

#### Basic Syntax

```cpp
try {
    // Code that may throw an exception
    throw exceptionType;
} catch (exceptionType e) {
    // Code to handle the exception
}
```

#### Example

```cpp
#include <iostream>
using namespace std;

int main() {
    try {
        int a = 10, b = 0;
        if (b == 0) {
            throw "Division by zero error!";
        }
        cout << a / b << endl;
    } catch (const char* msg) {
        cerr << "Error: " << msg << endl;
    }
    return 0;
}
```

### Standard Template Library (STL)

The Standard Template Library (STL) is a powerful set of C++ template classes to provide general-purpose classes and functions with templates that implement many popular and commonly used algorithms and data structures like vectors, lists, queues, and stacks.

#### Components of STL

1. **Containers** : Store collections of objects.
2. **Algorithms** : Perform operations on containers.
3. **Iterators** : Provide a way to access elements in containers.

#### Common STL Containers

1. **Sequence Containers** : Maintain the order of elements.
   - **`vector`**
   - **`deque`**
   - **`list`**

2. **Associative Containers** : Maintain a sorted order of elements.
   - **`set`**
   - **`multiset`**
   - **`map`**
   - **`multimap`**

3. **Unordered Containers** : Do not maintain order but provide fast access.
   - **`unordered_set`**
   - **`unordered_multiset`**
   - **`unordered_map`**
   - **`unordered_multimap`**

#### Example: Using `vector`

```cpp
#include <iostream>
#include <vector>
using namespace std;

int main() {
    vector<int> v; // Create a vector of integers

    // Add elements to the vector
    v.push_back(10);
    v.push_back(20);
    v.push_back(30);

    // Access elements using an iterator
    for (vector<int>::iterator it = v.begin(); it != v.end(); ++it) {
        cout << *it << " ";
    }
    cout << endl;

    // Access elements using range-based for loop
    for (int val : v) {
        cout << val << " ";
    }
    cout << endl;

    return 0;
}
```

### Example: Using `map`

```cpp
#include <iostream>
#include <map>
using namespace std;

int main() {
    map<string, int> ageMap;

    // Insert elements
    ageMap["Alice"] = 30;
    ageMap["Bob"] = 25;
    ageMap["Charlie"] = 35;

    // Access elements
    for (map<string, int>::iterator it = ageMap.begin(); it != ageMap.end(); ++it) {
        cout << it->first << ": " << it->second << endl;
    }

    // Find an element
    map<string, int>::iterator it = ageMap.find("Alice");
    if (it != ageMap.end()) {
        cout << "Alice is " << it->second << " years old." << endl;
    } else {
        cout << "Alice not found." << endl;
    }

    return 0;
}
```

### Example: Using `set`

```cpp
#include <iostream>
#include <set>
using namespace std;

int main() {
    set<int> s;

    // Insert elements
    s.insert(10);
    s.insert(20);
    s.insert(10); // Duplicate elements are not added
    s.insert(30);

    // Access elements
    for (set<int>::iterator it = s.begin(); it != s.end(); ++it) {
        cout << *it << " ";
    }
    cout << endl;

    // Check if an element exists
    if (s.find(20) != s.end()) {
        cout << "20 is in the set." << endl;
    } else {
        cout << "20 is not in the set." << endl;
    }

    return 0;
}
```

- **Exception Handling** : Use `try`, `catch`, and `throw` to manage runtime errors.
- **STL Containers** :
  - **Sequence Containers** : `vector`, `deque`, `list`.
  - **Associative Containers** : `set`, `multiset`, `map`, `multimap`.
  - **Unordered Containers** : `unordered_set`, `unordered_multiset`, `unordered_map`, `unordered_multimap`.
- **Iterators** : Used to traverse the elements in containers.
- **Algorithms** : Perform operations like sorting, searching, etc.

# Introduction to Python Programming

## The Basic Elements of Python

- Python is a high-level, interpreted programming language known for its readability and simplicity.
- Here are the basic elements you need to get started with Python :

### 1. **Variables and Data Types**

#### Variables
- Variables are used to store data values.
- Python has dynamic typing, so you don't need to declare the type of a variable explicitly.

```python
x = 10         # Integer
y = 3.14       # Float
name = "John"  # String
is_valid = True # Boolean
```

#### Data Types
Common data types in Python include:

- **Integer** (`int`)
- **Float** (`float`)
- **String** (`str`)
- **Boolean** (`bool`)
- **List** (`list`)
- **Tuple** (`tuple`)
- **Dictionary** (`dict`)
- **Set** (`set`)

### 2. **Basic Operators**

#### Arithmetic Operators
```python
a = 10
b = 3
print(a + b)  # Addition
print(a - b)  # Subtraction
print(a * b)  # Multiplication
print(a / b)  # Division
print(a % b)  # Modulus
print(a ** b) # Exponentiation
print(a // b) # Floor division
```

#### Comparison Operators
```python
a = 10
b = 3
print(a == b)  # Equal
print(a != b)  # Not equal
print(a > b)   # Greater than
print(a < b)   # Less than
print(a >= b)  # Greater than or equal to
print(a <= b)  # Less than or equal to
```

#### Logical Operators
```python
x = True
y = False
print(x and y)  # Logical AND
print(x or y)   # Logical OR
print(not x)    # Logical NOT
```

### 3. **Control Structures**

#### Conditional Statements
```python
x = 10
if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")
```

#### Loops

**For Loop**
```python
for i in range(5):  # 0 to 4
    print(i)

# Loop through a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

**While Loop**
```python
count = 0
while count < 5:
    print(count)
    count += 1
```

### 4. **Functions**

#### Defining and Calling Functions
```python
def greet(name):
    print(f"Hello, {name}")

greet("Alice")
```

#### Returning Values from Functions
```python
def add(a, b):
    return a + b

result = add(5, 3)
print(result)
```

### 5. **Lists**

Lists are ordered, mutable collections of items.

```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])         # Access by index
fruits.append("date")    # Add an item
print(fruits)
fruits.remove("banana")  # Remove an item
print(fruits)
```

### 6. **Tuples**

Tuples are ordered, immutable collections of items.

```python
coordinates = (10, 20)
print(coordinates[0])  # Access by index
```

### 7. **Dictionaries**

Dictionaries are unordered collections of key-value pairs.

```python
person = {"name": "John", "age": 30}
print(person["name"])     # Access by key
person["age"] = 31        # Modify value
person["city"] = "New York" # Add new key-value pair
print(person)
```

### 8. **Sets**

Sets are unordered collections of unique items.

```python
numbers = {1, 2, 3, 3}  # Duplicate 3 will be removed
print(numbers)
numbers.add(4)          # Add an item
print(numbers)
numbers.remove(2)       # Remove an item
print(numbers)
```

### 9. **String Manipulation**

```python
s = "hello"
print(s.upper())         # Convert to uppercase
print(s.lower())         # Convert to lowercase
print(s.replace("h", "y")) # Replace substring
print(s[1:4])            # Slicing
```

### 10. **Input and Output**

#### Getting User Input
```python
name = input("Enter your name: ")
print(f"Hello, {name}")
```

#### File I/O
```python
# Writing to a file
with open("example.txt", "w") as file:
    file.write("Hello, World!")

# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

### 11. **Exception Handling**

Handle runtime errors gracefully using `try`, `except`, `else`, and `finally`.

```python
try:
    x = int(input("Enter a number: "))
    print(10 / x)
except ValueError:
    print("Invalid input! Please enter a number.")
except ZeroDivisionError:
    print("Division by zero is not allowed.")
else:
    print("No exceptions occurred.")
finally:
    print("This will always be executed.")
```

- **Variables and Data Types** : Store and manage data.
- **Operators** : Perform operations on variables and values.
- **Control Structures** : Direct the flow of execution (if statements, loops).
- **Functions** : Encapsulate reusable code blocks.
- **Lists, Tuples, Dictionaries, Sets** : Handle collections of data.
- **String Manipulation** : Work with text data.
- **Input and Output** : Get user input and read/write files.
- **Exception Handling** : Manage runtime errors.

## Branching Programs

- Branching programs, also known as decision-making programs, allow the code to execute different parts of the program based on conditions.
- This is mainly achieved using conditional statements like `if`, `elif`, and `else`.

### Basic Conditional Statements

#### `if` Statement

The `if` statement is used to execute a block of code only if a specified condition is true.

```python
x = 10

if x > 5:
    print("x is greater than 5")
```

#### `if-else` Statement

The `if-else` statement provides an alternative block of code to execute if the condition is false.

```python
x = 3

if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

#### `if-elif-else` Statement

The `if-elif-else` statement allows checking multiple conditions.

```python
x = 7

if x > 10:
    print("x is greater than 10")
elif x > 5:
    print("x is greater than 5 but not greater than 10")
else:
    print("x is 5 or less")
```

### Nested Conditional Statements

You can nest conditional statements to create more complex branching logic.

```python
x = 10
y = 5

if x > 5:
    if y > 2:
        print("x is greater than 5 and y is greater than 2")
    else:
        print("x is greater than 5 but y is not greater than 2")
else:
    print("x is not greater than 5")
```

### Logical Operators

Logical operators can combine multiple conditions within a single `if` statement.

- **and** : Both conditions must be true
- **or** : At least one condition must be true
- **not** : Inverts the condition

```python
x = 8
y = 6

if x > 5 and y > 5:
    print("Both x and y are greater than 5")

if x > 10 or y > 5:
    print("Either x is greater than 10 or y is greater than 5")

if not (x > 10):
    print("x is not greater than 10")
```

### Examples of Branching Programs

#### Example 1: Even or Odd

A simple program to check if a number is even or odd.

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print("The number is even.")
else:
    print("The number is odd.")
```

#### Example 2: Grade Evaluation

A program to evaluate grades based on the score.

```python
score = int(input("Enter your score: "))

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
elif score >= 60:
    print("Grade: D")
else:
    print("Grade: F")
```

#### Example 3: Finding the Largest Number

A program to find the largest of three numbers.

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print(f"The largest number is {a}")
elif b >= a and b >= c:
    print(f"The largest number is {b}")
else:
    print(f"The largest number is {c}")
```

- **`if` Statement** : Executes a block of code if a condition is true.
- **`if-else` Statement** : Provides an alternative block of code if the condition is false.
- **`if-elif-else` Statement** : Checks multiple conditions and executes corresponding blocks of code.
- **Nested Conditional Statements** : Create complex decision-making structures by nesting `if` statements.
- **Logical Operators** : Combine multiple conditions using `and`, `or`, and `not`.

## Control Structures

- Control structures are essential elements in programming that control the flow of execution of statements in a program.
- In Python, control structures include conditional statements, loops, and branching statements.

### 1. Conditional Statements

#### `if` Statement

Executes a block of code if a specified condition is true.

```python
x = 10
if x > 5:
    print("x is greater than 5")
```

#### `if-else` Statement

Provides an alternative block of code to execute if the condition is false.

```python
x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

#### `if-elif-else` Statement

Checks multiple conditions in sequence.

```python
x = 7
if x > 10:
    print("x is greater than 10")
elif x > 5:
    print("x is greater than 5 but not greater than 10")
else:
    print("x is 5 or less")
```

### 2. Loops

#### `for` Loop

Iterates over a sequence (like a list, tuple, dictionary, set, or string) and executes a block of code for each item in the sequence.

```python
# Loop through a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# Loop through a range of numbers
for i in range(5):  # 0 to 4
    print(i)
```

#### `while` Loop

Executes a block of code as long as a specified condition is true.

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

### 3. Branching Statements

#### `break` Statement

Terminates the loop prematurely.

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

#### `continue` Statement

Skips the current iteration and proceeds to the next iteration of the loop.

```python
for i in range(10):
    if i == 5:
        continue
    print(i)
```

#### `pass` Statement

Acts as a placeholder, allowing you to write an empty block of code without causing an error.

```python
for i in range(5):
    if i == 3:
        pass  # Do nothing
    print(i)
```

### 4. Functions

Functions allow you to encapsulate a block of code into a reusable and callable unit.

#### Defining a Function

```python
def greet(name):
    print(f"Hello, {name}")

greet("Alice")
```

#### Function with Return Value

```python
def add(a, b):
    return a + b

result = add(5, 3)
print(result)
```

### 5. List Comprehensions

A concise way to create lists.

```python
# Basic list comprehension
squares = [x ** 2 for x in range(10)]
print(squares)

# List comprehension with condition
even_squares = [x ** 2 for x in range(10) if x % 2 == 0]
print(even_squares)
```

### 6. Dictionary Comprehensions

A concise way to create dictionaries.

```python
# Basic dictionary comprehension
squares_dict = {x: x ** 2 for x in range(10)}
print(squares_dict)

# Dictionary comprehension with condition
even_squares_dict = {x: x ** 2 for x in range(10) if x % 2 == 0}
print(even_squares_dict)
```

### Examples

#### Example 1 : Factorial using `for` Loop

```python
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

print(factorial(5))  # Output: 120
```

#### Example 2 : Fibonacci Sequence using `while` Loop

```python
def fibonacci(n):
    a, b = 0, 1
    sequence = []
    while len(sequence) < n:
        sequence.append(a)
        a, b = b, a + b
    return sequence

print(fibonacci(10))  # Output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

- **Conditional Statements** : `if`, `if-else`, and `if-elif-else` allow you to execute code based on conditions.
- **Loops** : `for` and `while` loops enable repeated execution of a block of code.
- **Branching Statements** : `break`, `continue`, and `pass` control the flow within loops.
- **Functions** : Encapsulate reusable code blocks.
- **List and Dictionary Comprehensions** : Provide concise ways to create lists and dictionaries.

## Strings & Input

Strings are a fundamental data type in Python used to handle text data.

### 1. String Basics

#### Creating Strings

Strings in Python can be created using single quotes, double quotes, or triple quotes (for multi-line strings).

```python
single_quote_string = 'Hello, World!'
double_quote_string = "Hello, World!"
triple_quote_string = """This is a
multi-line string."""
```

#### Accessing Characters

You can access individual characters in a string using indexing. Python uses zero-based indexing.

```python
s = "Hello"
print(s[0])  # Output: H
print(s[1])  # Output: e
```

#### Slicing Strings

You can extract a substring using slicing.

```python
s = "Hello, World!"
print(s[0:5])  # Output: Hello
print(s[7:12]) # Output: World
```

### 2. String Operations

#### Concatenation

Combine strings using the `+` operator.

```python
s1 = "Hello"
s2 = "World"
s3 = s1 + ", " + s2 + "!"
print(s3)  # Output: Hello, World!
```

#### Repetition

Repeat a string using the `*` operator.

```python
s = "Hello"
print(s * 3)  # Output: HelloHelloHello
```

#### Length

Get the length of a string using the `len()` function.

```python
s = "Hello, World!"
print(len(s))  # Output: 13
```

#### Membership

Check if a substring is present using the `in` keyword.

```python
s = "Hello, World!"
print("Hello" in s)  # Output: True
print("hello" in s)  # Output: False (case-sensitive)
```

### 3. String Methods

Python provides many built-in methods for string manipulation.

#### Changing Case

```python
s = "Hello, World!"
print(s.lower())  # Output: hello, world!
print(s.upper())  # Output: HELLO, WORLD!
print(s.title())  # Output: Hello, World!
print(s.capitalize())  # Output: Hello, world!
```

#### Stripping Whitespace

```python
s = "  Hello, World!  "
print(s.strip())  # Output: Hello, World!
print(s.lstrip()) # Output: Hello, World!  
print(s.rstrip()) # Output:   Hello, World!
```

#### Replacing Substrings

```python
s = "Hello, World!"
print(s.replace("World", "Python"))  # Output: Hello, Python!
```

#### Splitting and Joining

```python
s = "Hello, World!"
words = s.split()  # Default split by spaces
print(words)  # Output: ['Hello,', 'World!']

s2 = "Hello, World, Python"
words2 = s2.split(", ")  # Split by comma and space
print(words2)  # Output: ['Hello', 'World', 'Python']

joined = " ".join(words)  # Join list into a string with spaces
print(joined)  # Output: Hello, World!
```

### 4. String Formatting

#### Using f-strings (Python 3.6+)

```python
name = "Alice"
age = 30
print(f"My name is {name} and I am {age} years old.")
```

#### Using `format()`

```python
name = "Bob"
age = 25
print("My name is {} and I am {} years old.".format(name, age))
```

### 5. Handling User Input

The `input()` function is used to take input from the user. The input is always returned as a string.

```python
name = input("Enter your name: ")
print(f"Hello, {name}!")

# Converting input to an integer
age = int(input("Enter your age: "))
print(f"You are {age} years old.")
```

### Examples

#### Example 1: Checking Palindrome

A simple program to check if a given string is a palindrome.

```python
s = input("Enter a string: ")
if s == s[::-1]:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

#### Example 2: Count Vowels

A program to count the number of vowels in a given string.

```python
s = input("Enter a string: ")
vowels = "aeiouAEIOU"
count = 0

for char in s:
    if char in vowels:
        count += 1

print(f"The number of vowels in the string is: {count}")
```

- **Creating Strings** : Use single, double, or triple quotes.
- **Accessing Characters** : Use indexing and slicing.
- **String Operations** : Concatenation, repetition, length, and membership.
- **String Methods** : Changing case, stripping whitespace, replacing substrings, splitting, and joining.
- **String Formatting** : Use f-strings or the `format()` method.
- **Handling User Input** : Use the `input()` function to take input from the user.

## Iteration

Iteration allows you to execute a block of code repeatedly. Python provides several ways to perform iteration, including `for` loops, `while` loops, and comprehensions.

### 1. `for` Loop

The `for` loop in Python iterates over a sequence (like a list, tuple, dictionary, set, or string) and executes a block of code for each item in the sequence.

#### Iterating Over a List

```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

#### Iterating Over a Range of Numbers

```python
for i in range(5):  # 0 to 4
    print(i)
```

#### Iterating Over a String

```python
s = "Hello"
for char in s:
    print(char)
```

#### Iterating Over a Dictionary

```python
d = {"name": "Alice", "age": 25, "city": "New York"}
for key, value in d.items():
    print(f"{key}: {value}")
```

### 2. `while` Loop

The `while` loop executes a block of code as long as a specified condition is true.

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

### 3. Nested Loops

You can nest loops to perform iteration inside another iteration.

```python
for i in range(3):  # Outer loop
    for j in range(2):  # Inner loop
        print(f"i = {i}, j = {j}")
```

### 4. Loop Control Statements

#### `break`

Terminates the loop prematurely.

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

#### `continue`

Skips the current iteration and proceeds to the next iteration.

```python
for i in range(10):
    if i == 5:
        continue
    print(i)
```

#### `pass`

Acts as a placeholder, allowing you to write an empty block of code without causing an error.

```python
for i in range(5):
    if i == 3:
        pass  # Do nothing
    print(i)
```

### 5. List Comprehensions

A concise way to create lists.

```python
# Basic list comprehension
squares = [x ** 2 for x in range(10)]
print(squares)

# List comprehension with condition
even_squares = [x ** 2 for x in range(10) if x % 2 == 0]
print(even_squares)
```

### 6. Dictionary Comprehensions

A concise way to create dictionaries.

```python
# Basic dictionary comprehension
squares_dict = {x: x ** 2 for x in range(10)}
print(squares_dict)

# Dictionary comprehension with condition
even_squares_dict = {x: x ** 2 for x in range(10) if x % 2 == 0}
print(even_squares_dict)
```

### Examples

#### Example 1: Factorial Calculation

A program to calculate the factorial of a number using a `for` loop.

```python
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

print(factorial(5))  # Output: 120
```

#### Example 2: Fibonacci Sequence

A program to generate the first `n` Fibonacci numbers using a `while` loop.

```python
def fibonacci(n):
    a, b = 0, 1
    sequence = []
    while len(sequence) < n:
        sequence.append(a)
        a, b = b, a + b
    return sequence

print(fibonacci(10))  # Output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

#### Example 3: Prime Numbers

A program to print all prime numbers within a given range.

```python
def is_prime(num):
    if num < 2:
        return False
    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            return False
    return True

primes = [x for x in range(2, 50) if is_prime(x)]
print(primes)  # Output: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]
```

- **`for` Loop** : Iterates over a sequence (list, tuple, string, etc.).
- **`while` Loop** : Repeats as long as a condition is true.
- **Nested Loops** : Loop inside another loop.
- **Loop Control Statements** : `break`, `continue`, and `pass` to control the loop's flow.
- **List and Dictionary Comprehensions** : Concise ways to create lists and dictionaries.

## Functions & Scoping

- Functions are reusable blocks of code that perform a specific task.
- Scoping defines the accessibility of variables within different parts of the code.

### 1. Functions

#### Defining a Function

Use the `def` keyword to define a function.

```python
def greet(name):
    print(f"Hello, {name}!")
```

#### Calling a Function

Invoke the function by its name followed by parentheses.

```python
greet("Alice")  # Output: Hello, Alice!
```

#### Function Arguments

Functions can take arguments to pass data into them.

```python
def add(a, b):
    return a + b

result = add(5, 3)
print(result)  # Output: 8
```

#### Default Arguments

Specify default values for arguments.

```python
def greet(name, message="Hello"):
    print(f"{message}, {name}!")

greet("Bob")           # Output: Hello, Bob!
greet("Charlie", "Hi")  # Output: Hi, Charlie!
```

#### Variable-length Arguments

Use `*args` for variable-length positional arguments and `**kwargs` for variable-length keyword arguments.

```python
def print_numbers(*args):
    for number in args:
        print(number)

print_numbers(1, 2, 3, 4)

def print_info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

print_info(name="Alice", age=30)
```

### 2. Scoping

- Scoping rules determine the visibility and lifetime of variables.
- Python uses the LEGB (Local, Enclosing, Global, Built-in) rule.

#### Local Scope

Variables defined within a function are local to that function.

```python
def my_function():
    x = 10  # Local variable
    print(x)

my_function()  # Output: 10
# print(x)     # Error: x is not defined
```

#### Enclosing Scope

Nested functions can access variables from their enclosing functions.

```python
def outer_function():
    x = "outer"
    
    def inner_function():
        print(x)  # Accessing outer function's variable
    
    inner_function()

outer_function()  # Output: outer
```

#### Global Scope

Variables defined at the top level of a script or module are global.

```python
x = "global"

def my_function():
    print(x)  # Accessing global variable

my_function()  # Output: global
```

#### Built-in Scope

Python's built-in namespace contains functions like `print()`, `len()`, etc.

```python
print(len("Hello"))  # Output: 5
```

### 3. The `global` and `nonlocal` Keywords

#### `global` Keyword

To modify a global variable inside a function, use the `global` keyword.

```python
x = 5

def change_global():
    global x
    x = 10

change_global()
print(x)  # Output: 10
```

#### `nonlocal` Keyword

To modify a variable in the enclosing (non-global) scope, use the `nonlocal` keyword.

```python
def outer_function():
    x = "outer"
    
    def inner_function():
        nonlocal x
        x = "inner"
    
    inner_function()
    print(x)

outer_function()  # Output: inner
```

### 4. Anonymous (Lambda) Functions

Lambda functions are small anonymous functions defined using the `lambda` keyword.

```python
# Lambda function to add two numbers
add = lambda a, b: a + b
print(add(3, 5))  # Output: 8

# Lambda function for sorting
pairs = [(1, 'one'), (2, 'two'), (3, 'three')]
pairs.sort(key=lambda pair: pair[1])
print(pairs)  # Output: [(1, 'one'), (3, 'three'), (2, 'two')]
```

### Examples

#### Example 1: Calculating Factorial

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

print(factorial(5))  # Output: 120
```

#### Example 2: Checking Prime Number

```python
def is_prime(num):
    if num <= 1:
        return False
    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            return False
    return True

print(is_prime(11))  # Output: True
print(is_prime(4))   # Output: False
```

- **Defining Functions** : Use `def` keyword, can have arguments, default values, and variable-length arguments.
- **Scoping** : LEGB rule (Local, Enclosing, Global, Built-in) determines variable visibility.
- **`global` and `nonlocal`** : Keywords to modify variables in global and enclosing scopes.
- **Lambda Functions** : Anonymous functions created with the `lambda` keyword.

## Specifications

- Specifications in programming define the expected behavior and properties of functions, classes, and modules.
- specifications can be represented through docstrings, type hints, and comments.
- They help in understanding the code, ensuring correctness, and facilitating maintenance.

### 1. Docstrings

- Docstrings are a way to document Python code.
- They describe what a function, class, or module does.
- You can access them using the `__doc__` attribute or with the `help()` function.

#### Function Docstrings

A function's docstring explains what the function does, its parameters, and its return value.

```python
def add(a, b):
    """
    Add two numbers.
    
    Parameters:
    a (int or float): The first number.
    b (int or float): The second number.
    
    Returns:
    int or float: The sum of the two numbers.
    """
    return a + b

print(add.__doc__)
```

#### Class Docstrings

A class's docstring explains what the class represents and describes its methods.

```python
class Dog:
    """
    A class representing a dog.
    
    Attributes:
    name (str): The name of the dog.
    age (int): The age of the dog.
    """
    
    def __init__(self, name, age):
        """
        Initialize a new dog.
        
        Parameters:
        name (str): The name of the dog.
        age (int): The age of the dog.
        """
        self.name = name
        self.age = age

    def bark(self):
        """
        Make the dog bark.
        """
        return "Woof!"

print(Dog.__doc__)
print(Dog.bark.__doc__)
```

#### Module Docstrings

A module's docstring describes the contents of the module.

```python
"""
This module provides arithmetic operations.

Functions:
    add(a, b): Return the sum of two numbers.
    subtract(a, b): Return the difference between two numbers.
"""

def add(a, b):
    """Return the sum of two numbers."""
    return a + b

def subtract(a, b):
    """Return the difference between two numbers."""
    return a - b

print(__doc__)
```

### 2. Type Hints

- Type hints specify the expected types of variables, parameters, and return values.
- They improve code readability and help with static type checking tools like `mypy`.

#### Function Type Hints

```python
def add(a: int, b: int) -> int:
    return a + b

def greet(name: str) -> str:
    return f"Hello, {name}!"

# Example with type hints in the function definition
print(add(2, 3))  # Output: 5
print(greet("Alice"))  # Output: Hello, Alice!
```

#### Variable Type Hints

```python
from typing import List, Dict

# Specify the type of a list
numbers: List[int] = [1, 2, 3, 4, 5]

# Specify the type of a dictionary
person: Dict[str, str] = {"name": "Alice", "city": "Wonderland"}

print(numbers)
print(person)
```

### 3. Comments

- Comments explain code and are ignored by the Python interpreter.
- Use comments to clarify complex or important parts of the code.

#### Single-line Comments

```python
# This is a single-line comment
x = 42  # This is an inline comment explaining the variable
```

#### Multi-line Comments

```python
"""
This is a multi-line comment,
also known as a docstring, when used to document modules,
classes, and functions.
"""

'''
This is also a multi-line comment.
However, triple double-quotes are the preferred style for docstrings.
'''
```

### 4. Assertions

Assertions are used to verify that a condition holds true. If the condition is false, the program raises an `AssertionError`.

```python
def divide(a: int, b: int) -> float:
    assert b != 0, "The divisor b cannot be zero."
    return a / b

print(divide(10, 2))  # Output: 5.0
# print(divide(10, 0))  # Raises AssertionError: The divisor b cannot be zero.
```

### 5. Example

#### Example: Specifying a Function

Let's put together docstrings, type hints, and comments in a function specification.

```python
def factorial(n: int) -> int:
    """
    Calculate the factorial of a number.
    
    Parameters:
    n (int): The number to calculate the factorial of.
    
    Returns:
    int: The factorial of the number.
    
    Raises:
    ValueError: If n is a negative number.
    """
    if n < 0:
        raise ValueError("Input must be a non-negative integer.")
    if n == 0:
        return 1
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

# Example usage:
print(factorial(5))  # Output: 120
# print(factorial(-1))  # Raises ValueError: Input must be a non-negative integer.
```

- **Docstrings** : Provide documentation for functions, classes, and modules.
- **Type Hints** : Specify the expected types of variables, parameters, and return values.
- **Comments** : Explain code and improve readability.
- **Assertions** : Verify conditions and raise errors if they are not met.

## Recursion

- Recursion is a programming technique where a function calls itself to solve smaller instances of the same problem.
- It is useful for problems that can be broken down into smaller, similar sub-problems.
- recursion is supported and can be used effectively with proper base cases to avoid infinite recursion.

### Key Concepts

1. **Base Case** : The condition that stops the recursion.
2. **Recursive Case** : The part where the function calls itself with a smaller or simpler input.

### Basic Example

#### Factorial

The factorial of a non-negative integer \( n \) is the product of all positive integers less than or equal to \( n \). It can be defined recursively as:
- \( 0! = 1 \)
- \( n! = n \times (n-1)! \) for \( n > 0 \)

```python
def factorial(n):
    if n == 0:  # Base case
        return 1
    else:
        return n * factorial(n - 1)  # Recursive case

print(factorial(5))  # Output: 120
```

### Recursive Functions

#### Fibonacci Sequence

- The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones, usually starting with 0 and 1.
- It can be defined recursively as :
- \( F(0) = 0 \)
- \( F(1) = 1 \)
- \( F(n) = F(n-1) + F(n-2) \) for \( n > 1 \)

```python
def fibonacci(n):
    if n <= 0:  # Base case 1
        return 0
    elif n == 1:  # Base case 2
        return 1
    else:
        return fibonacci(n - 1) + fibonacci(n - 2)  # Recursive case

print(fibonacci(10))  # Output: 55
```

### Practical Example

#### Sum of a List

Summing all elements of a list using recursion.

```python
def sum_list(lst):
    if not lst:  # Base case: empty list
        return 0
    else:
        return lst[0] + sum_list(lst[1:])  # Recursive case

numbers = [1, 2, 3, 4, 5]
print(sum_list(numbers))  # Output: 15
```

#### Reverse a String

Reversing a string using recursion.

```python
def reverse_string(s):
    if len(s) == 0:  # Base case: empty string
        return s
    else:
        return s[-1] + reverse_string(s[:-1])  # Recursive case

print(reverse_string("hello"))  # Output: "olleh"
```

### Handling Recursion Depth

- Python has a limit on the depth of recursion to prevent infinite recursions and stack overflows.
- You can check and modify this limit using the `sys` module.

```python
import sys
print(sys.getrecursionlimit())  # Output: 1000 (default value)

# To change the recursion limit
sys.setrecursionlimit(1500)
```

### Recursion vs. Iteration

- While recursion can be elegant and straightforward for certain problems, it is not always the most efficient approach due to overheads of function calls and limited recursion depth.
- Iterative solutions can often be more efficient in terms of time and space.

#### Iterative Factorial

```python
def factorial_iterative(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

print(factorial_iterative(5))  # Output: 120
```

#### Iterative Fibonacci

```python
def fibonacci_iterative(n):
    if n <= 0:
        return 0
    elif n == 1:
        return 1
    else:
        a, b = 0, 1
        for _ in range(2, n + 1):
            a, b = b, a + b
        return b

print(fibonacci_iterative(10))  # Output: 55
```

### Tail Recursion

- Tail recursion is a special case of recursion where the recursive call is the last operation in the function.
- Python does not optimize tail recursion, unlike some other languages.
- Therefore, it is generally better to use iteration for problems that would naturally use tail recursion.

- **Base Case** : Stops the recursion.
- **Recursive Case** : Function calls itself with a simpler input.
- **Applications** : Factorial, Fibonacci, list sum, string reversal, etc.
- **Limitations** : Python's recursion limit and potential inefficiency.
- **Iteration** : Often more efficient alternative for deep recursion.

## Global Variables

- Global variables are variables that are defined outside of any function and can be accessed from any function within the same module.
- They have a global scope, meaning they can be used throughout the entire program.

### Key Concepts

1. **Definition** : Global variables are declared outside of all functions.
2. **Access** : They can be read from any function.
3. **Modification** : To modify a global variable within a function, the `global` keyword must be used.

### Example

#### Defining and Accessing Global Variables

```python
# Global variable
counter = 0

def increment():
    global counter  # Accessing the global variable
    counter += 1

increment()
increment()
print(counter)  # Output: 2
```

### Reading Global Variables

You can read global variables without using the `global` keyword.

```python
# Global variable
message = "Hello, World!"

def greet():
    print(message)  # Reading the global variable

greet()  # Output: Hello, World!
```

### Modifying Global Variables

To modify a global variable within a function, use the `global` keyword.

```python
# Global variable
count = 10

def update_count():
    global count  # Indicating that we are modifying the global variable
    count += 5

update_count()
print(count)  # Output: 15
```

### Best Practices

#### Minimize Global Variables

Global variables can lead to code that is difficult to understand and maintain. They can be modified from anywhere in the program, leading to unexpected side effects. It is generally best to minimize their use.

#### Use Constants

If a global variable should not be modified, consider using a constant. In Python, constants are typically defined using all uppercase letters.

```python
PI = 3.14159  # Constant value

def area_of_circle(radius):
    return PI * radius * radius

print(area_of_circle(5))  # Output: 78.53975
```

#### Avoid Global Variables in Large Programs

In larger programs, consider encapsulating variables within classes or passing them as arguments to functions to reduce dependency on global state.

### Example of Using Global and Local Variables

```python
# Global variable
total = 0

def add_to_total(amount):
    global total  # Modify the global variable
    total += amount

def print_total():
    print(f"Total: {total}")

add_to_total(10)
add_to_total(5)
print_total()  # Output: Total: 15
```

### Local vs. Global Variables

Local variables are defined within a function and can only be accessed within that function. They have a local scope.

```python
def my_function():
    local_var = "I'm local"  # Local variable
    print(local_var)

my_function()  # Output: I'm local
# print(local_var)  # Error: NameError: name 'local_var' is not defined
```

### Nested Functions and Global Variables

In nested functions, you can use the `global` keyword to modify a global variable, but it's often better to use the `nonlocal` keyword to modify variables from the enclosing (non-global) scope.

```python
x = "global"

def outer_function():
    x = "outer"
    
    def inner_function():
        nonlocal x  # Modify the variable from the enclosing scope
        x = "inner"
    
    inner_function()
    print(x)  # Output: inner

outer_function()
print(x)  # Output: global
```

- **Global Variables** : Defined outside of any function and can be accessed globally.
- **Access** : Readable from any function without special keywords.
- **Modification** : Use the `global` keyword within a function to modify a global variable.
- **Best Practices** : Minimize the use of global variables to avoid unexpected side effects and improve code maintainability. Use constants where appropriate.

## Strings

- Strings are sequences of characters used to store and manipulate text.
- strings are immutable, meaning their content cannot be changed after they are created.
- Python provides many built-in methods and operators to work with strings.

### Creating Strings

#### Single Quotes and Double Quotes

You can create strings using single quotes (`'`) or double quotes (`"`).

```python
single_quote_string = 'Hello, World!'
double_quote_string = "Hello, World!"
```

#### Triple Quotes

Triple quotes (`'''` or `"""`) are used for multi-line strings.

```python
multi_line_string = """This is a
multi-line string."""
```

### String Operations

#### Concatenation

Use the `+` operator to concatenate strings.

```python
greeting = "Hello"
name = "Alice"
message = greeting + ", " + name + "!"
print(message)  # Output: Hello, Alice!
```

#### Repetition

Use the `*` operator to repeat strings.

```python
repeat = "A" * 5
print(repeat)  # Output: AAAAA
```

#### Accessing Characters

You can access individual characters using indexing (0-based).

```python
word = "Python"
print(word[0])  # Output: P
print(word[-1])  # Output: n (negative index for last character)
```

#### Slicing

Extract substrings using slicing.

```python
word = "Python"
print(word[0:2])  # Output: Py
print(word[2:])  # Output: thon
print(word[:2])  # Output: Py
print(word[:])  # Output: Python
print(word[-3:])  # Output: hon
```

### String Methods

Python provides many methods to work with strings.

#### Common String Methods

```python
text = "hello world"

# Convert to uppercase
print(text.upper())  # Output: HELLO WORLD

# Convert to lowercase
print(text.lower())  # Output: hello world

# Capitalize the first letter
print(text.capitalize())  # Output: Hello world

# Title case (capitalize the first letter of each word)
print(text.title())  # Output: Hello World

# Strip whitespace from both ends
text_with_spaces = "  hello world  "
print(text_with_spaces.strip())  # Output: hello world

# Replace a substring
print(text.replace("world", "Python"))  # Output: hello Python

# Split a string into a list
print(text.split())  # Output: ['hello', 'world']

# Join a list into a string
words = ['hello', 'world']
print(" ".join(words))  # Output: hello world
```

### Formatting Strings

#### Using `f-strings` (formatted string literals)

```python
name = "Alice"
age = 30
print(f"My name is {name} and I am {age} years old.")  # Output: My name is Alice and I am 30 years old.
```

#### Using `str.format()`

```python
name = "Alice"
age = 30
print("My name is {} and I am {} years old.".format(name, age))  # Output: My name is Alice and I am 30 years old.
```

#### Using `%` Operator

```python
name = "Alice"
age = 30
print("My name is %s and I am %d years old." % (name, age))  # Output: My name is Alice and I am 30 years old.
```

### Checking String Content

#### `in` and `not in` Operators

```python
text = "hello world"
print("hello" in text)  # Output: True
print("Python" not in text)  # Output: True
```

#### String Methods for Checking Content

```python
text = "hello world"

# Check if the string starts with a substring
print(text.startswith("hello"))  # Output: True

# Check if the string ends with a substring
print(text.endswith("world"))  # Output: True

# Check if the string contains only alphabetic characters
print(text.isalpha())  # Output: False (because of the space)

# Check if the string contains only digits
print("12345".isdigit())  # Output: True

# Check if the string is alphanumeric
print("hello123".isalnum())  # Output: True
```

### Escape Characters

Use backslashes (`\`) for special characters in strings.

```python
# Newline
print("Hello\nWorld")  # Output: Hello (newline) World

# Tab
print("Hello\tWorld")  # Output: Hello (tab) World

# Backslash
print("This is a backslash: \\")  # Output: This is a backslash: \

# Single quote
print('It\'s a beautiful day')  # Output: It's a beautiful day

# Double quote
print("He said, \"Hello!\"")  # Output: He said, "Hello!"
```

### Raw Strings

Use `r` prefix for raw strings to ignore escape characters.

```python
raw_string = r"C:\Users\Alice\Documents"
print(raw_string)  # Output: C:\Users\Alice\Documents
```

### Examples

#### Example 1: Palindrome Check

```python
def is_palindrome(s):
    s = s.replace(" ", "").lower()  # Remove spaces and convert to lowercase
    return s == s[::-1]  # Check if the string is equal to its reverse

print(is_palindrome("A man a plan a canal Panama"))  # Output: True
```

#### Example 2: Count Vowels

```python
def count_vowels(s):
    vowels = "aeiou"
    return sum(1 for char in s if char.lower() in vowels)

print(count_vowels("Hello World"))  # Output: 3
```

- **Creating Strings** : Single quotes, double quotes, triple quotes.
- **Operations** : Concatenation, repetition, indexing, slicing.
- **Methods** : `upper()`, `lower()`, `capitalize()`, `title()`, `strip()`, `replace()`, `split()`, `join()`.
- **Formatting** : `f-strings`, `str.format()`, `%` operator.
- **Checking Content** : `in`, `not in`, `startswith()`, `endswith()`, `isalpha()`, `isdigit()`, `isalnum()`.
- **Escape Characters** : Newline (`\n`), tab (`\t`), backslash (`\\`), single quote (`\'`), double quote (`\"`).
- **Raw Strings** : Use `r` prefix to ignore escape characters.

## Tuples

- Tuples are immutable sequences used to store collections of items.
- They are similar to lists, but unlike lists, tuples cannot be changed after they are created.
- Tuples are defined by enclosing elements in parentheses `()`.

### Creating Tuples

#### Empty Tuple

```python
empty_tuple = ()
```

#### Single Element Tuple

To create a single element tuple, you need a trailing comma.

```python
single_element_tuple = (5,)
```

#### Multiple Elements Tuple

```python
tuple1 = (1, 2, 3)
tuple2 = ("apple", "banana", "cherry")
```

### Accessing Elements

Elements in a tuple can be accessed using indexing, similar to lists.

```python
my_tuple = (10, 20, 30, 40)

print(my_tuple[0])  # Output: 10
print(my_tuple[-1])  # Output: 40
```

### Slicing

You can slice tuples to create a new tuple from a subset of elements.

```python
my_tuple = (10, 20, 30, 40, 50)

print(my_tuple[1:3])  # Output: (20, 30)
print(my_tuple[:2])  # Output: (10, 20)
print(my_tuple[3:])  # Output: (40, 50)
print(my_tuple[:])  # Output: (10, 20, 30, 40, 50)
```

### Tuple Methods

Tuples have limited methods due to their immutability. The primary methods available are `count` and `index`.

#### `count()`

Returns the number of times a specified value appears in the tuple.

```python
my_tuple = (1, 2, 3, 2, 2, 4)

print(my_tuple.count(2))  # Output: 3
```

#### `index()`

Returns the index of the first occurrence of a specified value.

```python
my_tuple = (1, 2, 3, 4, 2)

print(my_tuple.index(2))  # Output: 1
```

### Tuple Operations

#### Concatenation

Tuples can be concatenated using the `+` operator.

```python
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)

result = tuple1 + tuple2
print(result)  # Output: (1, 2, 3, 4, 5, 6)
```

#### Repetition

Tuples can be repeated using the `*` operator.

```python
my_tuple = (1, 2, 3)

result = my_tuple * 3
print(result)  # Output: (1, 2, 3, 1, 2, 3, 1, 2, 3)
```

### Tuple Packing and Unpacking

#### Packing

Packing is the process of assigning multiple values to a tuple.

```python
my_tuple = 1, 2, 3  # Parentheses are optional
print(my_tuple)  # Output: (1, 2, 3)
```

#### Unpacking

Unpacking is the process of extracting values back into variables.

```python
my_tuple = (1, 2, 3)
a, b, c = my_tuple

print(a)  # Output: 1
print(b)  # Output: 2
print(c)  # Output: 3
```

### Nested Tuples

Tuples can contain other tuples, creating nested tuples.

```python
nested_tuple = (1, 2, (3, 4), (5, 6))

print(nested_tuple)  # Output: (1, 2, (3, 4), (5, 6))
print(nested_tuple[2])  # Output: (3, 4)
print(nested_tuple[2][1])  # Output: 4
```

### Tuple vs. List

- **Mutability**: Tuples are immutable, while lists are mutable.
- **Syntax**: Tuples use parentheses `()`, lists use square brackets `[]`.
- **Methods**: Lists have more methods due to their mutability.

### Example : Using Tuples in Functions

Tuples are often used to return multiple values from a function.

```python
def get_student_info():
    name = "John"
    age = 21
    course = "Computer Science"
    return name, age, course  # Returns a tuple

student_info = get_student_info()
print(student_info)  # Output: ('John', 21, 'Computer Science')

# Unpacking the tuple
name, age, course = student_info
print(name)   # Output: John
print(age)    # Output: 21
print(course) # Output: Computer Science
```

### Tuple Immutability

Because tuples are immutable, attempting to change an element will result in an error.

```python
my_tuple = (1, 2, 3)
# my_tuple[0] = 10  # TypeError: 'tuple' object does not support item assignment
```

### Use Cases for Tuples

- **Fixed Collections** : Use tuples to represent fixed collections of items, like coordinates `(x, y)`.
- **Returning Multiple Values** : Functions can return multiple values in a tuple.
- **Dictionary Keys** : Tuples can be used as keys in dictionaries because they are hashable.

- **Creation** : Using parentheses `()` or without parentheses.
- **Access** : Indexing and slicing.
- **Methods** : `count()` and `index()`.
- **Operations** : Concatenation (`+`), repetition (`*`).
- **Packing/Unpacking** : Assigning multiple values to/from tuples.
- **Immutability** : Tuples cannot be changed after creation.

## List

- Lists are one of the most versatile and commonly used data structures in Python.
- They are ordered, mutable collections of items, which means you can change their contents after they are created.

### Creating Lists

#### Empty List

```python
empty_list = []
```

#### List with Elements

```python
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3, 4, 5]
mixed = [1, "apple", 3.14, True]
```

### Accessing Elements

#### Indexing

Lists use zero-based indexing to access elements.

```python
fruits = ["apple", "banana", "cherry"]

print(fruits[0])  # Output: apple
print(fruits[1])  # Output: banana
print(fruits[-1])  # Output: cherry (last element)
```

#### Slicing

You can access a range of elements using slicing.

```python
numbers = [0, 1, 2, 3, 4, 5]

print(numbers[1:4])  # Output: [1, 2, 3]
print(numbers[:3])  # Output: [0, 1, 2]
print(numbers[3:])  # Output: [3, 4, 5]
print(numbers[:])  # Output: [0, 1, 2, 3, 4, 5]
print(numbers[::2])  # Output: [0, 2, 4] (step by 2)
```

### Modifying Lists

#### Changing Elements

```python
fruits = ["apple", "banana", "cherry"]
fruits[1] = "blueberry"
print(fruits)  # Output: ['apple', 'blueberry', 'cherry']
```

#### Adding Elements

- **`append()`** : Adds a single element to the end of the list.

    ```python
    fruits = ["apple", "banana"]
    fruits.append("cherry")
    print(fruits)  # Output: ['apple', 'banana', 'cherry']
    ```

- **`insert()`** : Adds an element at a specific position.

    ```python
    fruits = ["apple", "banana"]
    fruits.insert(1, "cherry")
    print(fruits)  # Output: ['apple', 'cherry', 'banana']
    ```

- **`extend()`** : Adds multiple elements to the end of the list.

    ```python
    fruits = ["apple", "banana"]
    fruits.extend(["cherry", "date"])
    print(fruits)  # Output: ['apple', 'banana', 'cherry', 'date']
    ```

#### Removing Elements

- **`remove()`** : Removes the first occurrence of a specific element.

    ```python
    fruits = ["apple", "banana", "cherry", "banana"]
    fruits.remove("banana")
    print(fruits)  # Output: ['apple', 'cherry', 'banana']
    ```

- **`pop()`** : Removes and returns an element at a specific position. By default, it removes the last element.

    ```python
    fruits = ["apple", "banana", "cherry"]
    fruit = fruits.pop(1)
    print(fruit)  # Output: banana
    print(fruits)  # Output: ['apple', 'cherry']
    ```

- **`clear()`** : Removes all elements from the list.

    ```python
    fruits = ["apple", "banana", "cherry"]
    fruits.clear()
    print(fruits)  # Output: []
    ```

### List Operations

#### Concatenation

```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined = list1 + list2
print(combined)  # Output: [1, 2, 3, 4, 5, 6]
```

#### Repetition

```python
numbers = [1, 2, 3]
repeated = numbers * 3
print(repeated)  # Output: [1, 2, 3, 1, 2, 3, 1, 2, 3]
```

#### Membership

```python
fruits = ["apple", "banana", "cherry"]
print("apple" in fruits)  # Output: True
print("date" not in fruits)  # Output: True
```

### List Methods

- **`index()`** : Returns the index of the first occurrence of a specified element.

    ```python
    fruits = ["apple", "banana", "cherry"]
    print(fruits.index("banana"))  # Output: 1
    ```

- **`count()`** : Returns the number of times a specified element appears in the list.

    ```python
    numbers = [1, 2, 3, 1, 1, 2]
    print(numbers.count(1))  # Output: 3
    ```

- **`sort()`** : Sorts the list in ascending order.

    ```python
    numbers = [3, 1, 4, 1, 5, 9]
    numbers.sort()
    print(numbers)  # Output: [1, 1, 3, 4, 5, 9]
    ```

- **`reverse()`** : Reverses the order of elements in the list.

    ```python
    numbers = [3, 1, 4, 1, 5, 9]
    numbers.reverse()
    print(numbers)  # Output: [9, 5, 1, 4, 1, 3]
    ```

- **`copy()`** : Returns a shallow copy of the list.

    ```python
    original = [1, 2, 3]
    copy = original.copy()
    print(copy)  # Output: [1, 2, 3]
    ```

### List Comprehensions

List comprehensions provide a concise way to create lists.

```python
# Create a list of squares
squares = [x**2 for x in range(10)]
print(squares)  # Output: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

### Nested Lists

Lists can contain other lists, creating nested structures.

```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

print(matrix[1][1])  # Output: 5
```

### Example : Using Lists

#### Example 1 : Finding the Maximum Element

```python
numbers = [10, 20, 30, 40, 50]
max_number = max(numbers)
print(max_number)  # Output: 50
```

#### Example 2 : Filtering Even Numbers

```python
numbers = [1, 2, 3, 4, 5, 6]
even_numbers = [num for num in numbers if num % 2 == 0]
print(even_numbers)  # Output: [2, 4, 6]
```

- **Creation** : Using square brackets `[]`.
- **Access** : Indexing, slicing.
- **Modification** : Changing elements, adding (`append()`, `insert()`, `extend()`), removing (`remove()`, `pop()`, `clear()`).
- **Operations** : Concatenation, repetition, membership.
- **Methods** : `index()`, `count()`, `sort()`, `reverse()`, `copy()`.
- **Comprehensions** : Concise way to create lists.
- **Nested Lists** : Lists within lists for complex data structures.
