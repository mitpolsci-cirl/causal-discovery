# causal-discovery
Literature about causal discovery


## analogy of SuppChain to Causal Relations
- Input A -> Output B interpreted as Causal Relation.
   - Any loophole in this relationship?

- (Emprical) How's the output result causal graph discovered by current literature over SuppChian 
   - Does it reflect the Ground Truth well?   
   - (Corr vs Casuation) Soybean -> fed to -> Pig (and) Pig -> proceessed into -> Lad, Soybean will have correlation with Lad, however, that's not interpreted as direct neighbor in terms of SupplyChain

## methodological class

### score-based
- generate a number of candidate causal graphs, assign a score to each, and select a final graph based on the scores. (combinatoric & search base)

### constraint-based algorithms 
- construct the causal structure based on conditional independence constraints, 
- may more fit to current DL algorithms

## Refs

https://arxiv.org/pdf/2103.02582.pdf
