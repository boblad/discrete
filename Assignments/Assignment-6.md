#Assignment 6#
#Bryant Oblad#
#A01770171#

##Question 1##
Let P denote the Petersen graph.
 
- Compute τ(P), the complexity of P, i.e., the number of spanning trees in P.
-  Define P to be the Petersen graph with an edge removed. Compute τ(P'). Argue that τ(P') does not
depend on which edge you delete. (800)
- Define P to be the Petersen graph with two edges removed. Compute τ(P''). Does τ(P'') depend on which two edges are deleted? (648) (240)

(A) To see the matrix and labels used in this calculation, See the attached image on the back of this assignment. If we remove the first row and the first column of the petersen graph matrix, where each diagonal value of the degree matrix is equal to 3 and and -1 defines the existance of an edge between 2 nodes. We find that the determinant of the derived matrix (which is a Laplacian matrix) is equal to 2000 spanning trees.

(B) I found that if we remove one edge of the petersen graph (denoted as τ(P')  ) and compute the laplacian matrix, we see that τ(P') will always be equal to 800 spanning tree's. It does not matter because it is impossible to tell 2 points apart because every degree matrix is equal to 3.

(C) Let a peterson graph with 2 edges removed be denoted as τ(P'') , Calculating the laplacian matric of τ(P'') with come out to either 648 or 240 total spanning tree's. We get 240 spanning tree's if the removed edges are adjacent to the same node, and if the 2 removed edges are not adjacent through any node we will get 648 spanning trees.


##Question 2##

The trace of a (square) matrix is the sum of its diagonal entries. Let G be a graph and A its adjacency matrix. Show that the trace of A$^3$ is 6t, where t is the number of K3s in the graph G.

k3 has to have 3 walks, k3 has 6 different walks, 

_Theorem_:
Suppose G is a graph and V(G) = {v1, v2, . . . , vn}. Then if A is the adjacency matrix of G, entry (i, j) in Ak is the number of walks of length k from vi to vj.

_Claim_:
The trace of A$^3$ is 6t where t is the number of K3s in the graph G.

_Proof_: If we refer to Figure 2 in the attached sheet on the back I show how to interpret A which is the matrix representation of G. The diagonal values of A is the trace of A. If we use the theorem stated above we can prove that A$^2$ has 2 walks, and A$^3$ has 3 walks. If we disect a k$_3$ from G, lets use the {a, b, c} K$_3$, (Refer to figure 2.2) we notice that there are 2 ways to travel back to any node a while going through all other nodes in the K$_3$. If we do this for each node in the K$_3$ we see that there are two ways to travel back to the starting node for every available node. Because we can guarentee this pattern we see that a K$_3$ has 2 possiblities for each walk making a K$_3$ having 6 different walks. This proves that A$^3$ is 6t where t is the number of K3s in the graph G.


