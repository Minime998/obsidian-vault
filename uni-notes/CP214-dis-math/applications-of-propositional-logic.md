#dis-math 
# Applications of Propositional Logic
## Section 1.2
### Summary 
[[#Translating English Sentences]]
[[#System Specifications]]


#### Translating English Sentences

Steps to convert an English sentence to a statement in propositional logic
- identify atomic (simple) propositions and represent using propositional variables
- determine appropriate logical connectives

>"If I go to Harry's or to the country, then I will not go shopping."

* *p*: I go to Harry's
* *q*: I go to the country.
* *r*: I will go shopping.

If *p* or *q*, then not *r*.

(*p* $\vee$ *q*) $\rightarrow$ $\neg$*r*

>"You can access the internet from campus only if you are a computer science major or you are not a freshman."

Let *a*, *c*, and *f* represent respectively
*a* $\rightarrow$ (*c* $\vee$ $\neg$*f*)

#### System Specifications

System and software engineers take requirements in English and express then in a precise specification language based on logic

>__Example__: Express in propositional logic
>"The automated reply cannot be sent when the file system is full"

*q* $\rightarrow$ $\neg$*p*

##### Consistent System Specifications

A list of propositions is *consistent* if it is possible to assign truth values to the proposition variables so that each proposition is true.

>__Example__: Are these specifications consistent?
	>"The system has at least 8GB of memory."
	>"The system has Intel i5 or AMD 4500 processor."
	>"The system has 512GB of storage."

Let *p* denote "The system has at least 8GB of memory.", *q* denote "The system has Intel i5 or AMD 4500 processor." and *r* denote "The has 512GB of storage." The specification can be written as: *p*,*q*,*r*
