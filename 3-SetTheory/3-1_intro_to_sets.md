# 3.1 Intro to sets

## Definition 3.1
### A _set_ is an unorderd collection of unique objects called its elements. If A is a set and x is an element of A, we write x ∈ A. Otherwise, we write x ∉ A.
Ex:
A = { 1, 2, 8, 17}
ℕ = { 1, 2, 3, ... }
ℤ = { ..., -3, -2, -1, 0, 1, 2, ... }
ℚ = { r ∈ ℝ | r = p/q where p, q ∈ ℤ and q != 0 }
ℝ = the set of real numbers

## Definition 3.2
### The set having no elements is called the empty set and is denoted by the Danish letter ∅.
∅ = {}

## Example 3.3
∅ = { r ∈ ℝ | r² + 1 = 0 }

## Definition 3.4
### There are certain sets of real numbers that garner special notation (a and b denote real numbers throughout):
(a, b) = {x ∈ R : a < x < b}
 (the open interval from a to b)
[a, b] = {x ∈ R : a ≤ x ≤ b}
 (the closed interval from a to b)
(a, ∞) = {x ∈ R : a < x}
 (the open ray from a to infinity)
[a, ∞) = {x ∈ R : a ≤ x}
 (the closed ray from a to infinity)
(−∞, b) = {x ∈ R : x < b}
 (the open ray from minus infinity to b)
(−∞, b] = {x ∈ R : x ≤ b}
 (the closed ray from minus infinity to b)

## Definition 3.6
_subsets_
We say that A is a subset of B and write A ⊆ B,
provided each element of the set A is also an element of the set B.
That is, A ⊆ B ⇔ [x ∈ A ⇒ x ∈ B].
_set equality_
We say A equals B and write A = B,
provided A ⊆ B and B ⊆ A.
That is, A = B ⇔ [A ⊆ B ∧ B ⊆ A].

## Proposition 3.7
### {1, 2, 3, π} ⊆ [1, 4).

## Proposition 3.8
### ∅ = {∅}.

## Proposition 3.9
### ∅ ∉ ∅.


## Proposition 3.10
### For every set A, ∅ ⊆ A.
Proof:
since in [x ∈ ∅ ⇒ x ∈ B] x ∈ ∅ is always false, (∀ A)(ø ⊆ A)

## Proposition 3.11
### { ½, ⅖ } ⊆ ℚ.
Proof:
Proceeding by the definition of subset,
½ ∈ ℚ
and
⅖ ∈ ℚ,
□

## Proposition 3.12
### {{∅}} ⊆ {∅, {∅}}.
Proof:
Proceeding by the definition of subset,
{ø} ∈ {ø, {ø}}
□

## Proposition 3.13
### { 1, 2 } ∈ {{ 1, 2, 3 }, { 2, 3 }, 1, 2 }.
DisProof:
{ 1, 2, 3 } ≠ { 1, 2 },
{ 2, 3 } ≠ { 1, 2 },
1 ≠ { 1, 2 },
2 ≠ { 1, 2 },
□

## Proposition 3.14
### If A and B are both sets of real numbers, A ⊆ B or B ⊆ A
DisProof:
Consider:
A = { 1 }
B = { 2 }
□

## Theorem 3.15
### Let A, B and C be sets. If A ⊆ B and B ⊆ C, then A ⊆ C.
Proof:
Let A, B and C be sets.
Suppose A ⊆ B and B ⊆ C; let some x ∈ A
Because A ⊆ B, x ∈ B.
let arbitary y ∈ B.
Because B ⊆ C, y ∈ C.
Consider letting y be x.
In that way, x ∈ A ⇒ x ∈ C.
therefore, A ⊆ C
□

## CAUTION 3.16
There is a big difference between studying axiomatic set theory,
which is a deep and difficult subject lying at the very foundations of logic and mathematics,
and naive set theory, which takes some liberties in the interest of brevity and practicality.

## Definition 3.17
### A set A is called _ordinary_ if it does not contain itself as an element,i.e. if A ∉ A.

## Exercise 3.18
### Let X = { A : A is an ordinary set }. Is X ordinary? Is X not ordinary?
If X is ordinary, then it is a member of all the ordinary sets, making it not ordinary.
If X is not ordinary, then it is not a member of all the ordinary sets, but that would make itself ordinary.

