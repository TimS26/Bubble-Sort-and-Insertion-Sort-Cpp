# Sorting Algorithms in C++: Bubble Sort & Insertion Sort (Descending Order)

This repository contains two classic sorting algorithms implemented in C++ with clear, educational comments. Both algorithms sort data **in descending order**.

---

## Algorithms Included

### 1. Bubble Sort (Descending Order)

- Compares adjacent elements in an integer array.
- Swaps elements if the left element is smaller than the right, pushing larger values to the front.
- Uses a `sorted` flag to optimize and stop early if the array is already sorted.
- Each pass reduces the sorting range because the largest elements settle at the beginning.

### 2. Insertion Sort (Descending Order)

- Sorts a character array by taking each element and inserting it into its correct position.
- Moves smaller elements one position to the right to make space.
- Builds a sorted portion of the array from left to right in descending order.

---

## How to Use

1. Compile the program containing the sorting functions:

```bash
g++ sorting_algorithms.cpp -o sorting_algorithms
---
Original integer array: 3 1 4 2 
Sorted array (descending) by Bubble Sort: 4 3 2 1 

Original char array: a d c b 
Sorted array (descending) by Insertion Sort: d c b a 

