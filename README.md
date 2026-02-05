# PYTHON

### Index 

* [History of PYTHON](#history-of-PYTHON)
* [Features of PYTHON](#features-of-python)
* [Basics](#basics)
* [Header Files](#header-files)
* [Data Handling](#data-handling)
* [Flow of Control](#flow-of-control)
* [Functions](#functions)
* [Arrays](https://github.com/Saujanya-rajvanshi/Arrays-)
* [Pointers](#pointers)
* [Dynamic Memory Allocation](#dynamic-memory-allocation)
* [Structures & Unions](#structures-unions)
* [File Handling](#file-handling)
* [Preprocessor & Macros](#preprocessor-macros)
* [String Handling](#string-handling)
* [Standard Libraries](#standard-libraries)
* [Advanced Concepts](#advanced-concepts)
* [Competitive Programming / DSA Readiness](#competitive-programming)
* [Basic Maths Codes](https://github.com/Saujanya-rajvanshi/basic-maths)

---

###### history of PYTHON
# 🎗 HISTORY
Python is one of the most popular, high-level, general-purpose programming languages. It was created with a focus on code readability and allows developers to write concepts in fewer lines compared to C++ or Java.

* Who Invented Python? <br>
**Creator :** Guido van Rossum <br>
**Started :** 1989, at Centrum Wiskunde & Informatica (CWI), Netherlands <br>
**First Release :** 1991 <br>
**Reason :** Started as a hobby project during Christmas holidays <br>
**Predecessor :** Inspired by the ABC language, but Guido improved it by fixing its limitations <br>

* Why is it called Python? <br>
Named after the BBC comedy series “Monty Python’s Flying Circus” <br>
Guido wanted a name that was short, unique, and a little mysterious <br>
He served as Python’s BDFL (Benevolent Dictator for Life) until 2018 <br>
Worked at Google and later at Dropbox <br>

<img width="1080" height="1955" alt="image" src="https://github.com/user-attachments/assets/2f9e46e2-3bc9-416b-b72c-b0488bc2728c" />

* Evolution of Python
When first released, Python already supported: <br>
Classes with inheritance <br>
Core data types <br>
Exception handling <br>
Functions <br>

* Key Versions: <br>
Python 2.x → Popular for many years, but now outdated <br>
Python 3.x → Current standard, actively developed <br>
Latest Version: Python 3.12.1 (as of now) <br>

###### features of python
# 🎗 FEATURES OF PYTHON

1. **Free & Open Source**
   Python is free to use and its source code is publicly available.

2. **Easy to Code**
   Simple syntax, fewer lines of code, beginner-friendly.

3. **Easy to Read**
   Uses **indentation instead of braces or semicolons**, making code readable.

4. **Object-Oriented**
   Supports classes, objects, inheritance, encapsulation, etc.

5. **GUI Programming Support**
   GUI apps can be built using **Tkinter, PyQt, wxPython**.

6. **High-Level Language**
   No need to manage memory or hardware details.

7. **Large Community Support**
   Huge support through forums, StackOverflow, documentation.

8. **Easy to Debug**
   Clear error messages and line-by-line execution.

9. **Portable (Platform Independent)**
   Same code runs on **Windows, Linux, macOS** without modification.

10. **Integrated Language**
    Can be integrated with **C, C++, Java**, etc.

11. **Interpreted Language**
    Code executes **line by line**, no separate compilation needed.

12. **Large Standard Library**
    Built-in libraries for regex, testing, web, math, etc.

13. **Dynamically Typed**
    Variable type decided at **runtime**, no declaration required.

14. **Frontend & Backend Support**

    * Frontend: PyScript
    * Backend: Django, Flask

15. **Dynamic Memory Allocation**
    Memory allocated automatically at runtime.

---

###### basics
# 🎗 BASICS

* [character set](#character-set)
* [tokens](#tokens)
* [Barebones of Program](#barebones-of-program)
* [Data Types (overview)](#data-types-overview)
* [Variables & Constants](#variables--constants)
* [Type Modifiers](#type-modifiers)
* [Type Conversion / Type Casting](#type-conversion--type-casting)
* [sizeof equivalent](#sizeof-equivalent)
* [Comments](#comments)
* [data handling](#data-handling-basics)
* [boiler plate code](#boiler-plate-code)
* [next line](#next-line)
* [Escape Sequences](#escape-sequences)
* [output & input](#output--input)


###### character set
## 🧩 character set

✅ **NO major difference (conceptually)**

* **Letters:** A–Z, a–z
* **Digits:** 0–9
* **Special symbols:** `+ - * / % = < > ! & | ^ ~ ? : ; , . ' " # @ _ ( ) { } [ ]`
* **Whitespace:** space, tab (`\t`), newline (`\n`)

📌 Python is **Unicode-based**, supports emojis & international characters.

###### tokens
## 🧩 tokens

Tokens are the **smallest units** of a Python program.
* **Keywords**
* **Identifiers**
* **Literals**
* **Operators**
* **Delimiters**


### 💎 KEYWORDS

❌ **NOT in Python (C++ only)**

* int, float, double, char
* static, extern, register
* switch, case
* goto
* sizeof
* const, constexpr

✅ **Python Keywords**

* if, elif, else
* for, while, break, continue, pass
* def, return, lambda
* class, object
* import, from, as
* try, except, finally
* True, False, None

📌 **Python ≈ 35 keywords**

### 💎 IDENTIFIER

✅ **Almost same rules**

* Starts with letter or `_`
* Cannot start with digit
* Case-sensitive

❌ Python identifiers **cannot use special symbols** except `_`

### 💎 LITERALS

✅ Python

* Integer → `10`
* Float → `10.5`
* Boolean → `True`, `False`
* String → `"Hello"`
* None → `None`

❌ C++ only

* `nullptr`
* Binary literal syntax differs

### 💎 STRING

❌ C++

* `string` (STL)
* `<string>` header

✅ Python

* Built-in type
* Immutable

```python
s = "Hello"
```

* Functions: `len()`, `upper()`, `lower()`, `replace()`


### 💎 BOOLEAN

❌ C++

* `bool`, `true`, `false`

✅ Python

* `bool`
* `True`, `False`


### 💎 NULL / NONE

❌ C++

* `NULL`, `nullptr`

✅ Python

* `None`

```python
x = None
```

### 💎 OPERATORS

❌ C++ only

* `::`, `->`, operator overloading syntax

✅ Python

* Arithmetic, logical, relational
* Special operators: `is`, `in`
* Supports operator overloading via magic methods


### 💎 DELIMITERS

✅ Python

* `()  []  {}  ,  :  .`

❌ No `;` required


## Barebones of Program

❌ C++

```cpp
int main() {
    return 0;
}
```

✅ Python

```python
# No main function required
print("Hello")
```

📌 Execution is **top to bottom**


## Data Types Overview

❌ C++

* Static typed

✅ Python

* **Dynamically typed**
* Type decided at runtime


## Variables & Constants

### Variables

❌ C++

```cpp
int x = 10;
```

✅ Python

```python
x = 10
```

* No declaration
* No data type required


### Constants

❌ Python has **NO true constants**

Convention:

```python
PI = 3.14
```

📌 Constants are enforced by **developer discipline**


## Type Modifiers

❌ Python has **NO**

* signed / unsigned
* short / long

✅ Python integers are **unlimited precision**


## Type Conversion / Type Casting

❌ C++

```cpp
int x = (int)3.5;
```

✅ Python

```python
x = int(3.5)
```

* `int()`, `float()`, `str()`, `bool()`


## sizeof equivalent

❌ C++

```cpp
sizeof(int)
```

✅ Python

```python
import sys
sys.getsizeof(x)
```

## Comments

❌ C++

```cpp
// comment
/* multi-line */
```

✅ Python

```python
# comment
"""
multi-line comment
"""
```


## data handling basics

❌ C++

* Manual memory handling
* Pointers

✅ Python

* Automatic memory management
* Garbage collection
* No pointers (reference-based)


## boiler plate code

❌ C++

* Required structure

✅ Python

* No boilerplate
* Just write code


## next line

❌ C++

```cpp
cout << endl;
```

✅ Python

```python
print()
```

## Escape Sequences

✅ **Same**

* `\n` → new line
* `\t` → tab
* `\\` → backslash
* `\"` → double quote


## output & input

❌ C++

```cpp
cin >> x;
cout << x;
```

✅ Python

```python
x = input()
print(x)
```


###### header files
# 🎗 HEADER FILES

###### data handling
# 🎗 DATA HANDLING

###### flow of control
# 🎗 FLOW OF CONTROL

###### functions
# 🎗 FUNCTION

###### pointers
# 🎗 POINTERS

###### dynamic memory allocation
# 🎗 DYNAMIC MEMORY ALLOCATIONS 

###### structures and unions
# 🎗 STRUCTURES AND UNIONS 

###### file handling
# 🎗 FILE HANDLING 

###### preprocessor and macros
# 🎗 PREPROCESSOR AND MACROS 

###### string handling
# 🎗 STRING HANDLING 

###### standard libraries
# 🎗 STANDARD LIBRARIES 

###### advanced concepts
# 🎗 ADVANCED CONCEPTS

###### competitive Programming DSA Readiness
# 🎗 COMPETITIVE PROGRAMMING 

###### basic maths codes
# 🎗 BASIC MATHS CODES 






