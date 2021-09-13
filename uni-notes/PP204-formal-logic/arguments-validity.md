#formal-logic
# Arguments and Validity
## Summary
[[#Arguments]]
- [[#Conclusion Indicators]]
- [[#Premise Indicators]]

[[#Validity]]
- [[#A strange thing about validity]]

[[#Two ways an argument can go wrong]]
- [[arguments-validity#^57e5f2|soundness]]
- [[arguments-validity#^f54b57|entailment]]
- [[arguments-validity#^d0cf7b|counterexample]]

[[#Deductive arguments vs inductive arguments]]

### Arguments
An *argument* is a series of statements consisting of premises and a conclusion
- The conclusion is meant to follow from the argument's premises
Often, in English the conclusion will come after the premises. But, this need not always be the case.

>Dumbo is an elephant. All elephants are bigger than a breadbox. <Mark>Therefore</Mark>, Dumbo is bigger than a breadbox

But we could have said:

>Dumbo is bigger than a breadbox. <Mark>After all</Mark>, Dumbo is an elephant, and all elephants are bigger than a bread box

#### Conclusion Indicators
Notice, in the first way of putting our argument about Dumbo, the conclusion was signaled by the work "therefore".
- Words like *so, hence, therefore* often signal a conclusion
- these are **conclusion indicator words**.

#### Premise Indicators
In our second example, the conclusion was stated first and the words "after all" signaled the premises
- *after all* is a **premise indicator**. Often premise indicators: *given that, since, because*

### Validity
An argument is **valid** iff it is impossible for the premises to be true and the conclusion false
- the conclusion must be true (premises dependent)

	>Validity concerns the logical relationship between an argument's premises and conclusion. If an argument is valid it tells us that <u>if</u> the premises are true, so the conclusion must also be true. Our definition does not say that the premises must be true or are true. In fact it is possible to construct an argument that is **logically valid**, yet contains one or more false premises

### A strange thing about *validity*
It has to do with the *relationship* between premises and conclusion. *If* the premises were true, must the conclusion also be true?
- yes!

>All professors are aliens.
<u>Jill is a professor</u>
Therefore, Jill is an alien

## Two ways an argument can go wrong
- one or more of the premises might be false
	-->*Soundness:* An argument is sound if and only if it is valid AND its premises are true. ^57e5f2

- The conclusion might not follow from the premises.
	-->*Entailment*, or logical consequence, is a relation between premises and conclusion 
   ^f54b57

If the premises are assumed to be true, then is it impossible for the conclusion to be false?

![](CaptureLogic_argumentwrong.png)

>Either Alice went to the playground or she went to the movies. She didn't really like anything paying at the movie theater.

conclusion: Alice went to the playground.

A valid argument?

Answer: 
(see [[#Validity]])

According to the definition of validity an argument is only valid if it is impossible for the premises to be true and the conclusion false which is exactly how this argument is structured as the premises are true yet the conclusion could be false therefore, the argument can not be called valid and by extension sound

this is proving invalidity by *counterexample* ^d0cf7b

## Deductive arguments vs. inductive arguments
>Note: When you are thinking about what is "possible" or considering "cases" or scenarios, make sure that you don't equivocate or rely on vagueness in your cases. Since logician theorize about logical consequences/entailment, they don't want the distraction of ambiguity of terms (equivocation) or indeterminate predicate terms. Rather fix terms as clearly as possible (that is, both names and predicates or properties should be clearly interpreted and not shifting), so that we can then ask, given that statement or claim what follows from it?

Can't do this:
Ryan is now 43 years old. --> T
So, Ryan us now more than 40 years old --> F

Ryan is a person, not all Ryans

- So we evaluate arguments as __valid__ or __invalid__, __sound__ or __unsound__.
	- But not: true or false. *Sentences* are evaluated as true or false
		- *arguments* are evaluated as valid or invalid, sound or unsound 