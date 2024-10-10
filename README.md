# matplotlib-bubble-sort
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-003B57?style=flat&logo=matplotlib&logoColor=white)

A visual representation of bubble sort with Matplotlib using the `FuncAnimation`.

<img src="/assets/bubble-sort.gif">

## 🌀 What is Bubble Sort?
Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.

The algorithm gets its name because smaller elements "bubble" to the top of the list. Although it is not efficient for large datasets, Bubble Sort is a great algorithm for educational purposes due to its simplicity.

## ⚙️ How Bubble Sort Works
1. **Starting at the beginning of the list**, compare the first two adjacent elements.
2. **If the first element is greater than the second**, swap them.
3. Move to the next pair of adjacent elements and repeat the process until the end of the list is reached.
4. At the end of each pass through the list, the next largest element will have been placed in its correct position.
5. Repeat the entire process for the remaining unsorted elements until no swaps are needed, indicating that the list is sorted.

## 📊 Example
For instance, given the list `[5, 2, 9, 1, 5, 6]`, Bubble Sort will:
- Compare 5 and 2, swap them → `[2, 5, 9, 1, 5, 6]`
- Compare 5 and 9, no swap → `[2, 5, 9, 1, 5, 6]`
- Compare 9 and 1, swap them → `[2, 5, 1, 9, 5, 6]`
- Continue until the entire list is sorted.

## 📈 Project Overview
In this project, the Bubble Sort algorithm is visually represented using Python's Matplotlib library. The `FuncAnimation` feature allows for a dynamic visualization of the sorting process, making it easier to understand how the algorithm works step by step.
