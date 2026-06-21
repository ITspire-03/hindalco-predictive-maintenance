# hindalco-predictive-maintenance
AI-Powered Predictive Maintenance and Intelligent Failure Detection for Smart Manufacturing Systems
<br>
An end-to-end AI engineering project that ingests public industrial sensor datasets, trains anomaly detection and sequence-prediction models, and delivers a deployable FastAPI + React dashboard — directly mirroring what Hindalco's manufacturing lines produce.

## Datasets
- AI4I 2020 Predictive Maintenance (UCI, ID 601)
- SECOM Semiconductor Manufacturing (UCI)

## Stack
Python · PyTorch · scikit-learn · SHAP · FastAPI · Docker · React

## Structure
data/       → raw and processed datasets  
notebooks/  → EDA and modelling notebooks  
models/     → saved model weights  
api/        → FastAPI serving layer  
dashboard/  → React frontend  

## Setup
pip install -r requirements.txt
jupyter notebook