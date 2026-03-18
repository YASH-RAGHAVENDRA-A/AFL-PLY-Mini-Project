# Implementation of Basic Language Constructs using PLY

## Overview

This project demonstrates the implementation of basic programming language constructs using PLY (Python Lex-Yacc). It simulates a simple interpreter that supports variables, arithmetic operations, conditional statements, loops, and input/output.



## Objective

To understand and implement concepts of lexical analysis and syntax analysis using PLY, and to demonstrate how programming language constructs are parsed and executed.



## Technologies Used

* Python
* PLY (Python Lex-Yacc)



## Key Concepts

* Lexical Analysis (Lexer)
* Syntax Analysis (Parser)
* Tokenization
* Grammar Rules
* Symbol Table Management



## Features

* Variable declaration and assignment
* Arithmetic expressions (+, -, *, /)
* Relational operators (>, <, >=, <=, ==, !=)
* Conditional statements (if)
* Loop constructs (while)
* Input and output operations (read, print)



## Lexer Implementation

The lexer identifies tokens such as:

* Identifiers (ID)
* Numbers (NUMBER)
* Strings (STRING)
* Operators (+, -, *, /, =)
* Relational operators
* Keywords (if, else, while, print, read)

Tokens are defined using regular expressions.


## Parser Implementation

The parser defines grammar rules for:

* Assignment statements
* Arithmetic expressions
* Conditional statements
* Loop statements
* Input/output statements

It evaluates expressions and updates values using a symbol table.



## Data Structures Used

* Symbol Table (Dictionary in Python)

  * Stores variable names and values



## Working

1. Input code is passed to the lexer.
2. Lexer converts input into tokens.
3. Parser applies grammar rules.
4. Expressions are evaluated.
5. Output is displayed based on execution.



## Sample Test Cases

### Variable Assignment

```
x = 10
```

### Arithmetic Expression

```
y = 3 + 7 * 2
```

### Conditional Statement

```
if (5 < 10) { print("Condition True") }
```

### Loop

```
while (1 < 3) { print("Inside loop") }
```

### Output

```
print("Hello World")
```

---

## Execution

Run the program using:

```
python filename.py
```

Make sure PLY is installed:

```
pip install ply
```

---

## Project Structure

```
AFL-PLY-Mini-Project/
│
├── main.py
├── README.md
```



## Future Enhancements

* Support for functions
* Better error handling
* Abstract Syntax Tree (AST) visualization
* Full interpreter support



## Author

Yash Raghavendra
GitHub: https://github.com/YASH-RAGHAVENDRA-A



## Conclusion

This project demonstrates how lexical and syntax analysis work together to process and execute programming language constructs using PLY.
