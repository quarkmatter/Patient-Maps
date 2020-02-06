# Patient-Maps
Various algorithms for assigning drug treatment to patients based on ranked gene expression data

These are my attempts at assigning patients to "states" developed via clustering of gene expresison data. 

StatRank is based on the spearman rank coefficient. I have phrased this quantity as a 
linear regression over the distribution of entries in a permutation matrix designed 
to take one specific ranking to another 

GeneFlip is based on the identification of antagonistic TFs between states and identifying which of these pairs are
common to a given patient. 
