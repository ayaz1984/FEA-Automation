# FEA-Automation
-->Automating routine pre and post processing tasks in FEA using Abaqus.(time savings > 90%)
-->Improved Diagnostic insights to the user for analysis convergence issues 

1. Abaqus Convergence Graph -
Use this code to creare the Abaqus convergence criteria graphs for Abaqus static/dynamic implicit analyses. The code scans the message file (msg file) from the analysis output files and plots the residual forces compared to the default Abaqus convergence criteria. This gives the user an understanding of where the analysis is having problems for focused and faster debugging. Also, the graphs generated also highlight the number of issues encountered during analysis helping the user to guage the efficieny of the analysis.



