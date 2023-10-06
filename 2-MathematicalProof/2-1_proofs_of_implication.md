## Theorem 2.1
### If the list { sit, hut, sum, W } is tight and W begins neither with “s” nor “h”, then the last letter of W is a “t”.
Proof:
Suppose { sit, hut, sum, W } is tight and W starts with neither 's' nor 'h'.
If the second letter of W is a 'u', then tightness requires d(sit, W) <= 2 so the last letter of W is a 't'. On the other hand, if the second letter of W is not a 'u', then tightness requires d(hut"", W) <= 2 so the third letter of W is a 't' in this case as well. Subsequently, the third letter of W is 't'. 
□

## Def 2.2 
### let _ℤ_ = {... , -2, -1, 0, 1, ...} be the integers. The integer a _divides_ the integer b if there exists an integer k such that b = ak

## Example 2.3
### The integer 6 divides the integer 42 because 42 = 6 · 7. The integer 8 does not divide the integer 34 because there is no integer k such that 34 = 8k 

## Theorem 2.4
### Let a, b and c be integers. If a divides b, then a divides bc.
Proof:
Suppose integer a divides integer b such that b = ak for some other integer k.
For some other integer c, the product of b and c is equivalent to (ak)c which by associativity is a(kc) where k and c are integers.
Therefore, in any case where a divides b, a will also divide the product bc. 
□

## Theorem 2.5
### Let a, b and c be integers. If a divides b and a divides b + c, then a divides 3c.
Proof:
Suppose integer a divides integer b such that b = ak, and that a divides the sum b + c such that b + c = aj.
Because b + c = aj, for j to be an integer equal to (ak + c) / a, a must divide c as well.
Therefore, because a always divides c, a also divides 3c.
□

Official Proof:
Suppose any integer a divides any integer b such that b = ak, and that a divides the sum b + c such that b + c = aj.
the equation b + c = aj, equates to c = aj - ak, equates to c = a(j - k) where j and k are integers.
By the definition of divides, a always divides c, or any multiple of c by 2.4.
Therefore, a always divides 3c.
□

## Exercise 2.6
### Create a definition for what it means for an integer to be even.
An integer n is defined as _even_ when 2 divides n
An integer n is defined as _even_ when a = 2n for some a

## Exercise 2.7
### Create a definition for what it means for an integer to be odd.
An integer n is defined as _odd_ when 2 does not divide n
An integer n is defined as _odd_ when a = 2n + 1 for some a


## Theorem 2.8
### If x and y are even integers, then x + y is an even integer.
Proof:
Suppose x and y are even integers, such that x = 2a and y = 2b for some integers a and b.
The sum of x and y can be expressed as (2a + 2b) or 2(a + b).
Because a + b is an integer being multiplied by 2, 2(a + b) will always be even.
Therefore, x + y is even.
□

## Theorem 2.9
### If x and y are odd integers, then x + y is an even integer.
Suppose x and y are even integers, such that x = 2a + 1 and y = 2b + 1 for some integers a and b.
The sum of x and y can be expressed as (2a + 1 + 2b + 1) or 2(a + b + 1).
Because a + b + 1 is an integer being multiplied by 2, 2(a + b + 1) will always be even.
Therefore, x + y is even.
□

## Theorem 2.10
### If x and y are even integers, then 4 divides x · y.
Proof:
Suppose x and y are even integers where x = 2a and y = 2b for some integers a and b.
The product of x and y can be expressed as (2a · 2b) or 4(a + b).
Because a + b is an integer, 4 always divides 4(a + b).
Therefore, 4 divides x · y.
□

## Theorem 2.11
### If x is an integer, then x² + x + 3 is an odd integer.
Proof: 
Suppose x is an integer.
In the situation where x is even, then x = 2k for some integer k.
□

## Theorem 2.12
### The product of consecutive integers is an even integer.
Proof:
We will show that if x is an integer, then x · (x + 1) is even.
Suppose there are two consecutive integers x and x + 1.
When x is even, x + 1 is odd, and when x is odd, x + 1 is even.
In both cases, the product can be expressed as 2k · (2j + 1) or 2 · (k(2j + 1)) where k and j are integers.
Therefore, The product of consecutive integers is an even integer.
□
