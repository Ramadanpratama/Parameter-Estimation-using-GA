Thermal Degradation Kinetics of Aluminium Composite Panels (ACP)
This repository contains data and analysis related to a study on the thermal degradation behavior of Aluminium Composite Panels (ACP) used in building facades. The research aims to address the insufficient characterization of ACP thermal properties, which may pose potential safety risks in building applications.
Study Overview
We investigated the kinetics of thermal degradation in ACP using non-isothermal thermogravimetric analysis (TGA) under the following conditions:

Temperature range: 300-1000 K
Heating rates: 5, 10, 15, and 20 K/min
Atmosphere: Nitrogen

Repository Contents

TGA Data: Excel files containing raw thermogravimetric analysis data for various heating rates.
Isoconversional Analysis: Excel files with calculated values from isoconversional methods (Friedman, Flynn-Wall-Ozawa, and Kissinger-Akahira-Sunose).
Gpyro Software: Link to download the Gpyro software used for genetic algorithm (GA) optimization.

Key Findings

ACP exhibited a single weight loss stage between 707-783 K, suggesting a single-step reaction mechanism.
Isoconversional methods yielded consistent activation energies of 257-258 kJ/mol across the 10-90% conversion range.
GA optimization using a simple n-order kinetic model produced:

Activation energy: 210 kJ/mol
Pre-exponential factor: 7.89 × 10^13 s^-1
Reaction order: 0.5


The GA approach demonstrated superior performance with a low relative error of 0.49%, compared to 12.22-31.09% for isoconversional methods.

Software
The genetic algorithm optimization was implemented using Gpyro software.
