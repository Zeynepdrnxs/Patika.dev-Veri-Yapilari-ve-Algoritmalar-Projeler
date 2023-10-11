**Merge Sort:**

Given array: [16, 21, 11, 8, 12, 22]

**Step 1: Splitting the Array**
- Divide the array into smaller subarrays recursively until each subarray contains only one element.
- The array is split into [16, 21, 11] and [8, 12, 22].

**Step 2: Sorting and Merging Subarrays**
- Start merging the subarrays back together while sorting them in the process.

  **Merge [16, 21, 11] and [8, 12, 22]:**

    - Compare the first elements of both subarrays, which are 16 and 8.
    - Take the smaller element (8) and move it to the merged array.
    - Move to the next element in the subarray that contributed the element (subarray [8, 12, 22]).
    - Compare the next element (12) with 16 and take the smaller element (12).
    - Repeat this process until one of the subarrays is completely merged.
    - After merging one subarray, simply add the remaining elements of the other subarray ([16, 21, 11]).

  **Merged array:** [8, 12, 16, 21, 11, 22]

**Step 3: Continue Merging**
- Continue merging and sorting the subarrays until the entire array is merged back together.

  **Merge [8, 12, 16, 21, 11, 22] and []:**

    - Since one subarray is empty, the merging is straightforward.
    - The merged array remains [8, 12, 16, 21, 11, 22].

**Final sorted array:** [8, 11, 12, 16, 21, 22]

**Big-O Notation for Merge Sort:** The time complexity of Merge Sort is O(n log n), where 'n' is the number of elements in the array. It provides consistent performance across different cases, making it a reliable sorting algorithm.

Merge Sort follows a divide-and-conquer approach, splitting the array into smaller parts, sorting them, and then merging them back together while maintaining the sorted order. This ensures that the final merged array is sorted.
