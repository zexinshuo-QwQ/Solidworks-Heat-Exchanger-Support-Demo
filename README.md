# Heat Exchanger Saddle Support Design & Structural Optimization

## Project Overview
This project presents the mechanical design and finite element analysis (FEA) of saddle supports for a horizontal shell-and-tube heat exchanger with an operational weight of 1200 kg.

Two alternative support configurations were evaluated to investigate the trade-off between structural stiffness and material efficiency.

## Design Configurations
- Assem1: Reinforced configuration with 4 mm vertical side support plates  
- Assem2: Lightweight configuration with 2 mm vertical side support plates  

Both designs provide 180-degree saddle contact with the cylindrical vessel to ensure uniform load distribution.

## Analysis Methodology
Static structural analysis was conducted using SolidWorks Simulation under gravitational loading conditions.

The following evaluation criteria were considered:
- Maximum von Mises stress  
- Maximum displacement  
- Factor of Safety (FOS)  
- Reaction force equilibrium  
- Mesh convergence behavior  

A mesh convergence study was performed for both configurations by refining the global mesh size from 20 mm to 5 mm to ensure numerical accuracy of the simulation results.

## Key Findings
Results indicate that increasing the side support thickness from 2 mm to 4 mm significantly improves structural performance:

- Maximum stress reduced from approximately 43–44 MPa to below 28 MPa  
- Maximum displacement reduced from approximately 0.22 mm to 0.15 mm  
- Minimum factor of safety increased from ~4 to above 7  

Although the reinforced configuration increased the structural mass by approximately 1.34 kg, it provided enhanced rigidity and safety margin.

## Engineering Interpretation
Mesh convergence was achieved at a global mesh size of 10 mm.

Localized peak stress observed in the lightweight configuration was attributed to stress singularity at welded geometric intersections and was not considered representative of structural failure.

## Tools
- SolidWorks (3D modeling)
- SolidWorks Simulation (Static Structural FEA)

## Repository Contents
- CAD models for both support configurations  
- Engineering FEA reports  
- Stress and displacement contour plots  
- Mesh convergence study results  
