# FTIR-Based Botanical Origin Classification of Honey Using ML and DL

This repository contains code and materials for a machine learning and deep learning study on classifying the botanical origin of honey using FTIR spectroscopy data.

The project focuses on building reproducible and interpretable data analysis pipelines for food authenticity and quality assessment, and was presented as a poster at the MACKIE 2025 Conference.

---

## Project Overview

Honey composition varies depending on floral source, influencing quality, flavor, and economic value. Conventional identification methods are accurate but time-consuming and laboratory-intensive.

This project explores FTIR spectroscopy combined with machine learning (ML) and deep learning (DL) as a rapid, non-destructive alternative for classifying the botanical origin of honey. The emphasis is on careful preprocessing, model validation, and interpretability rather than black-box performance.

---

## Methods

- FTIR spectral preprocessing and normalization  
- Feature scaling and dimensionality reduction (PCA)  
- Classical machine learning models:
  - Logistic Regression  
  - Support Vector Machines (SVM)  
  - Decision Trees  
  - Random Forest and ensemble methods  
- Deep learning model:
  - 1D Convolutional Neural Network (CNN)  
- Model evaluation using accuracy and macro F1-score  
- Feature importance analysis using Random Forest  
- Visualization of spectral structure using PCA and t-SNE  

All analyses were conducted in Python using standard scientific and machine learning libraries.

---

## Results Summary

- Classical ML models achieved strong classification performance (up to ~96% accuracy).
- The CNN model provided the highest overall performance and better generalization.
- Feature importance analysis indicated that classification depends on distributed spectral regions rather than isolated peaks.
- Results support FTIR combined with ML/DL as a robust framework for honey authentication and origin classification.

---

## Repository Structure

- `src/` – Python scripts for data processing, modeling, and evaluation  
- `figures/` – Visualization outputs (PCA plots, feature importance, model comparisons)  
- `poster/` – Conference poster presented for this work  

---

## Conference Presentation

This work was presented as a poster at the **MACKIE 2025 Conference**.

**Title:** Decoding Honey Origins: ML and DL Methods for Botanical Classification  
**Author:** Nathan Mekuria Solomon  
**Institution:** Izmir Institute of Technology  

The conference poster is included in the `poster/` directory.

---

## Notes on Data Availability

Due to data ownership and size constraints, the raw FTIR datasets are not included in this repository. The provided code is structured to allow reproduction of the workflow using similar FTIR datasets.

---

## Author

**Nathan Mekuria Solomon**  
Background in Chemistry, Computer Engineering (minor), and Data Analysis / Machine Learning
