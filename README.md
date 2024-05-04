[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## My proof

By the definition of a bijection, we know that each node in the set of nodes $V_1$ from the graph $G_1$ needs to be paired with exactly one node in the set of nodes $V_2$ from the graph $G_2$. If one of the graphs were to have more nodes, we would not be able to complete the bijection because there would be an extra node that didn't have a pair in one of the graphs. This would create a situation where if $V_1 < V_2$ then there would be elements in $V_2$ that aren't mapped to and if $V_1 > V_2$, then there will be no more elements in $V_2$ to map to.





















