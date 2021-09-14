#dis-math 
# Nested Quantifiers
## Section 1.5
[[predicates-quantifiers|Section 1.4]]
[[propositional-equivalences|Section 1.3]]
[[applications-of-propositional-logic|Section 1.2]]
[[propositional-logic|Section 1.1]]

### Summary

#### Nested Quantifiers

Nested quantifiers are often necessary to express the meaning of sentences in English as well as important concepts in computer science and mathematics.

__Example__: "Every real number has an inverse" is:
- $\forall$*x* $\exists$*y*(x + y = 0)

Where the domains of x and y are real numbers.

We can also think of nested propositional functions:
- $\forall$*x* $\exists$*y*(x + y = 0) can be viewed as $\forall$*x* Q(x) where Q(x) is $\exists$*y* P(x,y) where P(x,y) is ( x + y = 0)