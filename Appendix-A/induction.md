# Appendix A: Induction
Recall ℕ = { 1, 2, 3, 4, ... }

ℕ is identifiable by _5_ properties
1. 1 ∈ ℕ.
2. For each x ∈ ℕ, there exists a _unique_ successor x + 1 ∈ ℕ.
3. 1 is _not_ a successor.
4. If x and y have the same successor, x = y
5. Principle of mathematical induction:
    If S ⊆ ℕ satisifies
        1. 1 ∈ S
        2. ∀k ∈ ℕ, k ∈ S ⇒ k + 1 ∈ S,
    then, S = ℕ



## Proposition A.3
### For each n ∈ ℕ, 1 + 2 + 3 + ... + n = n(n + 1)/2
Proof:
    Proceeding by induction, let S = { n ∈ ℕ | 1 + 2 + 3 + ... + n = n(n + 1) / 2 }.
    1. Note, 1 = 1(1 + 1) / 2, so 1 ∈ S.
    2. Suppose k ∈ S such that 1 + 2 + 3 + ... + k = k(k + 1) / 2.
        Therefore, 1 + 2 + 3 + ... + k + (k + 1) =
            k(k + 1) / 2 + (k + 1) = 
            (k + 1)(k/2 + 1) =
            (k + 1)(k + 2) / 2
        Thus, k + 1 ∈ S
    Therefore, by PMI, S = ℕ.
□
