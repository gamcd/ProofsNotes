# 4.1 Relations and Products

## Definition 4.1
### Let A and B be sets. The _Cartesian product_ of A and B, A x B = { (a, b) : a ∈ A, b ∈ B }

## Proposition 4.4
### Let A, B and C be sets. Then A × (B ∩ C) = (A × B) ∩ (A × C).
1. [x ∈ A × (B ∩ C) ⇒ x ∈ (A × B) ∩ (A × C)]
    Suppose (x, y) ∈ A × (B ∩ C) such that x ∈ A, y ∈ B, and y ∈ C
    Thus, (x, y) ∈ A × B, and (x, y) ∈ A × C.
    Therefore, x ∈ (A × B) ∩ (A × C)
2. [x ∈ (A × B) ∩ (A × C) ⇒ x ∈ A × (B ∩ C)]
    Suppose (x, y) ∈ ((A × B) ∩ (A × C) such that (x, y) ∈ A 
    ...
    Therefore, x ∈ A × (B ∩ C)]


## Definition 4.6
### Let A and B be sets. A _relation from A to B_ is simple a subset of A × B.

## Convention 4.7
### for R ⊆ A × A, people call R a "relation on A" instead of "relation from A to A". (a, b) ∈ R is often written a-R-b where "a is related to b"

## Exercise 4.8
### Consider the relation on ℝ given by R = { (x, y) ∈ ℝ×ℝ | y - x ∈ [0, ∞)}
R = ≤

For some U, equality is { (x, y) ∈ U×U | x ⊆ y ∧ x ⊇ y }

## Definition 4.9
### The _domain_ of the relation R from A to B is the set Dom(R) = { x ∈ A : (∃y)(y ∈ B ∧ (x, y) ∈ R) } consisting of the “first entries” of ordered pairs in R.
### The _range_ of the relation R from A to B is the set Ran(R) = { y ∈ B : (∃x)(x ∈ A ∧ (x, y) ∈ R) } consisting of the “second entries” of ordered pairs in R.

## Exercise 4.10
### Define the relation C on ℝ by C = { (x, y) ∈ ℝ × ℝ : x² + y² ≤ 9 }.
1. Dom(C) = [-3, 3]
2. Ran(C) = [-3, 3]

## Exercise 4.11
### Determine the domain and range of the relation H from ℝ to [−5, ∞) given by H = { (x, y) ∈ ℝ × [−5, ∞) : xy = 1 }.
1. Dom(H) = [-5, ∞)
2. Ran(H) = ℝ

## Definition 4.12
### Let A be a set. The relation I<sub>A</sub> = { (x, x) ∈ A × A : x ∈ A } is called the identity relation on A. Note that by definition Dom(I<sub>A</sub>) = Ran(I<sub>A</sub>) = A

