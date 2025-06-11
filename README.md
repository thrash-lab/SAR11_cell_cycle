# SAR11_cell_cycle
Analyses that are involved in the SAR11 cell cycle project (Cheng et al. 2025)

## CH_index_Ecoli_Vibrio_SAR11.ipynb
Calculation of the Cooper-Helmstetter Indexes from previous E.coli (Skarstad, Steen, and Boye 1985; Boye and Løbner-Olesen 1991; Olsson et al. 2003), V.cholerae (Stokke, Waldminghaus, and Skarstad 2011), and SAR11 HTCC1062 (Carini et al. 2013) ploidy level distributions (Supplementary materials).

## Theoretical_DNA_distribution.ipynb
Detailed implementation of analytical simulations of theoretical ploidy level distributions based on a combination of τ, and the B, C, and D periods. 

## FCS_analyses.ipynb
Full process of reading one “.fcs” file and gain cell cycle analysis. 

## Growth_curve_instantaneous_rates.ipynb
The example code in parsing one growth curve (cell density vs. time) with a defined sliding window size (the number of time points per linear regression) into the instantaneous doublign rates over time as shown in Extended Data Figure 10. 

## SYBR_green_microscopic_images_analyses.ipynb
Implementation of reading the fluorescence microscopic images (“.jpg” format), parse the image data and highlight cells with large sizes (Supplementary Note 3). 

## SAR11_pangenome.ipynb
The code for generating the marker gene presence/absence data in Supplementary Table 3.
