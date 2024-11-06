Ambiguity: Extremely high

Adjust positional encoding method to fit primitive-base ontological representation
- Use a separate positional embedding matrix and add it to the primitive embeddings.
- Represent positional coding as a series of edge vector-dependent transformations applied to nodes' primitive embeddings as the subgraph representing a text is traversed?
- More traditional approaches:
	- Use sine, cosine approach as in multi-head attention layer of current models?
	- [RoPE?](https://arxiv.org/abs/2104.09864)

[Previous](Ontology-Edge-Representation)