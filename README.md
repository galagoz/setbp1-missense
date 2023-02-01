# Code for manuscript "SETBP1 variants outside the degron disrupt DNA-binding and transcription to cause a heterogeneous neurodevelopmental disorder"

`rnaseq-analysis.Rmd` is an Rmarkdown file with multiple chunks of code which will read bam files, create a count table, prepare the data for DE analysis, perform DE analysis and visualize the results. The script has in-code comments explaining each step. Users must adapt the script (input and output paths) to their own data and research purposes. 

`custom_plotPCA.R` script is a slightly edited version of the generic `plotPCA` function of DESeq2, which allows plotting additional PCs to PC1 and PC2.

Codes for count table generation and differential gene expression analysis were adapted from manual of the Seminar and Practical course "Computational analysis of RNA-Seq data" (LMU Munich).

Please contact goekberk.alagoez@mpi.nl and maggie.wong@mpi.nl for questions.
