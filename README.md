# dismathportfolio-laurengonzaga
dismathportfolio-laurengonzaga created by Classroom for GitHub

#Week 1
✓ Introduction to **DISMATH** and some of its applications

        - Proofs and Logical Analysis
          e.g. Knights and Knaves
 
✓ **Mathematical Proof**

        - a chain of logical deductions leading to the proposition from a base set of axioms

**Proposition**

        - a statement that is either true or false
          e.g. "Today is Tuesday."

**Logical Deduction**

        - a process of reasoning from one or more statements (premises)
          to reach a logically certain conclusion

**Axiom**

        - a statement or proposition that is regarded as being established, accepted, or self-evidently true

✓ **Logical Operations**

| Logical Symbol  |  Logical Operator | Shorthand | Logical Expression |
| :-----: | :-------: | :-----: | :-------: |
| ¬ | Negation | not | ¬p |
| ∧ | Conjunction | and | p ∧ q |
| v | Disjunction | or | p v q |
| ⊕ | Exclusive Disjunction | xor |  p ⊕ q |
| → | Conditional | if, then | p → q |
| ↔ | Biconditional | iff | p ↔ q |
  
  
✓ Truth table for **Conjunction**, **Disjunction**, **Exclusive Disjunction**, **Conditional**, and **Biconditional**
  
| p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |
| :-----: | :-----: | :-----: | :-------: | :-----: | :-------: | :-------:|
| F | F | F | F | F | T | T |
| F | T | F | T | T | T | F |
| T | F | F | T | T | F | F |
| T | T | T | T | F | T | T |


✓ **Propositional Logic** (p → q)
  
       - the area of logic that deals with propositions
  
✓ **Implication Equivalence**

       p → q ≡ ¬p ∨ q
 
**Inverse**

       ¬p → ¬q
**Converse**

       q → p
**Contrapositive**

       ¬q → ¬p


#Week 2
✓ **Logical Equivalences**

| Equivalence | Name |
| :---------: | :--: |
| p ∧ <b>T</b> ≡ p <br>p ∨ <b>F</b> ≡ p | Identity Laws |
| p ∨ <b>T</b> ≡ <b>T</b> <br>p ∧ <b>F</b> ≡ <b>F</b> | Domination Laws |
| p ∨ p ≡ p <br>p ∧ p ≡ p | Idempotent Laws |
| ¬(¬p) ≡ p | Double Negation Law |
| p ∨ q ≡ q ∨ p <br>p ∧ q ≡ q ∧ p | Commutative Laws |
| (p ∨ q) ∨ r ≡ q ∨ (p ∨ r) <br>(p ∧ q) ∧ r ≡ q ∧ (p ∧ r) | Associative Laws |
| p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (q ∨ r) <br>p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (q ∧ r) | Distributive Laws |
| ¬(p ∧ q) ≡ ¬p ∨ ¬q <br>¬(p ∨ q) ≡ ¬p ∧ ¬q | De Morgan's Law |
| p ∨ (p ∧ q) ≡ p <br>p ∧ (p ∨ q) ≡ p | Absorption Laws |
| p ∨ ¬p ≡ <b>T</b> <br>p ∧ ¬p ≡ <b>F</b> | Negation Laws |


✓ **Quantifiers**

| Existential Quantifier  | Symbol  |
| :-----: | :-------: | :-------: |
| "there exist" | ∃(x) |

| Universal Quantifier  | Symbol  |
| :-----: | :-------: | :-------: |
| "for all" | ∀(x) |


#Week 3

✓ **Rules of Inference**

        - used to test the validity of arguments


| Name | Equivalent | Tautology |
|:-----------:|:-------------:|:-----------:|
| Modus ponens | p, p→q ∴ q | (p ∧ (p → q)) → q |
| Modus tollens | ¬q, p→q ∴ ¬p | (¬q ∧ (p → q)) → ¬p |
| Hypothetical syllogism | p → q, q → r ∴ p → r | ((p → q) ∧ (q → r)) → (p → r) |
| Disjunctive syllogism | p ∨ q, ¬p ∴ q | ((p ∨ q) ∧ ¬p) → q |
| Addition | p ∴ p ∨ q | p → (p ∨ q) |
| Simplication | p ∧ q ∴ p | (p ∨ q) → p |
| Conjunction | p, q ∴ p ∧ q | ((p) ∨ (q)) → (p ∨ q) |
| Resolution | p ∨ q, ¬p ∨ r ∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |


**Argument**

        - a sequence of statements that end with a conclusion

**Valid**

        - the conclusion, or final statement of the argument, must follow from the truth of the preceding
          statements, or premises of the argument

**Fallacy**

        - common form of incorrect reasoning which lead to invalid arguments
        
**Tautology**

        - a statement that is always true


#Week 4

✓ **Mathematical Proofs**

| Method of Proof | | Steps |
|:-----: | :-------: | :-------: | 
| Direct Proof | (p → q) | 1. Assume p is true <br>2. Show that q is also true (based on 1) |
| Proof by Contraposition | (¬q → ¬p) | 1. Assume ¬q is true <br>2. Show that ¬p is also true (based on 1) |
| Vacuous Proof | (¬p → (p → q)) | Show that p is false, <p>because (p → q) must be true when p is false |
| Trivial Proof | (q → (p → q)) | Show that q is true, <br>it follows that (p → q) must also be true |
| Proof by Contradiction | | 1. Assume ¬P is true <br>2. Show that 1. ends up in a contradiction |


#Week 5

✓ **Mathematical Proofs**

| Method of Proof | | Steps |
|:-----: | :-------: | :-------: | 
| Proof by Equivalence | (p ↔ q) | Show that (p → q) and (q → p) are both true |
| Mathematical Induction | | 1. Basis Step (Substitution) <br>2. Inductive Step |


