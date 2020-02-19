# Deep-Energy-Retrofits-for-Heritage-Buildings
Repository for code that was used in the deep energy retrofit analysis of a heritage house 

Project name: Balancing Trade-Offs Between Deep Energy Retrofits and Heritage Conservation

Description: With the need for greater carbon emission reductions, deep energy retrofits are required in existing and heritage buildings. Heritage buildings hold cultural and social values that should be conserved. This project contains code that was used in the deep energy retrofit analysis of a heritage house in Ottawa as part of my M.A.Sc. thesis. The analysis tools that were used are energyplus and python code. 

Table of Contents: 
    Import Dependencies
    Functions for sensitivity analysis
      def run_ep
      def summarize_results_sensitivity
      def get_para_results_sensitivity
      def show_results_lights_equip_split
    Example for Sensitivity Analysis
    Calibration Functions
      def NMBE_CVRMSE_for_calib_lights_equip_split
    Example Calibration Code
    Converting ACH to Flow Coefficients for Spaces

Installation: Install the Anaconda Python package to install many useful libraries and environments for python. Can use this code in Jupyter Notebooks directly.  

Usage: Use this code to edit idfs in energyplus, run parametric one factor at a time sensitivity analyses, check NMBE and CVRMSE of energy simulation data to measured energy data, analyse results from energyplus simulation from the output table or the output variable excel sheet. 

Contributing: I made this available so people reading my thesis can have look at and use the code. If you improve the code for yourself, then it would be great if you share. 

Credits: Larissa Ide. Balancing Trade-Offs Between Deep Energy Retrofits and Heritage Conservation. M.A.Sc. Thesis, Carleton University, 2020.

License: MIT License
