#Assignment 2#
#Bryant Oblad A01770171#

##Question 1##
Please respond to the following prompt:

Understand the {M, I, U}-system well enough to state and prove a metatheorem about what strings are in S. One way to think of this is as though you are creating some sort of litmus test to determine whether a given string is a theorem of the {M, I, U}-system. Your statement should be able to be used in the following way: If someone presents you with a string of Ms, Is, and Us and asks \Is this an MIU-theorem?" you might be able to answer deni-tively. I don't expect you to, because you won't be able to, classify all strings of the {M, I, U}-system.

_Metatheorem_: A string with never not start with a M.

To answer a question about understanding the {M, I U} - system, we must first define the axioms of the M I U syestem, They are as follows

| # | Axiom |
|:-:|:-:|
| 0 | MI ∈ S |
| 1 | xI ∈ S $\Rightarrow$ xIU |
| 2 | Mx ∈ S $\Rightarrow$ Mxx ∈ S |
| 3 | xIIIy ∈ S $\Rightarrow$ xUy ∈ S |
| 4 | xUUy ∈ S $\Rightarrow$ xy ∈ S |

_Proof_: If we observe axiom 0 we see that each axiom that follows axiom 0 is implied from a derived axiom 0. This implies that every M I U axiom after axiom 0 cannot exist without the definition of axiom 0, also we notice that axiom 0 is the only axiom of the 5 M I U axioms that does not contain any sort of variable (such as x), this allows for expansion on axiom 0. Therefore with the use of a variable, we see that for each axiom, axiom 0 implies another axiom, this proves that all M I U axioms will always start with an M.


##Question 2##
Let P = {(a,b,c) : a, b, c ∈ $\mathbb{Z}$, and a$^2$ + b$^2$ = c$^2$}, and T = {(p, q, r) : p = x$^2$ - y$^2$, q = 2xy, and r = x$^2$ + y$^2$, where x, y ∈ $\mathbb{Z}$}.

_Claim_: T $\subseteq$ P

_Proof_: To prove that T $\subseteq$ P, we have to show that the ordered triple of p$^2$ + q$^2$ = r$^2$. 

If we compute r$^2$, p$^2$ and q$^2$ we get the equations r$^2$ = x$^4$ + 2x$^2$y$^2$ + y$^4$,  p$^2$ = x$^4$ - 2x$^2$y$^2$ + y$^4$, q$^2$ = 4x$^2$y$^2$. If we replace p$^2$ + q$^2$ = r$^2$ into the form a$^2$ + b$^2$ = c$^2$, this shows that (4x$^2$y$^2$) + (x$^4$ - 2x$^2$y$^2$ + y$^4$) = x$^4$ + 2x$^2$y$^2$ + y$^4$ which is true and of the form a$^2$ + b$^2$ = c$^2$, Therefore T $\subseteq$ P. 

##Question 3##
Determine, with proof, the number of ordered triples (A$_1$, A$_2$, A$_3$) of sets which have the property that

(i) A$_1$ $\cup$ A$_2$ $\cup$ A$_3$ = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}, and

(ii) A$_1$ $\cap$ A$_2$ $\cap$ A$_3$ = $\oslash$
express the answer in the form 2$^a$3$^a$5$^c$7$^d$

_Claim_: There are 60,466,176, (6$^{10}$) different ordered triples in A$_1$ $\cup$ A$_2$ $\cup$ A$_3$ = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}, and that 60,466,176 can also be expressed in the form 2$^a$3$^a$5$^c$7$^d$ where a = 10, b = 10, c = 0, and d = 0

_Proof_: Let i $\in$ {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}, We need to compute how many variations of A$_1$ $\cup$ A$_2$ $\cup$ A$_3$ = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10} exist to make the statement A$_1$ $\cap$ A$_2$ $\cap$ A$_3$ = $\oslash$ true. To do this task we can derive that a single instance of A$_1$, A$_2$, A$_3$ can contain, at least 1 instance of i and at most 2 instance of i, for each instance of i we need to compute how many variations each instance of i can have. Therefore I have constucted a table below to signigy the possibilities each instance of i can have.

| A$_1$ | A$_2$ | A$_3$ |
|:-----:|:-----:|:-----:|
|   i   |   -   |   -   |
|   -   |   i   |   -   |
|   -   |   -   |   i   |
|   i   |   i   |   -   |
|   i   |   -   |   i   |
|   -   |   i   |   i   |

for i at 1, 2, 3, 4, 5, 6, 7, 8, 9, 10. Each one holds 6$^1$ possiblities to keep the statement A$_1$ $\cap$ A$_2$ $\cap$ A$_3$ = $\oslash$ true. But since i $\in$ {1, 2, 3, 4, 5, 6, 7, 8, 9, 10},
we can say that 6$^1$ * 6$^1$ ..... 6$^1$ for however many elements i could be, which is 10. This can be rewritten to be 6$^{10}$ and in terms of 2$^a$3$^a$5$^c$7$^d$, a = 10, b = 0, c = 0, and d = 0, which is the same as 60,466,176.

##Question 4##

_Claim_: The system {$\mu$, $\Phi$, $\neg$, $\vee$, $\wedge$, $\Rightarrow$} can be reduced to {$\mu$, $\Phi$, $\bigtriangledown$}, where x $\bigtriangledown$ y is equivalent to $\neg$(x $\vee$ y)

_Proof_: In order to get the system {$\mu$, $\Phi$, $\neg$, $\vee$, $\wedge$, $\Rightarrow$} to reduce to {$\mu$, $\Phi$, $\bigtriangledown$} where $\neg$ is "not", $\vee$ is "or", $\wedge$ is "and", $\Rightarrow$ is "if/implies".   
First we must prove a way to resolve each symbol in the set {$\neg$, $\vee$, $\wedge$, $\Rightarrow$}, to be equivelant to a set using the symbol $\bigtriangledown$. Given to us in the prompt x $\bigtriangledown$ y $\equiv$ $\neg$(x $\vee$ y). I show the equivelancy of x $\bigtriangledown$ y $\equiv$ $\neg$(x $\vee$ y) in the truth table below.

| x | y | $\neg$(x $\vee$ y)  |x $\bigtriangledown$ y|
|---|:-:|:-----------------:|:-------------:|
| T | T |         F         |       F       |
| T | F |         T         |       T       |
| F | T |         T         |       T       |
| F | F |         T         |       T       |

The truth table above proves x $\bigtriangledown$ y $\equiv$ $\neg$(x $\vee$ y) because the results of the truth table above are exactly the same, (FTTT). Following, we can now define the symbol $\bigtriangledown$ as being nor, nor meaning "not or", however "not or" is difficult for me to think about in terms of a truth table so I prefer to evalaute or, then not.
Since we now have nor defined we can use nor to mean the symbol $\bigtriangledown$.

The next thing we can interpret is the that $\neg$x $\equiv$ x$\bigtriangledown$x as I show in the truth table below which allows us to safely remove $\neg$. This is an important definition because it will be used in later truth tables.

| x | $\neg$x  |x$\bigtriangledown$x |
|---|:--------:|:-------:|
| T |  F       | F       |
| T |     F    |      F  |
| F |      T   |   T     |
| F |   T      |    T    |

Next we will prove that $\vee$ is removable. See the truth table below.


| x | y | x $\vee$ y  |(x $\bigtriangledown$ y) $\bigtriangledown$ (x $\bigtriangledown$ y)|
|---|:-:|:-----------:|:-------------:|
| T | T |     T       |       T       |
| T | F |     T       |       T       |
| F | T |     T       |       T       |
| F | F |     F       |       F       |

Notice that we can explicetly say now that x $\vee$ y $\equiv$ (x $\bigtriangledown$ y) $\bigtriangledown$ (x $\bigtriangledown$ y) because we proved that for possible situation of x and y,  x $\vee$ y $\equiv$ (x $\bigtriangledown$ y) $\bigtriangledown$ (x $\bigtriangledown$ y) holds true.

Next we will prove that $\wedge$ can be shown via terms of $\bigtriangledown$.

| x | y | (x $\wedge$ y)| $\neg$($\neg$x $\vee$ $\neg$y) |((x $\bigtriangledown$ x)$\bigtriangledown$(y $\bigtriangledown$ y))$\bigtriangledown$ ((x $\bigtriangledown$ x)$\bigtriangledown$(y $\bigtriangledown$ y))|
|---|:-:|:-----------------:|:------------:|:--:|
| T | T |         T         |       T      | T |
| T | F |         F         |       F      | F |
| F | T |         F         |       F      | F |
| F | F |         F         |       F      | F |

Now we say that (x $\wedge$ y) $\equiv$ $\neg$($\neg$x $\vee$ $\neg$y) $\equiv$ ((x $\bigtriangledown$ x)$\bigtriangledown$(y $\bigtriangledown$ y))$\bigtriangledown$ ((x $\bigtriangledown$ x)$\bigtriangledown$(y $\bigtriangledown$ y)) because of the definition we established in a previous truth table that $\neg$x $\equiv$ x $\bigtriangledown$ x. Therefore have proved we can remove $\vee$ from the set in question.

Lastly, we need to prove that $\Rightarrow$ can be removed from the set in question.

| x | y | x $\Rightarrow$ y  | $\neg$ (y $\bigtriangledown$(x $\bigtriangledown$ y))|(y $\bigtriangledown$(x $\bigtriangledown$ y)) $\bigtriangledown$ (y $\bigtriangledown$(x $\bigtriangledown$ y))|
|---|:-:|:-----------:|:-------------:|:---:|
| T | T |     T       |       T       |  T  |
| T | F |     F       |       F       |  F  |
| F | T |     T       |       T       |  T |
| F | F |     T       |       T       | T |

Referring to the truth table above we can now prove that x $\Rightarrow$ y $\equiv$ (y $\bigtriangledown$(x $\bigtriangledown$ y)) $\bigtriangledown$ (y $\bigtriangledown$(x $\bigtriangledown$ y) because of the  definition we established in a previous truth table that $\neg$x $\equiv$ x $\bigtriangledown$ x and using nor which we previously defined.

Finally we have proved that he system {$\mu$, $\Phi$, $\neg$, $\vee$, $\wedge$, $\Rightarrow$} can be reduced to {$\mu$, $\Phi$, $\bigtriangledown$}, where x $\bigtriangledown$ y is equivalent to $\neg$(x $\vee$ y).



