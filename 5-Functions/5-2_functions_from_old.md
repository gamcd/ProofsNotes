# New Functions From Old

## Example 5.14
### Let f : ℝ → ℝ be given by f(x) = e<sup>x</sup> and g : ℝ → ℝ be given by g(x) = x². In the formal sense of these functions as sets of ordered pairs, f = {(x, y) ∈ ℝ × ℝ : y = e<sup>x</sup>}
f ∘ g = { (a, c) ∈ ℝ × ℝ | (∃b ∈ ℝ)((a, b) ∈ g ∧ (b, c) ∈ f) }
f ∘ g = { (a, c) ∈ ℝ × ℝ | (∃b ∈ ℝ)(b = a² ∧ c = e<sup>b</sup>) }
f ∘ g = { (a, c) ∈ ℝ × ℝ | c = e<sup>a²</sup> }

## Theorem 5.16
### If f : A → B and g : B → C, then g ◦ f : A → C
Proof:
    Suppose f : A → B and g : B → C.
    Dom(f) = A, Dom(g) = B.
    From chapter 4, g ∘ f is a relation from A to C.
    1. [Dom(g ∘ f) = A]
        1. Dom(g ∘ f) ⊆ Dom(f), and Dom(f) = A, so Dom(g ∘ f) = A
        2. if x ∈ A, then (x, f(x)) ∈ f ∧ (f(x), g(f(x))) ∈ g
            thus, (x, f(x)) ∈ (g ∘ f). So x ∈ Dom(g ∘ f)
    2. Suppose (a, c₁) ∈ g ∘ f and (a, c₂) ∈ g ∘ f.
        By relationship composition from chapter 4, we know there exists some b₁, b₂ ∈ B


