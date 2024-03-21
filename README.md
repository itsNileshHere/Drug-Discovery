# Drug Discovery Pipeline for SARS Coronavirus

## Overview
This project presents a comprehensive pipeline for drug discovery targeting the SARS coronavirus. It utilizes data from the ChEMBL database, employs various data preprocessing techniques, performs analysis, and builds a predictive model to identify potential drug candidates.

## Features
- Data retrieval from ChEMBL database
- Data preprocessing including cleaning and filtering
- Calculation of bioactivity thresholds
- Calculation of Lipinski descriptors
- Visualization of data through plots
- Statistical analysis using Mann-Whitney U test
- PubChem fingerprinting for feature generation
- Model building using Random Forest regression
- Model evaluation using R-squared and mean squared error
- Exporting trained model for future use

## Installation
1. Clone the repository:
```
git clone https://github.com/itsNileshHere/Drug-Discovery.git
cd Drug-Discovery
```

## Usage
1. Run the Jupyter notebook `Drug Detection.ipynb` to execute the entire pipeline.
2. Follow the step-by-step instructions within the notebook to preprocess data, analyze, build, and evaluate the model.
3. Modify the notebook as needed for custom datasets or analyses.

## Data
- The data used in this project is retrieved from the ChEMBL database.
- PubChem fingerprints are generated for feature extraction using the PaDEL software.
