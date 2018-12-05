# Galway-Genomics

## Code
This directory contains code used to generate read counts using Hisat2 & Stringtie. <br/>
Mapping stats for each sample is provided under 'Hisat stats'.<br/>
R code used to generate Quality Control plots, Heatmaps are also stored here. <br/>

## DESeq2
This directory contains all genes falling under a significant P value (0.05) and Adj P value (0.1)<br/>
For Control samples, Treated samples, and then Merged samples.<br/>
Control and Treated are contrasting S2+ vs. WT.<br/>
Fold Change in the excel sheets is in reference to WT. <br/>

Merged samples, the contrast is Treated vs. Control, AdjVars = 'Type' (S2+ vs WT). <br/>
Again, Fold Change is in relation to WT<br/>

log2FC == posiitve numbers indiciate upregulation in WT<br/>
          negative numbers indicate upregulation in S2+ <br/>

## Log2FC Explained:
Take CYTO_0.1_Padj.csv as an example:<br/>
Gene : AL162258.1 Log2FC : 4.5028496338372<br/>

log2(4.5028496338372) = 2.1708383017660506 FOLD CHANGE<br/>

Thus, AL162258.1 is upregulated 217% more in WT. <br/>
