# Parkinson's Disease Detection from Voice Features

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

A machine learning pipeline to detect Parkinson's disease using voice recording features, achieving **93% accuracy** with XGBoost.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Dataset](#-dataset)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Technical Approach](#-technical-approach)
- [Contributing](#-contributing)
- [License](#-license)

## 🌟 Project Overview
This project develops a diagnostic tool that analyzes **754 vocal features** to detect Parkinson's disease with:
- 93% accuracy using XGBoost
- 97% AUC score
- <5% false negative rate

**Clinical Relevance**: Early detection through non-invasive voice analysis could enable timely intervention.

## 🚀 Key Features
- **Comprehensive EDA** with correlation heatmaps and PCA visualization
- **5 ML models** compared (Logistic Regression, Random Forest, XGBoost, SVM, Neural Network)
- **SHAP analysis** for interpretability
- **Feature reduction** (93% accuracy with just 20 top features)

## 📂 Dataset
**parkinson_disease.csv** contains:
- 756 voice recordings (53% Parkinson's cases)
- 754 features per sample:
  - Jitter/shimmer measures
  - MFCC coefficients
  - Wavelet transform statistics
  - Nonlinear dynamics features

Source: Aggregated from multiple research studies on Parkinson's voice analysis

## ⚙️ Installation
1. Clone repository:
   ```bash
   git clone https://github.com/temela/parkinson_disease.git
   cd parkinson-voice-detection



