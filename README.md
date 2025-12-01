A modular, menu-driven C application designed to manage student fee records using structures, functions, pointers, dynamic memory allocation, file handling, and decision-making.

This system allows schools/institutions to:
✔ Add student records
✔ Calculate outstanding balances
✔ Apply late payment penalties
✔ Generate fee receipts
✔ Produce course-wise revenue summaries
✔ Save/load student data using files (persistent storage)

1. Student Record Management

Stores: roll number, name, course, total fee, fee paid, outstanding balance.

Uses structures to group related information.

2. Dynamic Student List

Allocates memory using malloc() and expands with realloc() as new students are added.

Uses pointers to manage and resize the list.

3. Fee Calculations

Automatically updates outstanding balance.

Applies 5% late penalties on pending dues (using decision-making).

4. Modular Functions

Separate functions for:

Adding records

Printing receipts

Updating balances

Applying penalties

Displaying revenue summary

Saving & loading records

5. File I/O – Persistent Storage

Saves all student records to student_data.dat.

Loads the data automatically at the start of the program.

** Technologies Used**

 1) C Programming

2) Structures

3) Dynamic Memory Allocation (malloc, realloc)

4) Pointers

5) File Handling (binary file)

6) Loops & Decision-Making

7) Functions
