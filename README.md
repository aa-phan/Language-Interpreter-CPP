# Language Interpreter in C++

This project implements a basic language interpreter in C++, designed to analyze and execute code by breaking it down into tokens, parsing it into an abstract syntax tree (AST), and evaluating the result. The project was developed as part of ECE 312: Software Design and Implementation I, taken at the University of Texas at Austin.

## Project Structure

- **main.cpp**: Entry point for the interpreter, initializing the necessary components and handling input.
- **parser.cpp / parser.h**: Parses tokenized input to generate an abstract syntax tree (AST), organizing code syntax for later evaluation.
- **scanner.cpp / scanner.h**: Lexical analysis component that scans the input text, identifies syntax elements, and tokenizes them.
- **token.h**: Defines the `Token` class and various token types, supporting lexical analysis.
- **value.cpp / value.h**: Implements the `Value` class, representing the data types and values within the interpreter.

## Features

- **Lexical Analysis**: Scans and tokenizes input to distinguish keywords, identifiers, literals, and operators.
- **Parsing**: Converts tokens into an AST, which organizes the syntax structure for interpretation.
- **Interpretation**: Evaluates the AST to execute statements and expressions, processing code meaningfully.

## Setup and Build

To build the project, you can use `CMake` or a `Makefile`:

This code is not to be used in any manner consistent with cheating, plagiarism, or other form of uncredited usage. For any questions related to implementation or usage, please contact me at atp2323@utexas.edu. This code is meant to be used for portfolio demonstration purposes with potential employers.
