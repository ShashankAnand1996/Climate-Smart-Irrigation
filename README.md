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

For the example simulations, we use soil, weather, and crop parameters representative of the corn growing season in the **Texas High Plains**, a major agricultural region in the United States that relies heavily on irrigation for sustainable production.  

A detailed discussion of the model structure and its mathematical formulation is provided in the supporting information for the manuscript. Please refer to that document for in-depth explanations.  

This Python code was developed to run simulations for a submitted manuscript that introduces a **dual-index framework** to evaluate trade-offs between **productivity** and **soil GHG emissions (climate impact)** across different irrigation practices and the rainfed baseline.  

- The manuscript is published *Earth’s Future*: [Publication_Link](https://doi.org/10.1029/2025EF006116).

## Funding Support

This work was supported by the Foundation for Food and Agriculture Research, United States (22–000070), the USDA National Institute of Food and Agriculture (2024-67019-42685, Hatch Project 1023954), and the Water Exceptional Item, Texas Water Resources Institute.


## License  

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). 
