# Molecular Solubility Prediction (logS) with Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2.2-orange)
![pandas](https://img.shields.io/badge/pandas-1.5.3-red)
![matplotlib](https://img.shields.io/badge/matplotlib-3.7.1-green)

A machine learning project that predicts aqueous solubility (logS) of chemical compounds using molecular descriptors and linear regression.

## 📌 Table of Contents
- [Features](#-features)
- [Dataset](#-dataset)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Future Work](#-future-work)
- [License](#-license)

## 🚀 Features
- Predictive modeling of molecular solubility (logS)
- Quantitative Structure-Property Relationship (QSPR) approach
- Feature analysis using molecular descriptors:
  - MolLogP (Octanol-water partition coefficient)
  - MolWt (Molecular weight)
  - NumRotatableBonds
  - AromaticProportion
- Model evaluation with MSE and R² metrics
- Visualization of predicted vs experimental values

## 📊 Dataset
The Delaney solubility dataset contains:
- 1,288 chemical compounds
- Experimental logS values
- 4 molecular descriptors

Dataset source: [GitHub](https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv)

## 💻 Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/solubility-prediction.git
cd solubility-prediction
