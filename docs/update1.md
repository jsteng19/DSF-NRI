## Data Exploration
We haven't got our data yet and we are using the [pbmc](https://satijalab.org/seurat/articles/pbmc3k_tutorial.html) dataset from Seurat for simulations. In our real dataset, observations are single cells collected from scRNA-sequenced brain organoids. The organoids were generated using the "Pasca" method. Data collectors of the lab dissociated the organoids and utilized a technique called drop-seq to collect single cell transcriptomes data. 
The main variables of our data set are MAPT mutant and control organoids derived from different induced pluripotent stem cell lines. In total, we have 6 mutant lines and 5 control lines. THe 6 mutant lines include 3 V337M heterozygous mutant lines, 2 R406W heterozygous mutant lines, and 1 R406W homozygous mutant line. Another variable in the data set is different organoid ages with 2,3,4,6, and 8 months.

**References:**
1. Drop-seq technique: [Macosko et al. (2015). Highly Parallel Genome-wide Expression Profiling of Individual Cells Using Nanoliter Droplets. Cell, 161(5), 1202-1214.](https://doi.org/10.1016/j.cell.2015.05.002.)
2. Pasca method: -[Pasca et al. (2015). Functional cortical neurons and astrocytes from human pluripotent stem cells in 3D culture. Nature Methods, 12, 671–678.](https://doi.org/10.1038/nmeth.3415)
                 -[Yoon et al. (2019).Reliability of human cortical organoid generation. Nature Methods, 16, 75-78.](https://www.nature.com/articles/s41592-018-0255-0) 


## Technology
- R
- RStudio
- [Seurat](https://satijalab.org/seurat/index.html): Seurat is an R package designed for QC, analysis, and exploration of single-cell RNA-seq data. 

