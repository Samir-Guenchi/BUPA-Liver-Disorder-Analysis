# BUPA Liver Disorder Analysis Pipeline

## Overview
End-to-end machine learning pipeline for liver disorder prediction featuring:

**Data Processing**
- 📈 Smart augmentation (10K-50K synthetic samples with medical constraints)
- 🚨 Outlier detection (IQR/z-score methods)
- ⚖️ Feature scaling (Standard/Robust/MinMax options)

**Model Evaluation**
- 🤖 6 Regression Models Tested:
  - 🏆 **Random Forest** (Best: R²=0.953)
  - 📊 KNN (R²=0.951)
  - 🌳 Decision Tree (R²=0.925)
  - 🧠 Neural Network (R²=0.706)
  - 🔍 SVM (R²=0.605)
  - 📉 Linear Regression (R²=0.284)

**Visual Outputs**
- 📊 8+ visualization types generated:
  - Actual vs Predicted plots
  - Residual analysis
  - Feature importance charts
  - Model comparison dashboards

## Quick Start
```bash
git clone https://github.com/yourusername/bupa-liver-analysis.git
cd bupa-liver-analysis
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
pip install -r requirements.txt
python main.py
