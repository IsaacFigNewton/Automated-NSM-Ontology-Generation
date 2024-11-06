- Represent words as subgraphs of nodes that have been “activated” within the ontology
- Represent Learned association edges as qualifier vectors, with 1 dimension for each form of qualia
	- ex: degree of membership/ownership to another node’s concept, degree of desire for other node’s concept, similitude, etc.
- Don’t use positional encoding for intensifiers or similarity encoding, instead multiplying or otherwise increasing similitude dimension of all edge associations
- Decide which words act as edge vector dimensions, which act as dimensions

- Represent conditional logical operations with ambiguous solutions as follows:
	- Activation or deactivation of input nodes, semi-activation of ambiguous nodes
	- Activate resultant node/s based on likelihood of input outcome

[Next](Extrapolating-Embeddings-to-Subtokens.md)