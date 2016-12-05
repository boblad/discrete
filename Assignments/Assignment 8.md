#Bryant Oblad#
#Assignment 8#
#A01770171#

1) Find a closed formula for the recurrence a$_n$ = a$_{n − 1}$ + 2a$_{n−2}$ + n, for n ≥ 2 with a$_0$ = 0 and a$_1$ = 1.

_Claim_: The closed formula for the recurrence a$_n$ = a$_{n − 1}$ + 2a$_{n−2}$ + n, for n ≥ 2 with a$_0$ = 0 and a$_1$ = 1 is equal to a$_n$ = $\frac{4}{3}$(2$^n$) + $\frac{-1}{12}$(-1$^n$) - $\frac{1}{2n}$ - $\frac{5}{4}$

_Proof_: For this problem, we need to establish 3 things, Solve the homogeneous part of the equation, identify the non-homogeneous part, then solve for constants. First we take a$_n$ = a$_{n − 1}$ + 2a$_{n−2}$ for the homogeneous part. Using the approach we were given in class we see that a$^{n - (n - 2)}$ = a$^{(n - 1) - (n - 2)}$ + 2. We find that if we simplity this equation we get -a$^2$ + a + 2 = 0, which has the roots 2 and -1. Therefore for the nonhomogeneous part we get a$_n$ = A(2$^n$) + B(-1$^n$).

Next, we need to identify the non-homogenous part of the equation. We can determine this by defining Cn + D = a$_{n − 1}$ + 2a$_{n−2}$ + n, this is equal to [C(n-1) + D] + 2[C(n - 2) + D] + n, which can be simplified to be Cn + D = (3C + 1)n + (-5C + 3D), Solving this equation we find that C = $\frac{-1}{2}$, and D = $\frac{-5}{4}$. Now we can merge the non-homogenous and homogenous parts of the equation and find that a$_n$ = A(2$^n$) + B(-1$^n$) - $\frac{1}{2n}$ - $\frac{5}{4}$, After solving for A and B, A will be $\frac{4}{3}$ and B will be $\frac{-1}{12}$
then the closed equation will be a$_n$ = $\frac{4}{3}$(2$^n$) + $\frac{-1}{12}$(-1$^n$) - $\frac{1}{2n}$ - $\frac{5}{4}$ for n ≥ 2 with a$_0$ = 0 and a$_1$ = 1

2) Modiﬁed Tower of Hanoi. Consider the Tower of Hanoi game and label the three pegs L, M, and R, for the left peg, the middle peg, and right peg, respectively. Determine the minimum number of moves required to transfer n disks as in the Tower of Hanoi game, but with the additional constraint that a disk can only be moved to an adjacent peg; that is, a disk can only be moved to M from L or R, and can only be moved to L or R from M.

_Claim_: The minimum number of moves required to transfer n disks as in the Tower of Hanoi game is T$_n$ = 3(T$_{n - 1}$) + 2 where n ≥ 1 and T$_0$ = 0 and T$_1$ = 2

_Result_: After I played the tower of hanoi game and understood the rules corresponding to the quetion at hand. I started to notice a pattern. We see that for every move we make, it can only go to a pole or place that is right next to the disc's current location. We form the for each set it takes (T$_{n - 1}$) + (T$_{n - 1}$) + (T$_{n - 1}$), which is the same thing as 3(T$_{n - 1}$). But for the equations to add up we have a corresponing addition of 2 so that our base cases T$_0$ = 0 and T$_1$ = 2 to verify my solution. 

3) Consider paths in the (x, y)-plane of length n (having n steps taken) starting from (0, 0) with steps R : (x, y) → (x+1, y), L : (x, y) → (x−1, y), and U : (x, y) → (x, y+1). We require that a step R is not followed by a step L and vice versa. Put p$_n$ equal to the number of such paths or length n and determine a closed formula for p$_n$.

_Claim_: The formula where p$_n$ is equal to the number of such paths or length n is p$_n$ = P$_n$ = 2(P$_{n - 1}$) + P$_{n - 2}$

_Proof_:
First we need to look at all of the available moves that are possible from a single point, We have L, R, and U for the last move and LL RR UR UL UU LU and RU for the second to last move.
For any given "string" or sequece of moves. We must guarentee the same length or count of moves it takes the variation of paths. To get to the First possible outcome for the last move made on the string we look at the L, R, and U. For each of these moves there is only one other possible move that could have been made before, which are LL for the L, RR for the R, and UL for the U. (for the U we only allow one variation to allow the use of the other U moves in a later reason). the moves we just made can now be seen as P$_{n - 1}$. We notice that for each of the L, R, and U moves, there was another route we could have taken, it is LU, RU, UU for each of the respected roots. This too is a result of P$_{n - 1}$. This only leaves the availablity of the move UR left, after which fulfilled will clear all possible moves making this the result of all the available moves that could be made. Following the UR we see that it is equivelant to P$_{n - 2}$. Now if we add all of these sections up. We see that P$_n$ = 2(P$_{n - 1}$) + P$_{n - 2}$. However, this is not the closed equation, to get the closed equation we would to need to use proof by induction.
