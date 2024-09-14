#### Gene Expression Analysis of a Glioblastoma dataset


We analyzed and visualized glioblastoma gene expression data by generating 5 heatmaps and performing functional enrichment analysis for the upregulated and downregulated genes.


###### Analysis tools :
R studio 4.4.0
ShinyGO http://bioinformatics.sdstate.edu/go/

##### Project Workflow :
dataset of top 500+ differentially expressed genes under different conditions of glioblastoma samples: https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/Cancer2024/glioblastoma.csv
Generating 3 heatmaps [1] for genes only ,[2] for samples only which helps in identifying clusters ,[3] for genes and samples 
Generating 2 heatmaps of the entire dataset using a sequential and diverging color palettes.
Subsetting upregulated and downregulated genes based on p-value and foldchange cutoffs 
functional enrichment analysis using ShinyGO: http://bioinformatics.sdstate.edu/go/
generation of a lollipop plot showing the top 5 enriched pathways in the dataset
Interpreting the top 3  upregulated and downregulated pathways 



