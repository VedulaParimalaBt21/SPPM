# SPPM PROJECT 
## Semaglutide
INTRODUCTION

This reporsitory contains the information of the semaglutide PK, PD and Interactive visualisation data and the sequence of running the codes. As we know Semaglutide is a GLP-1 like agonist and is used to treat type-2 diabetes and also can be used for weight loss.

Running the Analysis

To run the analysis, follow these steps in order:

Set Up Your Environment
Ensure MATLAB (version 9.14.0 R2023a or later) is installed.
Ensure R (version 4.3.1 or later) is installed along with the required packages (ggplot2, tidyverse, R.matlab, etc.).

Downloading the data

Download the data from the canvas website which is availible as a zip folder. The zip folder consists of three folders PK codes, PD codes and Interactive visualisation codes.
Run Pharmacokinetic (PK) Model Simulations

The folder PK codes has two sub folders:- Project PK codes and interactive visualisation. First run all the cases in the semaglutide_driver_opt. Doing this will also save the data that required for plotting in the R. 

After this run the PK project figures in R for viewing the plots in R. 

Run Pharmacodynamics (PD) Model simulations 

All the necessary codes for running the PD model are present in the folder PD codes-3, first run the "runcodesemaglutide.m" file before proceeding to the plotting.
We highly recommend to run all the .R files as different files give different parameter information. 

Interactive visualisation codes

The interactive visualisation files for PK and PD are in present in their respective folders. For the PK models, we recommend you to run the "semaglutide_simulation.m" file before running the code, as this file is modified to ease the storage of the data. After this please run the file named "app.R" to access the app which shows the concentration vs time plots for different patients. 

For the PD models, the necessary codes for the app are present in the sub folder named "Final Project Semaglutide" and run the file named app.R.


