[![DOI](https://zenodo.org/badge/675946766.svg)](https://zenodo.org/doi/10.5281/zenodo.10637702)

This README file documents the contents of the "code" and "data" folders for the manuscript deCamp et al., npj Vaccines 2024, entitled "Human immunoglobulin gene allelic variation impacts germline-targeting vaccine priming".

Principal Investigator: William Schief, PhD <br>
Institution: Scripps Research <br>
Email: schief@scripps.edu <br>

# Data overview

The "data" folder contains 2 files: <br>

visit_info.csv: <br>
Contains information for formatting visit codes.

Data S1.xlsx: <br>
Supplemental data file 1 from deCamp et. al. Counts and frequencies for IGHV1-2 allele mRNA UMIs and unique HCDR3s in two IgM libraries for each trial participant.

# Code overview

The "code" folder contains IGHV1_2_G001_Allele_Manuscript.Rmd: Generates analyses, figures, and tables.

Note, the provided code accesses a public dataset from Leggat et al., Science 2022. The previous release (v1.0.0) of this repository for deCamp et al. described some minor discrepancies between the analyses in the deCamp et al. manuscript and the analysis produced by running the code on the public dataset. However, we have now resolved those discrepancies by correcting the manuscript to reflect the results of analyzing the public dataset. These corrections were made in the proofs stage, prior to publication. Hence, the analyses in the published deCamp et al. manuscript are identical to the results that would be produced if the code provided here is run on the public dataset.
 
