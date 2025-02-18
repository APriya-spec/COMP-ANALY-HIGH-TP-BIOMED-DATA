# *Assignment 1 | Correlation Analysis of Cancer Data *

### *Programmer Name: Aruna Priya Cheekatla*

Language of the script: Python

Date: 02/18/2025

### *Description:* 
The primary goal of this assignment is to study and compare miRNA expression data from two distinct cancer-related datasets. The script uses Pearson correlation analysis to determine how different cancer types link inside each dataset and between the two datasets.

### *Dependencies:*
pandas
seaborn
matplotlib
numpy
google.colab (for file downloading in Google Colab)

### *Input Files:* 
1. matrix1.txt: Data matrix 1 with cancer type expressions.
2. matrix2.txt: Data matrix 2 with cancer type expressions.
   
### *Generated files:*

1. Heatmaps:

heatmap_matrix1.png = Heatmap of Pearson Correlation for Matrix 1
heatmap_matrix2.png = Heatmap of Pearson Correlation for Matrix 2

2. CSV Files:

correlation_matrix1.csv = Pearson correlation coefficients for all cancer types in Matrix 1
correlation_matrix2.csv = Pearson correlation coefficients for all cancer types in Matrix 2
overall_correlations_data.csv = Final cancer-specific correlations + overall correlation between the two matrices
