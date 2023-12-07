# 5.4 Set Images

## Definition 5.45
### Let f : A → B and X ⊆ A. The _image_ of the subset X is the set f(X) = {f(x) ∈ B : x ∈ X}.

## Definition 5.47
### Let f : A → B and Y ⊆ B. The _preimage_ of the subset Y is the set f⁻¹(Y) = {x ∈ A : f(x) ∈ Y }.

## Exercise 5.50
### Let f : R → R be given by f(x) = x². Determine the following set images and preimages.
1. f({1, 2, 3}) → {1, 4, 9}
2. f([0, 2]) → [0, 4]
3. f⁻¹({4}) → {-2, 2}
4. f⁻¹([0, 4)) → (-2, 2)
5. f((−3, −2]) → [0, 9)
6. f⁻¹(f((−3, −2])) → (-3, 3)
7. f⁻¹((−4, 1])) → [-1, 1]
8. f(f⁻¹((−4, 1]))) → [0, 1]

## Theorem 5.51
### If f : A → B and E ⊆ B, then f(f⁻¹(E)) ⊆ E.
Proof:
    Suppose f : A → B and E ⊆ B.
    To show f(f⁻¹(E)) ⊆ E, 
    Let w ∈ f(f⁻¹(E)), so w = f(z) for some z ∈ f⁻¹(E).
    z being in the preimage of E under f implies that f(z) ∈ E.
    So, w ∈ E.
□

## Theorem 5.55
### Let f : A → B. Let {D<sub>α</sub> : α ∈ ∆} be a family of subsets of A and let {E<sub>β</sub> : β ∈ Γ} be a family of subsets of B.
1. f(∩<sub>α ∈ ∆</sub>)D<sub>α</sub> ⊆ ∩<sub>α ∈ ∆</sub>(f(D<sub>α</sub>))
2. f(∪<sub>α ∈ ∆</sub>)D<sub>α</sub> = ∪<sub>α ∈ ∆</sub>(f(D<sub>α</sub>))
Proof:
    [⊆]
    Let w ∈ f(∪<sub>α ∈ ∆</sub>)D<sub>α</sub>.
    So, ∃(z) ∈ ∪<sub>α ∈ ∆</sub> such that f(z) = w,
    and ∃(α) such that w ∈ f(D<sub>α</sub>).
    Therefore, w ∈ ∪<sub>α ∈ ∆</sub>(f(D<sub>α</sub>))
    [⊇]
    _Similar_
□
