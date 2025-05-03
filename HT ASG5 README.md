# Assignment 5
### *Programmer Name: Aruna Priya Cheekatla*

Language of the script: Python

Date: 05/03/2025

### *Description:*  
This assignment evaluates the structural characteristics of a human protein-protein interaction (PPI) network by calculating and comparing shortest path lengths between proteins in two distinct protein sets. It uses graph theory and statistical hypothesis testing to assess network-based differences.

The script performs the following key tasks:

1. Loads a human PPI network and constructs a graph using NetworkX.
2. Loads two protein lists (`protein-list1.txt` and `protein-list2.txt`).
3. Calculates all pairwise shortest path lengths within each protein list (ignoring disconnected nodes).
4. Performs a Mann-Whitney U test to statistically compare the path length distributions between the two protein sets.
5. Prints the test statistic and p-value for interpretation.

### *Dependencies:*  
- pandas (for data loading)  
- networkx (for graph creation and shortest path analysis)  
- scipy (for statistical testing)

### *Input Files:*  
1. Human-PPI.txt — space-separated file containing protein interaction pairs  
2. protein-list1.txt — first list of proteins to compare  
3. protein-list2.txt — second list of proteins to compare

### *Generated Output:*  
- Prints:
  - Number of valid path comparisons from each list  
  - Mann-Whitney U test statistic  
  - Mann-Whitney U test p-value

### *Use Case:*  
This script is designed to support the comparison of network centrality and connectivity properties between two functional protein sets. It is useful in identifying biologically meaningful topological differences, such as those between disease-associated versus normal proteins, and is applicable in systems biology, bioinformatics, and network medicine.
