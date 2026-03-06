# Uncertainty-Aware Prediction of Thermal Expansion in Complex Oxides

This repository contains the dataset and code used in the manuscript:

**"Uncertainty-Aware Prediction of Thermal Expansion in Complex Oxides via LLM-Curated Literature Data"**

## Repository Contents

- **cte_dataset.xlsx**  
  Curated dataset of experimentally reported coefficients of thermal expansion (CTE) used for model development.

- **Final_CTE_Code_Main.ipynb**  
  Jupyter notebook implementing the full workflow including:
  - dataset preprocessing
  - composition normalization
  - feature generation
  - probabilistic machine learning
  - uncertainty calibration
  - model evaluation and figure generation

## Workflow Overview

The workflow implemented in this repository includes:

1. Literature-curated dataset of experimentally measured CTE values
2. Composition-based feature construction
3. Probabilistic machine learning using gradient-boosted regression
4. Prediction of both mean CTE and composition-dependent uncertainty
5. Calibration and evaluation of prediction intervals

## Reproducibility

All code required to reproduce the results in the manuscript is provided in the notebook.  
Running the notebook sequentially will reproduce the model training and evaluation workflow.

## Citation

If you use this dataset or code, please cite:

Marshall, J.; Alexander, M.; Garcia, V. J.; Safin, J.; Sanchez, S. L.; Foadian, E.; Rawn, C.; Page, K.; Kalinin, S. V.; Ahmadi, M.  
*Uncertainty-Aware Prediction of Thermal Expansion in Complex Oxides via LLM-Curated Literature Data.*
