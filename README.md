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
- [Object-Oriented Programming (OOP)](https://github.com/Saujanya-rajvanshi/THEORY?tab=readme-ov-file#Oops)
- [Exception Handling](#exception-handling)
- [File Handling](#file-handling)
- [Templates](#templates)
- [STL (Standard Template Library)](https://github.com/Saujanya-rajvanshi/STL)
- [Advanced C++ Concepts](#advanced-concept)
- [Competitive Programming / DSA Readiness](#competitive-programming)
- [string manipulation](#string-manipulation)
- [basic maths codes](https://github.com/Saujanya-rajvanshi/basic-maths)

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


## character set

✅ **NO major difference (conceptually)**

* **Letters:** A–Z, a–z
* **Digits:** 0–9
* **Special symbols:** `+ - * / % = < > ! & | ^ ~ ? : ; , . ' " # @ _ ( ) { } [ ]`
* **Whitespace:** space, tab (`\t`), newline (`\n`)

📌 Python is **Unicode-based**, supports emojis & international characters.

## tokens

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


---

###### header files
# 🎗 HEADER FILES

### ❌ Header Files

* Python has **NO header files**
* No `#include`
* No separate declaration & definition files

📌 Python code is written directly in `.py` files

### Imports (instead of headers)

```python
import math
import sys
from math import sqrt
```

* Imports **modules**, not headers
* Executed at **runtime**, not compile time


### Namespaces

✅ **Python has namespaces by default**

* Every module is a namespace
* Access using **dot operator**

```python
math.sqrt(25)
```

📌 No `using namespace` concept


### ❌ Scope Resolution Operator `::`

* `::` ❌ **not used**
* Python uses `.` instead

```python
module.variable
Class.method()
```


### ❌ `<bits/stdc++.h>`

* ❌ Not applicable in Python
* No “include everything” header
* Standard library modules imported as needed


###### data handling
# 🎗 DATA HANDLING

### Data Types

* Python is **dynamically typed**
* No need to declare type

```python
x = 10
x = "hello"   # valid
```

📌 Type decided at runtime


### Strings

* Strings are **built-in**
* **Immutable**

```python
s = "hello"
```

📌 No `char[]`, no `string.h`


### Boolean Type

* Built-in `True` / `False`
* Case-sensitive

```python
flag = True
```


### Mutable vs Immutable (Important)

| Immutable | Mutable       |
| --------- | ------------- |
| int       | list          |
| float     | dict          |
| string    | set           |
| tuple     | class objects |

📌 Direct language-level support (unlike C++)


### References & Pointers

* ❌ No pointers
* ❌ No references
* Python uses **object references internally**

```python
a = 10
b = a   # reference copy
```


### ❌ User-defined data types (C++ style)

* No `struct`
* No `union`
* No `typedef`

📌 Use:

* `class`
* `dict`
* `namedtuple`


---

# Python Modules (Equivalent to Header Files)

📌 **Important first point (exam-ready):**

> Python **does NOT have header files**.
> Python uses **modules and packages**, imported using `import`.


## 🔹 Input / Output

| Python Module | Purpose          | Comparable C++ Header |
| ------------- | ---------------- | --------------------- |
| `sys`         | System-level I/O | `<iostream>`          |
| `io`          | Stream handling  | `<iostream>`          |
| `print()`     | Output           | `cout`                |
| `input()`     | Input            | `cin`                 |

📌 Example:

```python
print("Hello")
x = input()
```

---

## 🔹 Strings & Characters

| Python Module    | Purpose             | Comparable C++ Header |
| ---------------- | ------------------- | --------------------- |
| `str` (built-in) | String operations   | `<string>`            |
| `string`         | Constants & helpers | `<cstring>`           |
| `re`             | Regular expressions | `<regex>`             |

📌 Example:

```python
s = "Hello"
print(len(s))
```

---

## 🔹 Data Structures / Containers

| Python Module | Purpose           | Comparable C++ Header |
| ------------- | ----------------- | --------------------- |
| `list`        | Dynamic array     | `<vector>`            |
| `tuple`       | Immutable array   | `<array>`             |
| `set`         | Unique collection | `<set>`               |
| `dict`        | Key-value store   | `<map>`               |
| `collections` | Advanced DS       | `<deque>`, `<queue>`  |

📌 Example:

```python
arr = [1, 2, 3]
mp = {"a": 1}
```

---

## 🔹 Algorithms & Utilities

| Python Module | Purpose          | Comparable C++ Header |
| ------------- | ---------------- | --------------------- |
| `math`        | Math functions   | `<cmath>`             |
| `statistics`  | Mean, median     | `<numeric>`           |
| `functools`   | Functional tools | `<functional>`        |
| `itertools`   | Iterators        | `<iterator>`          |
| `operator`    | Operators        | `<utility>`           |

📌 Example:

```python
import math
print(math.sqrt(16))
```

---

## 🔹 File Handling

| Python Module | Purpose       | Comparable C++ Header |
| ------------- | ------------- | --------------------- |
| `open()`      | File I/O      | `<fstream>`           |
| `os`          | File system   | `<filesystem>`        |
| `pathlib`     | Path handling | `<filesystem>`        |

📌 Example:

```python
f = open("file.txt", "r")
```

---

## 🔹 Memory Management

| Python Module | Purpose            | Comparable C++ Header |
| ------------- | ------------------ | --------------------- |
| `gc`          | Garbage collection | `<memory>`            |
| Automatic     | Auto memory mgmt   | Smart pointers        |

📌 Notes:

* No `new` / `delete`
* Python uses **Garbage Collector**

---

## 🔹 Exception Handling

| Python Module       | Purpose         | Comparable C++ Header |
| ------------------- | --------------- | --------------------- |
| Built-in exceptions | Error handling  | `<exception>`         |
| `try-except`        | Catch errors    | `try-catch`           |
| `raise`             | Throw exception | `throw`               |

📌 Example:

```python
try:
    x = 1 / 0
except:
    print("Error")
```

---

## 🔹 Time & Date

| Python Module | Purpose        | Comparable C++ Header |
| ------------- | -------------- | --------------------- |
| `time`        | Time functions | `<ctime>`             |
| `datetime`    | Date & time    | `<chrono>`            |

📌 Example:

```python
import datetime
print(datetime.datetime.now())
```

---

## 🔹 Multithreading & Concurrency

| Python Module     | Purpose        | Comparable C++ Header |
| ----------------- | -------------- | --------------------- |
| `threading`       | Multithreading | `<thread>`            |
| `multiprocessing` | Parallelism    | `<thread>`            |
| `asyncio`         | Async tasks    | `<future>`            |

📌 Note:

* Python has **GIL (Global Interpreter Lock)**

---

## 🔹 Type & Runtime Information

| Python Module | Purpose      | Comparable C++ Header |
| ------------- | ------------ | --------------------- |
| `typing`      | Type hints   | `<type_traits>`       |
| `inspect`     | Runtime info | `<typeinfo>`          |

📌 Example:

```python
def add(a: int, b: int) -> int:
    return a + b
```

---

## 🔹 OS & System Interaction

| Python Module | Purpose       | Comparable C++ Header |
| ------------- | ------------- | --------------------- |
| `os`          | OS operations | `<cstdlib>`           |
| `sys`         | System info   | `<cstdlib>`           |
| `subprocess`  | Run commands  | `<process>`           |

---

## 🔹 Random & Cryptography

| Python Module | Purpose        | Comparable C++ Header |
| ------------- | -------------- | --------------------- |
| `random`      | Random numbers | `<random>`            |
| `secrets`     | Secure random  | `<random>`            |
| `hashlib`     | Hashing        | `<openssl>`           |

---

## ⭐ Key Differences (Exam Gold)

| Feature       | Python        | C++            |
| ------------- | ------------- | -------------- |
| Headers       | ❌ No          | ✅ Yes          |
| Compilation   | Interpreted   | Compiled       |
| Memory mgmt   | Automatic     | Manual / Smart |
| STL / Library | Built-in rich | STL            |
| Type safety   | Dynamic       | Static         |

---











###### flow of control
# 🎗 FLOW OF CONTROL (PYTHON)

### Blocks & Scope

* ❌ No `{ }`
* Uses **indentation**

```python
if x > 0:
    print(x)
```

📌 Indentation is **mandatory**


### Decision Statements

* `if`, `elif`, `else`
* No `switch` (before Python 3.10)

```python
if x > 0:
    pass
elif x == 0:
    pass
else:
    pass
```


### Loops

* `for` is **iterator-based**
* No traditional C-style for loop

```python
for i in range(5):
    print(i)
```


### ❌ do–while loop

* ❌ Not available


### Jump Statements

* `break`
* `continue`
* `return`
* ❌ `goto` not supported


### Ternary Operator

Different syntax:

```python
max = a if a > b else b
```


### Infinite Loop

```python
while True:
    pass
```













###### functions
# 🎗 FUNCTION

### ✅ CONCEPTS THAT STAY

* Function definition & calling
* Parameters & return values
* Recursion
* Modular programming
* Scope (local / global)
* Reusability
* Default arguments (Python supports them)

### ❌ C++ FEATURES NOT IN PYTHON

| C++ Concept                | Python          |
| -------------------------- | --------------- |
| Return type                | ❌ Not needed    |
| Function prototypes        | ❌ Not needed    |
| Overloading (by signature) | ❌ Not supported |
| Call by value / reference  | ❌ Not explicit  |
| Inline functions           | ❌ Not needed    |

### ✅ Python Reality

```python
def add(a, b=10):
    return a + b
```

📌 **Exam Line (Python):**

> Python functions are **dynamically typed** and support **default & keyword arguments**.

---

## 🎗 Arrays — Python vs C++

### ❌ C++ Arrays DON’T EXIST in Python

| C++              | Python |
| ---------------- | ------ |
| Fixed size       | ❌      |
| Same data type   | ❌      |
| Index-based only | ❌      |

### ✅ Python Uses

* **List** (most common)
* Tuple
* Set
* Dictionary

```python
arr = [1, 2, 3, "hello"]
```

📌 **Exam Line:**

> Python lists are **dynamic, heterogeneous, and resizable**.

---














###### pointers
# 🎗 POINTERS

### ❌ COMPLETE REMOVAL

| Pointer Concept    | Python |
| ------------------ | ------ |
| `*`, `&`           | ❌      |
| Pointer arithmetic | ❌      |
| Null pointer       | ❌      |
| Dangling pointer   | ❌      |
| Pointer to pointer | ❌      |

### ✅ Python Replacement

* Everything is an **object**
* Variables store **references**, but **not accessible**

```python
a = 10
b = a
```

📌 **Exam Line:**

> Python does not support pointers; it uses **automatic reference handling**.

---

###### dynamic memory allocation
# 🎗 DYNAMIC MEMORY ALLOCATIONS 

### ❌ REMOVE ENTIRE C++ SECTION

| C++                      | Python |
| ------------------------ | ------ |
| `new`, `delete`          | ❌      |
| `malloc/free`            | ❌      |
| Manual memory management | ❌      |

### ✅ Python Handles Automatically

* Garbage Collector
* Reference counting

📌 **Exam Line:**

> Python uses **automatic memory management** via garbage collection.

---















###### structures and unions
# 🎗 STRUCTURES AND UNIONS 

### ❌ Structures & Unions DO NOT EXIST

### ✅ Python Alternative

* Class
* Dictionary
* NamedTuple / Dataclass

```python
student = {"roll": 1, "name": "A"}
```

📌 **Exam Line:**

> Python replaces structures with **classes and dictionaries**.

---
















## 🎗 Exception Handling — Python vs C++

### ✅ CONCEPTS SAME

* Runtime error handling
* Prevent program crash
* Multiple catch blocks

### ❌ C++ Keywords NOT USED

| C++         | Python |
| ----------- | ------ |
| `try-catch` | ❌      |
| `throw`     | ❌      |

### ✅ Python Syntax

```python
try:
    x = int(input())
except ValueError:
    print("Error")
finally:
    print("Done")
```

📌 **Exam Line:**

> Python uses `try-except-finally` for exception handling.

---












## 🎗 File Handling — Python vs C++

### ❌ C++ FILE POINTER CONCEPT REMOVED

### ✅ Python Way

```python
with open("a.txt", "r") as f:
    print(f.read())
```

📌 **Exam Line:**

> Python uses **high-level file objects**, not file pointers.

---

## 🎗 Templates / STL — Python vs C++

### ❌ REMOVE ENTIRELY

| C++       | Python       |
| --------- | ------------ |
| Templates | ❌            |
| STL       | ❌            |
| Iterators | ❌ (explicit) |

### ✅ Python Replacement

* Dynamic typing
* Built-in collections
* List comprehensions

```python
squares = [x*x for x in range(5)]
```

---















###### competitive Programming DSA Readiness
# 🎗 COMPETITIVE PROGRAMMING 

### ⚠️ CONCEPTS SAME, PERFORMANCE DIFFERENT

| Aspect          | Python      |
| --------------- | ----------- |
| Logic           | ✅           |
| STL speed       | ❌           |
| Execution speed | ❌ Slower    |
| Ease of coding  | ✅ Very high |

📌 **Exam Line:**

> Python is preferred for **rapid development**, C++ for **performance**.

---

# 🔥 FINAL SUMMARY (VERY IMPORTANT)

### ✔️ You can reuse C++ notes for Python:

* **Only for concepts**
* **Not syntax**
* **Not memory**
* **Not pointers**
* **Not STL/templates**

### ❌ You must REMOVE:

* Pointers
* Manual memory
* Templates
* Struct/Union
* Fixed arrays

---












###### string manipulation
# 🎗 STRING MANIPULATION 

## 1️⃣ What is a String?

### C++

* Two types:

  * C-style strings (`char[]`, `\0` terminated)
  * `std::string` (STL)

### Python (CHANGE ⚠️)

* **Only one string type**
* Strings are:

  * **Objects**
  * **Immutable**
  * **No null character**

```python
s = "Hello"
```

📌 No `char[]`, no `<string>`, no STL.

---

## 2️⃣ Input & Output

### C++

```cpp
cin >> s;
getline(cin, s);
```

### Python (CHANGE ⚠️)

```python
s = input()     # reads full line (spaces included)
print(s)
```

📌 `input()` = `getline()`
📌 No `cin.ignore()` needed

---

## 3️⃣ String Length

### C++

```cpp
s.length();
```

### Python (CHANGE ⚠️)

```python
len(s)
```

📌 `len()` is a **built-in function**, not a method

---

## 4️⃣ Concatenation

### C++

```cpp
a + b
a.append(b)
```

### Python (CHANGE ⚠️)

```python
a + b
```

📌 No `append()` for strings
📌 `append()` exists only for **lists**

---

## 5️⃣ Accessing Characters

### C++

```cpp
s[0]
s.at(1)
```

### Python (CHANGE ⚠️)

```python
s[0]
```

📌 No `.at()`
📌 Index out of range → **IndexError**

---

## 6️⃣ Comparing Strings

### C++

```cpp
s1 == s2
s1.compare(s2)
```

### Python (CHANGE ⚠️)

```python
s1 == s2
s1 < s2
```

📌 Lexicographical comparison is **built-in**
📌 No `compare()` function

---

## 7️⃣ Substring

### C++

```cpp
s.substr(0, 3)
```

### Python (CHANGE ⚠️)

```python
s[0:3]
```

📌 Called **string slicing**

---

## 8️⃣ Finding Substring

### C++

```cpp
s.find("World")       // returns index or string::npos
```

### Python (CHANGE ⚠️)

```python
s.find("World")       # returns index or -1
```

📌 `-1` instead of `string::npos`

---

## 9️⃣ Insert / Erase / Replace

### C++

```cpp
s.insert()
s.erase()
s.replace()
```

### Python (CHANGE ⚠️)

❌ Strings are **immutable**

✔ Use **new strings**:

```python
s.replace("Hello", "Hi")
```

📌 No direct `insert()` or `erase()`

---

## 🔟 Traversing a String

### C++

```cpp
for(int i=0;i<s.length();i++)
for(char c : s)
```

### Python (SIMPLER ✅)

```python
for c in s:
    print(c)
```

📌 Python prefers **for-each style**

---

## 1️⃣1️⃣ C-Style String Functions

### C++

```cpp
strlen()
strcpy()
strcat()
strcmp()
```

### Python (NOT NEEDED ❌)

* No `<cstring>`
* No manual memory
* Built-in methods instead:

```python
len(s)
s1 + s2
s1 == s2
```

---

## 1️⃣2️⃣ String Conversion

### C++

```cpp
strcpy(ch, s.c_str());
```

### Python (NOT REQUIRED ❌)

* No char arrays
* Everything is already a string

---

## 1️⃣3️⃣ Mutability (BIG EXAM POINT ⚠️)

| Feature | C++ `string` | Python `str` |
| ------- | ------------ | ------------ |
| Mutable | ✅ Yes        | ❌ No         |
| Memory  | Manual / STL | Automatic    |
| Safety  | Medium       | Very High    |

---

## 1️⃣4️⃣ Common Programs (Same Logic ✔)

These programs are **valid in both**, logic same:

* Reverse string
* Palindrome check
* Count vowels
* Frequency count
* Case conversion

📌 **Only syntax changes**

---

## ✅ Final Verdict

| Question                                   | Answer                           |
| ------------------------------------------ | -------------------------------- |
| Can I use this C++ string note for Python? | ❌ No                             |
| Are concepts reusable?                     | ✅ Yes                            |
| Main changes                               | Immutability, slicing, built-ins |
| Complexity                                 | Python is simpler                |

---

### 🧠 Memory Trick

> **C++ strings = manual + STL
> Python strings = built-in + immutable**

---









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








