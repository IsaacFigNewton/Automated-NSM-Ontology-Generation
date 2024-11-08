#Ambiguity/Low
#Relevance/Very_high

Formalize grammar of primitive-based English (the natural semantic metalanguage)
- Use [Chomsky Normal Form (CNF)](https://en.wikipedia.org/wiki/Chomsky_normal_form)

[Parsing issues and proposed solutions](Parsing-Issues)

Translate word tokens into primitive English, written using only primitives
- Parse English text into a **Context-Free Grammar (CFG) constituency-based parse tree**
	- See [Penn Treebank](https://catalog.ldc.upenn.edu/docs/LDC95T7/cl93.html)
	- Edges in the parse tree should be of the same composition as edges in the learned ontology
- Without context, terminals have ambiguous meaning
	- The terminals' nodes should contain only the terminals' values "cat", etc.

Terminals can be further broken down with lemmatization, then(?) stemming:
- Create grammar parse trees for English-specific grammatical artifacts, such as tense, ownership, etc.
	- Parse into primitive phrases, stems
- Stems are to be further broken down for ontology generation


[Previous](Text-to-Ontology)
[Map primitive English to an ontology language?](Primitive-English-to-Ontology-Language.md)
[Ontology creation with subgraph activations](Embedding-Text-as-Ontology-Subgraph-Activations)
