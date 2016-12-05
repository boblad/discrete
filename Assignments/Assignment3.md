#Homework 3#

#Bryant Oblad A01770171#

##Problem 1##
Prove that the following game must have a winner. Place 6 dots equally spaced on a circle on a piece of paper. Player A has a red marker and Player B has a blue marker. Players take turns connecting pairs of dots with line segments using their respective colored markers, only one line segment between any two dots (therefore at most 15 line segments will be drawn). The winner is the first to connect three dots mutually with their respective color, that is, the rst to create a monochromatic "triangle" in their marker's color.

_Claim_: The game described above will always have a winner.

_Proof_: Lets say that every possible line in the game has been used, all 15 lines. Lets disect a single point A and notice that there are 5 lines that go into point A, For point A there must be one player that has 3 - 5 lines going into point A, this is true for all 6 points in the game. For any line coming into point A as the player that has the most lines coming into point A (lets say player 1). Any connection between the sources of the lines coming into A from player 1 will signal a win. If the relationships between the sources of lines coming into point A from player 1 are blocked this proves that player 2 will be the winner through the availability of lines. This proves that there will always have a winner in this game.




##Problem 2##
Consider the following sets: $\mathbb{N}$, the set of nonnegative integers; E, the set of even integers (negative ones too); $\mathbb{Z}$, the set of integers.

- Please prove that each of the sets $\mathbb{N}$, E, and $\mathbb{Z}$ are infinite.
- Please prove that the sets $\mathbb{Z}$ and E have the same cardinality.


_Claim_: $\mathbb{N}$, E, and $\mathbb{Z}$ are infinite as well as the sets $\mathbb{Z}$ and E have the same cardinality.

_Proof_: By definition set X is infinite if there exists a bijection from a proper subset of X to X. In order to have a bijection every instance in the set X must have an inverse, 1 to 1 relationship and be "onto", onto meaning that a function lets say f: A $\rightarrow$ B, and f$^{-1}$: B $\rightarrow$ A, for f(f$^{-1}$(a)) = a and f(f$^{-1}$(b)) = b where a, b  ∈ $\mathbb{N}$, E, $\mathbb{Z}$. To prove that the positive integers of $\mathbb{Z}$ is a proper subset of $\mathbb{Z}$, there exists a bijection between the 2 sets because of the existance of the function f: the positive integers of $\mathbb{Z}$, lets say $\mathbb{Z^+}$ and $\mathbb{Z}$. For $\mathbb{N}$ and E there exists a proper subset because of an onto relationship $\mathbb{N}$ has to $\mathbb{Z^+}$, also E has an onto relationship with $\mathbb{Z}$ by proof on inverse.

Each set $\mathbb{N}$, $\mathbb{Z^+}$, and E all have the equal cardinality, to prove this with the definition of equal cardinalities, (2 sets A and B have equal cardinality "denoted card(A) = card(b)" if there exists a bijection from A to B), and for each set $\mathbb{N}$, $\mathbb{Z^+}$, and E, there exists a bijection for each as stated in the above paragraph by proof of inverse, which proves equal cardinality between card($\mathbb{N}$) = card($\mathbb{Z^+}$) = card(E)

##Problem 3##
Please prove the open interval (0, 1) = {x ∈ $\mathbb{R}$ : 0 < x < 1} does not have the same cardinality as $\mathbb{N}$.

_Claim_: The open interval (0, 1) = {x ∈ $\mathbb{R}$ : 0 < x < 1} does not have the same cardinality as $\mathbb{N}$ .

_Proof_: To prove that the open interval (0, 1) = {x ∈ $\mathbb{R}$ : 0 < x < 1} does not have the same cardinality as $\mathbb{N}$, I will use an indirect proof. My indirect proof has the claim that the open interval (0, 1) = {x ∈ $\mathbb{R}$ : 0 < x < 1} has the same cardinality as $\mathbb{N}$. For the cardinality to be equivelant in both sets, lets say set A is the open interval on (0, 1) = {x ∈ $\mathbb{R}$ : 0 < x < 1}, and B ∈ $\mathbb{N}$, by definition there needs to exist a bijection from A to B for equivelant cardinality to exist. In order to have a bijection the inverse of each instance of our function must exist. In the table below I lay out the idea that there will never allow an "onto" or surjective relationship.

|$\mathbb{N}$| (0, 1) |
|:----------:|:------:|
|  0  | 0.d$_{01}$d$_{02}$d$_{03}$d$_{04}$..... |
|  1  | 0.d$_{11}$d$_{22}$d$_{33}$d$_{44}$..... |
|  2  | 0.d$_{21}$d$_{22}$d$_{23}$d$_{24}$..... |

Lets say that if we add the integer 1 to each d$_{xy}$, this will create a new unique set of integers for each instance of $\mathbb{N}$ this proves that there is no surjective relationship which proves there is no onto function or therefore no bijection. Because there is no bijection the set A and set B do not have equivelant cardinalities.