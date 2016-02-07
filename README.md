# dismathportfolio-laurengonzaga
dismathportfolio-laurengonzaga created by Classroom for GitHub

#Week 1
✓ Introduction to **DISMATH** and some of its applications

        - Proofs and Logical Analysis
          e.g. Knights and Knaves
 
✓ **Proposition**

        - a statement that is either true or false
          e.g. "Today is Tuesday."
 
✓ **Logical Operations**

| Logical Symbol  |  Logical Operator | Shorthand | Logical Expression |
| :-----: |:-------:|:-----:| :-------: |
| ¬ |Negation | not | ¬p |
| ∧ | Conjunction | and | p ∧ q |
| v | Disjunction | or | p v q |
| ⊕ | Exclusive Disjunction | xor |  p ⊕ q |
| → | Conditional | if, then | p → q |
| ↔ | Biconditional | iff | p ↔ q |
  
  
✓ Truth table for **Conjunction**, **Disjunction**, **Exclusive Disjunction**, **Conditional**, and **Biconditional**
  
| p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |
| :-----: | :-----: | :-----: |:-------:|:-----:| :-------: | :-------:|
| F | F | F | F | F | T | T |
| F | T | F | T | T | T | F |
| T | F | F | T | T | F | F |
| T | T | T | T | F | T | T |


✓ **Propositional Logic** (p → q)
  
       - the area of logic that deals with propositions
  
✓ **Implication Equivalence**

       p → q ≡ ¬p ∨ q
  
|  | Logical Expression  |  |
| :-----: | :-------: | :-------: |
| Inverse | ¬p → ¬q | if not p, then q |
| Converse | q → p | if q, then p |
| Contrapositive | ¬q → ¬p | if not q, then not p |


#Week 2
✓ **Logical Equivalences**

| Equivalence | Name |
| :---------: | :--: |
| p ∧ <b>T</b> ≡ p <p>p ∨ <b>F</b> ≡ p</p> | Identity Laws |
| p ∨ <b>T</b> ≡ <b>T</b> <p>p ∧ <b>F</b> ≡ <b>F</b> | Domination Laws |
| p ∨ p ≡ p <p>p ∧ p ≡ p | Idempotent Laws |
| ¬(¬p) ≡ p | Double Negation Law |
| p ∨ q ≡ q ∨ p <p>p ∧ q ≡ q ∧ p</p> | Commutative Laws |
| (p ∨ q) ∨ r ≡ q ∨ (p ∨ r) <p>(p ∧ q) ∧ r ≡ q ∧ (p ∧ r)</p> | Associative Laws |
| p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (q ∨ r) <p> p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (q ∧ r)</p> | Distributive Laws |
| ¬(p ∧ q) ≡ ¬p ∨ ¬q <p>¬(p ∨ q) ≡ ¬p ∧ ¬q</p> | De Morgan's Law |
| p ∨ (p ∧ q) ≡ p <p>p ∧ (p ∨ q) ≡ p</p> | Absorption Laws |
| p ∨ ¬p ≡ <b>T</b> <p>p ∧ ¬p ≡ <b>F</b> | Negation Laws |


✓ **Quantifiers**

| Existential Quantifier  | Symbol  |
| :-----: | :-------: | :-------: |
| "there exist" | ∃(x) |

| Universal Quantifier  | Symbol  |
| :-----: | :-------: | :-------: |
| "for all" | ∀(x) |


✓ **Rules of Interference**

        - used to test the validity of arguments


|          Name              |            Equivalent          | Tautology |
|:--------------------------:|:------------------------------:|:------------------------------:|
|       Modus ponens         |            p, p→q ∴ q          | (p ∧ (p → q)) → q |
|     Modus tollens          |           ¬q, p→q ∴ ¬p         | (¬q ∧ (p → q)) → ¬p |
|     Hypothetical syllogism |       p → q, q → r ∴ p → r     | ((p → q) ∧ (q → r)) → (p → r) |
|      Disjunctive syllogism |           p ∨ q, ¬p ∴ q        | ((p ∨ q) ∧ ¬p) → q |
|       Addition             |            p ∴ p ∨ q           | p → (p ∨ q) |
|      Simplication          |            p ∧ q ∴ p           | (p ∨ q) → p |
|      Conjunction           |          p, q ∴ p ∧ q          | ((p) ∨ (q)) → (p ∨ q) |
|        Resolution          |       p ∨ q, ¬p ∨ r ∴ q ∨ r    | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |


**Argument**

        - a sequence of statements that end with a conclusion

**Valid**

        - the conclusion, or final statement of the argument, must follow from the truth of the preceding
          statements, or premises of the argument

**Fallacy**

        - common form of incorrect reasoning which lead to invalid arguments
