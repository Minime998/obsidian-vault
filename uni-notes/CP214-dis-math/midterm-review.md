#dis-math 

# Midterm review
Summary:
- Week 1:
	- [[#Proposition]]
		- [[#Proposition Logic]]
	- [[#Converse Contrapositive and Inverse]]
	- [[#Equivalent Propositions]]
	- [[#Consistent System Specifications]]
	- [[#Tautologies Contradictions and Contingencies]]
	- [[#Logically Equivalent]]
	- [[#De Morgan's Laws]]
	- [[#Equivalence Proofs]]
	- [[#Propositional Satisfiability]]
	- [[#Predicate Logic]]
		- [[#Propositional functions]]
		- 

## Chapter 1

### Proposition
- A *proposition* is a declarative sentence that is either true or false
>Examples:
>a) The Moon is made of green cheese
>b) Toronto is the capital of Canada
>c) Blue jays always win
>
>Examples that are not:
>a) Sit down!

#### Proposition Logic
- In propositional logic **Propositional variables** like *p*,*q*,*r*,*s* are used to represent a proposition
- Any proposition can be either *T* or *F*
- A more advanced form of logic is **Compound Propositions** which are constructed from combining propositions using symbols like:
	- **Negation** $\neg$
	- **Conjunction** $\wedge$
	- **Disjunction** $\vee$
	- **Implication** $\rightarrow$
	- **Biconditional** $\leftrightarrow$
	
### Converse, Contrapositive, and Inverse
>Example: Find the converse, inverse, and contrapositive of "It raining is a sufficient condition for my not going to town."

Solution:
- **converse**: If I do not go to town, then it is raining. *(flipped)*
- **inverse**: If it is not raining, then I will go to town. *(negative meaning)*
- **contrapositive**: If I go to town, then it is not raining. *(negative + flipped)*

### Equivalent Propositions
- Two propositions can be called *equivalent* if they always have the same truth value.

### Consistent System Specifications
- A system of propositions is *consistent* if there is a combination that makes all of them true

### Tautologies, Contradictions, and Contingencies
- A *tautology* is a proposition which is always true (all results are true)
- A *contradiction* is a proposition which is always false (all results are false)
- A *contingency* is a proposition which is neither of the above (none of the above)

### Logically Equivalent
- Two compound propositions are **logically equivalent** if the share the same truth values

### De Morgan's Laws
- **Identity laws**
- **Domination laws**
- **Idempotent laws**
- **Double Negation law**
- **Negation Laws**
- **Commutative Laws**
- **Associative Laws**
- **Distributive Laws**
- **Absorption Laws**

For more info see earlier notes into how each law works (but know they are all de morgan laws)

### Equivalence Proofs
- to show that two compound propositions are equivalent to each other de morgan's laws can be used to simplify one down into the other 

### Propositional Satisfiability
- A compound proposition is satisfiable if there is a combination of T and/or F that makes then end result *T*

### Predicate Logic
- uses the following:
	- Variables: *x*,*y*,*z*
	- Predicates: *P*, *M* (denoted by a capital)
	- Quantifiers (see later in note)

#### Propositional functions
- They use variables and a predicate e.g *P*(*x*)
- variables are stand ins for elements within their *domain*
- They are generalizations of propositions and become them when elements are introduced
> For Example:
> let *P*(*x*) denote "x > 0" and the domain be the integers. Then:
> *P*(-3) is false.
> *P*(0) is false.
> *P*(3) is true.
- Often the domain is denoted by *U* (so in the previous U is the integers)

#### Compound Expressions
- Connectives from **propositional logic** carry over to **predicate logic**
- 
---