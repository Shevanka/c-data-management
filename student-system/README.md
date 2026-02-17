# Student Data Management System

A simple console-based student data management program written in C.

This program demonstrates how student information can be modeled, stored, and displayed using `struct` and arrays in a terminal-based application.

## Overview

The Student Data Management System is designed to manage basic student records, such as name and date of birth, using structured programming techniques.

The program allows users to input multiple student records and view them in an organized format through the console.

## Concepts Implemented

- Struct declaration and initialization
- Nested struct (e.g., date of birth)
- Array of struct
- Structured input and output
- Loop-based data traversal
- Defensive input handling

## Program Flow

- User inputs student data (name and birthday)
- Data is stored in an array of struct
- The program iterates through the array to display stored student records
- Execution ends after all data has been displayed

## File Structure

```
student-system/
├── output
│  └── student_struct_system.exe
├── student_struct_system.c
└── README.md
```

## How to Compile

Compile the program using the following command:

```
gcc student_struct_system.c -o student
```

Run the program:

```
./student
```

## Example Output

```
=== DATA MAHASISWA ===
-------------------------------------------------------------------------------
No      NRP     Nama            Tugas   UTS     UAS     Akhir   Grade
-------------------------------------------------------------------------------
1       001     Brian           88.0    89.0    90.0    89.2    A
2       002     Ilham           90.0    89.0    95.0    91.6    A
-------------------------------------------------------------------------------
```

## Learning Outcomes

After completing this program, you should understand:

- How to model real-world entities using struct
- How to use nested struct for related data
- How to manage collections of structured data
- How to design simple data-oriented console programs
- How to handle user input safely

## Notes

- The program is intentionally kept simple
- No dynamic memory allocation is used
- Focus is on data structure clarity and correctness

## Repository Context

This program is part of the `c-data-management` repository and complements other struct-based data management examples.

## License

MIT License
