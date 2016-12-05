#Assignment 9#
#Bryant Oblad#
#A01770171#


A 6-sided die labeled with the integers 1,2,3,4,5,6 will be called a standard die. The goal for this part is to determine all ways to label a pair of dice with positive integers so that the probabilities of rolling the usual sums 2, 3, . . . , 12 are the same, but the labels are non-standard.
Step 1. Let p(x) = x + x$^2$ + x$^3$ + x$^4$ + x$^5$ + x$^6$, and explain in at least one sentence why (p(x))$^2$ is the generating function for the probabilities of outcomes in rolling a pair of standard dice.

When we square p(x) we get(p(x))$^2$ = x$^2$ + 2x$^3$ + 3x$^4$ + 4x$^5$ + 5x$^6$ + 6x$^7$ + 5x$^7$ + 4x$^9$ + 3x$^{10}$ + 2x$^{11}$ + x$^{12}$ where the coefficent is the number of possibilities that se can get the sum of the exponent. This is assuming that (p(x)) is a standard die. It is a generating function because we simulate the information between the 2 die.

Step 2. Let A = (a1, a2, a3, a4, a5, a6) and B = (b1, b2, b3, b4, b5, b6) be two lists of positive integers. Put p$_A$(x) = x$^{a1}$ +x$^{a2}$ +x$^{a3}$ +x$^{a4}$ +x$^{a5}$ +x$^{a6}$ and p$_B$(x) = x$^{b1}$ +x$^{b2}$ +x$^{b3}$ +x$^{b4}$ +x$^{b5}$ +x$^{b6}$. Explain in at least one sentence why finding a$_i$s and b$_i$s such that p$_A$(x)p$_B$(x) = (p(x))$^2$ is relevant this part of the Experience.

We express that it doesnt matter what the face value of each die has. for a$_i$s and b$_i$s we can see that for whatever value it has, lets say that a1 = 1, a2 = 2, a3 = 3, a4 = 4, a5 = 5, a6 = 6, and for b, lets say b1 = 400, b2 = 410, b3 = 420, b4 = 422, b5 = 500, and b6 = 501. No matter what the face value is we will find that the number of possibilities for each variation is the same as a pair of standard dice. The sum of the dice will be different (different exponents), but the overall purpose is the idea that it doesnt matter what the face value is of each die. As long as the each number is unique to that die. (for now, I will later show that this is not true)

Step 3. Factor p(x) into irreducible polynomials and use this factorization to help solve for the a$_i$s and b$_i$s. Specifically, the factorization will force the form of p$_A$(x) to be something like p$_1$(x)$^q$p$_2$(x)$^r$p$_3$(x)$^s$p$_4$(x)$^t$, where 0 ≤ q,r,s,t ≤ 2 and pi(x), for 1 ≤ i ≤ 4, is a factor of p(x). In your solution to this step, you must motivate why you take this step; that is, explain why the step is taken.

The factorization of p(x) is broken out to be x(x + 1)(x$^2$ - x + 1)(x$^2$ + x + 1). The factorization gets us one step closer to being able to determine for a pair of dice which portion of p(x) is absolutely essential to be associated with a single die.
This factorization will help in step 4. 

Step 4. Begin to reduce the possibilities for q, r, s, and t by using information from p$_A$(1) and p$_A$(0). Note that, on one hand p$_A$(1) = 1$^{a1}$ +1$^{a2}$ +1$^{a3}$ +1$^{a4}$ +1$^{a5}$ +1$^{a6}$ = 6 (since ai > 0), and on the other hand we have p$_A$(1) = p$_1$(1)$^q$p$_2$(1)$^r$p$_3$(1)$^s$p$_1$(1)$^t$. Similarly, there are two ways to view p$_A$(0).

We see that p$_1$(1)$^q$p$_2$(1)$^r$p$_3$(1)$^s$p$_1$(1)$^t$ = x$^q$(x + 1)$^r$(x$^2$ - x + 1)$^s$(x$^2$ + x + 1)$^t$ respectfully. we can see that for P$_A$(0) = 0$^q$1$^r$1$^s$1$^t$ = 0. P$_A$(1) = 1$^q$2$^r$1$^s$3$^t$. That first factor of x, it however does not matter what the exponent value is because 0 times anything is 0. Now we can show that r and t will have to be 1 for P$_A$(1) because of the presence of the 2 and 3 which is multiplied to be 6.

Step 5. List all possible ways to label a pair of dice so that the probabilities of obtaining the sums 2, 3, 4, 5, 6, 7, 8, 9, 10,11,12 are $\frac{1}{36}$ , $\frac{2}{36}$ , $\frac{3}{36}$ , $\frac{4}{36}$ , $\frac{5}{36}$ , $\frac{6}{36}$ , $\frac{5}{36}$ , $\frac{4}{36}$ , $\frac{3}{36}$ , $\frac{2}{36}$ , $\frac{1}{36}$ ,respectively. One such way will be the standard way. Aspart of your solution for this step, should be the proof that the labels you have found are the only possible ones that give the desired probabilities for roll-outcomes.

The only possibility to get this distribution is through the face values 1,3,4,5,6,8 1,2,2,3,3,4. If we took what we did in step 4 with x$^q$(x + 1)$^r$(x$^2$ - x + 1)$^s$(x$^2$ + x + 1)$^t$ where we take the values of the q,r,s,t for each instance used, after distributing we get (x + x$^3$ + x$^4$ + x$^5$ + x$^6$ + x$^8$)(x + 2x$^2$ + 2x$^3$ + x$^4$) which describes the only possiblity to get the respected values.