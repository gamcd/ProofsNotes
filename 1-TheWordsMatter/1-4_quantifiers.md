
## Definition 1.44
### An _open sentence_ P(x1, x2, ..., xk) with one or more variables that becomes a proposition only when the variables are assigned specific values.
### The complete collection of values that the variables may be assigned is called _the universe_
### The Variable Values that P(x1, x2, ..., xk) true constitute the _truth set_ of the open sentence.

## Example 1.45
### Consider the open sentence P(x): “x² = 4.”
If the universe is the set R of all real numbers, then the truth set is {−2, 2}.
On the other hand, if the universe is the set R+ of positive real numbers, then thetruth set is {2}.

## Exercise 1.46
### Write an open sentence in the universe of real numbers that is true for every member of the universe.
(n - 1)(n + 1) = n² - 1 for any number n in universe ℝ

## Exercise 1.47
### Write an open sentence in the universe of cats that is true for no member of the universe.
P(cat): the cat is a reptile

## Def 1.49 (Universal Qualifier)
### Given an open sentance P(x), the proposition (∀x) P(x) is read "for all x in the universe, P(x) is true"
### This means that (∀x) is true no matter what value from the universe is assigned to x

## Exercise 1.51
1. (∀x)(x² >= 0) T
2. (∀x)(x < 0) F
3. (∀x)(x² > 0) F

## Def 1.50 (Existential Qualifier)
### Given an open sentance P(x), (∃x) P(x) is read "There exists at least  one x in the universe such that P(x) is true"

## Exercise 1.52
1. (∃x)(x² = 4): T
2. (∃x)(|x| = 0): T
3. (∃x)(2x + 7 = 3x - 9): T
4. (∃x)(x² < 0): F
5. (∃x)(Σ(n = 0, ∞, xⁿ converges)): T

## Exercise 1.53
### Name a universe in which (∃x)(x^2 + 1 = 0) is true.
ℂ

observe,
## Exercise 1.54
### ~(∀x) P(x) ⇔ (∃x)(~P(x)))
true

## Exercise 1.55
### ~(∃x) P(x) ⇔ (∀x)(~P(x)))
true

## Exercise 1.59
### Let the universe be the real numbers ℝ. Determine the truth value for each proposition.
1. (∀x)(∃y)(x < y) in universe ℝ
    for all x, there exists a y where x < y
     - true
2. (∃y)(∀x)(x < y) in universe ℝ
    there exists a y, where for any x, x < y
     - false

## Exercise 1.60
### Let the universe be the real numbers ℝ. Write the negation of each proposition.
1. (∀x)(∃y)(x < y)
    - (∃x)(∀x)(x > y))
2. (∃y)(∀x)(x < y)
    - (∀x)(∃y)(x > y)

## Definition 1.61 (Unique Existential Quantifier)
### Let P(x) be an open sentence with variable x. The proposition (∃!x)P(x) is read “There exists a unique x such that P(x)” and is true precisely when P(x) is true for exactly one value of x in the universe

## Exercise 1.62
### Let the universe be the real numbers ℝ. Determine the truth value for each proposition.
1. (∃!x)(x ≥ 0 ∧ x ≤ 0)
    - true
2. (∃!x)(x > 5)
    - false
3. (∃!x)(x² = 4)
    - false
