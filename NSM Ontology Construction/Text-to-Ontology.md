#Root
#Ambiguity/Very_high 
#Relevance/Very_high

More interpretable means:
- Easier for governments to regulate
- Easier to mitigate [representational harm](https://arxiv.org/abs/1607.06520)
"dense vectors work better in every NLP task than sparse vectors."
This will only apply to formal english with a 

Embedding process:
1. Break text into context-free grammar parse tree variations based on ambiguities in the structural interpretation
[Syntax tree generator](https://mshang.ca/syntree/)
[Parse tree rules](https://en.wikipedia.org/wiki/Parse_tree)
![[Pasted image 20241108151723.png]]
2. Assigning a likelihood to each parse tree variation  
3. Decompose terminals representing compound words into prefixes, suffixes, lemmas in additional parse trees
![[Pasted image 20241108160634.png]]
5. Decompose prefixes, suffixes, and lemmas into their various definitions as appropriate for the current context, using only semantic primitives
[GPT prompt for creating a primitive definition for a concept](GPT-Prompt-Describe-Using-only-Primitives)
**beauty ==>** When people see something and think it is very good. They feel very good inside because of it. They want to see it more because it makes them feel very good.
**ful        ==>** Something is like that thing or full of it.
7. Assigning likelihoods to different possible definitions  
8. Finally, create grammar parse trees for the semantic primitive-based concept descriptions using a reduced grammar composition ruleset
[GPT prompt for parsing into grammar parse tree](GPT-Prompt-Parse-Tree-Generation.md)
Beauty:
![[Pasted image 20241108155242.png]]
-ful:
![[Pasted image 20241108155331.png]]

Build an ontology with the following properties:
- Vertex properties:
	- Only value-holding nodes are semantic primitive nodes
	- All non-primitive concept nodes are ultimately defined by a fixed set of semantic primitive nodes
	- Neighboring slightly-lower-order concept nodes should be used to construct other concept nodes
- Edge properties:
	- Represent Learned association edges as qualifier vectors with a limited basis, representing primitive concept modifiers (quantity, similarity, etc.)
	- Edges should have meaningful inversions
	- Positional encoding information must be contained in edge weights

[Traditional/similar ontological generation approaches](Existing-Ontology-Generation-Approaches.md)

[Custom approach](Create-Bijective-Mapping-to-Primitive-English-Grammar.md)