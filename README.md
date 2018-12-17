# Galway-Genomics

## Code
This directory contains code used to generate read counts using Hisat2 & Stringtie. <br/>
Mapping stats for each sample is provided under 'Hisat stats'.<br/>
R code used to generate Quality Control plots, Heatmaps are also stored here. <br/>

## DESeq2
This directory contains all genes falling under a significant P value (0.05) and stricter Adj P value (0.1) For Control samples, Treated samples, and then Merged samples.<br/>
Control and Treated are contrasting S2+ vs. WT.<br/>
Fold Change in the excel sheets is in reference to WT. <br/>
(positive = upreg in WT, negative = upreg in S2+) <br/>

Merged samples, the contrast is Treated vs. Control, AdjVars = 'Type' (S2+ vs WT). <br/>
Again, Fold Change is in relation to WT<br/>

