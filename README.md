# Visualizing Tsunami Fragility Curves

**Authors:**  
- Fatemeh Jalayer  
- Hossein Ebrahimian  

**Date:** 2025-11-13

## Description
This Jupyter Notebook provides a workflow for visualizing tsunami fragility curves from the  
**Empirical Tsunami Risk Products Dataset (ETRiS v0)**, accessible through the EPOS ICS-C portal.

The notebook demonstrates how to:
- Load fragility datasets directly from CSV files  
- Automatically detect the number of damage levels  
- Plot mean, mean–sigma, and mean+sigma fragility curves  
- Generate visualizations using Plotly  

## Data
A small example dataset is expected in the working directory.  
You may place example CSV files inside the working folder.

Full datasets are available at:  
https://github.com/eurotsunamirisk/etris_data_and_data_products/tree/main/etris_data_products/Fragility_Curves

## How to Run the Notebook
1. Install dependencies:
pip install -r requirements.txt
2. Open the notebook:
jupyter lab VisualizeFragility.ipynb
3. Restart the kernel and run all cells from top to bottom.

## Dependencies
See `requirements.txt`.

## References
- https://github.com/eurotsunamirisk/etris_data_and_data_products/tree/main/etris_data_products/Fragility_Curves
- Jalayer, F., Ebrahimian, H., Trevlopoulos, K., Bradley, B. (2023). Empirical tsunami fragility modelling for hierarchical damage levels. Natural Hazards and Earth System Sciences, 23(2), 909-931. https://nhess.copernicus.org/articles/23/909/2023/

## Citation
Please cite this notebook using the information provided in `CITATION.cff`.


