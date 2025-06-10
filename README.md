# **FRP-Steel-Concrete-Bond-Strength-Prediction-Using-Tree-Based-ML**

This repository contains the source code, dataset, and simulation results used in the study: “Interpretable machine learning models for predicting flexural bond strength between FRP/steel bars and concrete”

# **Overview**

Predicting bond strength between reinforcement and concrete is a major challenge in structural design—especially under variable environmental and material conditions. This study compiles 268 data points from 19 experimental studies and applies tree-based machine learning models—including Decision Tree (DT), Random Forest (RF), Gradient Boosting (GB), and eXtreme Gradient Boosting (XGB)—to predict:

Flexural bond strength (τₘₐₓ)

for FRP- and steel-reinforced concrete beams subjected to various material and environmental parameters. The models were tuned using grid search, and Shapley values were used for interpretability.

# **Contents**

Notebooks: Jupyter notebooks for data preprocessing, model training, tuning, evaluation, and SHAP-based interpretation

Data: Preprocessed experimental dataset.

Models: Scripts for implementing and tuning DT, RF, GB, and XGB regressors

Results: Model performance metrics, SHAP plots, traditional model comparisons, and a user-friendly GUI

# **Requirements**

Python version: Python 3.8 or higher

IDE: Jupyter Notebook, VS Code, or any Python IDE

# **License**

This project is shared for academic and research purposes. Please cite the associated paper if you use this work.

Paper: Interpretable machine learning models for predicting flexural bond strength between FRP/steel bars and concrete.

DOI: https://doi.org/10.1007/s42107-023-00764-5
