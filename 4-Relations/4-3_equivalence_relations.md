# 4.3 Equivalence relations

## Definition 4.24
### Let R be a relation on the set A. We call R an _equivalence relation_ on A if R has the following three properties:
1. ∀ a ∈ A, then (a, a) ∈ R.
    (Reflexivity)
2. If (x, y) ∈ R, then (y, x) ∈ R.
    (Symmetry)
3. If (x, y) ∈ R and (y, z) ∈ R, then (x, z) ∈ R.
    (Transitivity)

## Exercise 4.25
### Check the following relations on A = { 1, 2, 3 } for reflexivity, symmetry and transitivity.
1. R₁ = {(1, 1), (2, 2), (3, 3)} = I<sub>A</sub>
    - True
2. R₂ = {(1, 1), (1, 2), (2, 1), (2, 2), (3, 3)}
    - False
3. R₃ = {(1, 1), (1, 2), (2, 1), (2, 2), (3, 3)}
    - True, but weird

## Proposition 4.27
### The relation R on ℤ defined by R = { (x, y) ∈ ℤ × ℤ : x² = y² }

## Definition 4.30
### Let R be an equivalence relation on the set A. For each x ∈ A, the equivalence class of x determined by R is the set x/R = {y ∈ A : (x, y) ∈ R}.
note x _mod_ R ≠ ø since at least x ∈ x/R.
Moreover, A/R = { x/R | x ∈ A }

## A True classic example
### Let R be the relation on ℤ given by R = { (x, y) ∈ ℤ × ℤ : 5 divides x-y }.

## Example 4.31
#### "R" -> "≡₅"
#### "(2, 7) ∈ R" -> "(2, 7) ∈ ≡₅"
#### "(2, 7) ∈ ≡₅" -> "2≡₅7"
#### "(2, 7) ∈ ≡₅" -> "2 ≡ 7 mod 5"
#### ℤ/R = ℤ/≡<sub>m</sub> = ℤ<sub>m</sub>

## Proposition 4.35
### Let m ∈ Z \ {0}. If a ≡<sub>m</sub> b and c ≡<sub>m</sub> d, then (a + c) ≡<sub>m</sub> (b + d).
Proof:
    Suppose a ≡<sub>m</sub> b and c ≡<sub>m</sub>.
    So m divides a-b and m divides c-d, such that a-b = mk and c-d = mj for some k, j of ℤ.
    Consider that m divides m(k + j).
    m(k + j)
    = mk + mj
    = (a - b) + (c - d)
    = (a + c) - (b + d).
    thus, m divides (a + c) - (b + d).
□

## Theorem 4.37
### Let R be an equivalence relation on the set A.
(a) For each x ∈ A, x ∈ x/R.
Proof:
    let some arbitary w ∈ A. by Reflexivity, (w, w) ∈ R.
    It would stand to reason then, that w ∈ w/R.
□

(b) A = ∪<sub>x∈A</sub>x/R.
Proof:
1. [z ∈ A ⇒ z ∈ ∪<sub>x∈A</sub>x/R]
    Suppose z ∈ A.
    Consider x = z, such that z ∈ x/R.
2. [z ∈ ∪<sub>x∈A</sub>x/R ⇒ z ∈ A]
    let z ∈ ∪<sub>x∈A</sub>x/R such that there exists an x ∈ A where z ∈ x/R.
    In other words, (z, x) ∈ R where z ∈ A.
    Thus, z ∈ A
□

(c) (x, y) ∈ R iff x/R = y/R.
Proof:
    1. [(x, y) ∈ R ⇒ x/R = y/R]
        Suppose xRy
        1. let w ∈ x/R.
            So xRw.
            Since xRy and wRx, 
            by transitivity wRy, and by symmetry, yRw.
            Thus, w ∈ y/R
        2. let z ∈ y/R.
            ... Similar.
    2. [x/R = y/R ⇒ (x, y) ∈ R]
        Suppose x/R = y/R such that w ∈ x/R ⇒ w ∈ y/R, and w ∈ x/R ⇒ w ∈ y/R.
        ...
□

(d) (x, y) ∉ R iff x/R ∩ y/R = ∅.
1. [(x, y) ∉ R ⇒ x/R ∩ y/R = ∅]
2. [x/R ∩ y/R = ∅ ⇒ (x, y) ∉ R]

## Example 4.39
### The family Ā = {(−∞, 0], (0, ∞)} is a partition of ℝ into two infinite rays.

## Exercise 4.40
### Construct a partition Ā of the real numbers ℝ into infinitely many disjoint sets.
Ā = {{|x| = |y| : y ∈ ℝ} : x ∈ ℝ}
