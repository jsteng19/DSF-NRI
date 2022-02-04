## NRI Group Update 1

## Team Information

**Members:**
- Sara Mandic
- Jake Stenger
- Nancy Zha

**Sponsor:**
- Stella Glasauer

**Mentor:**
- Megan Elcheikhali

**Research Lab:**
- Neuroscience Research Institute 

## Project Description:
This project aims to model neurodegeneration in brain organoids by single-cell RNA sequencing. Through the use of statistical methods we are aiming to compare differences in gene expression between control and mutant brain organoids. In addition we aim to identify cell populations that are more or less abundant in the mutant brain organoids. Thus, we are aiming to gain insight in disease mechanisms that lead to neurodegeneration. 

## Background: 
Listed below are some definitions and concepts that are relevant to our project. 

**Biological Terminology:**
- DNA: Carries the information to make a functional product (the protein) 
- RNA: Acts as a messenger to carry the information to the ribosome
- Protein: Functional units of cells that consist of amino acids
- Brain Organoids: Structures that can be grown in a dish that mimic aspects of the real human brain 
- Single Cell RNA Sequencing: Provides transciptional profiling of thousands of individual cells which allows people to understand at the single-cell level what genes are expressed, in what quantities, and how they differ across thousands of cells.
- MAPT mutations: 
  - Microtuble-associated protein tau 
  - causes heterogenous forms of frontotemporal lobar degeneration with taupathy (FLTD-Tau)
    - patients with FLTD-Tau exhibit a broad range of neurological deficits including movement and motor neuron disease

**Dimensionality reduction methods:**
- UMAP
  - uses graph layout algorithms to arrange data in low-dimensional space 
  - constructs a high dimensional graph representation of the data then optimizes a low-dimension graph to be as structrually similar as possible 
- t-SNE
  - nonlinear dimensionality reduction
  - mostly used to understand high-dimensional data and project it into low-dimensional space
  - finds a 2-dimensional mapping such that the difference in point-neigborhood distance is minimized across points



## Data Exploration
We haven't got our data yet and we are using the [pbmc](https://satijalab.org/seurat/articles/pbmc3k_tutorial.html) dataset from Seurat for simulations. In our real dataset, observations are single cells collected from scRNA-sequenced brain organoids. The organoids were generated using the "Pasca" method. Data collectors of the lab dissociated the organoids and utilized a technique called drop-seq to collect single cell transcriptomes data. 
The main variables of our data set are MAPT mutant and control organoids derived from different induced pluripotent stem cell lines. In total, we have 6 mutant lines and 5 control lines. THe 6 mutant lines include 3 V337M heterozygous mutant lines, 2 R406W heterozygous mutant lines, and 1 R406W homozygous mutant line. Another variable in the data set is different organoid ages with 2,3,4,6, and 8 months.

**References:**
1. Drop-seq technique: [Macosko et al. (2015). Highly Parallel Genome-wide Expression Profiling of Individual Cells Using Nanoliter Droplets. Cell, 161(5), 1202-1214.](https://doi.org/10.1016/j.cell.2015.05.002.)
2. Pasca method: 
[Pasca et al. (2015). Functional cortical neurons and astrocytes from human pluripotent stem cells in 3D culture. Nature Methods, 12, 671–678.](https://doi.org/10.1038/nmeth.3415) <br />
Yoon et al. (2019).Reliability of human cortical organoid generation. Nature Methods, 16, 75-78.](https://www.nature.com/articles/s41592-018-0255-0) 


## Technology
- R
- RStudio
- [Seurat](https://satijalab.org/seurat/index.html): Seurat is an R package designed for QC, analysis, and exploration of single-cell RNA-seq data. 

