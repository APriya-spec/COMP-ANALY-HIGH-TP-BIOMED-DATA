# Assignment 4
### *Programmer Name: Aruna Priya Cheekatla*

Language of the script: Python

Date: 04/10/2025

### *Description:*  
This assignment implements a motif discovery pipeline for identifying transcription factor binding sites in prokaryotic gene upstream sequences. Specifically, the assignment focuses on detecting high-scoring motif matches for the *argR* transcription factor using a weight matrix (PWM) derived from a known base count matrix.

The script performs the following key tasks:

1. Parses the given base counts matrix and computes:
   - Frequency matrix F(b, j)
   - Adjusted frequency matrix F′(b, j) with pseudocounts
   - Weight matrix W(b, j) using log-odds scores
2. Loads upstream gene sequences from a `.bz2`-compressed FASTA-like format
3. Scans all sequences using the PWM to identify potential binding sites
4. Displays the top 30 high-scoring gene subsequences predicted to be *argR* binding sites

### *Dependencies:*  
- numpy (for matrix calculations)  
- bz2 (for reading compressed sequence files)

### *Input Files:*  
1. argR-counts-matrix.txt — tab-separated file containing the base counts matrix for motif construction  
2. E_coli_K12_MG1655.400_50.bz2 — compressed file containing upstream regulatory sequences of *E. coli* genes

### *Generated Output:*  
1. Printed matrices:
   - Frequency matrix F(b, j)
   - Adjusted frequency matrix F′(b, j)
   - Weight matrix W(b, j)
2. A list of the top 30 predicted binding sites showing:
   - Gene ID
   - Score
   - Start position of the match
   - Matched subsequence

### *Use Case:*  
This script supports the study of bacterial transcription regulation by identifying upstream motif matches for known transcription factors. It serves as a basis for genome-wide motif scanning, comparative motif analysis across species, or integration with gene expression data for regulatory network inference. The modular design allows for easy adaptation to different motif matrices or transcription factors.
