# Employee Data Management System

A simple console-based employee data management program written in C.

This program demonstrates how structured data can be modeled and processed using `struct` and arrays in a terminal application.

## Overview

The Employee Data Management System is designed to manage basic employee information using structured programming techniques.

The program allows users to input multiple employee records and display them in a clear and organized format through the console.

## Concepts Implemented

- Struct declaration and initialization
- Array of struct
- Structured input and output
- Loop-based data traversal
- Basic data validation

## Program Flow

- User inputs employee data (such as name and other attributes)
- Data is stored in an array of struct
- The program iterates through the array to display stored employee records
- Execution ends after all data has been displayed

## File Structure

```
employee-system/
├── employee_struct_system.c
└── README.md
```

## How to Compile

Compile the program using the following command:

```
gcc employee_struct_system.c -o employee
```

Run the program:

```
./employee
```

## Example Output

```
Data pegawai yang telah diinputkan

No id       : 1
Nama        : Rudi
Tgl Lahir   : 12=12=2004
Jenis Kelamin: L
Gaji/bln    : Rp 5000000.00

No id       : 2
Nama        : Andi
Tgl Lahir   : 2-2-2002
Jenis Kelamin: L
Gaji/bln    : Rp 4000000.00
```

## Learning Outcomes

After completing this program, you should understand:

- How to model real-world entities using struct
- How to manage collections of structured data
- How to traverse and display structured records
- How to build simple data-oriented programs in C

## Notes

- The program is intentionally kept simple
- No dynamic memory allocation is used
- Focus is on clarity, structure, and correctness

## Repository Context

This program is part of the `c-data-management` repository and complements other struct-based data management examples.

## License

MIT License
