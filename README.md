# Insertion Sort vs. Bucket Sort

This repository contains a Jupyter Notebook dedicated to analyzing and comparing the performance of two popular sorting algorithms: **Insertion Sort** and **Bucket Sort**. Each algorithm has unique properties and performance characteristics, making them suitable for specific types of datasets and use cases.

## Project Overview

The notebook compares **Insertion Sort** and **Bucket Sort** by measuring their execution time on different types of lists. By running these tests, we aim to highlight the strengths and weaknesses of each algorithm, providing insights into which might be more efficient under various conditions.

## Dataset and Testing Methodology

### List Types
To test the sorting algorithms under various conditions, we use four types of lists:
- **Random list**: Elements are generated randomly.
- **Sorted list**: Elements are pre-sorted in ascending order.
- **Reverse sorted list**: Elements are sorted in descending order.

### Testing Process
For each list type, we measure the execution time of both algorithms. We increase the size of the lists incrementally to observe how the algorithms perform with varying input sizes. Execution times are recorded and plotted for a clear comparison.

### Key Functions
- `test()`: This function performs the main tests for each list type, iterating over increasing list sizes and capturing execution time for each algorithm.
- `main()`: This function initiates the tests across all list types, running them in sequence to produce comparable results.

## Results and Visualization
The results are visualized using **Matplotlib**, plotting the execution time of each algorithm against list sizes. This allows for a straightforward comparison between Insertion Sort and Bucket Sort, highlighting their performance in different scenarios.