[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Being isomorphic only means that two graphs need to map onto one another in terms of edges and nodes. They also need to be one to one. A graph does not necessarily need to have any edges though. 
If we consider G1 and G2 to be two disconnected graphs with 3 vertices and no edges connecting them, then we only need to consider the number of vertices in the graphs. The set of edges of both graphs are an empty
set which have a bijective relationship. So as long as the nodes of the graphs map onto one another in a one-to-one function, the two graphs are isomorphic. For example, G1 has the nodes A, B, and C, and G2 has
the nodes 1, 2, and 3. As long as there exists no edges in both graphs, and they map onto each other like so:

A -> 1
B -> 2
C -> 3 

Or any mapping with a bijective relationship, then G1 and G2 are isomorphic without being completely connected.

