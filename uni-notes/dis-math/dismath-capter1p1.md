#dis-math 
# Propositional Logic
## Section 1.1
### Summary:
[[#Propositions]]
[[#Propositional Logic and Compound Propositions]]:
- [[#Compound Propositions Negation]]
- [[#Compound Propositions Conjunction]]
- [[#Compound Propositions Disjunction]]
- [[#Compound Propositions Implication]] 
- [[#Understanding Implication]] 
- [[#Different ways of Expressing p rightarrow q]]
- [[#Converse Contrapositive and Inverse]]
- [[#Biconditional]]
- [[#Truth Tables For Compound Propositions]]

#### Propositions
A *proposition* is a declarative sentence that is either true or false
Examples of *Propositions*:

	a) The Moon is made of green cheese.
	b) Toronto is the capital of Canada
	c) Blue jays always win
	d) 0+0=2
Examples that are not *Propositions*:

	a) Sit down!
	b) What time is it?
	c) he might be in a bad mood.

##### Propositional Logic and Compound Propositions
* Propositional variables: we use *p,q,r,s...* to represent a proposition
* Any Proposition can have one of two truth values, true denoted by T and false denoted by F
* Compound Propositions; constructed from logical connectives and other propositions
	* Negation $\neg$
	* Conjunction $\wedge$
	* Disjunction $\vee$
	* Implication $\rightarrow$
	* Biconditional $\leftrightarrow$

#### Compound Propositions: Negation
The *negation* of a proposition *p* is denoted by 
$\neg$*p* and has the truth table:

![](CaptureDis_Negation.png)

**Example**: if *p* denotes "The Earth is round.", then $\neg$*p* denotes "It is not the case that the Earth is round" or more simply "The Earth is not round"

#### Compound Propositions: Conjunction
The *conjunction* of propositions *p* and *q* is denoted by *p $\wedge$ q* and has the truth table:

![](CaptureDis_Conjunction.PNG)

**Example**: if *p* denotes "I am at home." and *q* denotes "It is raining." then *p $\wedge$ q* denotes "I am at home, and it is raining."

#### Compound Propositions: Disjunction
The *disjunction* of propositions *p* and *q* is denoted by *p $\vee$ q* and has the truth table:

![](CaptureDis_Disjunction.PNG)

**Example**: if *p* denotes "I am at home." and *q* denotes "It is raining." then *p $\vee$ q* denotes "I am at home or it is raining." 

##### The Connective Or in English
In English "or" has two distinct meanings. Inclusive or or exclusive or
* "Inclusive Or" - [[#Compound Propositions Disjunction]]
* "Exclusive Or" - ![](CaptureDis_Xor.PNG)

#### Compound Propositions: Implication 
If *p* and *q* are propositions, then *p $\rightarrow$ q* is a *conditional statement* or *implication* which is read as "if *p*, then *q*" and has the following truth table:

![](CaptureDis_Implication.PNG)

**Example**: if *p* denotes "I am at home." and *q* denotes "it is raining." then *p $\rightarrow$ q* denotes "If I am at home then it is raining." 

##### Understanding Implication
In the *p $\rightarrow$ q* there does not need to be any connection between the antecedent or the consequent. the "meaning" of *p $\rightarrow$ q* depends only on the truth values of *p* and *q*.
These implications are perfectly fine but would not be use in ordinary English.
* "If the moon is made of green cheese, then I have more money than Bill gates."
* "If the moon is made of green cheese, then I'm on welfare."
* "If 1+1 =3, then your grandma wears combat boots."

#### Different ways of Expressing *p $\rightarrow$ q*
- if *p*, then *q*
- if *p*,*q*
- *q* unless $\neg$*p*
- *q* if *p*
- *q* whenever *p*
- *q* follows from *p*
- a necessary condition for *p* is *q*
- a sufficient condition for *q* is *p*
- *p* implies *q*
- *p* only if *q*
- *q* when *p*
- *p* is sufficient for *q*
- *q* is necessary for *p*

### Converse, Contrapositive, and Inverse
From *p* $\rightarrow$ *q* we can form new conditional statements.
* *q* $\rightarrow$ *p* is the **converse** of *p* $\rightarrow$ *q*
* $\neg$*q*$\rightarrow$ $\neg$*p* is the **contrapositive** of *p*$\rightarrow$ *q*
* $\neg$*p*$\rightarrow$ $\neg$*q* is the **inverse** of *p*$\rightarrow$ *q*

**Example**: Find the converse, inverse, and contrapositive of "It raining is a sufficient condition for my not going to town."

**converse**: If I do not go to town, then it is raining.
**inverse**: if it is not raining, then I will go to town.
**contrapositive**: if I go to town, then it is not raining.

### Biconditional
Let *p* and *q* be propositions. The *biconditional* statement *p* $\leftrightarrow$ *q* is the *proposition* "*P* if and only if *q*." The biconditional *p* $\leftrightarrow$ *q* is true when *p* and *q* have same truth values

![](CaptureDis_Biconditional.PNG)

**Example**: if *p* denotes "I am at home." and *q* denotes "it is raining." then *p* $\leftrightarrow$ *q* denotes "I am at home if and only if it is raining."

#### Expressing the Biconditional
Some alternative ways "*p* if and only if *q*" is expressed in English:
* *P* is necessary and sufficient for *q*
* if *p* then *q*, and conversely
* *p* if *q*

### Truth Tables For Compound Propositions
Construction of a truth table:
Rows
* Need a row for every possible combination of values for the *atomic propositions*
Columns
* Need a column for the compound proposition (usually at far right)
* Need a column for the truth value of each expression

#### Example Truth Table
Construct a truth table for *p* $\vee$ *q* $\rightarrow$$\neg$*r*
![](CaptureDis_TruthTable.PNG)

### Equivalent Propositions
Two propositions are *equivalent* if they always have the same truth value.

**Example**: Show using a truth table that the conditional is equivalent to the contrapositive
![](CaptureDis_EquivalentTable.PNG)

#### Using a Truth Table to show Non-Equivalence
**Example**: Show using truth tables that neither the converse nor the inverse of an implication are equivalent to the implication.
![](CaptureDis_Non-Equivalence.PNG)

## Precedence of Logical Operators
![](CaptureDis_Logical-Operators.PNG)

*p* $\vee$ *q* $\rightarrow$ $\neg$*r* is equivalent to (*p* $\vee$ *q*) $\rightarrow$ $\neg$*r* if the intended meaning is *p* $\vee$(*q* $\rightarrow$ $\neg$*r*) then parentheses must be used