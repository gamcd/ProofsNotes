## Def 1.15:
### A _proposition_ is a statement that is either true or false
    - EX:
        1. Dr. Retsek had eggs for breakfast on the morning of his tenth birthday   - Proposition
        2. Elvis Lives                                                              - Proposition
        3. What time is it?                                                         - Not a Proposition
        4. x^2 = 4                                                                  - Needs more to be a proposition

## Def 1.18:
### Let P and Q be propositions. The _conjunction_ of P, Q denoted P ^ Q, is a new proposition that is true preciseley when P, Q are  both true

## Def 1.19:
### Let P and Q be propositions. The _disjunction_ of P, Q denoted P v Q, is a new proposition that is true when at least one of P, Q is true

## Def 1.20:
### Let P be a proposition. The _negation_ of P denoted ~P, is true precisely when P is false and vice versa

## Exercise 1.21:
    - let P be "All stable lists are tight"             False
    - let Q be "Cal Poly is on semesters"               False
    - let R be "Betsy Ross was the first US president"  False
    - ~(P v (~Q))
        - False
    - (~(~(~P))) ^ (~R)
        - True
    - ((~R) v Q) ^ (P v (~Q))
        - True

## Exercise 1.24
### Create a definition for what it means for two propositional forms to be equivalent.
    - Two propositional forms can be called equivalent if they have the same representation in the truth tables (I.E. same outputs for same inputs)

## Exercise 1.25
### Conjecture a propositional form equivalent to ∼ (P ∨ Q) and use truth tables to verify your conjecture. The preceding exercises indicate that the negation operation ∼ “distributes” across parentheses in a regular and intuitive way. This is an important part of writing useful and stylistic “denials”.
~(P v Q) = (~P) ^ (~Q)
| P | Q | ~(P v Q) | (~P) ^ (~Q) |
|---|---|----------|-------------|
| T | T | F        | F           |
| T | F | F        | F           |
| F | T | F        | F           |
| F | F | T        | T           |

## Definition 1.26
### A _denial_ of a proposition P is any proposition with the sametruth value as ∼P .

## Exercise 1.27
### Write a denial of the proposition “Cal Poly is on semesters.”
    - "Cal Poly is not on semesters."

## Exercise 1.28
### Write a denial of the proposition “The window is open and the pie is missing.”
    -  “The window is closed and the pie is not missing.”

## Exercise 1.29
### Write a denial of the proposition “The function f(x) is unbounded or constant.”
    - “The function f(x) is not unbounded or constant."
