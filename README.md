# Msc_project_scripts
LTspice scripts used in the project

The file contains three sub-files 
#
no_parasiticcapacitance contains four model scripts without parasitic capacitance, the dispersion curve could also be plotted from these scripts. All the codes needed to plot the S-parameters and the dispersion curve are included in the command.
###
Notice:
The result of the dispersion relation is in dB, which needs to be changed to linear.
#
fix&random_parasiticcapacitance contains four model scripts with parasitic capacitance. It is free to change the value of parasitic capacitance to fixed value or Gaussian distribution.

The random result might be different from what the project shows. But in general, it should be similar.
###
Notice:
The additional scripts contain the parasitic capacitance of the loaded transmission line cable to the ground; and the parasitic capacitance of the MI waveguide with one side of the transmission line connected to the ground.
#
Mitigating_strategy contains the mitigation strategy used in the project, the models are similar to the models with random parasitic capacitance. However, there are slight changes, like the value of coupling coefficients.

The random result might be different from what the project shows. But in general, it should be similar.
###
Notice:

The number of runs is 10,000, and the results should be exported as a text file. A Matlab script could be used to plot the distribution.
