# Galway-Genomics

## Code
This directory contains code used to generate read counts using Hisat2 & Stringtie. 
Mapping stats for each sample is provided under 'Hisat stats'.
R code used to generate Quality Control plots, Heatmaps are also stored here. 

## DESeq2
This directory contains all genes falling under a significant P value (0.05) and Adj P value (0.1)
For Control samples, Treated samples, and then Merged samples.
Control and Treated are contrasting S2+ vs. WT.
Fold Change in the excel sheets is in reference to WT. 

Merged samples, the contrast is Treated vs. Control, AdjVars = 'Type' (S2+ vs WT). 
Again, Fold Change is in relation to WT

log2FC == posiitve numbers indiciate upregulation in WT
          negative numbers indicate upregulation in S2+ 
