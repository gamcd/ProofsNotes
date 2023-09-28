⇒
⇔
π

## Def 1.30:
### The _conditional sentance_ denoted P ⇒ Q, has truth table
| P | Q | P ⇒ Q |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |
|---|---|-------|

## Exercise 1.30:
1. "If CP is on Quarters, then this room is 38-226": True
2. "If 2^2 = 4, then cal poly is on Quarters": True
3. "If 2^2 = 5, then cal poly is on Quarters": True
4. "If 2^2 = 5, then cal poly is on Semester": True
5. "If 2^2 = 4, then cal poly is on Semester": False

## Def 1.32
### Given conditional sentance P ⇒ Q, P is called the _antecedant_, Q is called the _consequent_
Here,
| P | Q | P ⇒ Q | ~P | Q v ~P |
|---|---|-------|----|--------|
| T | T | T | F | T |
| T | F | F | F | F |
| F | T | T | T | T |
| F | F | T | T | T |

## Def 1.37
### Given the conditional sentance P ⇒ Q, the _converse_ is Q ⇒ P
| P | Q | Q ⇒ P |
|---|---|-------|
| T | T | T |
| T | F | T |
| F | T | F |
| F | F | T |

## Def 1.38
### Given the conditional sentance P ⇒ Q, the _contrapositive_ is ~Q ⇒ ~P)
| P | Q | ~Q ⇒ ~P | P ⇒ Q |
|---|---|---------|-------|
| T | T | T | T |
| T | F | F | F |
| F | T | T | T |
| F | F | T | T |
 - So, P ⇒ Q is equal to the contrapositive, ~Q ⇒ ~P


## Exercise 1.39
### Determine which of the converse and/or contrapositive is logically equivalent to the conditional sentence P ⇒ Q and justify your conclusions with truth tables.
| P | Q | ~Q ⇒ ~P | P ⇒ Q | Q ⇒ P |
|---|---|---------|-------|-------|
| T | T | T | T | T |
| T | F | F | F | T |
| F | T | T | T | F |
| F | F | T | T | T |
 - So, P ⇒ Q is equal to the contrapositive because they have the same truth table values, ~Q ⇒ ~P

## Exercise 1.40  
### Write the converse and contrapositive of the conditional sentence “If f is an even function, then f (2) = f (−2).” When the implication between propositions P and Q “runs both ways”, we have a much stronger logical relationship.``
Contrapositive: "If f(2) != f(-2) then f is an odd function"
Converse:       "If f(2) = f(-2) then f is an even function"

## Definition 1.41
### Let P and Q represent propositions. The _biconditional_ sentence “P if and only if Q” is expressed symbolically P ⇔ Q and has truth table
| P | Q | Q ⇔ P |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | T |

## Exercise 1.42
### Use truth tables to show that P ⇔ Q is logically equivalent to (P ⇒ Q) ∧ (Q ⇒ P).
| P | Q | (P ⇒ Q) | (Q ⇒ P) | (Q ⇒ P) ∧ (P ⇒ Q) | (P ⇔ Q) |
|---|---|---------|---------|-------------------|---------|
| T | T | T | T | T | T |
| T | F | F | T | F | F |
| F | T | T | F | F | F |
| F | F | T | T | T | T |

## Exercise 1.43
### Determine the truth value for each of the following biconditional sentences.
1. The moon is made of cheese if and only if the earth is flat.
    - True
2. 1 + 1 = 2 if and only if cos(π) = −1.
    - True
3. “If 5 < 2, then 10 < 7.” if and only if “Elvis lives.” is a proposition.
    - False, the biconditional will always disagree resulting in False
