# Pardun_et_al2023

This repository contains all the information needed to replicate the series of simulations used in Pardun et al. (2023). Each simulation was conducted using version 19.1 of Cloud Model 1 (CM1), maintained by Dr. George Bryan (https://www2.mmm.ucar.edu/people/bryan/cm1/).

The "input_sounding" is a text file that is the base state used to initiate the left-moving supercell. This is a modified version of the observed 15 June 2019 23:19 UTC sounding launched in the field. The text file are formatted to use as the "input_sounding" file to be imported directly by CM1. 

The "namelist.input" is the namelist file used for each simulation. This is standard across all three simulations.

The folders "full_soundings" and "therm_soundings" house the three interpolated soundings during BSS for the FULL and THERM simulations, respectively. Inside each folder, there are three thermodynamic replacements and kinematic replacements in identical text file format of the "input_sounding" used by CM1. These follow the convectional text format for BSS in CM1. 
