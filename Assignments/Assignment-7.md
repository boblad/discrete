#Assignment 7#
#Bryant Oblad A01770171#

##Question 1##
Place n points on a circle so that the chords drawn by connecting each pair of points are such that no three chords intersect at a point inside the circle (if n ≥ 4, then every point on the circle will be incident to three or more chords). Determine a closed formula for the number of regions inside the circle created by the chords and the circle. (Understanding check: If there are 3 points on the circle, there are 4 regions created by the chords and the circle; if there are 4 points on the circle, 8 regions are created.)

_Claim_: ($\frac{n!}{2 (n - 2)!}$) + ($\frac{n!}{ 24(n - 4)!}$) + 1 is a closed formula that gives the maximum number of regions inside a circle with chords and a circle where n is a point on the circle that is a connecting pair of points. 

_Proof_: ${n}\choose{2}$ symbolfies the relationship between each drawn line for every point n. Each point of intersections (lets say i), adds another region, which will be regions = i + 1 for every additional region. Then the total amount of intersections can be defined as ${n}\choose{4}$ because we have one intersection for every 4 points placed on the circle. If we add all of these sections up together we come to the equation ${n}\choose{2}$ + ${n}\choose{0}$ + ${n}\choose{4}$. By the definition of the binomial coefficent ($\frac{n!}{i! (n - i)!}$) we can state the equation as ($\frac{n!}{2 (n - 2)!}$) + ($\frac{n!}{ 24(n - 4)!}$) + 1

##Question 2##
Number of shortest paths using the city-block metric. Consider only the points of the Cartesian coordinate system with nonnegative integer coordinates. The distance between two points (x1, y1) and
(x2, y2) using the city block metric is |x1 − x2| + |y1 − y2|. Count the number of shortest paths from (0, 0) to (X, Y), where X, Y ∈ N. An alternative perspective to this problem is to count paths from (0, 0) to (X, Y)
using steps of the form L : (x, y) → (x + 1, y) or U : (x, y) → (x, y + 1).

_Claim_: Using Pascals triangle we can and find the count of shortest paths between (x$_1$, y$_1$) and (x$_2$, y$_2$) will be equal to the equations ${r + c}\choose{r}$ or ${r + c}\choose{c}$

_Proof_: If we refer to the actual distance between point a and point b, The shortest distance will always be the hypotnuse of the pathagorean theorem. However this would not be using the city-block metric, Therefore we can always guarentee that the required distance to travel will always be more than the hypotunese length. In the prompt above we are given that |x1 − x2| + |y1 − y2| gives the shortest distance between two points using the city-block metric. To find the total count of shortests paths between point a and b we need to know how many rows and how many columns are used, where rows, lets say r = |y1 − y2| and columns, lets say c = |x1 − x2|. If we look at these equations, we see that ${r + c}\choose{r}$ and ${r + c}\choose{c}$ will always return in the same result, this equation is a reflection of Pascals triangle. By proof on induction we can conclude that for any situation the count of shortest paths between two points is equal to ${r + c}\choose{r}$ or ${r + c}\choose{c}$


##Question 3##
Determine a closed formula for the nth term of the sequence (L$_i$)$_i$ ≥ 0, where L$_n$ is recursively defined via L$_n$ = L$_n$−1 + L$_n$−2, for n ≥ 2, and with L$_0$ = 2 and L$_1$ = 1.

In class we were given the Charactoristic equation q$^2$ - q - 1 = 0, Therefore we can use L$_n$ = q$_n$
If we use the Quadratic formula on the Charactoristic equation we get ($\frac{1 + \sqrt{5}}{2}$).

Because L$_n$ = L$_n$−1 + L$_n$− 2 and L$_n$ = q$_n$ we can derive that q$_n$ = A($\frac{1 + \sqrt{5}}{2}$)$^n$ + B($\frac{1 - \sqrt{5}}{2}$)$^n$ 

Now for the instances of L$_0$ = 2 and L$_1$ = 1 we can evaluate A and B to evaluate L$_n$.

q$_0$ = 2 = A($\frac{1 + \sqrt{5}}{2}$)$^0$ + B($\frac{1 - \sqrt{5}}{2}$)$^0$

q$_1$ = 1 = A$(\frac{1 + \sqrt{5}}{2}$)$^1$ + B($\frac{1 - \sqrt{5}}{2}$)$^1$

We can conclude that the closed formula for the nth term of the sequence (L$_i$)$_i$ ≥ 0 is L$_n$ =  ($\frac{1 + \sqrt{5}}{2}$)$^n$ + ($\frac{1 - \sqrt{5}}{2}$)$^n$