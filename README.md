This README file documents the contents of the "code" and "data" folders for deCamp et al. manuscript: "Human immunoglobulin gene allelic variation impacts germline-targeting vaccine priming".

Principal Investigator: William Schief, PhD <br>
Institution: Scripps Research <br>
Email: schief@scripps.edu <br>

# Code overview
Note, the provided code accesses a public dataset (Leggat et. al., Science 2022).  The analyses in deCamp et. al. were run before the public dataset was available. The values are identical between datasets for 95% (293 out of 307) samples where "Percent of IgG memory B cells detected as VRC01−class" is defined.  Of the 14 samples where the values differ, all but two differ by less than 2-fold.  As a result, the analyses presented in deCamp et. al. have minor differences compared to the results generated on the finalized dataset. Furthermore, these differences do not impact the interpretation of the results presented in deCamp et. al.

The "code" folder contains IGHV1_2_G001_Allele_Manuscript.Rmd: 
Generates analyses, figures, and tables.

# DATA OVERVIEW

The "data" folder contains 2 files: <br>

visit_info.csv: <br>
Contains information for formatting visit codes.

Data S1.xlsx: <br>
Supplemental data file 1 from deCamp et. al. Counts and frequencies for IGHV1-2 allele mRNA UMIs and unique HCDR3s in two IgM libraries for each trial participant.
