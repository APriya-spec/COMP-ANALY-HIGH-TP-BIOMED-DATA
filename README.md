# Assignment 2  

### *Programmer Name: Aruna Priya Cheekatla*

Language of the script: Python

Date: 03/07/2025

### *Description:* 
This assignment's main goal is to use time-series decay data to compute yeast gene transcript half-lives.  The script analyses the provided dataset, extracts expression levels for each transcript through time, and fits an exponential decay function to estimate each transcript's half-life.  The ultimate half-life of each gene is calculated using the average of three replicate calculations.  The script also selects the top and bottom 10% of genes by half-life for additional functional enrichment analysis.
### *Dependencies:*
pandas, numpy, scipy

### *Input Files:* 
DecayTimecourse.txt
   
### *Generated files:*

1. half_lives.csv
2. top_10_percent.csv
3. bottom_10_percent.csv
4. bottom10_half_life_genes_overview.png
5. bottom10_half_life_genes_detailed.png
6. top10_half_life_genes_overview.png
7. top10_half_life_genes_detailed.png

### *Further Analysis:*
g:Profiler was used to analyse genes with extreme half-lives for functional enrichment.  Important biological mechanisms, molecular roles, and cellular constituents linked to transcript stability were emphasised by the investigation.  The findings shed light on the mechanisms underlying yeast gene regulation.  These results can be applied to comparative research and additional biological validation.


