# BatteryCellAnalyticalModel
This repository contains a suite of matlab scripts that implement an analytical model for predicting the rate performance of battery cells, which is described in the following paper: "_A Quantitative Analytical Model for Predicting and Optimizing the Rate Performance of Battery Cells_", Fan Wang and Ming Tang, [arXiv:2004.10707](https://arxiv.org/abs/2004.10707) (2020). 

Files:
1. "PredictDischargeCapacity_AnalyticalModel.m" calculates the normalized galvanostatic discharge capacity of battery cells based on input cell parameters and discharge current density. 
1. "NMC_Graphite_CellParameters.m" provides an example of the Matlab structure array that defines the cell parameters used by "PredictDischargeCapacity_AnalyticalModel".
1. "SpecificCapacity_ContourPlot.m" provides an applicaiton example of the analytical model by using it to make contour plots of the cell-level specific capacity of NMC half cells and NMC/Graphite full cells at 1C discharge in the parameter space of cathode thickness and porosity. 

Authors:
Fan Wang and Ming Tang, 
Department of Materials Science & NanoEngineering, 
Rice University, Houston, TX, USA\
Contact: mingtang@rice.edu

