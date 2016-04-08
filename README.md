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
| Vacuous Proof | (¬p → (p → q)) | Show that p is false, <br>because (p → q) must be true when p is false |
| Trivial Proof | (q → (p → q)) | Show that q is true, <br>it follows that (p → q) must also be true |
| Proof by Contradiction | | 1. Assume ¬P is true <br>2. Show that 1. ends up in a contradiction |


#Week 5

✓ **Mathematical Proofs**

| Method of Proof | | Steps |
|:-----: | :-------: | :-------: | 
| Proof by Equivalence | (p ↔ q) | Show that (p → q) and (q → p) are both true |
| Mathematical Induction | | 1. Basis Step (Substitution) <br>2. Inductive Step |

#Week 6

✓ **Cardinality**

        - the total number of distinct elements
    
        (ℵ₀) pronounced as “aleph-zero"/“alephnought”/“aleph-null”
  
✓ Nested Quantifiers

        2 quantifiers are nested if one is within the sccope of the other
        Examples:
      
         ∀x∀y(x≠y) 
          
         ∃x∃y(x≠y)
          
         ∀x∃y(x≠y)
          
         ∃y∀x(x≠y)
  
✓ **Functions**

**One-to-one Function**
       
          - each domain is assigned to a certain co-domain
          - no common co-domain
       
**Onto Function**
       
         - each co-domain is assigned to a domain
         - no co-domain is left without a partner

#Week 7

No Classes

#Week 8

✓ **Algorithm**

    - is a finite set of precise instruction
    
**Precondition**
    
           - describes the input
    
**Postcondition**
    
           - describes what the output should satisfy
    
**Properties**
      
           • Input
           • Output
           • Definiteness
           • Correctness
           • Finiteness
           • Generality
    
✓ **Psuedocode**

        - a high level description of an algorithm that uses the structural conventions of programming knowledge

#Week 9

✓ **Seaching Algorithm**

        - The problem of locating an element in an ordered list

✓ **Linear Search**

        Precondition: ({A1,A2,...,Ai,...An})
        Postcondition: location of x (loc)
      
      i=1
      while [(x≠A)^(i≤n)]
          i = i+1
        if(i≤n)
          loc = i
        else
           loc = -1

✓ **Binary Search**

        Precondition: ({A1,A2,...,Ai,...An})
        Postcondition: location of x (loc)
    
          while [(i≠j) ≠ (i>j)]
             mid = [(i+j)/2]
                if x>A(mid) 
                   then i = 1+mid
                else j=mid
                if (x==Ai)
                    loc=i
                else 
                   loc = -1
    
#Week 10

✓ **Sorting Algorithm**

        - the problem of putting elements in increasing order

✓ **Bubble sort**

        Precondition: ({A1,A2,...,Ai,...An})
        Postcondition: (X1<X2<...<Xn)
      
          for j: 1 to n-1
             for i: 1 to n-j
                if(Ai > Aj+1)
                   swap (Ai,Ai+1)

✓ **Insertion sort**

        Precondition: ({A1,A2,...,Ai,...An}) ∈ n≥2 for j= 2 to n
        Postcondition: (X1<X2<...<Xn)
      
          for j = 2 to n
              i = 1
          while Aj>Ai
              i = i+1
           m = Aj
           for k = 0 to j-i-1
            Aj-k = Aj-i-1
            Ai = m

✓ **Greedy Algorithm**

        - selects the best choice instead of considering all sequences
        - applied in optimization problems

        Precondition: ({C1,C2,...,Ci,...Cn})
        Postcondition: (C1>C2>...>Cni n ∈ Z+) 
      
          for i = 1 to 4 
            while(n≥Ci)
                n = n-Ci
                n = n+1

#Week 11

✓ **Growth of Functions**

        - is often described using the big o notation

**Big O Notation**

        - upper bound of a function

        - Let f and g be functions from R to Ri f(x) is O(g(x)) if there are constants c and k such that 
          |f(x)|≤ C|g(x)| whenever x>k

**Big Omega**

        - lower bound of a function
    
**Big Theta**

        - lower and upper bound of a function
   
✓ **Complexity of Algorithms**

        - can be expressed in terms of the number of operationsused by the algorithm when the input 
          has a particular size

#Week 12

No Classes

#Week 13

✓ **Graph Theory**

        - consist of vertices (nodes) and degrees (edges)

✓ **Handshaking Theorem**

        2e = Σ(degrees)*v
    
✓ **Euler Circuit**

        - passes through all the edges
        - is closed 
        - has the same starting and ending point
        
✓ **Euler Path**

        - passes through all the edges
        - can be open 
        - can have a different starting and ending point

✓ **Hamilton Circuit**

        - passes through all the vertices
        - is closed 
        - has the same starting and ending point
    
✓ **Hamilton Path**

        - passes through all the vertices
        - can be open 
        - can have a different starting and ending point
    
✓ **Matrices**

**Adjacency Matrix**

        - relationship between the vertices
        - relationship between the edges

✓ **Isomorphism**

        - a comparison of 2 graphs

✓ **Planar**

        - a plane that has no intersecting edges

✓ **Non-Planar**

        - a plane that has intersecting lines/edges/degrees

✓ **Euler's Formula**

        r = e(edges) - v(vertices) + 2

#Week 14

✓ **Graph Coloring**

        - the assignment of colors to each node in a graph considering the adajaceny relationship between them.
    
Chromatic Number
    
        - the least number of colors needed in coloring a graph
       
Four color Theorem
     
        - states that the chomatic number of a planar graph should not be grater than 4

✓ **Trees**

        - is simply an undirected graph
     
        - it has no circuit in it
  
Rooted tree
     
        - a tree by which a node is assigned as the root and has edges that is directed away from it
        
Subtree
       
        - is a branch-like part of the main tree 

✓ **Language and Grammar**

        - Grammar generates words and identifies whether a word is from a certain language
        - Java C language is not that vital in the formal language

✓ **SYNTAX** 

        - the form of a formal language
        - a derivation tree may be used to check validity of the grammar

✓ **Automata theory** 

        - studies the laws of computation

✓ **Finite Automation** 
        
        - the  simplest model of computing device, based on the concept of states
          initial state
          final state
          dead/stuck state
          transition state
        
✓ **Lexical analysis** 

        - the process where the stream of characters making up the source program is read
          from left to right and grouped into tokens

✓ **Finite State Machine**

        M = {S, I, O, f, g, s(0)} with S-states
      
        SYMBOLS:
          I-input 
          O-output 
          f-function 
          g-function output  
          s(0)-initial state

#Additional Readings

✓ **Tree**

Tree Traversal 

        - is to visit every vertex of an ordered rooted tree

Spanning tree

        - subgraph of simple graph G that is a tree containing every vertex of G
    
Minimum spanning tree 
      
        - spanning tree that has the smallest possible sum of weights of its edges

✓ **Relations**

        - relationship of elements between two sets
    
Binary relation 

        - realation is from set A to set B and is a subset of A x B
      
Reflexive relation 
      
        - if (a,a) is an element of R (relation) for every element a in set A
      
Symmetric relation 
      
        - if (b,a) is an element of R whenever (a,b) is an element of R, for all a,b in set A; 
          antisymmetric - if a = b
        
Transitive relation
      
        - whenever (a,b) and (b,c) are elements of R, then (a.c) is an element of R; a,b,c are in set A
      
Equivalence relation 
        
        - a relation that is reflexive, symmetric and transitive
      
Equivalencee class (a) 
        
        - set of all elements that are related to an element a of A
        
N-ary relation 
      
        - the relationship of elements from two or more sets; A1 x A2 x An, where A-domains and n-degree
      
✓ **Composite (S o R)**

        - (a,b) and (b,c) such that (a,c), from sets A, B, C

✓ **Partial ordering**

        - a reflective, antisymmetric and transitive relation on a set S

✓ **Lexicographic order**

        - based in the ordering of the letters in the alphabet

✓ **Lattices**

        - a partially unordered set in which every pair of elements has both a least upper bound and a greatest lower bound

