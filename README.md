## Disk Ultramicroelectrode (UME) Size Characterization

## Overview
This Python code is designed for characterizing the size of a disk ultramicroelectrode (UME) using cyclic voltammetry (CV) data. It automates data import, analysis, and visualization, providing UME size information based on steady-state current measurements.

## Features
- **Automated Data Processing**:
  - Imports all raw data files from a specified folder.
  - Saves analyzed plots in a designated folder with size information labeled.
- **Customizable Solution Parameters**:
  - Users can input:
    1. Concentration of the redox species.
    2. Diffusion coefficient.
    3. Number of electrons transferred.
- **Data Analysis and Visualization**:
  - Plots all raw cyclic voltammetry data.
  - Performs baseline fitting.
  - Extracts steady-state current.
  - Calculates disk UME size and labels it on the plot.

## Usage
1. **Set File Paths**:
   - Define the raw data file path and the data save path.
2. **Configure Solution Parameters**:
   - Input concentration, diffusion coefficient, and electron transfer number.
3. **Run the Code**:
   - The program will automatically import, analyze, and generate plots with size information.
4. **Save Results**:
   - Processed plots with labeled size information will be stored in the designated folder.

