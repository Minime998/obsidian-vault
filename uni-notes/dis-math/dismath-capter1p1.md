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

### # Headers
```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------
```

# Emphasis

```markdown
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

# Lists
```markdown
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.
# Links
```markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
[I'm an inline-style link](https://www.google.com)
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

# Images
```markdown
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```
Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
# Tables
```markdown
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

| Tables        |      Are      |  Cool |
|:------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |
|               |               |       |
|               |               |       |

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
# Videos
```markdown
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

# Unordered Lists
```markdown
<ul>  
<li>First item</li>  
<li>Second item</li>  
<li>Third item</li>  
<li>Fourth item</li>  
</ul>
```
<ul>  
<li>First item</li>  
<li>Second item</li>  
<li>Third item</li>  
<li>Fourth item</li>  
</ul>
Equivalent Propositions
Two propositions are *equivalent* if they always have the same truth value.
**Example**: Show using a truth table that the conditional is equivalent to the contrapositive

