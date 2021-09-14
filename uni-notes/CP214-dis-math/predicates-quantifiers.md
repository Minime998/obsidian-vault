#dis-math 

# Predicates and Quantifiers
## Section 1.4
[[propositional-equivalences|Section 1.3]]
[[applications-of-propositional-logic|Section 1.2]]
[[propositional-logic|Section 1.1]]

### Summary
[[#Propositional Logic Not Enough]]

[[#Propositional Functions]]
- [[#Examples of Propositional Functions]]

[[#Compound Expressions]]

#### Propositional Logic Not Enough

If we have:
- "All men are mortal."
- "Socrates is a man."

Does it follow that "Socrates is mortal?"

Can't be represented in propositional logic. Need a language that talks about objects, their properties, and their relations.

Later we'll see how to draw inferences

#### Propositional Functions

Propositional functions become propositions (and have truth values) when their variables are each replaced by a value from the *domain* (or *bound* by a quantifier, as we will see later).

The statement *P(x)* is said to be the value of the propositional function *P* at *x*.

For example, let P(x) denote "x > 0" and the domain be the integers. Then:
- P(-3) is false.
- P(0) is false
- P(3) is true.

Often the domain is denoted by *U*. So in this example *U* is the integers

##### Examples of Propositional Functions

Let "x + y = z" be denoted by R(x,y,z) and U (For all three variables) be the integers. Find these truth tables:
- R(2,-1,5)
	- __Solution__: F
- R(x,3,z)
	- __Solution__: Not a Proposition

Now let "x -y = z" be denoted by Q(x, y, z) with U as the integers. Find these truth values:
- Q(2,-1,3)
	- __Solution__: T

#### Compound Expressions

Connectives from propositional logic carry over to predicate logic.

If P(x) denotes "x > 0", find these truth values:
- P(3) $\vee$ P(-1)
	- __Solution__: T
- P(3) $\rightarrow$ P(-1)
	- __Solution__: F
- P(3)



