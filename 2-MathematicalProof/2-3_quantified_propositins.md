# Subsection 2.3.1
Proofs of existence

## Proposition 2.25
### (∃x)(x² = 4)
Proof:
Consider x = 2
□

## CAUTION 2.26
### Not all existence proofs are constructive. Sometimes, a valid existence proof leaves us certain that some object with particular properties exists, yet leaves us with no idea what specific object it is.

## Proposition 2.27
### There exists a three-digit number less than 400 with distinct digits that sum to 17 and multiply to 108.
Proof:
Consider x = 269
□

## Proposition 2.28
### There exist irrational numbers x and y such that x + y is rational
Proof:
Consider x = π, y = -π
□

## Proposition 2.29
### There exists an irrational number r such that r<sup>√2</sup> is rational.
Proof:
    Consider the number p =  √2<sup>√2</sup>.
    In the case the p is rational, we are done because the irrational number r = √2
    In the case that p is not rational, Notice that (√2<sup>√2</sup>)<sup>√2</sup> = 2.
    So in this case, r = √2<sup>√2</sup> is the desired irrational number.
    In either case, we have exhibited the claimed irrational number r.
□

## Proposition 2.30
### There exist integers m and n such that 7m + 2n = 1.
Proof:
Consider m = -1, n = 4
□

## Proposition 2.31
### Some two grandmothers of past or present U.S. presidents have birthdays within eleven days of one another.
Proof:
There have been 46 presidents to date, each with 2 grandmothers, such that there are 92 total that we have to keep track of.
Proceeding by contradiction:
For each grandmother to be spaced 
□

# Subsection 2.3.2
Proofs of Universal Proposition

## Proposition 2.32
### For every odd integer n, 2n² + 3n + 4 is odd.
Proof:
Let n be an arbitrary odd integer.
Then n = 2k + 1 for some integer k.
So 2n² + 3n + 4 = ... = 2(Some integer) + 1.
So for all odd integers n, 2n² + 3n + 4 is itself odd.
□

## Theorem 2.33
### For all positive real numbers x and y, (x + y)/2 ≥ √xy.

Proof:
Let x and y be arbitrary positive real numbers.
Certainly, (x - y)² >= 0.
Thus, x² - 2xy + y² >= 0.
Adding 4xy to both sides,
we obtain x² + 2xy + y² >= 4xy, or (x + y)² >= 4xy.
Rooting each side leaves us with
x + y >= 2√xy,
(x + y)/2 >= √xy.
□

## Proposition 2.34
### For every real number x, there exists a real number y such that x < y.
Proof:
Let x be an arbitrary real number.
Consider y = x + 1.
□

## Proposition 2.35
### There exists a real number y such that for every real number x, x < y.
DisProof:
Let y be any arbitrary real number.
By 2.34, there exists a real number j such that j > y.
Because j exists, the Proposition is false.
□


## Proposition 2.36
### For each real number x there exists a real number y such that x + y = 0.
Proof:
Let x be an arbitrary real number.
Certainly, x - x = 0.
Consider y = -x.
□

## Proposition 2.37
### For every positive real number x there exists a positive real number y < x such that (∀z)(z > 0 ⇒ yz ≥ z).
DisProof:
Consider x = 1, such that all possible y are less than 1.
Consider z = 1.
Because all possible y are less than 1, z being positive does not imply that the product of z and y is greater than or equal to z.
Therefore, the proposition is false
□

## Proposition 2.38
### For every positive real number ε there exists a positive integer N such that n ≥ N ⇒ 1/n < ε.
Proof:
Let ε be an arbitrary positive real number.
Certainly, if a positive real number n is greater than ε, then 1/n < ε.
There will always exist a real number j greater than ε (by 2.34).
Consider N being j rounded up to the nearest natural number,
such that n >= N, and n is greater than ε.
□

# Subsection 2.3.3
Proofs of unique existence
Proof:
1. Show (∃x)(P(x))
2. Show P(x<sub>1</sub>) ^ P(x<sub>2</sub>) ⇒ x<sub>1</sub> = x<sub>2</sub>
□

## Proposition 2.39
### There exists a unique positive real number x whose square is 9.
Proof:
1. Consider x = 3
2. Suppose Some positive reals x and y both equal 9 when squared.
    Surely, x² - y² = 0.
    So, (x - y)(x + y) = 0.
    Since x and y are positive, (x + y) is nonzero,
    so (x - y) = 0 or x = y
□


