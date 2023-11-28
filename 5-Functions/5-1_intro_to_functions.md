## Definition 5.1
### Let f be a relation from A to B. We call f a _function_ from A to B and write f : A → B if f has the following two properties:
1. Dom(f) = A.
2. [(x, y) ∈ f ∧ (x, z) ∈ f] ⇒ y = z.
The set B is called the codomain of the function.

## Proposition 5.10
### Let A be a set. The identity relation I<sub>A</sub> is a function from A to A.
Proof:
    Consider I<sub>A</sub>.
    1. Note that by definition, Dom(I<sub>A</sub>) = A.
    2. Suppose (x, y) ∈ f ∧ (x, z) ∈ f.
        For an Identity relation, any x ∈ A corresponds to an (x, x) ∈ I<sub>A</sub>.
        Thus, y = x and z = x, and by transativity, y = z.
□

## Exercise 5.12
### Let U be some universe and A ⊆ U . Let χ<sub>A</sub> : U → {0, 1} be the function
χ<sub>[1, 3)</sub> = 1 if x ∈ [1, 3) else 0

The function χ<sub>A</sub> is called the characteristic function of the set A
1. Give a representation of this function f as a mapping diagram.
2. If U = R and A = (1, 3], give a representation of χ<sub>A</sub> by drawing its graph in the
xy-plane.

## Theorem 5.13
### Two functions f and g are equal if and only if
1. Dom(f) = Dom(g), and
2. For each x ∈ Dom(f), f(x) = g(x).
