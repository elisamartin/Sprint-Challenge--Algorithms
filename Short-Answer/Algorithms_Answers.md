Add your answers to the Algorithms exercises here.

## Exercise I

a) n^3 = a + n^2 
   n^3 = n^2 
   n^3 / n^2 = n = O(n)
  
  Linear time O(n), since the number of additional operations the algorithm needs to make grows in direct proportion to the size of n

b) n * n * n * 1 = n^3 = O(n^3)

  The algorithm involves nested operations

c)  Linear time O(n), the function runs n times, the times it runs grows in direct proportion to the size of n/bunnies

## Exercise II

Divide the number of floors in 2
Got to the middle floor and throw an egg
  
  If the egg breaks -> Start the process again but only on the lower half of floors (because you are too high)

  If the egg doesn't break -> Start the process again but only on the higher floors

Stop when there's only one floor left and return that floor as _f_ (this would be at the top to stop everything)

Runtime complexity O(log n) as this is an example of binary search, the algorithm increases the number of operations as a logarithmic function of n. 