# Energy Surplus Prediction Project

## Project Overview

This project aims to develop a system that can reliably predict, at least 24 hours in advance, whether there will be a surplus of energy (from either wind or solar sources) in a specific area. The system will be utilized to offer free energy to local clients when a surplus is predicted, as part of a pilot project.

## Dataset Description

- The Colchester dataset was chosen for this project.
- A 20-year period of data (from 2004 to 2024) was selected from the entire dataset.
- The data was split into two parts:
  - **Training Data**: From 2004 to 2020
  - **Test Data**: From 2020 to 2024

## Model

- The model used for predicting energy surplus is **Ridge Regression**.

## How to Run the Project

1. Open the code file (in `.ipynb` format) in Jupyter Notebook.
2. Provide the dataset directory path to load the data.
3. Run the code file sequentially.

## Exploration Assumptions

During the exploration phase, the following assumptions were made:

### Annual Electricity Use (kWh) in the UK:

- **Low**: 1,800 kWh
- **Medium**: 2,700 kWh
- **High**: 4,100 kWh

### Formula for Calculating Wind Power Energy:

- **Power** = 0.5 × Swept Area × Air Density × Velocity³

## References

- [Ofgem: Average Gas and Electricity Use Explained](https://www.ofgem.gov.uk/information-consumers/energy-advice-households/average-gas-and-electricity-use-explained)
- [OVO Energy: How Much Electricity Does a Home Use?](https://www.ovoenergy.com/guides/energy-guides/how-much-electricity-does-a-home-use)
- [REUK: Calculation of Wind Power](http://www.reuk.co.uk/wordpress/wind/calculation-of-wind-power/)
