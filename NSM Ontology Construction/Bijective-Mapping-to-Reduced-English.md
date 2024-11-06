
Formalize grammar of reduced English (the natural semantic metalanguage)
- Use lemmatization, stemming to parse tense, ownership, other English-specific grammatical artifacts
- Create grammatical structure for undecomposed lemmatized/stemmed words

Translate word tokens into basic English, written using only primitives
- Maybe bootstrap by prompting existing LLM models?
- Use contextual clues to determine lemma/stem meanings for lemma/stems
	- Take “X” for example; https://chatgpt.com/share/672977ac-e414-800a-8391-a33649218b5b
	- Aggregate all sentences/documents containing a word
	- Break down each sentence into its semantic components, identifying the relationships to the word
	- Examine how "X" is used in each sentence to gather clues about its possible meaning
	- Determine the semantic roles "X" plays in the sentences

[Next](Embed-the-ontology-subgraph.md)