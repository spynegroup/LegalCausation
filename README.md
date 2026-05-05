# Applications of Causal Discovery Algorithms for Automated Generation of Legal Arguments
Six widely-used causal discovery algorithms are applied on a novel legal dataset consisting of 150 homicide cases.  
The algoithms are able to discover interesting causal patterns in the given cases.  
These causal patterns are utilized to generate legally persuasive and mathematically explainable arguments.  
The algorithms used are--PC, GES, GRaSP, BOSS, LiNGAM, and ANM.  
This repo contains the following files.  

## Code
* TagExtraction_TableFormation.ipynb: The script used for extracting the annotation of the case files.
  The output of this script is a binary matrix, which is saved as `Dataset/AnnotatedTable150.csv`.
  
* Causal_Graph.ipynb: The Jupyter notebook which contains the causal discovery source code.
  The input to this script is `Dataset/AnnotatedTable150.csv`.

## Dataset
* AnnotatedTable150.csv: The novel legal dataset consisting of 150 homicide cases.
  It is a binary matrix with homicide cases on the rows and legal concepts on the columns.

