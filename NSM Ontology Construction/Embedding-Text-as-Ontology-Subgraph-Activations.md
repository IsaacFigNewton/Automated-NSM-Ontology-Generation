#Ambiguity/Very_high
#Relevance/Very_high

Represent words as subgraphs of nodes that have been “activated” within the ontology
- Start with primitive dimensions
- Progressively aggregate/form each dimension of the word’s final embedding with respect to the primitive basis by combining/transforming nodes based on their associations

![[Pasted image 20241107131633.png]]

Decide which words act as edge vector dimensions, which act as concept embedding space dimensions
- Ultimate embedding should be a vector with <65 dimensions representing a location in the concept space (defined by permutations of the vertex basis concepts)
	- <65 dimensions because some of the 65 semantic primes are augmenters (edge/transformation vector dimensions)
- [Vertex Descriptors](Ontology-Vertex-Representation)
- [Edge Descriptors](Ontology-Edge-Representation.md)

## Logic
- Logical Concepts:
	- maybe
	- can
	- because
	- if
- Represent conditional logical operations with ambiguous solutions as follows:
	- Activation or deactivation of input nodes, semi-activation of ambiguous nodes
	- Activate resultant node/s based on likelihood of input outcome


[Text parsing](Create-Bijective-Mapping-to-Primitive-English-Grammar)
[English to an ontology language](Primitive-English-to-Ontology-Language.md)
[Next](Extrapolating-Embeddings-to-Subtokens.md)

[Visualization design](Ontology-Visualizations.md)
[Decoding](Decoding-Embeddings.md)