#dis-math 
# Chapter 2

## Sets

Sets are on of the basic building blocks for the types of objects considered in discrete mathematics.
- important for counting 
- programming languages have set operations

Set theory is an important branch of mathematics
- many different systems of **axioms** have been used to develop set theory
- here we are not concerned with a formal set of axioms for set theory. Instead, we will use what is called **naive set theory** 

A *Set* is an unordered collection of well defined objects.
- the students in the class
- the chairs in this room
The **objects** in a set are called the *elements* or *members* of the set. A set is said to *contain* its elements.

The notation *a* $\in$ *A* denotes that *a* is an element of the set *A*.

if *a* is not a member of *A*, write *a* $\notin$ *A*

### Describing a Set: Roster Method

*S* = {*a*,*b*,*c*,*d*}
Order is not important
*S* = {*a*,*b*,*c*,*d*} = {*b*,*c*,*a*,*d*}

Each distinct object is either a member or not; listing more than once does not change the set.
*S*={*a*,*b*,*c*,*d*} = {*a*,*b*,*c*,*d*}

Can we describe a set without listing all of the members when the pattern is clear?
*S*={*a*,*b*,*c*,*d*,......,*z*}

Examples:
>Set of all vowels in the English alphabet:
*V*={*a*,*e*,*i*,*o*,*u*}

>Set of all odd positive integers less than 10:
*O*={1,3,5,7,9}

>Set of all positive integers less than 100:
*S*={1,2,3,........,99}

>Set of all integers less than 0:
*S*={.....,-3,-2,-1}

Important Sets:

*N* = *natural numbers* = {0,1,2,3,...}
*Z* = *integers* = {...,-3,-2,-1,0,1,2,3,...}
*Z+* = *positive integers* = {1,2,3,.....}
*R* = set of *real numbers*
*R+* = set of *positive real numbers*
*C* = set of *complex numbers*
*Q* = set of *rational numbers*

## Set-Builder Notation

Specify the property or properties that all members must satisfy:
- *S* = {*x* | *x* is a positive integer less than 100}
- *O* = {*x* | *x* is an odd positive integer less than 10}
- *O* = {*x* $\in$ *Z+* | *x* is odd and *x* < 10}

A predicate may be used:
- *S* = {*x* | *P(x)*}
Example: *S* = {*x* | Prime(*x*)}
Positive rational numbers:
*Q+* = {*x* $\in$ *R* | *x* = *p/q*, for some positive integers *p,q*}

## Interval Notation

[*a,b*] = {*x* | *a* $\leq$ *x* $\leq$ *b*}
[*a*,*b*)
(*a*,*b*]
(*a*,*b*)

*closed interval* [*a*,*b*]
*open interval* (*a*,*b*)

## Universal Set and Empty Set

The *universal set U* is the set containing everything currently under consideration.
- sometimes implicit
- sometimes explicitly stated
- content depend on the context

The empty set is the set with no elements. Symbolized $\emptyset$, but {} also used.

## Russell's Paradox

Let *S* be the set of all sets which are not members of themselves. A paradox results from trying to answer the question: "is *S* a member of itself?"

Related paradox:
- Henry is a barber who shaves all people who do not shave themselves. A paradox results from trying to answer the question: "Does Henry shave himself?"

## Things to remember:

Sets can be elements of sets.
{{1,2,3},*a*,{*b*,*c*}}
{*N*,*Z*,*Q*,*R*}

The empty set is different from a set containing the empty set.
$\emptyset$ $\ne$ {$\emptyset$}

## Set Equality

**Definition**: Two elements are *equal* if and only if they have the same elements.
- There































































