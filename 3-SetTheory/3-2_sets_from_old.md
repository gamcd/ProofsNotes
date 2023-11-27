# 3.2 New Sets from Old

## Definition 3.19
### Let A and B be sets with elements from some universe U .
1. The _union_ of A and B is the set
A ∪ B = {x ∈ U : x ∈ A ∨ x ∈ B}.
2. The _intersection_ of A and B is the set
A ∩ B = {x ∈ U : x ∈ A ∧ x ∈ B}.
When A ∩ B = ∅, we say that A and B are _disjoint_.
3. The difference A \ B is the set
A \ B = {x ∈ U : x ∈ A ∧ x ∉ B}.

## Proposition 3.23
### Let A, B and C be sets. If A ⊆ B, then A \ C ⊆ B \ C.
Proof:
Let A, B and C be sets.
Suppose A ⊆ B such that [x ∈ A ⇒ x ∈ B] for some arbitrary element x;
Suppose x ∈ A \ C.
Then x ∈ A ∧ x ∉ C.
Because A ⊆ B and x ∉ C, x ∈ B and x ∉ C.

## Proposition 3.24
### Let A, B, C and D be sets. If A∪B ⊆ C∪D, A∩B = ∅, and C ⊆ A, then B ⊆ D.
Proof:
Suppose A∪B ⊆ C∪D, A∩B = ∅, and C ⊆ A.
In that way, 
Let x ∈ B.
because [x ∈ A∪B ⇒ x ∈ C∪D],
x ∈ C∪D.
if x ∈ C, because C ⊆ A, x ∈ A;
This is impossible however,
because A ∩ B = ø,
so x ∉ A, so x ∉ C.
Because x ∈ C∪D and x ∉ C, x ∈ D.
Therefore, [x ∈ B ⇒ x ∈ D], and B ⊆ D.
□


## Kerry's Theorem
### Let A and B be sets. then A ∪ B = A if and only if B ⊆ A.
Proof:
1. [A ∪ B = A ⇒ B ⊆ A]
    Suppose A ∪ B = A
        Let x ∈ A
        ...
        Therefore,  x ∈ B
    Therefore, B ⊆ A
2. [B ⊆ A ⇒ A ∪ B = A]
    Suppose B ⊆ A
        1. [x ∈ A ∪ B ⇒ x ∈ A]
            let x ∈ A ∪ B 
                ...
            Therefore, x ∈ A
        2. [x ∈ A ⇒ x ∈ A ∪ B]
            let x ∈ A
                ...
            Therefore, x ∈ A ∪ B
    Therefore, A ∪ B = A
□

## Proposition 3.25
### If A, B and C are sets, then A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C).
Proof:
1. [x ∈ A ∩ (B ∪ C) ⇒ x ∈ (A ∩ B) ∪ (A ∩ C)]
    let x ∈ A ∩ (B ∪ C) such that x ∈ A and x ∈ (B ∪ C).
    It stands to reason that x is either a member of B or C.
    In the case that x ∈ B:
        x ∈ (A ∩ B), so x ∈ (A ∩ B) ∪ (A ∩ C)
    In the case that x ∈ C:
        x ∈ (A ∩ C), so x ∈ (A ∩ B) ∪ (A ∩ C)
    in either either case, x ∈ (A ∩ B) ∪ (A ∩ C).
2. [x ∈ (A ∩ B) ∪ (A ∩ C) ⇒ x ∈ A ∩ (B ∪ C)]
    let x ∈ (A ∩ B) ∪ (A ∩ C).
    It stands to reason that x is either a member of (A ∩ B) or (A ∩ C)
    in the case that x ∈ (A ∩ B) such that x ∈ A and x ∈ B:
        x ∈ B, so x ∈ (B ∪ C).
        x ∈ A, so x ∈ A ∩ (B ∪ C)
    in the case that x ∈ (A ∩ C) such that x ∈ A and x ∈ C:
        x ∈ B, so x ∈ (B ∪ C).
        x ∈ A, so x ∈ A ∩ (B ∪ C)
    in either case, x ∈ A, so x ∈ A ∩ (B ∪ C)
□


## Definition 3.26
### Let A be a set with elements in some universe U. The _complement_ of A is the set A~ given by A~ = U \ A

## Exercise 3.28
### Let the universe be the real numbers ℝ.
Proof:
1. Determine the complement of (2, ∞).
    (-∞, 2]
2. Determine the complement of [1, 3).
    (-∞, 1) ∪ [3, ∞)
3. Determine ∅.
    ø = {n ∈ ℝ : n ∈ (n, n)} = U~
□

## Proposition 3.29
### For any set A in any universe U , A~~ = A. (A~~ is double compliment)
Proof:
1. [ x ∈ A~~ ⇒ x ∈ A ]
    if x ∈ A~~ then x ∉ A~, so x must be a member of A.
    therefore, x ∈ A.
2. [ x ∈ A ⇒ x ∈ A~~ ]
□


## Proposition 3.30
### Let A and B be sets in some universe. If A ⊆ B, then B~ ⊆ A~.
Proof:
Suppose A ⊆ B.
Let x ∈ A~ such that x ∉ A.
Since A ⊆ B, x ∉ A.
Thus, x ∈ A~.
Therefore, B~ ⊆ A~.
□

## Theorem 3.31 (DeMorgan’s Laws : Initial Version)
### Let A and B be sets in some universe.

Proof:
1. (A ∪ B)~ = A~ ∩ B~
    1. [x ∈ (A ∪ B)~ ⇒ x ∈ A~ ∩ B~]
        let x ∈ (A ∪ B)~, so x ∉ A and x ∉ B,
        which means x ∈ A~ and x ∈ B~.
        So  x ∈ A~ ∩ B~
    2. [x ∈ A~ ∩ B~ ⇒ x ∈ (A ∪ B)~]
        let x ∈ A~ ∩ B~, so x ∉ A and x ∉ B,
        which means x ∉ (A ∪ B).
        So  x ∈ (A ∪ B)~
    Therefore, (A ∪ B)~ = A~ ∩ B~
□

Proof:
2. (A ∩ B)~ = A~ ∪ B~
    1. [x ∈ (A ∩ B)~ ⇒ x ∈ A~ ∪ B~]
        let x ∈ (A ∩ B)
        ...
    2. [x ∈ A~ ∪ B~ ⇒ x ∈ (A ∩ B)~]
        let x ∈ A~ ∪ B
        ...
    Therefore, (A ∩ B)~ = A~ ∪ B~
□

Stopping point for the midterm
