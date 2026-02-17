# C Data Management

A collection of console-based C programs focused on managing structured data using `struct` and arrays.

This repository demonstrates how fundamental C programming concepts can be applied to model, store, and process real-world data in simple data management systems.

## Overview

The projects in this repository emphasize structured data handling rather than algorithmic complexity.

Each program focuses on organizing related data fields, managing multiple records, and displaying structured information clearly in the terminal.

This repository complements the `c-fundamentals` and `c-mini-games` projects by showcasing data-oriented programming using C.

## Concepts Implemented

- Struct declaration and initialization
- Nested struct
- Array of struct
- Structured input and output
- Basic data processing
- Defensive input handling

## Folder Structure

```
c-data-management/
├── employee-system/
│   ├── employee_struct_system.c
│   └── README.md
│
├── student-system/
│   ├── student_struct_system.c
│   └── README.md
│
└── README.md
```

## Programs Included

### Student Data Management

A simple student data management program that allows users to input and display student information such as name and date of birth.

Concepts demonstrated:
- Nested struct
- Array of struct
- Input validation
- Structured output formatting

### Employee Data Management

A basic employee data management program that models employee records using struct and displays the stored data in a structured format.

Concepts demonstrated:
- Struct-based data modeling
- Array traversal
- Clear separation of data fields

## How to Compile

Compile any program using the following format:

```
gcc filename.c -o output
```

Example:

```
gcc student-system/student_struct_system.c -o student
./student
```

## Learning Outcomes

After working with this repository, you should understand:

- How to model real-world entities using struct
- How to manage collections of structured data
- How to design simple data-oriented console programs
- How to organize code for clarity and maintainability

## Notes

- Programs are intentionally kept simple
- No dynamic memory allocation is used
- Focus is on clarity, structure, and correctness

## Repository Purpose

This repository serves as:
- Practice for struct-based programming in C
- A demonstration of data modeling fundamentals
- A foundation for more advanced systems such as file-based databases

## License

MIT License
