#Root
#Ambiguity/Very_high 
#Relevance/Very_high

"dense vectors work better in every NLP task than sparse vectors."
This will only apply to formal english with a 

Parsing down to core concepts:
1. Break text into grammar parse tree variations
	1. Use formal English grammar grammar composition ruleset
	2. Handle ambiguity by only "partially activating" associated nodes
2. Decompose compound words into prefixes, suffixes, lemmas in syntactic parse tree
3. Probabilistically decompose prefixes, suffixes, and lemmas into likely definitions using only semantic primitives
	1. Stuck here
	2. Handle context ambiguity by only "partially activating" associated nodes and regressing edge values more or less, as appropriate
4. Create grammar parse tree for the semantic primitive-based concept descriptions
	1. Use primitive Natural Semantic Metalanguage (NSM) grammar composition ruleset
6. "Activate" each primitive's node proportional to the weighted/transformed activations passed down through the hierarchical representation
	1. What should these transformations look like?
	2. Represent the whole text embedding as the combination of the semantic primitives' orthogonal vectors	   



Build an ontology with the following properties:
- Vertex properties:
	- Only value-holding nodes are semantic primitive nodes (though for speed, higher-order concept nodes could save their associated vectorizations)
	- All non-primitive concept nodes are ultimately defined by a fixed set of semantic primitive nodes
	- Intermediate, higher-order concept nodes can (and should) be used to construct other concept nodes
- Edge properties:
	- Represent Learned association edges as qualifier vectors with a limited basis, representing primitive concept modifiers (quantity, similarity, etc.)
	- Edges should have meaningful inversions
	- Positional encoding information contained in edge weights

[Traditional/similar ontological generation approaches](Existing-Ontology-Generation-Approaches.md)

[Custom approach](Create-Bijective-Mapping-to-Primitive-English-Grammar.md)