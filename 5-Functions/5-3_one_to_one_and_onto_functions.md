# 5.3 One to One & Onto functions

## Definition 5.21
### Let f : A → B. The function f is called _one-to-one_ (1-1) if [(x, y) ∈ f ∧ (z, y) ∈ f] ⇒ x = z.

### Training wheels monologue

## Proposition 5.26
### If f : A → B and g : B → C are both 1-1, then g ◦ f : A → C is 1-1.
Proof:
    Suppose f : A → B and g : B → C are both 1-1.
    to show g ∘ f : A → C is 1-1, suppose (g ∘ f)(x) = (g ∘ f)(z), or g(f(x)) = g(f(z)).
    Since g is (1-1), f(x) = f(z), and because f is (1-1), x = z.
    So, showing that x = z, (g ∘ f) is also (1-1)
□

## Proposition 5.27
### If g ◦ f : A → C is 1-1, f : A → B and g : B → C, then g : B → C is 1-1.
Proof:
    Suppose g ∘ f : A → C, f : A → B. and g : B → C
    is 1-1 and let b₁, b₂ ∈ B such that g(b₁) = g(b₂).
    Since f : A → B, there exist a₁, a₂ ∈ A such that f(a₁) = b₁ and f(a₂) = b₂.
    Since g ∘ f : A → C, (g ∘ f)(a₁) = (g ∘ f)(a₂), or g(f(a₁)) = g(f(a₂)).
    Since g is (1-1), f(a₁) = f(a₂), and because f is (1-1), a₁ = a₂.
    So, showing that a₁ = a₂, g is also (1-1)
□

## Proposition 5.28
### If g ◦ f : A → C is 1-1, f : A → B and g : B → C, then f : A → B is 1-1.

Given f : A → B, we can now characterize exactly when the inverse relation f⁻¹ is itself a function.

## Definition 5.31
### Let f : A → B. The function f is called _onto_ if Ran(f) = B. Onto functions are also called surjections. Ran(f) = CoDom(f)
