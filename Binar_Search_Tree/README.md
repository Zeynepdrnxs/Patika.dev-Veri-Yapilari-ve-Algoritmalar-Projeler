**Binary Search Tree Construction:**

Given array: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. **Step 1: Insert 7 as Root**
    - Insert 7 as the root of the BST.

   **BST:**
   7

2. **Step 2: Insert 5**
    - Compare 5 with the root (7).
    - Since 5 < 7, move to the left subtree.
    - Insert 5 as the left child of 7.

   **BST:**
   7
   /
   5

3. **Step 3: Insert 1**
    - Compare 1 with the root (7).
    - Since 1 < 7, move to the left subtree.
    - Compare 1 with the left child (5).
    - Since 1 < 5, move to the left subtree.
    - Insert 1 as the leftmost child of the left subtree.

   **BST:**
   7
   /
   5
   /
   1

4. **Step 4: Insert 8**
    - Compare 8 with the root (7).
    - Since 8 > 7, move to the right subtree.
    - Insert 8 as the right child of 7.

   **BST:**
   7
   / \
   5   8
   /
   1

5. **Step 5: Insert 3**
    - Compare 3 with the root (7).
    - Since 3 < 7, move to the left subtree.
    - Compare 3 with the left child (5).
    - Since 3 > 5, move to the right subtree.
    - Insert 3 as the right child of 5.

   **BST:**
   7
   / \
   5   8
   / \
   1   3

6. **Step 6: Insert 6**
    - Compare 6 with the root (7).
    - Since 6 > 7, move to the right subtree.
    - Compare 6 with the right child (8).
    - Since 6 < 8, move to the left subtree.
    - Insert 6 as the right child of 5.

   **BST:**
   7
   / \
   5   8
   / \
   1   3
   /
   6

7. **Step 7: Insert 0**
    - Compare 0 with the root (7).
    - Since 0 < 7, move to the left subtree.
    - Compare 0 with the left child (5).
    - Since 0 < 5, move to the left subtree.
    - Compare 0 with the left child (1).
    - Since 0 > 1, move to the right subtree.
    - Insert 0 as the right child of 1.

   **BST:**
   7
   / \
   5   8
   / \
   1   3
   /     \
   0       6

8. **Step 8: Insert 9**
    - Compare 9 with the root (7).
    - Since 9 > 7, move to the right subtree.
    - Compare 9 with the right child (8).
    - Since 9 > 8, move to the right subtree.
    - Insert 9 as the right child of 8.

   **BST:**
   7
   / \
   5   8
   / \   \
   1   3   9
   /     \
   0       6

9. **Step 9: Insert 4**
    - Compare 4 with the root (7).
    - Since 4 < 7, move to the left subtree.
    - Compare 4 with the left child (5).
    - Since 4 > 5, move to the right subtree.
    - Compare 4 with the right child (3).
    - Since 4 > 3, move to the right subtree.
    - Insert 4 as the right child of 3.

   **BST:**
   7
   / \
   5   8
   / \   \
   1   3   9
   / \   \
   0   4   6

10. **Step 10: Insert 2**
    - Compare 2 with the root (7).
    - Since 2 < 7, move to the left subtree.
    - Compare 2 with the left child (5).
    - Since 2 > 5, move to the right subtree.
    - Compare 2 with the right child (3).
    - Since 2 < 3, move to the left subtree.
    - Insert 2 as the left child of 3.

    **BST:**
    7
    / \
    5   8
    / \   \
    1   3   9
    / \   \
    0   4   6
    \
    2

**Final Binary Search Tree:**
```
           7
          / \
         5   8
        / \   \
       1   3   9
      / \   \
     0   4   6
          \
           2
```

This is the Binary Search Tree constructed from the given array [7, 5, 1, 8, 3, 6, 0, 9, 4, 2].
