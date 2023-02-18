# JOCBaxter2023Data
Data and results for "Heterogeneous Multi-Resource Planning and Allocation under Stochastic Demand" in INFORMS Journal on Computing. Please note that all data and results can be found at the Releases link to the right of the GitHub landing page.

Release Instance_Generation holds the data for all problem instances explored in the manuscript.
Release Solutions holds the results for computational experiments for smRmD-P.
Release Solutions_Budget holds the results for computational experiments for smRmD.
Release Budget_Comparison_Figures holds the data and results for Figures 1 and 2.

Files in Instance_Generation are of the form XResources_YDemands_ZScenarios.xlsx. This is a data file for the problem instance with X resource types, Y demands, and Z scenarios. Within the text file, lines "f" denote the demands x demands travel matrix and lines "f_bar" denote the resource starting locations x demands travel matrix. 

Files in Solutions and Solutions_Budget are of the form W_Solution_XResources_YDemands_ZScenarios.xlsx. This is a data solution file for the problem instance with X resource types, Y demands, and Z scenarios. W indicates whether the service times were multiplied by a factor. For instance, "x3Service" are solution files for when service times of the baseline instances were multiplied by 3. Solution files for baseline instances are given by W set to "full".

There are two types of files in the Budget_Comparison_Figures release. The first file type is of the form 2Resources_200Demands_10Scenarios_X.xlsx and is the data file for the Xth problem instance dipicted in Figures 1 and 2. The second file type is of the form Y_Solution_2Resources_200Demands_10Scenarios_X.xlsx and is the solution file for the Xth problem instance under budget (Y+1)*100 dipicted in Figures 1 and 2.

