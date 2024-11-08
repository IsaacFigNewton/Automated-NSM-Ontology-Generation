#Ambiguity/Medium
#Relevance/Very_high

Fano, R. M. 1961. Transmission of Information: A Statistical Theory of Communications. MIT Press

- "ratio gives us an estimate of how much more the two words co-occur than we expect by chance"
- It's fine that it has a context length of 2, as word n-grams are represented in the binary grammar parse tree
- Why not PPMI:
	- "To distinguish whether two words whose individual probability is each 10^−6 occur together less often than chance, we would need to be certain that the probability of the two occurring together is significantly less than 10^−12, and this kind of granularity would require an enormous corpus. " *unless you can break the words into their component concepts and compare against similar concepts*
	- **Instead, you can apply information about higher or lower concepts in the hierarchy to determine associations or inverted associations** 
- Use modified calculation to reduce bias towards infrequent terms, with alpha designated by current research
	- Levy, O., Y. Goldberg, and I. Dagan. 2015. Improving distributional similarity with lessons learned from word embeddings. TACL, 3:211–225. 
	- a setting of α = 0.75 improved performance of embeddings on a wide range of tasks

[Previous](Edge-Regression-Process)