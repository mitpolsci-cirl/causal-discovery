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

## Lits
- Causal Discovery
   - https://arxiv.org/pdf/2103.02582.pdf
   - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6558187/
   - https://www.nature.com/articles/s41598-020-59669-x


## discussable issue:
- Causual Discovery and Useo of Observational Data, or Including Interventional Data.
- Causal Induction - Fine line between Causal Discovery
   - "Methods are needed to automate the inference and identification of such causal variables (i.e. causal induction) from low-level state
representations (like images)." (https://arxiv.org/pdf/2107.00848.pdf)
