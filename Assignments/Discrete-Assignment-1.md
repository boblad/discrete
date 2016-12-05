#Assignment 1

###Bryant Oblad A01770171

$\ddot\smile + \ddot\smile = ?$

##Question 1

- Please interpret the quotation of Bertrand Russell given below and write an explanation you would use to a non-Mathematically indoctrinated friend (who is curious and patient enough to listen to you).

```
To choose one sock from each of innitely many pairs of socks
requires the Axiom of Choice, but for shoes the Axiom is not 
needed." { Bertrand Russell
```

_answer_: Suppose you have infinite socks and an infinite pair of shoes. For each set of shoes you can tell a difference between the left and the right shoe. But in a theoretical world there is absolutely no difference between a set of socks, therefore each set is exactly the same. The definition of Axiom of Choice states 'Every set with no empty elements has a choice function.' What this means in terms of infinate shoes and socks (the sets) means that if you must choose a sock that is completely identical to another, there is no logical reason to choose one sock over another, therefore a outside source of decision making (the function) must take place. This is the axium. Because in a real world we must choose a sock, an axium (or assumption) must take place.

##Question 2

- Define the set E via the equation E = {x ∈ $\mathbb{Z}$ : x is even}; dene the set F via F = {y ∈ $\mathbb{Z}$ : y = a +
b, where a and b are odd}. Please prove that E = F.

_Claim_: The set E = {x ∈ $\mathbb{Z}$ : x is even} is equal to the set F = {y ∈ $\mathbb{Z}$ : y = a +
b, where a and b are odd} which implies E = F.

_Proof_: We know that the definition of an odd number lets say $S_{odd}$ = 2$k_0$ + 1 where $k_0$ ∈ $\mathbb{Z}$. Also the defintion of an even number lets say $S_{even}$ = 2$k_1$  + 1 where $k_1$ ∈ $\mathbb{Z}$. With these definitions we can restate the problem to be E = {x, $k_0$ ∈ $\mathbb{Z}$ : x = 2$k_0$} is equal to F = {y, $k_2$, $k_3$ ∈ $\mathbb{Z}$ : y = a + b where a = 2$k_2$ + 1, b = 2$k_3$ + 1}. y = 2($k_2$ + $k_3$ + 1) let $k_4$ = $k_2$ + $k_3$ + 1 so y = 2$k_4$ which by definition is even, therefore F = E.

##Question 3
- Suppose x is a positive integer with n digits, say x = d1d2d3 · · · dn. In other words, di ∈ {0, 1, 2, . . . , 9} for 1 ≤ i ≤ n, but d1 $\neq$ 0. Please prove the following. Recall that, for a, b ∈ Z, a is a divisor of b if b = ak, for some k ∈ Z.

(a) If 9 is a divisor of d1 + d2 + · · · + dn, then 9 is a divisor of x. 

(b) If dn = 0 or dn = 5, then 5 is a divisor of x.

###(a)
_Claim_: If 9 is a divisor of $d_1$ + $d_2$ + · · · + $d_n$, then 9 is a divisor of $d_1$$d_2$$d_3$ · · · $d_n$, where $d_k$ is ∈ $\mathbb{Z}$ and 1 ≤ i ≤ n where $d_i$ ∈ {0, 1, 2, . . . , 9}, let x = $d_1$$d_2$$d_3$ · · · $d_n$.

_Proof_: Lets say x = $d_1$$d_2$$d_3$ · · · $d_n$. This can be expanded to be the same as x = $d_1(10^{(n-1)}$) + $d_2(10^{(n-2)}$) + $d_3(10^{(n-3)}$) + · · · + $d_n(10^{n}$) where 1 ≤ i ≤ n and $d_i$ ∈ {0, 1, 2, . . . , 9} and $d_1$ $\neq$ 0...  Therefore each term in $\frac{{d_1(10^{(n-1)}) - 1 }}{9}$ + $\frac{{d_2(10^{(n-2)}) - 1 }}{9}$ + $\frac{{d_3(10^{(n-3)}) - 1 }}{9}$ + · · · + $\frac{{d_n(10^{(n)}) - 1 }}{9}$ + $\sum_{i = 0} ^ {n} {d_i}$ must be divisible by 9, which is equal to $d_1$$d_2$$d_3$ · · · $d_n$, this proves that 9 is a divisor of $d_1$$d_2$$d_3$ · · · $d_n$ when 1 ≤ i ≤ n and $d_i$ ∈ {0, 1, 2, . . . , 9} and $d_1$ $\neq$ 0.

###(b) 
_Claim_:  When $d_n$ = 0 or $d_n$ = 5, then 5 is a divisor of x.

_Proof_: Lets say x = $d_1$$d_2$$d_3$ · · · $d_n$, where x $\geq$ 5 and x ∈ $\mathbb{Z}$, because we are using base 10 to model our values, 10$^n$ will always be divisiable by 10 excluding n = 0, this proves that any integer that ends in a 0 or 5 where x $\geq$ 5 will be divisable by 5 because 5 is always divisable by 10. 


##Question 4

- Please prove or disprove: If n ∈ Z+, then n$^2$ + n + 41 is prime.

_Disproof_: when n = 42, the result of 42$^2$ + 42 + 41 = 1763, which is not prime.
