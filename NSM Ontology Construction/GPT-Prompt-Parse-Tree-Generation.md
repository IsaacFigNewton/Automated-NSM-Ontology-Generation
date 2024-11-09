[Syntax tree generator](https://mshang.ca/syntree/)

Please parse the following into a grammar parse tree, written similar to a LISP AST, but with brackets denoting a subtree node instead of parentheses and use the following symbols:
S for sentence, the top-level structure in this example.
NP for noun phrase. The first (leftmost) NP, a single noun *John*, serves as the subject of the sentence _John hit the ball_. The second one is the object of the sentence.
VP for verb phrase, which serves as the predicate.
V for verb. In this case, it's a transitive verb hit.
D for determiner, in the instance of _John hit the ball_ the definite article is *the*.
N for noun.
A for adjective.

Example response: [S [NP This] [VP [V is] [^NP a wug]]

Parse this: "something I think is very good and not the same as many other things and looks or feels or sounds very good"

[Previous](Text-to-Ontology)