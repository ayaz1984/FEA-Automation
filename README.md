# FEA-Automation
The goal of this repository is to:
-->Automating routine pre and post processing tasks in FEA using Python.(time savings > 90%)
-->Improved Diagnostics insights on analysis convergence issues to the user

1. Abaqus Convergence Graph -
Use this code to create Abaqus convergence criteria graphs for Abaqus static/dynamic implicit analyses. The code scans the message file (msg file) from the analysis output files and plots the residual forces compared to the default Abaqus convergence criteria. This gives the user an understanding of where the analysis is having problems in the course of the run aiming for focused and faster debugging. Also, the graphs generated also highlight the number of issues encountered during analysis helping the user to guage the efficieny of the analysis.

2. Creating material and section automatically -
Use this script only if you have to create one linear elastic steel material and one section across all the parts. 

3. Run stress linearizations for a user input step (all frames) -
Use this script to run stress linearizations for all the franes in a step inputted by the user

