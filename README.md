# causal-discovery

## classification of CD methods

### 1. Score-based
- generate a number of candidate causal graphs, assign a score to each, and select a final graph with the highest score. (combinatoric & search base)

### 2. Constraint-based algorithms 
- construct the causal structure based on conditional independence constraints, 
- may more fit to current DL algorithms
- written by ElementAI https://arxiv.org/abs/2007.01754

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

- Evaluation Metric for Causal Discovery
   - <img width="992" alt="Screen Shot 2021-08-02 at 7 38 28 PM" src="https://user-images.githubusercontent.com/21968222/127848920-a63643e1-86de-4ccd-ac73-6e32135b2b4d.png">



## Key Terms
- Structural Causal Models
   - The existence of a directed edge from A to B indicates that intervening on A directly impacts B, and the absence of an edge indicates no direct interventional
impact (see Appendix B for formal definitions). (* Does this explanation exclude Confoudings?)
   - <img width="967" alt="Screen Shot 2021-08-01 at 11 11 11 PM" src="https://user-images.githubusercontent.com/21968222/127773977-400103e1-d185-41f7-ac97-47e82f8eaba1.png">

- Definition of Model Based RL (MBRL)
   - <img width="342" alt="Screen Shot 2021-08-02 at 12 28 21 PM" src="https://user-images.githubusercontent.com/21968222/127800707-8b5648ca-6042-414f-b490-201727083a40.png">
  
## Application
### Analogy of Supply Chain to Causal Relations between Commodities 
- Input A -> Output B interpreted as Causal Relation.
   - Most Causal Discovery literatures set acyclicity but Supply Chain is't necessarily acyclic. 

- (Emprical) How's the output result causal graph discovered by current literature over SuppChian 
   - Does it reflect the Ground Truth well?   
   - (Corr vs Casuation) Soybean -> fed to -> Pig (and) Pig -> proceessed into -> Lad, Soybean will have correlation with Lad, however, that's not interpreted as direct neighbor in terms of SupplyChain


