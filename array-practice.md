# Array Practice

1. `arr.push()`
    • Time complexity: O(1)
    • Space complexity: O(1)

    - Pushing an element to the end of an array involves adding the element to the next available index, which is a constant-time operation. It doesn't require any additional space beyond the new element itself.

2. `arr.pop()`
    • Time complexity: O(1)
    • Space complexity: O(1)

    - Popping an element from the end of an array involves removing the last element, which is a constant-time operation. No additional space is required for this operation.

3. `arr.shift()`
    • Time complexity: O(n)
    • Space complexity: O(1)

    - Shifting an element from the beginning of an array requires re-indexing all subsequent elements, which takes linear time. No additional space is required beyond the space already occupied by the array.

4. `arr.unshift()`
    • Time complexity: O(n)
    • Space complexity: O(1)

    - Unshifting an element to the beginning of an array requires re-indexing all existing elements, which takes linear time. No additional space is required beyond the new element itself.

5. `arr.splice()`
    • Time complexity: O(n)
    • Space complexity: O(n)

    - The time complexity of `splice` depends on the number of elements being added or removed and the re-indexing of subsequent elements, which can be linear. The space complexity can also be linear if new elements are added.

6. `arr.slice()`
    • Time complexity: O(n)
    • Space complexity: O(n)

    - Creating a shallow copy of a portion of the array involves iterating over the elements in a specified range, which takes linear time. The new array requires additional space proportional to the number of elements copied.

7. `arr.indexOf()`
    • Time complexity: O(n)
    • Space complexity O(1)

    - Searching for an element requires checking each element in the array until the target is found or the end is reached, which takes linear time. No additional space is required for this operation.

8. `arr.map()`
    • Time complexity: O(n)
    • Space complexity O(n)

    - Applying a function to each element of the array involves iterating over all elements, which takes linear time. The resulting array requires additional space proportional to the number of elements.

9. `arr.filter()`
    • Time complexity: O(n)
    • Space complexity: 0(n)

    - Filtering elements involves iterating over all elements and creating a new array with the elements that pass the test, which takes linear time. The new array requires additional space proportional to the number of elements that pass the test.

10. `arr.reduce()`
    • Time complexity: O(n)
    • Space complexity: O(1)

    - Reducing an array to a single value involves iterating over all elements and applying the accumulator function, which takes linear time. The space complexity is constant as no additional arrays are created.

11. `arr.reverse()`
    • Time complexity: O(n)
    • Space complexity: O(1)

    - Reversing an array involves swapping elements from the beginning with elements from the end until the middle is reached, which takes linear time. No additional space is required beyond the original array.

12. `[...arr]`
    • Time complexity: O(n)
    • Space complexity: O(n)

    - The spread operator creates a shallow copy of the array, which involves iterating over all elements, taking linear time. The new array requires additional space proportional to the number of elements.
