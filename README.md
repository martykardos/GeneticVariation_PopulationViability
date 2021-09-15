# GeneticVariation_PopulationViability
This repository contains the R code to replicate the simulations and figures in Kardos et al. 2021

All of the needed files are compressed in genVarConservation.zip.

Each subfolder contains code specific to a particular figure in the paper. To replicate the simulations and figures, first install 
the R package quantPop included in this repository using install.packages("quantPop_0.3.8.tar.gz",repos=NULL,type="source"). 

In each subfolder there is a single script with the format rCode_FIG_1August2021, where "FIG" is replaced by a specific
Figure indicator. For example, for figure S1, the figure script is named rCode_figureS1_1August2021. Before running a 
figure script, you will need to run all of the simulations with ALL of the other scripts in that folder. Each script uses setwd() 
to set the working directory. You will have to change the working directory in each script to run the simulations and plotting scripts 
on your own computer. 

Send inquiries to martin.kardos@noaa.gov.
