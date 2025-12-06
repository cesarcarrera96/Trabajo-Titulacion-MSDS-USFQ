# Medical Appointment No-Show Prediction – Model Comparison

This repository contains the code, experiments, and supporting material for a research project focused on predicting medical appointment no-shows using tabular classification models.

The main goal of this study is to compare the performance of four different algorithms on a real hospital appointment dataset:

- Extreme Gradient Boosting (XGBoost)
- Ensemble Learning (stacking model with XGBoost as meta-learner)
- TabNet
- Tabular Probabilistic Transformer (TabPFN)

The models are trained and evaluated under identical preprocessing and validation conditions, using metrics such as Accuracy, F1-score, ROC-AUC, and Precision. Additionally, a statistical hypothesis test is performed to determine whether the Ensemble model achieves statistically superior performance compared to the other methods, particularly in terms of ROC-AUC and F1-score.

---

## Repository Structure

The repository is organized as follows:

```text
.
├── README.md
├── data/
├── models/
├── outputs/
