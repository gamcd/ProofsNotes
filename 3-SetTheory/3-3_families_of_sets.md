# 3.3 Families of sets

## Example 3.32
### The family Ā = {{1, 2}, {2, 3, 5}, {−π, 2}} has three elements, each of which is a set of real numbers.

## Definition 3.33
### Let Ā be a family of sets in some universe U. The union and intersection of all sets in Ā are given by
∪<sub>A ∈ Ā</sub>A = { x ∈ U : x ∈ A for at least one set A ∈ Ā }
∩<sub>A ∈ Ā</sub>A = { x ∈ U : x ∈ A for at least one set A ∈ Ā }

## Exercise 3.34
### Let Ā = {[a, ∞) ⊆ ℝ : a ∈ ℝ}. Determine ∪<sub>A ∈ Ā</sub>A ∩<sub>A ∈ Ā</sub>A
∪<sub>A ∈ Ā</sub>A = [-∞, ∞)
∩<sub>A ∈ Ā</sub>A = ø

## Exercise 3.35
### Let Ā = {(-a, a) ⊆ ℝ : a ∈ ℝ}. Determine ∪<sub>A ∈ Ā</sub>A ∩<sub>A ∈ Ā</sub>A
∪<sub>A ∈ Ā</sub>A = [-∞, ∞]
∩<sub>A ∈ Ā</sub>A = (0, 0)

## Proposition 3.36
### If Ā is a family of sets, then for each B ∈ Ā, the Union of A for A ∈ Ā is a subset of B
Proof:
    Let B ∈ Ā.
    Let x ∈ ∪<sub>A ∈ Ā</sub>A such that each member of x is also a member of each element of Ā.
    Because B ∈ Ā, each member of x is also a member of B.
    In this way, [x ∈ ∪<sub>A ∈ Ā</sub>A ⇒ x ∈ B].
    Therefore, the Union of A for A ∈ Ā is a subset of B.
□



## Definition 3.42
### Let ∆ be a nonempty set. Suppose for each α ∈ ∆ there is a corresponding set A<sub>α</sub>. The family of sets Ā = {A<sub>α</sub> : α ∈ ∆} is called an _indexed family of sets_. Each α ∈ ∆ is a particular index and the set ∆ is called the indexing set.
Union of A<sub>α</sub for α ∈ Δ = { x ∈ U | x ∈ A<sub>α</sub> for at least one α ∈ Δ }
Intersection of A<sub>α</sub for α ∈ Δ = { x ∈ U | x ∈ A<sub>α</sub> for all α ∈ Δ }

## Exercise 3.46
### Let ∆ = ℕ. For each n ∈ ∆, let A<sub>n</sub> = (−1/n, 2 + 2/n]. Determine the union and intersection of A<sub>n</sub> for n ∈ ℕ.
Union of A<sub>n</sub> = A₁ = (-1, 4]
Intersection of A<sub>n</sub> = [0, 2]

## Proposition 3.51
### If Ā = { A<sub>α</sub> : α ∈ ∆ } is an indexed family of sets and B is a set, then ∪(Ā) \ B = ∪<sub>α ∈ Δ</sub>(A<sub>α</sub> \ B)
1.
    Suppose x ∈ (∪(Ā) \ B) such that x ∈ ∪(Ā) and x ∉ B.
    In that way, x ∈ Ā for at least one α ∈ Δ,  so x ∈ Ā and x ∉ B for at least one α ∈ Δ.
    Therefore, it leaves in the union of all A<sub>α</sub> \ B for α ∈ Δ.
2.
    Suppose x ∈ ∪<sub>α ∈ Δ</sub>(A<sub>α</sub> \ B), such that there exists an α ∈ Δ where x ∈ Ā and x ∉ 
