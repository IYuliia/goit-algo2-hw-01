### Task 1 (Mandatory): Finding the Maximum and Minimum Elements

Implement a function that finds the maximum and minimum elements in an array using the "divide and conquer" method.

#### Acceptance Criteria:
- The function accepts an array of numbers of any length.
- A recursive approach is used.
- The function returns a tuple of values (minimum, maximum).
- The algorithm's complexity is **O(n)**.

---

### Task 2* (Optional): Finding the k-th Smallest Element

Implement an algorithm to find the **k-th smallest** element in an unsorted array using the **Quick Select** principle.

#### Conditions:
- The function should accept an array of numbers and a number **k**.
- The approach should use a **pivot selection** strategy.
- The array should **not** be fully sorted.
- The expected average-case complexity should be **O(n)**.

📌 **Note:** Quick Select is an example of the "divide and conquer" method, but in our case, the **Combine** step requires no additional work. Once we find the desired element, we simply return it.