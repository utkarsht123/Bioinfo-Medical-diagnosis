BioML Drug Discovery

Overview
This project combines bioinformatics and machine learning techniques for drug discovery. It uses Python to analyze molecular structures and protein sequences, and implements a machine learning model to predict compound-target interactions.

Features
- Calculation of molecular descriptors for drug compounds
- Analysis of protein sequences
- Machine learning model for predicting drug-target interactions
- Visualization of feature importance

Dependencies
- numpy
- pandas
- scikit-learn
- RDKit
- Biopython
- matplotlib
- seaborn

Key Components
1. MolecularDescriptorCalculator: Calculates chemical properties of compounds
2. ProteinSequenceAnalyzer: Analyzes protein sequence properties
3. DrugDiscoveryML: Main class for machine learning model training and prediction

Usage
The script demonstrates:
1. Data preparation from compound SMILES and protein sequences
2. Model training and evaluation
3. Prediction of activity for new compound-target pairs
4. Visualization of feature importance

Future Work
- Incorporate more advanced molecular descriptors
- Implement deep learning models for improved prediction
- Integrate with external databases for larger datasets
