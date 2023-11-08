[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12578207&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## My Response
Let $A$ and $B$ both be graphs that have the same number of nodes and are each completely connected.  Then let $f$ be a function that maps $A$ onto $B$ such that each node in $A$ maps to only one node in $B$.  Then this function is both one to one as well as onto which satisfies the need for bijection.  And since both graphs are completely connected there will always be an edge in $A$ that corresponds to an edge in $B$.  
$\therefore$ Two graphs $A$ and $B$ must be isomorphic if they have the same number of nodes and are each completely connected.
