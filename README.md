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

Compile the program containing the sorting functions:

```bash
g++ sorting_algorithms.cpp -o sorting_algorithms
./sorting_algorithms

#Detailed Example of Program Functionality
Suppose you input the following array to be sorted in descending order:

Enter number of elements: 4
Enter elements separated by spaces: 3 2 4 1
The program will output:
Sorted array (descending) by Bubble Sort: 4 3 2 1
---
How to Change Sorting Order or Algorithm
If you want to change the sorting behavior (for example, sort in ascending order or implement an exponential sort), you need to modify the sorting function.

* The Bubble Sort function is located between lines 6 and 23 in sorting_algorithms.cpp.
To change sorting order, modify the comparison on line 11:
  -
  if (arr[i] < arr[i + 1])  // For descending order
  Change to:
  if (arr[i] > arr[i + 1])  // For ascending order
  --
* The Insertion Sort function is located between lines 25 and 40.
To change sorting order, modify the comparison on line 32:
  -
  while (j >= 0 && arr[j] < temp)  // For descending order
  Change to:
  while (j >= 0 && arr[j] > temp)  // For ascending order
  ---
By making these changes, the program will output:
Sorted array (ascending): 1 2 3 4
