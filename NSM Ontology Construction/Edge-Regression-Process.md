#Ambiguity/High
#Relevance/Very_high

Probabilistically determine word association
- strengths
- relationships
- frequencies
- other edge qualia dimensions

Approaches for determining strength of association:
- [Pointwise mutual information (PMI) extraction approach](Modified-PMI-Association-Embedding-Approach.md)
	- How to modify for different aspects of word associations?
- maybe also combine with specific grammar parse tree variation to determine co-occurrences within different context branches?

Encourage sparse activations to make the primitive combinations interpretable.
	• Penalize unlikely primitive combinations based on a predefined coherence matrix or learned during training.
	• Soft constraints guide the model toward interpretability without hindering performance.

[Previous](Ontology-Edge-Representation)