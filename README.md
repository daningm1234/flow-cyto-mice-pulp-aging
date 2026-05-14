# Flow Cytometry Data: Age-Associated Dental Pulp Fibrosis in Mice

## Study Background
This repository contains flow cytometry data supporting the study:  
**Elucidating the molecular mechanisms regulating progenitor dynamics and immune-mesenchymal crosstalk during age-associated dental pulp fibrosis.**

The primary goal is to characterize immune cell changes in middle-aged mouse dental pulp, focusing on the CCL4+ immune cell population identified by single-cell RNA-seq analysis.

## Panel Design
 Marker       | Fluorochrome  | Purpose                                  
--------------|---------------|------------------------------------------
 Zombie Violet| Zombie Violet | Live/dead discrimination (viability dye) 
 CCL4         | FITC          | Chemokine marker of interest             
 CD45         | PE            | Pan-immune cell marker                   
 CD68         | APC           | Macrophage marker                        


##  File Description
- All `.fcs` files correspond to flow cytometry samples from young vs. middle-aged mouse dental pulp tissue.
- Each file is labeled with sample ID, age group, and biological replicate number.
- Single-stained controls are included in the folder where applicable.

## Gating strategy: 
  1.  Live cells (Zombie Violet negative)
  2.  Singlets (FSC-A vs FSC-H)
  3.  Immune cells (CD45+)
  4.  Subset analysis: CCL4+ and CD68+ populations within CD45+ cells
- This data is shared for transparency and reproducibility of our study on age-related pulp immune changes.
