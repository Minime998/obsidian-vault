#dis-math 
# Propositional Equivalences
## Section 1.3
[[applications-of-propositional-logic|Section 1.2]]
[[propositional-logic|Section 1.1]]

### Summary
[[#Tautologies Contradictions and Contingencies]]

[[#Logically Equivalent]]
- [[#Key Logical Equivalences]]
	- [[#More Logical Equivalences]]
	- [[#Constructing new Logical Equivalences]]
- [[#Equivalence Proofs]]

#### Tautologies, Contradictions, and Contingencies

A *tautology* is a proposition which is always true.
* Example: *p* $\vee$ $\neg$*p*

A *contradiction* is a proposition which is always false.
* Example: *p* $\wedge$ $\neg$*p*

A *contingency* is a proposition which is neither a tautology nor a contradiction, such as *p*

![[CaptureDis_TCCChart.png]]

#### Logically Equivalent

Two compound propositions *p* and *q* are logically equivalent if *q* $\leftrightarrow$ *q* is a tautology

We write this as *p* $\leftrightarrow$ *q* or as p $\equiv$ *q* where *p* and *q* are compound propositions.

Two compound propositions *p* and *q* are equivalent if and only if the columns in a truth table giving their truth values agree.

This truth tale shows that $\neg$*p* $\vee$ *q* is equivalent to *p* $\rightarrow$ *q*

![[CaptureDis_LogicallyEquivalentTable.png]]

##### Key Logical Equivalences

Identity Laws: *p* $\wedge$ *T* $\equiv$ *p* | *p* $\vee$ *F* $\equiv$ *p*

Domination Laws: *p* $\vee$ *T* $\equiv$ *T* | *p* $\wedge$ *F* $\equiv$ *F*

Idempotent Laws: *p* $\vee$ *p* $\equiv$ *p* | *p* $\wedge$ *p* $\equiv$ *p*

Double Negation Laws: $\neg$($\neg$*p*) $\equiv$ *p*

Negation Laws: *p* $\vee$ $\neg$*p* $\equiv$ *T* | *p* $\wedge$ $\neg$*p* $\equiv$ *F*

Commutative Laws: *p* $\vee$ *q* $\equiv$ *q* $\vee$ *p* | *p* $\wedge$ *q* $\equiv$ *q* $\wedge$ *p*

Associative Laws: 
(*p* $\wedge$ *q*) $\wedge$ *r* $\equiv$ *p* $\wedge$ (*q* $\wedge$ *r*)
(*p* $\vee$ *q*) $\vee$ *r* $\equiv$ *p* $\vee$ (*q* $\vee$ *r*)

Distributive Laws:
(*p* $\vee$ (*q* $\wedge$ *r*)) $\equiv$ (*p* $\vee$ *q*) $\wedge$ (*p* $\vee$ *r*)
(*p* $\wedge$ (*q* $\vee$ *r*)) $\equiv$ (*p* $\wedge$ *q*) $\vee$ (*p* $\wedge$ *r*)

Absorption Laws:
*p* $\vee$ (*p* $\wedge$ *q*) $\equiv$ *p* | *p* $\wedge$ (*p* $\vee$ *q*) $\equiv$ *p*

###### More Logical Equivalences

![[CaptureDis_Table7.png]]

![[CaptureDis_Table8.png]]

###### Constructing new Logical Equivalences

We can show that two expressions are logically equivalent by developing a series of logically equivalent statements.

To prove that *A* $\equiv$ *B* we produce a series of equivalences beginning with *A* and ending with *B*

![[CaptureDis_Series.png]]

Keep in mind that whenever a proposition (represented by a propositional variable) occurs in the equivalences listed earlier, it may be replaced by an arbitrarily complex compound proposition 

#### Equivalence Proofs

![[CaptureDis_EquivProof1.png]]

![[CaptureDis_EquivProof2.png]]

#### Propositional Satisfiability

A compound proposition is *satisfiable* if there is an assignment of truth values to its variables that make it true. When no such assignments exist, the compound proposition is *unsatisfiable*.

A compound proposition is unsatisfiable if and only if its negation is a tautology

##### Questions on Propositional Satisfiability

__Example__: Determine the Satisfiability of the following compound propositions:

(*p* $\vee$ $\neg$*q*) $\wedge$ (*q* $\vee$ $\neg$*r*) $\wedge$ (*r* $\vee$ $\neg$*p*)

__Solution__: assign T to all variables 






