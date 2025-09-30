This repository contains the python codes to simulate the dynamics of bacterial communities with species that can communicate through Quorum Sensing (QS).

Authors: Ivan Lechuga and James Boedicker. 

The file LVQS_model contains the basic model that captures QS as density dependent interaction parameters. The code allows to generate data for different
parameters considered as variables (the density activation threshold is shown as an example). This model considers a fitness cost to QS that can be activated
with a binary variable. It generates the data for Figures 2, 3A and S1-3 of the main manuscript. Also shows the code to generate Figure 1D of the manuscript.

The file LVQS_cheating shows the code to include a QS strain that does not pay the fitness cost of QS. Generates data for Figure 3C.

The file LVQS_antifragility contains the code to increase the variability of QS species within the community and generate the data for testing antifragility in
the LVQS model with no cost. Generates data for Figure 4.

The file experimental_data_analysis shows the analysis of experimental data of communities' dynamics experiments and its comparision with our model results.
It has the code to generate tables S1 and S2 and Figures 5 and S4 of the main manuscript.

The file LVQS_data_analysis_figures has the code used to analyse the data generated with our model. It generates data for figures 2A,2D, and 4B. Plots Figures
2B, 2C, 2E, 2F, 3A, 3C, 4A, S1, S2 and S3.
