---
layout: post
title: Basic Structure and Syntax of C Programming Language
date: 2025-09-23 22:30:00
description: an example of a blog post with some code on the structure and syntax of C language
tags: C-programming
categories: sample-posts
featured: true
---

## 🎯 Lab Objective
The objective of this lab is to:
- Understand the **basic structure** of a C program.
- Learn the role of **header files, main function, and statements**.
- Write, compile, and execute a simple C program.
- Get familiar with **syntax rules** such as semicolons, case-sensitivity, and indentation.


## 📖 Background
C is one of the most widely used programming languages, developed by **Dennis Ritchie** in the early 1970s at Bell Labs. It is the foundation of many modern languages (like C++, Java, and Python).

A C program typically contains:
1.  **Preprocessor directives** (like `#include`)
2.  **Main function** (`int main()`)
3.  **Variable declarations**
4.  **Statements** for input/output, processing, and logic
5.  **Return statement** to end the program

## 🧩 General Structure of a C Program

```c
#include <stdio.h>    // Preprocessor directive

// Main function: program execution starts here
int main() {
    // Variable declaration
    int number;

    // Input from user
    printf("Enter a number: ");
    scanf("%d", &number);

    // Output
    printf("You entered: %d\n", number);

    return 0;   // Exit status
}
```

##🔎 Explanation of Each Part
1. Preprocessor Directives

Lines starting with `#` are instructions to the compiler before actual compilation.

Example: 
```c
#include <stdio.h>    
```
Includes the **Standard Input Output library** so that we can use `printf()` and `scanf()` 

2. Main Function

Every C program must have `main()` 
Execution begins here:
```c
int main() { ... } 
```
3. Variable Declarations

All variables must be declared before use.
Example:
```c
int number;
```
4. Input and Output

- Input:
```c
scanf("%d", &number);
```
- Output:
```c
printf("You entered: %d\n", number);
```
5. Return Statement

Ends the program and returns control to the operating system:
```c
return 0;
```

## Syntax Rules in C

- Every statement must end with a semicolon (;).
- C is case-sensitive (main ≠ Main).
- Curly braces {} define the beginning and end of code blocks.
- Indentation and spacing are not mandatory, but they improve readability.
