# Random_Walk
SDSC 3001 Assignment


$ d_v $ -> degree of the node $v$ which is the number of neighbour nodes of $v$ in the graph

$ n_v = d_v/D $ -> normalized degree of $v$ where $D= \sum _vd_v $ is the sum of the degrees of all nodes

$M$ -> number of steps in random walks, with process as follow:

1) Starting point is randomly selected, hence each node being selected as starting point has probability $1/|v|$ where $V$ is the set of all nodes

2) At each step, randonmly jump to a neighbour node of the current node. Let $m_v$ be the number of time that $v$ is visited in the random walk.

Denote $f=(f_1,f_2,....,n_|v|)$ be the empirical frequency vector where $f_v = m_v/M$.

Let $n=(n_1,n_2,...,n_|v|)$ be the normalized degree vector.

The program below will stimulate the above random walk and calculate $l_1 - distance$ between $n$ and $f(|n-f|_1 = \sum_v |n_v - f_v|)$.
