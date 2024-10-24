# Supporting Information

This repository contains all code for bioinformatic analysis for the manuscript, Jech et al. biocrust cultivation.


# What can I do with this code?

In publishing this repository, our hope is that this code is useful to other members of the scientific community. This repository is released under a Creative Commons BY (CC-BY) license, which means that all code published here can be shared and adapted for any purposes so long as appropriate credit and citation of the original paper is given. See attribution section for details.


# How do I run this code?

1. Go to NCBI and download the raw sequence files. 
2. Download and install R for your operating system.
3. Download and install RStudio for your operating system.
4. Download a zip file of this repository and decompress it in a directory of your choosing on your computer.
5. Navigate to the directory and open biocrustCult.Rproj file to start Rstudio and load this project's files.
6. Open the script(s) you would like to run. Scripts are numbered in the order they should be executed e.g, 01, 02, 03. Duplicate numbers mean those scripts can be run in any order relative to each other. If you are interested in the bioinformatic pipeline, run script 01.processing_and_bioinformatics.Rmd. If you are interested in ASV table manipulations, run script 02.phyloseq_ASV_Table.Rmd. All other scripts are associated with figures, statistical analysis, and calculations for the manuscript.
7. Ensure that you have all of the required libraries installed by inspecting the Setup chunks. In these scripts, we note the CRAN/GitHub version/release that was used. If any libraries fail to install, note the name of the library and attempt to manually install its most recent version via CRAN or GitHub.
8. To generate an HTML report, select File --> Knit from the menu.


# Scripts
- 01.processing_and_bioinformatics.md
- 02.phyloseq_ASV_Table.Rmd
- 03.biocrust_IntactBare_community_comp.Rmd
- 04.biocrust_community_comp.Rmd
- 05.cyano_abundance_figures.Rmd
- 06.cyano_taxa_abundance_figures.Rmd
- 07.ordination.Rmd
- 08.cyano_richness_figure.Rmd
- 09.cyano_taxa_abundance_values.Rmd
- 10.cyano_taxa_stacked_bars_figures.Rmd
- 11.restore_soil_chemistry.Rmd
- 12.IntactBare_ordination_AppendixA.Rmd
- 13. IntactBare_abundance_AppendixA.Rmd


# Folders
- 'data' 
- 'data_output'
- 'output' 
- 'figures'
