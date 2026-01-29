# Decoding Honey Origins: FTIR-Based Botanical Classification with ML and DL

This repository contains the code and materials for a machine learning and deep learning study on classifying the botanical origin of honey using FTIR spectroscopy data.

The project was presented as a poster at an international academic conference and focuses on building reproducible, interpretable, and scalable models for food authenticity analysis.

## Project Overview

Honey composition varies with floral origin, affecting quality, flavor, and market value. Traditional identification methods are accurate but slow and labor-intensive. This project explores FTIR spectroscopy combined with machine learning and deep learning as a rapid, non-destructive alternative for botanical classification.

The work compares classical ML models with deep learning approaches and investigates which spectral regions contribute most to classification performance.

## Methods

- FTIR spectra preprocessing and normalization  
- Feature scaling and dimensionality reduction (PCA)  
- Classical ML models: SVM, Logistic Regression, Decision Tree, Random Forest, Ensemble methods  
- Deep learning: 1D Convolutional Neural Network  
- Model evaluation using accuracy and macro F1-score  
- Feature importance analysis using Random Forest  
- Visualization of latent structure using PCA and t-SNE  

All analyses were performed in Python using scikit-learn and TensorFlow/Keras.

## Results (Summary)

- Classical ML models achieved strong performance (up to ~96% accuracy).
- CNN models achieved the highest performance, demonstrating stronger generalization.
- Feature importance analysis showed that classification depends on distributed spectral regions rather than isolated peaks.
- Results support FTIR + ML/DL as a robust framework for rapid honey authentication.

## Repository Structure

- `src/` – Core Python scripts for data processing, modeling, and evaluation  
- `figures/` – Plots and visual outputs (PCA, feature importance, model results)  
- `poster/` – Conference poster presented for this work  

## Conference Presentation

This work was presented as a poster:

**“Decoding Honey Origins: ML and DL Methods for Botanical Classification”**  
Nathan Mekuria Solomon, Cansu Turan, Durmuş Özdemir  
Izmir Institute of Technology

The poster is available in the `poster/` directory.

## Notes on Data

Due to data ownership and size constraints, raw FTIR datasets are not included in this repository. The code is structured to allow reproduction of the workflow with similar FTIR datasets.

## Author

Nathan Mekuria Solomon  
Background: Chemistry, Computer Engineering (minor), Data Analysis & Machine Learning

