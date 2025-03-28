
# Assignment 3
### *Programmer Name: Aruna Priya Cheekatla*

Language of the script: Python

Date: 03/28/2025

### *Description:* 
This assignment aims to predict operons — defined as the longest contiguous co-directional multi-gene transcriptional units — in prokaryotic genomes. The prediction is based on the rule that adjacent genes on the same strand with an intervening distance of less than 50 base pairs belong to the same operon.
The script processes annotated .ptt files for four bacterial genomes and a .gff file from a crop microbiome dataset. Operons are detected, grouped, and printed in a scrollable HTML format for clarity and readability within Google Colab. Fallbacks to gene product descriptions are included when gene names are not available.
### *Dependencies:*
pandas, gunzip

### *Input Files:* 
1. E_coli_K12_MG1655.ptt.gz

2. B_subtilis_168.ptt.gz

3. Halobacterium_NRC1.ptt.gz

4. Synechocystis_PCC6803_uid159873.ptt.gz

5. 2088090036.gff
   
### *Generated output*
Operon predictions are printed in scrollable sections within Colab, displaying:

1. Total number of operons detected per genome

2. Gene names or gene products per operon

### *Use Case:*
This script provides a general framework to explore transcriptional organization in bacteria. It can be extended for comparative genomics, expression studies, or functional clustering based on operonic structures. The logic is modular, making it suitable for further integration with visualization or export tools.
