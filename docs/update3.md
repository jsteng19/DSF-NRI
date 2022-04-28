
## NRI Group Update 3

## Current Efforts 
In the past month we have spent a lot of our time performing different [methods??, experiments??] on our data. Primarily we started off by using sctransform to normalize our data in order to recover sharper biological distinction compared to log-normalization. After doing so we performed dimensionality reduction by PCA and UMAP embedding as mentioned in update 2. Then we continued by performing differential expression tests on our data. We were testing differential expression between the mutant and the control cell groups specifically the 337VM, 406RW, and 406WW mutations (The 337VM mutation is 3 lines, 406RW is a 2 line mutation and 406WW is a 1 line mutation). 

## Findings

## Future Work
We have broken up our future on a week by week basis in order to keep ourselves accountable and have concrete deadlines for ourselves. 
- Week 5: 
  - We will finish working with DE 
  - We will introduce Monocole3 
    - Monocle3 can help you perform three main types of analysis:
      - Clustering, classifying, and counting cells. Single-cell RNA-Seq experiments allow you to discover new (and possibly rare) subtypes of cells. Monocle 3 helps you identify them.
      - Constructing single-cell trajectories. In development, disease, and throughout life, cells transition from one state to another. Monocle 3 helps you discover these transitions.
      - Differential expression analysis. Characterizing new cell types and states begins with comparisons to other, better understood cells. Monocle 3 includes a sophisticated, but easy-to-use system for differential expression.
- Week 6: 
  - We will wrap up Monocole3 trajectory analysis
  - We will introduce WGCNA
    - Weighted correlation network analysis (WGCNA) can be used for finding clusters (modules) of highly correlated genes, for summarizing such clusters using the module eigengene or an intramodular hub gene, for relating modules to one another and to external sample traits (using eigengene network methodology), and for calculating module membership measures. 
- Week 7: 
  - We will continue working with WGCNA
- Week 8:
  - We will wrap up with WGCNA
- Week 9/10:
  - Wrap up everything
    - look at all the results we have from DE, Metascape, Monocle3, WGCNA
  - Start finalizing presentation and poster 
  - Practice for presentation
