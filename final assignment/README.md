This project is part of the EPA141A Model based decision making course at the Faculty of Technology, Policy and Management at the Delft University of Technology.

# EPA-simmodel
This repository contains a Many-Objective Robust Decision Making (MORDM) analysis for flood risk management in the Upper IJssel River, conducted by a group of analysists working for the Delta Commission in the Netherlands. The goal is to identify robust and equitable strategy under deep uncertainty that fulfills Delta's Mandate requirments. 

# Motivation 
Rising flood risks due to climate change threaten lives and infrastructure. The past methods were traditional determinist and thus fail to capture true, real-life systemic complexities. 

# Authors and TU Delft IDs

Group 30 

Aline Mellersh (6348718);
Carsten Mohr (6350178);
Lyka Ocampo (6353142);
Sofia Salvador Mateo (6102239)

# Data Storage 

All data used within this project is stored in the "data" folder.


# Workflow
Our full analysis workflow is in: "MBDM_FINAL_Group_30 (final code)"

*Step 1*: Defining objectives, levers, and uncertainties relevant to the Upper IJssel.
*Step 2*: Conduct initial exploratory modeling.
*Step 3*: Run ε-NSGAII to generate Pareto-optimal policies for the MOEA 
*Step 4*: Select a reference scenario
*Step 5*: Visualize trade-offs among cost, fatalities, damage, and robustness.
*Step 6*: Scenario discovery using PRIM
*Step 7*: Calculate robustness metrics (signal-to-noise ratio and max regret).
*Step 8*: Select and interpret top-performing policies per Delta Commission’s criteria.

# Results Summary
The results are reproducible by running the notebooks chronologically. For convenience, the results folder also contains the most important results in CSV files.

# Figures 
The figures produced in the code are stored in the "MBDM_Final_Assignment_Files" > "Plots" folder. However, note that when the code is run again, the image in the file will be overwritten.
