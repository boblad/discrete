#Assignment 10#
###Bryant Oblad###
###A01770171###

##Question 1##
Please use the theory of generating functions to determine the number of solutions to the equation x$_1$ + x$_2$ + x$_3$ + x$_4$ = n, where the variables are constrained in the following way: x$_1$= 2k for some k $\in$ N, x$_2$$\in$ 0, 1, 2 x$_3$ = 3q for some q $\in$ N, and x$_4$ $\in$ 0,1.

_Claim_:
There are n + 1 solutions to x$_1$ + x$_2$ + x$_3$ + x$_4$ = n, where the variables are constrained in the following way: x$_1$= 2k for some k $\in$ N, x$_2$$\in$ 0, 1, 2 x$_3$ = 3q for some q $\in$ N, and x$_4$ $\in$ 0,1.

_Proof_: We can identify x$_1$, x$_2$, x$_3$, x$_4$ to be

x$_1$ = A(x) = $\frac{1}{1 - x^2}$

x$_2$ = B(x) = $\frac{1 - x^2}{1 - x}$ = 0 + 1 + 2

x$_3$ = C(x) = $\frac{1}{1 - x^3}$

x$_4$ = D(x) = $\frac{1 - X^2}{1 - x}$ = 0 + 1

To explore every possibility we multiple A(x)B(x)C(x)D(x) to get $\frac{1}{(1 - x)^2}$ and we know that $\frac{1}{(1 - x)^2}$ is equal to n + 1 so we can denote that

$\sum_{n>=0}$ (n + 1)x$^2$ = $\frac{1}{(1 - x)^2}$

The coefficient for x$^n$ is equal to n + 1

##Question 2##
Please revisit and re-solve the pizza problem using generating functions to obtain the closed formula: P (n) = $\frac{1}{2}$ n$^2$ + $\frac{1}{2}$n + 1 =  ${n}\choose{2}$ + n + 1.

_Claim_: P (n) = $\frac{1}{2}$ n$^2$ + $\frac{1}{2}$n + 1 is a solution to the pizza problem.

_Proof_: If we take the recurrence relation formula of a$_n$ = a$_{n - 1}$ + n as a generator function we can see that $\sum_{n>=0}$a$_{n - 1}x^n$ +  $\sum_{n>=0}$nx$^n$ = $\sum_{n>=0}$ a$_{n}x^n$. Using the lemma we were given in class of nx$^n$ is $\frac{x}{(1 - x)^2}$. Using this lemma we can get the equation $\frac{x}{(1 - x)^2}$ + x$\sum_{n>=0}$ a$_{n}x^n$ = $\sum_{n>=0}$ a$_{n}x^n$. With some factorization we can get $\frac{x}{(1 - x)^3}$ + $\frac{1}{1 - x}$ which is the same as $\sum_{n>=0}$P(a$_n$) = $\sum_{n>=0}$($\frac{n^2}{2}$ + $\frac{n}{2}$ + 1 which outlines P(n) to be $\frac{1}{2}$ n$^2$ + $\frac{1}{2}$n + 1 and as it is defined as ${n}\choose{2}$ + n + 1.

##Question 3##
Please solve the following recurrence relations using the theory of generating functions:

(a)  a$_n$ = a$_{n−1}$ + a$_{n−2}$ + n, n≥2 ,a0 = 0 , a1 = 1

(b)  b$_n$ = 4b$_{n−1}$ − b$_{n−2}$ − 6b$_{n−3}$, n≥3, b0 = 0, b1 = 1, b2 = 1
