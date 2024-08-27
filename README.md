# Dash_app_Acinetobacters

### Download genomes and their summaries from NCBI datasets database  

### Run orthofinder on proteomes  

### Build local python interactive dash app from orthofinder results  

#### Find HOGs of interest and select them at different phylogenetic levels
##### Select N0 node in tree to show info on selected HOG at NO level.
- Here we have selected HOG N0.HOG0000651, which contains all genes that descended from the species
  represented by the N0 node on this tree, the last common ancestor of all organisms in this analysis.
  These genes include AstAs and AstOs in acinetobacter.
![Logo](assets/N0.png)
  
##### Select N2 node in tree, LCA of all acinetobacters 
- This HOG contians all AstA/O genes that descended from the LCA of acinetobacters.
- This analysis suggests that the LCA of Acinetobacters still only contained one AstA/O gene.
![Logo](assets/N2.png)

##### Select N42 node in tree, a common ancestor of acb (I) and colisiniresistens (II) clades.
![Logo](assets/N42.png)

