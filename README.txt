The enclosed Notebook.Rmd file contains all of the R code used to generate Figures 1, 2G–H, 4, 6, and 7, and Supplementary Figures 5 and 6 from the manuscript by Phipps et al. entitled, "Collective interactions augment influenza A virus replication in a host-dependent manner." A preprint of this manuscript can be found at https://www.biorxiv.org/content/10.1101/736108v2.

The single-cell RNA sequencing data underlying Figure 6 and Supplementary Figures 5 and 6 has been omitted from this public repository pending review of the manuscript, but will be released upon publication. An "eval = FALSE" flag has been attached to the code chunk that processes these results, to prevent its execution and avoid "no such file" errors.

To generate the other plots, open the Notebook.Rmd file, change the Proj.Home file path to the parent folder "~/GFHK99_Multiplicity" and execute the code via the "Knit to HTML" or "Run All Chunks" commands. 

Note that the package "cellrangerRkit" is not available from CRAN, and must be installed from GitHub using "devtools."