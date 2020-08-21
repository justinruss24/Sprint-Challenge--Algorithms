#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n) -- The driver of runtime complexity here is the number of iterations of the while loop. The loop will run nnn (or n^3) times, for an initial runtime complexity of O(n^3). Inside each loop, addition is of O(1) complexity. Multiplication of two m-digit numbers has a minimum complexity of O(n log n), so overall computation complexity will depend on the size of the values used; ignoring multiplication, though, the computational complexity is O(n^3).


b)
O(n log n) -- The outer loop here is O(n) runtime, but the inner loop is O(log n) runtime since J is growing exponentially & the loop will stop once j reaches n.


c)
O(n) -- This runtime complexity is O(n) because the number of operations will increase linearly with the bunnies input number.

## Exercise II

- Start on the middle floor & throw an egg off of it.
- If the egg breaks, go to the floor between the current floor & the bottom floor and throw another egg.
- Repeat step 2 until the egg does not break.
- If the egg does not break, go to a floor between the current floor & the lowest floor where the egg broke.
- Repeat this until the next lowest floor where the egg breaks, and the current floor are next to each other.
- This will be runtime complexity of O(log n) as it is a binary search strategy.