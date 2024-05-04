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

We know that by definition, isomorphic graphs must have a one to one relationship where there must be the same amount of nodes and the relations that each node has must have a node in the other graph with comparable relations.

let A = (V,E)(V = {a, b}  with  E = {a,b})

let B = (V,E)(V = {d, e, f}  with  E = {{d,e},{d,f},{e,f}})

to check for isomorphism we can check the relationships that each graph has

when we try to check this, we see that {a, b} $\neq$ {d, e, f} because A has one less vertex than B.

This example doesnt comply to the fomal definition of isomorphism $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$. because in this example $(f(u),f(v)) \notin E_2$

This shows that you cant have the different number of nodes becasue each node in A needs to be represented in B but that cant happen if B has more nodes.





















