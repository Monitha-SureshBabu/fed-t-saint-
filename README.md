# Fed-T-SAINT++: Federated Early Warning System for Student Dropout

Federated learning framework for student dropout prediction using temporal 
decay modeling. Co-authored research accepted at COMSYS 2026 (Springer LNNS).

## What it does
- Converts VLE clickstream data into recency-weighted engagement scores
- Uses a hybrid SAINT-AutoInt transformer model for dropout prediction
- Trains across 5 simulated institutions using Federated Learning (privacy-preserving)
- Explains predictions using SHAP for educator interpretability

## Results
- 92.84% accuracy, 0.9736 AUC on the OULAD dataset (32,593 students)
- days_silent identified as the most important predictor of dropout risk

## Tech Stack
Python, PyTorch, SHAP, Federated Learning (FedAvg, SWA), Google Colab

## Author
Monitha S — B.Tech CSE (Data Science), Presidency University, Bengaluru
