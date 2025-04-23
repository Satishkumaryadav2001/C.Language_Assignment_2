# C.Language_Assignment_2

Ques 1  Which of the following are real constants?
        3, ‘A’, 4.5, 3.0, ‘+’, -25, -0.0

 Ans:-  To determine which of the values are **real constants**, we need to understand what qualifies as a *real constant*:

### 💡 Real constants:
- Represent **real numbers**, which include **integers, decimals, and floating-point numbers**, whether positive or negative.
- **Do not** include characters or symbols.

---

### Let's look at each item:

1. **`3`** – ✅ Yes, an integer (which is a real number).
2. **`'A'`** – ❌ No, this is a character.
3. **`4.5`** – ✅ Yes, a floating-point real number.
4. **`3.0`** – ✅ Yes, also a floating-point real number.
5. **`'+'`** – ❌ No, this is a character (a symbol in quotes).
6. **`-25`** – ✅ Yes, a negative integer (still a real number).
7. **`-0.0`** – ✅ Yes, a valid floating-point number (in programming, `-0.0` is distinct but still real).

---

### ✅ Final answer – **Real constants are**:
**`3`, `4.5`, `3.0`, `-25`, `-0.0`**


Ques 2   Which of the following are not keywords in C Language?
        auto, dynamic, static, typedef, define, enum, is, default, this, super


Ans :  To determine which of the following **are not keywords in C**, we compare each word to the list of **reserved keywords** in the C programming language.

---

### 🔍 Let's break it down:

1. **`auto`** – ✅ **Keyword** (storage class specifier)
2. **`dynamic`** – ❌ **Not a keyword** in C (might be confused with C++/Java concepts)
3. **`static`** – ✅ **Keyword** (storage class specifier)
4. **`typedef`** – ✅ **Keyword** (used to define new data type names)
5. **`define`** – ❌ **Not a keyword**, but a **preprocessor directive** (`#define`)
6. **`enum`** – ✅ **Keyword** (used for enumerated types)
7. **`is`** – ❌ **Not a keyword** in C (used in some other languages like Python)
8. **`default`** – ✅ **Keyword** (used in `switch` statements)
9. **`this`** – ❌ **Not a keyword** in C (C++ keyword, not in C)
10. **`super`** – ❌ **Not a keyword** in C (Java keyword, not in C)

---

### ❌ Final list – **Not C keywords**:
**`dynamic`, `define`, `is`, `this`, `super`**

Let me know if you want a full list of C keywords or their uses!


Ques 3  Which of the following is not a valid variable name in C language? 

Ans The names for Variables in C can only have letters, an alphabet, a number, or an underscore in the first position. No variable in C should ever start with a special character, space, or other than a number, alphabet, or underscore. No keywords will be considered as a variable.


Ques 4 Can we make a variable with the name switch? (Yes or No)

Ans  No. A variable cannot be named "switch" because "switch" is a reserved keyword in many programming languages, including C, C++, Java, and Python, used for conditional branching. In these languages, reserved words have specific meanings and cannot be used as identifiers (like variable names). 

Ques  5 Keywords are defined in the compiler or their meaning is stored in the library?

Ans : Great question!

**Keywords in C** are **defined in the compiler**, **not** in libraries.

---

### 🔍 Here's why:

- **Keywords** like `if`, `while`, `int`, `return`, etc., are part of the **C language syntax**.
- The **compiler** is programmed to **recognize** these words and treat them in specific ways during the **compilation process**.
- They are **hardcoded** into the compiler and have **special meaning** that the compiler understands—so you can't redefine or use them for other purposes like variable names.

---

### 📚 What about libraries?

- **Libraries** (like `stdio.h`, `math.h`, etc.) contain **function declarations**, **macros**, and **type definitions**, but **not the definitions of keywords**.
- Libraries provide **reusable code**, but they don’t control the **core language rules**—that’s the compiler’s job.

---

So the answer is:  
✅ **Keywords are defined in the compiler**. 

Ques 6  Where variables are created? (RAM, ROM, Secondary Storage or CPU):

Ans :- Variables are created in **✅ RAM (Random Access Memory)**.

---

### 💡 Here's why:

- When you run a program, the **variables are stored in RAM** because:
  - RAM is **fast** and allows **read/write** operations needed during program execution.
  - It's **temporary storage** — variables exist only while the program is running.

---

### ❌ Not in these places:

- **ROM** – Read-Only Memory; used for permanent storage (like firmware), not for variables.
- **Secondary Storage** – (like HDDs or SSDs) is used for storing files, not for runtime variables.
- **CPU** – Executes instructions and uses **registers** (tiny storage), but most variables are in RAM.

---

### Summary:
> Variables are **created and stored in RAM** during the execution of a program.

Ques 7 Who developed C Language ?

Ans: The **C language** was developed by **Dennis Ritchie** in the early **1970s** at **Bell Labs**.

---

### 🔹 Quick Facts:
- **Year**: Around **1972**
- **Purpose**: Created to develop the **Unix operating system**
- **Influence**: C has influenced many other languages like **C++**, **Java**, **C#**, and **Objective-C**

---

So the short answer:
> **Dennis Ritchie** developed the C programming language. 🧠💻

Ques 8 When was the C language developed?

Ans The **C language** was developed in the year **1972**. 📅

---

### 🧠 Context:
- **Created by**: Dennis Ritchie  
- **Where**: AT&T's **Bell Labs**, USA  
- **Purpose**: Originally developed to rewrite the **Unix operating system**, which was previously written in assembly language.

---

So, to summarize:

> **C was developed in 1972** at Bell Labs by Dennis Ritchie.

Ques 9 What is the name of the operating system which is responsible for the inception of
       the C language?

Ans :  The **C language** was developed in the year **1972**. 📅

---

### 🧠 Context:
- **Created by**: Dennis Ritchie  
- **Where**: AT&T's **Bell Labs**, USA  
- **Purpose**: Originally developed to rewrite the **Unix operating system**, which was previously written in assembly language.

---

So, to summarize:

> **C was developed in 1972** at Bell Labs by Dennis Ritchie.

Ques 10  Whether C language is a high level or low level programming language?

Ans: The **C language** is considered a **middle-level programming language**. ⚖️

---

### 🔍 Why middle-level?

- **High-level features**:
  - Supports functions, structured programming, abstraction, etc.
  - Easier to read and write than assembly.
  - Portable across platforms.

- **Low-level features**:
  - Allows **direct memory access** using pointers.
  - Can perform **bit-level operations**.
  - Very close to **machine hardware**, making it efficient for system-level programming (like writing operating systems).

---

### So the best answer is:

> **C is a middle-level language** because it combines features of both **high-level** and **low-level** languages.

Let me know if you want examples of both aspects!
