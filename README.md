# C-Array-Logic-Lab
# Count Even and Odd Elements

## Explanation

This C program counts how many even and odd numbers are present in an integer array.

Each array element is checked using the modulus operator `%`. If the remainder after dividing by 2 is zero, the number is even. Otherwise, it is odd.

## Problem Statement

Write a C program to count the number of even and odd elements in an array.

## Features

- Accepts array elements from the user
- Identifies even numbers
- Identifies odd numbers
- Counts even and odd elements separately
- Uses an array and loop

## How It Works

1. Read the number of elements.
2. Read the array elements.
3. Check each element using `% 2`.
4. Increment the even counter if the number is even.
5. Otherwise, increment the odd counter.
6. Display both counts.

## Technologies Used

- C Programming Language
- Standard Input/Output

## Data Structure Used

- Array

## Methods Used

- `main()`
- `scanf()`
- `printf()`

## Program Flow

Start
↓
Read number of elements
↓
Read array elements
↓
Check whether each element is even or odd
↓
Increment corresponding counter
↓
Display even and odd counts
↓
End

## Sample Input

Enter the number of elements: 6
Enter 6 elements:
10 15 20 25 30 35

## Sample Output

Number of even elements = 3
Number of odd elements = 3

## Time Complexity

O(n)

## Space Complexity

O(n)

## Key Learning

- Understanding the modulus operator
- Checking even and odd numbers
- Using counters
- Traversing an array with a loop
- Applying conditional statements

## File Location

`count_even_odd_elements.c`

## Repository Structure

C-Code-Journey/
│
├── smallest_array_element.c
├── largest_array_element.c
├── sum_of_array_elements.c
├── average_of_array_elements.c
├── count_even_odd_elements.c
└── README.md

## Author

V.Harini
