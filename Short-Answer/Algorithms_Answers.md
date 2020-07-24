#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) - This is O(n) as it is linear. Since we have three multiplications of n in the while statement and then we set a to a + n _ n we have two multiplications here. Since we have two multiplications in the body of the while statement, and three up top, we know that we will just be repeating the body n times as n _ n \* n can we rewritten as follows with the body of the equation:

 <!-- (n*n) * n = x(n*n) -->

Where x can be made equal to n.

b) This is O(n^2) as there are nested loops. While this is not a perfect alignment of n^2, this line increments exponentially close to n^2 as it is not close to a linear increase. As n get's larger, the difference between the difficulty of the last n also increases in it's size.

c) This is O(n) as it is linear. We will only call bunnyEars as many bunnies there are as we subtract one each time we call it.

## Exercise II

I would use a binary "search" algorithm. I would start at the center floor, and if the egg cracked, I would set the center floor as my new "top" value. Then I would find the center of that, and see if the egg broke.

If at any point the egg doesn't break, I would set that center value as my new "bottom" value and find the center of that.

Once I'm down to one value remaining, I will check to see if the egg breaks, if it doesn't I have found my center, and if it does, I will subract one from that value and I will find the floor in which it doesn't break.

This is a time complexity of O(log n), as we are using a binary search method. Which proven through mathematical analysis, comes out to log(n)
