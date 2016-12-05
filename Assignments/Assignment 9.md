#Assignment 9#
#Bryant Oblad#
#A01770171#


A 6-sided die labeled with the integers 1,2,3,4,5,6 will be called a standard die. The goal for this part is to determine all ways to label a pair of dice with positive integers so that the probabilities of rolling the usual sums 2, 3, . . . , 12 are the same, but the labels are non-standard.


When we square p(x) we get(p(x))$^2$ = x$^2$ + 2x$^3$ + 3x$^4$ + 4x$^5$ + 5x$^6$ + 6x$^7$ + 5x$^7$ + 4x$^9$ + 3x$^{10}$ + 2x$^{11}$ + x$^{12}$ where the coefficent is the number of possibilities that se can get the sum of the exponent. This is assuming that (p(x)) is a standard die. It is a generating function because we simulate the information between the 2 die.



We express that it doesnt matter what the face value of each die has. for a$_i$s and b$_i$s we can see that for whatever value it has, lets say that a1 = 1, a2 = 2, a3 = 3, a4 = 4, a5 = 5, a6 = 6, and for b, lets say b1 = 400, b2 = 410, b3 = 420, b4 = 422, b5 = 500, and b6 = 501. No matter what the face value is we will find that the number of possibilities for each variation is the same as a pair of standard dice. The sum of the dice will be different (different exponents), but the overall purpose is the idea that it doesnt matter what the face value is of each die. As long as the each number is unique to that die. (for now, I will later show that this is not true)



The factorization of p(x) is broken out to be x(x + 1)(x$^2$ - x + 1)(x$^2$ + x + 1). The factorization gets us one step closer to being able to determine for a pair of dice which portion of p(x) is absolutely essential to be associated with a single die.
This factorization will help in step 4. 



We see that p$_1$(1)$^q$p$_2$(1)$^r$p$_3$(1)$^s$p$_1$(1)$^t$ = x$^q$(x + 1)$^r$(x$^2$ - x + 1)$^s$(x$^2$ + x + 1)$^t$ respectfully. we can see that for P$_A$(0) = 0$^q$1$^r$1$^s$1$^t$ = 0. P$_A$(1) = 1$^q$2$^r$1$^s$3$^t$. That first factor of x, it however does not matter what the exponent value is because 0 times anything is 0. Now we can show that r and t will have to be 1 for P$_A$(1) because of the presence of the 2 and 3 which is multiplied to be 6.



The only possibility to get this distribution is through the face values 1,3,4,5,6,8 1,2,2,3,3,4. If we took what we did in step 4 with x$^q$(x + 1)$^r$(x$^2$ - x + 1)$^s$(x$^2$ + x + 1)$^t$ where we take the values of the q,r,s,t for each instance used, after distributing we get (x + x$^3$ + x$^4$ + x$^5$ + x$^6$ + x$^8$)(x + 2x$^2$ + 2x$^3$ + x$^4$) which describes the only possiblity to get the respected values.