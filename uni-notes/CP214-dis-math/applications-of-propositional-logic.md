#dis-math 
# Applications of Propositional Logic
## Section 1.2
- [[propositional-logic#^1d87bb|Section 1.1]]
### Summary 
[[#Translating English Sentences]]

[[#System Specifications]]
- [[#Consistent System Specifications]]


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

A list of propositions is *consistent* if it is possible to assign truth values to the proposition variables/atomic proposition so that each proposition is true.

>__Example__: Are these specifications consistent?
	>"The system has at least 8GB of memory."
	>"The system has Intel i5 or AMD 4500 processor."
	>"The system has 512GB of storage."

__Solution__:Let *p* denote "The system has at least 8GB of memory.", *q* $\vee$ *t* denote "The system has Intel i5 or AMD 4500 processor." and *r* denote "The has 512GB of storage." The specification can be written as: *p*,*q*,*t*,*r*

The specifications are consistent since all *p*, *q*, *t* and *r* are true.

>__Example__: Are these specifications consistent?
	>"The diagnostic message is stored in the buffer, or it is re-transmitted."
	>"The diagnostic message is not stored in the buffer."
	>"If the diagnostic message is stored in the buffer, then it is re-transmitted."

__Solution__:Let *p* denote "The diagnostic message is stored in the buffer." Let *q* denote "The diagnostic message is re-transmitted" The specification can be written as: *p* $\vee$ *q*, $\neg$*p*, *p* $\rightarrow$ *q*. When *q* is false, and *q* is true all three statements are true. So, the specification is consistent

* What if "The diagnostic message is not re-transmitted" is added?
	* __Solution__: Now their will be a $\neg$*q* and there is no satisfying assignment. So this would make the specification not consistent.
	
	#### Logic Puzzles
	>__Example__: An island has two kinds of inhabitants, knights, who always tell the truth, and their opposites, knaves, who always lie. You encounter two people *A* and *B*, if *A* says "*B* is a knight" and *B* says "The two of us are of opposite types", what are *A* and *B*




