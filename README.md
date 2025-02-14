# IoT Sensor Data Analysis for Equipment Failure Prediction

[![Open in Colab](https://colab.research.google.com/drive/1_Ur1mK63bhThaYx_Uhdhb7mFysLFrG1U#scrollTo=pQGXxmu52Chs)


## Overview
An end-to-end data analysis project predicting industrial equipment failures using IoT sensor data from semiconductor manufacturing processes. Implements machine learning to enable proactive maintenance planning.

## Problem Statement
- **Challenge**: 6% failure rate in semiconductor equipment causing unplanned downtime
- **Solution**: Developed predictive model identifying failures 24-48hrs in advance
- **Impact**: Reduced simulated maintenance costs by 18% through early detection

## Dataset
**SECOM Semiconductor Manufacturing Data**  
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/179/secom)
- Samples: 1,567 equipment records
- Features: 591 IoT sensors
- Target: Binary classification (Pass/Fail)

## Tech Stack
- **Data Processing**: Python, Pandas, NumPy
- **Machine Learning**: scikit-learn, imbalanced-learn
- **Visualization**: Matplotlib, Seaborn
- **Deployment**: Flask, Docker

## Key Features
✅ Missing value handling (70% completeness threshold)  
✅ Correlation-based feature selection (173 features removed)  
✅ Class imbalance mitigation (SMOTE oversampling)  
✅ Hyperparameter tuning (GridSearchCV)  
✅ Model explainability (Feature importance analysis)

## Installation
```bash
git clone https://github.com/yourusername/predictive-maintenance.git
cd predictive-maintenance
pip install -r requirements.txt

## 🛠️ Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/prachuryaphukan/predictive-maintenance.git
   cd predictive-maintenance
