# Quicksort Implementation and Analysis

This repository contains implementations and analysis of the **Quicksort** algorithm in Python, including both **deterministic** and **randomized** versions. You can **copy-paste the code** and run it directly in your local Python environment or Visual Studio Code.

---

## **Project Overview**

Quicksort is a classic divide-and-conquer sorting algorithm that works by:

1. Selecting a pivot element.
2. Partitioning the array so that elements less than the pivot go to the left, and elements greater go to the right.
3. Recursively sorting the left and right subarrays.

This project includes:

- Deterministic Quicksort using the last element as the pivot.
- Randomized Quicksort where the pivot is chosen randomly.
- Performance analysis on different input types (random, sorted, reverse-sorted).
- Discussion of time and space complexity for both versions.

---

## **Included Code**

Both sorting algorithms are included in this repository:

- `quickSort.py` – Deterministic Quicksort implementation
- `randomizedQuickSort.py` – Randomized Quicksort implementation

You can **copy the code** into your local Python environment or Visual Studio Code and run it directly without additional dependencies.

### Example Usage

```python
from quicksort_deterministic import quicksort
from quicksort_randomized import randomized_quicksort

arr = [10, 7, 8, 9, 1, 5]
print("Deterministic Quicksort:", quicksort(arr.copy()))
print("Randomized Quicksort:", randomized_quicksort(arr.copy()))
