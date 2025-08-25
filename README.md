This repository contains all files for the RNA sequencing analyses performed in the Nature Communications Biology manuscript (DOI: __________).

The method for differentially expressed gene (DEG) determination was edgeR using the open-source R/BioConductor software.29 EnrichR and clusterProfiler (Gene Ontology: Biological Process) were used to detect pathway-level differences among sample sets.
Sample NG-A0648_31 was determined to be an outlier and removed. 
The effects of separate RNA isolation dates were treated as covariates and batch-corrected using the ComBat normalization method.
