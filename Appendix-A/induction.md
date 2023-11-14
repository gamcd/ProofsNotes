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

## Proposition A.4
### For each n ∈ ℕ, 1 + 3 + ... + (2n - 1) = n²
Proof:
    Proceeding by induction,
    let S = { n ∈ ℕ : 1 + 3 + ... + (2n - 1) = n² }
    1. Note, (1) = 1², so 1 ∈ S
    2. Suppose k ∈ S such that 1 + 3 + ... + (2k - 1) = k².
        1 + 3 + ... + (2k - 1) + (2k + 1) = k² + (2k + 1) = (k + 1)².
        Thus,  (k + 1) ∈ S
    Therefore, by PMI, S = ℕ
□

## Proposition A.6
### For each n ∈ ℕ, a 2ⁿ × 2ⁿ chess board with one square missing can be covered exactly with non-overlapping triominos.
Proof:
    Let S = { n ∈ ℕ : 2ⁿ x 2ⁿ chess board }
    Let S be the subset of naturals that uphold the condition.
    1. Consider n = 1:
        □
        □ □
    2. Suppose for some k ∈ ℕ, k ∈ S such that a 2<sup>k</sup> x 2<sup>k</sup> can be tiled by triominos
        Consider a second 2<sup>k+1</sup> x 2<sup>k+1</sup> with a tile removed.
        Imagine tiling this second board with 'squares' the size of four tiles such that the number of squares is equal to the number of tiles from the original board.
        For some square B with the tile missing, a triomino can be placed in the other three tiles.
        Consider a third new board the same size as the first board, with the missing tile in the position of the square B from the second board.
        This third board is cleany tileable because it's 2<sup>k</sup> x 2<sup>k</sup>.
        Each triomino that would be placed on the third board can be represented by a 12 tile 'square triomino' on the second board.
        Because the third board is tileable and each tile of the second board can 'map' to tiles on the third board, the second board is also tileable.
        Therefore, k ∈ S ⇒ k + 1 ∈ S
    Therefore, S = ℕ
□

## Proposition A.7
### For each n ∈ N, 2ⁿ > n²
Disproof:
    consider n = 2
□


## Generalized PMI
If S ⊆ ℕ satisifies
    1. j ∈ S
    2. k ∈ S ⇒ k + 1 ∈ S,
then { j, j + 1, j + 2, ... } ⊆ S.

## PCI (principle of complete induction)
If S ⊆ ℕ satisifies
    1. ∀n ∈ ℕ, [{ k ∈ ℕ | k < n } ⊆ S ⇒ n ∈ S],
then S = ℕ

## WOP (well ordering principle)
If S ⊆ ℕ where S ≠ ø,
then S has a least number

through A.8

## Challenge
WOP ⇔ PCI

