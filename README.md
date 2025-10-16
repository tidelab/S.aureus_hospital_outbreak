# S. aureus hospital outbreak simulations

Supplementary material for

_Fast hospital discharge rates blur within-hospital 'transmission footprint' in bacterial genomes_

The folder ‘XML’ contains a separate subfolder for each community sampling scenario (i.e. s_c = 0.0 / 0.01 / 0.001 / 0.0001), with each subfolder including the corresponding XML files. Each XML file consists of sections defining (i) the transmission tree simulation under the respective scenario, (ii) the simulation of a sequence alignment along that tree under the specified substitution model and rate, and (iii) the Bayesian inference under the chosen birth-death-sampling model (bdsky or bdmm). A more detailed description of the simulation scenarios is provided in the main text.

The simulations included in the manuscript were run using BEAST2 version 2.6.2 with the following package versions:

BDSKY v1.4.7

BDMM v1.0

MASTER v6.1.2

BEASTLabs v1.9.6

MultiTypeTree v7.0.2 

For each scenario, 100 replicates were run using random number generator seeds ranging from 3100 to 3199. 
