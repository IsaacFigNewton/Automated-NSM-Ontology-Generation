#Ambiguity/High 
#Relevance/Very_high

Represent Learned association edges as qualifier vectors with a limited basis
Edges should have meaningful inversions
Positional encoding information contained in edge weights
## Primitives to use as a basis

#### Affective Meaning:
- Osgood, C. E., G. J. Suci, and P. H. Tannenbaum. 1957. The Measurement of Meaning. University of Illinois Press
	- valence: the pleasantness of the stimulus
	- arousal: the intensity of emotion provoked by the stimulus
	- dominance: the degree of control exerted by the stimulus

#### Quantity:
- **Intensifier, Augmentor**
	- very
	- more
- **Quantifiers**
	- one
	- two
	- some
	- all
	- much / many
	- little / few
- - **Descriptors**: Modify "size" primitive node
	- big
	- small
#### Similarity:
- **Similarity**
	- like
	- as
	- way
- **Determiners**
	- this
	- the same
	- other / else / another
#### Hierarchy:
- **Relational Substantives**
	- kind
	- part
- **Existence, Possession**:
	- be (somewhere)
	- there is
	- be (someone/something)
	- (is) mine
#### Mental Predicates:
- think
- know
- want
- feel
- see
- hear

- Edges as augmentors in different encoding methods
	- Instead apply edge vectors as transformation measures:
		- [Use group theory to determine suitable transformations/operations](Group-Theory-Approach)
	- [Positional Encoding](Positional-Encoding)




[Previous](Embedding-Text-as-Ontology-Subgraph-Activations)
[Training Process](Edge-Regression-Process.md)