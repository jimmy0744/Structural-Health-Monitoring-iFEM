# iFEM Digital Twin Structural Monitoring

## Project Overview
This project develops a structural health monitoring framework using the inverse Finite Element Method (iFEM) integrated with FEM simulation to create a Digital Twin for deformation analysis.

The system combines experimental strain measurements, numerical simulation, and automated visualization to validate structural behavior under static loading conditions.

## Key Features
- Structural deformation analysis using iFEM
- FEM validation with COMSOL
- Experimental strain and displacement measurements
- Automated simulation result visualization
- Digital Twin–driven monitoring workflow

## Tools & Technologies
- COMSOL Multiphysics
- MATLAB
- SolidWorks
- Python
- Strain Gauges
- Data Processing

## Engineering Workflow
Experiment → Strain Measurement → iFEM Calculation → FEM Simulation → Visualization

## Results
The validation results demonstrate high agreement between simulation and experimental data, confirming the accuracy of the proposed monitoring approach.

## Repository Structure

This repository contains the complete workflow of the structural monitoring experiment, including experimental data, numerical analysis, and validation materials.

- **Experiment_Video.mp4**  
  Demonstrates the experimental procedure and validation process.  
  The strain values measured from strain gauges were input into the iFEM program to compute structural displacement.  
  The computed displacement was then compared with measurements obtained from displacement sensors to evaluate the error and verify the accuracy of the proposed method.

- **iFEM Digital Twin Structural Monitoring.pdf**  
  Full project report describing the theoretical background, modeling approach, experiment design, and validation results.

- **K_Value.xlsx**  
  Contains the stiffness-related parameters and calculation data used in the iFEM analysis.

- **LICENSE**  
  MIT License for repository usage.
