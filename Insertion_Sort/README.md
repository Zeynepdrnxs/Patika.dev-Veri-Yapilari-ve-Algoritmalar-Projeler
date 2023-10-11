**Insertion Sort:**

Given array: [22, 27, 16, 2, 18, 6]

1. **[22], 27, 16, 2, 18, 6**
2. **[22, 27], 16, 2, 18, 6**
3. **[16, 22, 27], 2, 18, 6**
4. **[2, 16, 22, 27], 18, 6**
5. **[2, 16, 18, 22, 27], 6**
6. **[2, 6, 16, 18, 22, 27]**

**Big-O Notation for Insertion Sort:** The worst-case and average-case time complexity of the Insertion Sort algorithm is O(n^2), and the best-case time complexity is O(n) when the array is already sorted.

After the array is sorted, the number 18 falls under the **Average Case** for searching. In the average case, the desired number is in the middle of the array.

---

**Selection Sort:**

Given array: [7, 3, 5, 8, 2, 9, 4, 15, 6]

**Step 1:**
- Initial array: [7, 3, 5, 8, 2, 9, 4, 15, 6]
- Find the minimum element in the unsorted portion of the array, which is 2.
- Swap the minimum element with the first element.
- Array after step 1: [2, 3, 5, 8, 7, 9, 4, 15, 6]

**Step 2:**
- Initial array: [2, 3, 5, 8, 7, 9, 4, 15, 6]
- Find the minimum element in the unsorted portion of the array, which is 3.
- Swap the minimum element with the second element.
- Array after step 2: [2, 3, 5, 8, 7, 9, 4, 15, 6]

**Step 3:**
- Initial array: [2, 3, 5, 8, 7, 9, 4, 15, 6]
- Find the minimum element in the unsorted portion of the array, which is 4.
- Swap the minimum element with the third element.
- Array after step 3: [2, 3, 4, 8, 7, 9, 5, 15, 6]

**Step 4:**
- Initial array: [2, 3, 4, 8, 7, 9, 5, 15, 6]
- Find the minimum element in the unsorted portion of the array, which is 5.
- Swap the minimum element with the fourth element.
- Array after step 4: [2, 3, 4, 5, 7, 9, 8, 15, 6]

At this point, the first four steps of the Selection Sort are completed. The array is partially sorted.
Continuing the selection sort process will sort the remaining elements of the array.

**Final sorted array:** [2, 3, 4, 5, 6, 7, 8, 9, 15]
