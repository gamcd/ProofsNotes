# 4.2 New Relations From Old

## Definition 4.14
### Let R be a relation from A to B. The _inverse_ of R is the relation _R⁻¹_ = {(y, x) ∈ B × A : (x, y) ∈ R}. Note that R⁻¹ = B×A

## Prop 4.15
### Let R be a relation from A to B.
1. Dom(R⁻¹) = Ran(R).
    1. Suppose w ∈ Dom(R⁻¹), such that there exists a z ∈ A where (w, z) ∈ R⁻¹.
        Thus, (z, w) ∈ R. Notice, that w ∈ Ran(R).
        Therefore, w ∈ Dom(R⁻¹) ⇒ w ∈ Ran(R)
    2. Suppose w ∈ Ran(R), such that there exists a z ∈ B where (z, w) ∈ R.
        Thus, (w, z) ∈ R⁻¹. Notice, that w ∈ Dom(R⁻¹).
        Therefore, w ∈ Ran(R) ⇒ w ∈ Dom(R⁻¹)
2. Ran(R⁻¹) = Dom(R).
    1. ...
    2. ...

## Definition 4.19
### Let R be a relation from A to B and let S be a relation from B to C. The composition of R and S is the relation
### S ◦ R = {(a, c) ∈ A × C : (∃b ∈ B)((a, b) ∈ R ∧ (b, c) ∈ S)}.

## Exercise 4.20
### Let R = {(1, 5), (2, 2), (3, 4), (5, 2)} and S = {(2, 4), (3, 4), (3, 1), (5, 5)} be relations on N. Determine both S ◦ R and R ◦ S.

## Proposition 4.21
### If R is a relation from A to B and S is a relation from B to C, then Dom(S ◦ R) ⊆ Dom(R).
Suppose R is a relation from A to B and S is a relation from B to C

## Theorem 4.23
### Let A, B, C and D be sets. Let R be a relation from A to B, S a relation from B to C and T a relation from C to D.
### (a) (R⁻¹)⁻¹ = R.
Proof:
1. [(x, y) ∈ (R⁻¹)⁻¹ ⇒ (x, y) ∈ R]
    Let (x, y) ∈ (R⁻¹)⁻¹ such that (y, x) ∈ R⁻¹.
    In a similar way, you can un-invert the relation to show that (x, y) ∈ R
2. [(x, y) ∈ R ⇒ (x, y) ∈ (R⁻¹)⁻¹]
    Let (x, y) ∈ R such that for some R⁻¹, (y, x) ∈ R⁻¹.
    It would stand to reason that for some inverse of this relation, (R⁻¹)⁻¹, (x, y) ∈ (R⁻¹)⁻¹
□
### (b) T ◦ (S ◦ R) = (T ◦ S) ◦ R.
Proof:
    1. [(a, d) ∈ T ◦ (S ◦ R) ⇒ (a, d) ∈ (T ◦ S) ◦ R]
        Suppose (a, d) ∈ (T ◦ (S ◦ R)).
            this would mean that (∃c) (((∃b) (a, b) ∈ R ∧ (b, c) ∈ S) ∧ (c, d) ∈ T)
        because ∃c ∃b ((b, c) ∈ S) and ∃c ((c, d) ∈ T),
        ∃b ((b, d) ∈ (T ◦ S)).
        Knowing that (∃b) (a, b) ∈ R, we can say (∃b)((a, b) ∈ R, ∃b ((b, d) ∈ (T ◦ S)))
        Thus, (a, d) ∈ (a, d) ∈ (T ◦ S) ◦ R
    2. [(a, d) ∈ (T ◦ S) ◦ R ⇒ (a, d) ∈ (T ◦ S) ◦ R]
        ... Similar
□
### (c) I<sub>B</sub> ◦ R = R and R ◦ I<sub>A</sub> = R.
Proof:

□
### (d) (S ◦ R)⁻¹ = R⁻¹ ◦ S⁻¹ .
Proof:

□
