This repository contains the python codes to simulate the dynamics of bacterial communities with species that can communicate through Quorum Sensing (QS).

Authors: Ivan Lechuga and James Boedicker. 

The file LVQS_model contains the basic model that captures QS as density dependent interaction parameters. The code allows to generate data for different
parameters considered as variables (the density activation threshold is shown as an example). This model considers a fitness cost to QS that can be activated
with a binary variable. It generates the data for Figures 2, 3A, 5, 6 and 7 of the main manuscript. Also shows the code to generate Figure 1D of the manuscript.

The file LVQS_cheating shows the code to include a QS strain that does not pay the fitness cost of QS. Generates data for Figure 3C.

The file LVQS_antifragility contains the code to increase the variability of QS species within the community and generate the data for testing antifragility in
the LVQS model with no cost. Generates data for Figure 4.

The file LVQS_data_analysis_figures has the code used to analyse the data generated with our model. It generates data for figures 2A,2D, and 4B. It plots Figures 2B, 2C, 2E, 2F, 3A, 3C, 4A, 5, 6 and 7.
