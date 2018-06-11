# FEA-Automation
The goal of this repository is to:
-->Automating routine pre and post processing tasks in FEA using Abaqus.(time savings > 90%)
-->Improved Diagnostic insights to the user for analysis convergence issues 

1. Abaqus Convergence Graph -
Use this code to creare the Abaqus convergence criteria graphs for Abaqus static/dynamic implicit analyses. The code scans the message file (msg file) from the analysis output files and plots the residual forces compared to the default Abaqus convergence criteria. This gives the user an understanding of where the analysis is having problems for focused and faster debugging. Also, the graphs generated also highlight the number of issues encountered during analysis helping the user to guage the efficieny of the analysis.

2. Creating custom SAF value Fieldoutputs - 
This script is used to create "SAF field output requests" for 20%, 40%, 60%, 80% and 100% tension load case with no nominal/minimal pre-load for a marine riser joint. 

3. Creating material and section automatically -
Use this script only if you have to create one linear elastic steel material and one section across all the parts. 

4. Run stress linearizations for a user input step (all frames) -
Use this script to run stress linearizations for all the franes in a step inputted by the user

5. Generate a formatted report(csv file) of linearized stresses -
This program creates a .csv file(test1.csv) and print the VonMises Membrane and Membrane+Bending stress out of a linearized stress report for reporting purposes 
