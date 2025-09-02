# Climate-Smart Irrigation Model  

## Overview  

This repository contains three Jupyter notebooks designed to simulate crop growth and soil processes under different water management scenarios:  

- **Drip irrigation**  
- **Sprinkler irrigation**  
- **Rainfed** (serving as a control scenario without irrigation)  

Each notebook performs a growing season simulation of:  
- Vertically integrated soil moisture dynamics  
- Crop biomass growth  
- Soil greenhouse gas (GHG) emissions  

All code cells are thoroughly commented for clarity. The notebooks take as input a NumPy array representing rainfall distribution.  

As an example, the file **rain_Lubbock_lbd0p18_aphp0096.npy**, provided here, contains **200 seasons of a typical 140-day growing season of rainfall** representative of the **Texas High Plains**.  

## Model Context  

For the simulations, we use soil, weather, and crop parameters representative of the **Texas High Plains**, a major agricultural region in the United States that relies heavily on irrigation for sustainable production.  

A detailed discussion of the model structure and its mathematical formulation is provided in the supporting information for the manuscript. Please refer to that document for in-depth explanations.  

This Python code was developed to run simulations for a submitted manuscript that introduces a **dual-index framework** to evaluate trade-offs between **productivity** and **soil GHG emissions (climate impact)** across different irrigation practices and the rainfed baseline.  

- The manuscript is currently under revision at *Earth’s Future*.  
- The preprint is available here: [ESS Open Archive](https://essopenarchive.org/doi/full/10.22541/essoar.175399511.16884572).  

## License  

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).  

[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)  
