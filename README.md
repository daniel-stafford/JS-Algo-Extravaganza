# Algorithms and Data Structures in JavaScript!

## Big O

- Means of evaluating the performance of code
- Allows discussion of trade-offs between different approaches
- Helps debugging when code is slow or crashes
- Good code is a balancing act between

  - Speed
    - Timer (e.g. performance.now()) is a poor method
      - Difference machines = different times
      - Same machine = different times
      - Fast algo may be too quick, timer not precise enough
      - Big O allows for general categorization
  - Memory utilization
  - Readability

  ### Counting Operations

  - includes additions, assignments, comparisons, etc.
  - General trend is more important, e.g. (5n = 100n = n)
  - Formalization of fuzzy counting
  - Big O is upper bound run time i.e. worst case
  - Play around with [this](https://rithmschool.github.io/function-timer-demo/)!
  - Constants don't matter (5n = n)
  - Smaller terms don't matter (1000n + 50 = n) (n^2 + 5n = n^2)

  ### Shorthands

  - Constants
    - Arithmetic operations
    - Variable assingments
    - Access element in array using index or object by key
  - Loops
    - Complexity is length of loop \* complexity of functions inside loop
  - O(1) < O(log n) < O(n) < O(nlog n) < O(n^2)
