# SETBP1 missense variants project

Script for bulk RNA-seq data analysis of SETBP1 missense variants.

**Differential gene expression analysis:**
`rnaseq-analysis.Rmd` is an Rmarkdown file with multiple chunks of code which will read bam files, create a count table, prepare the data for DE analysis, perform DE analysis and visualize the results. The script has in-code comments explaining each step. Users must adapt the script (input and output paths) to their own data and research purposes.

`custom_plotPCA.R` script is a slightly edited version of the generic `plotPCA` function of DESeq2, which allows plotting additional PCs to PC1 and PC2.


Please contact goekberk.alagoez@mpi.nl and maggie.wong@mpi.nl for questions.
