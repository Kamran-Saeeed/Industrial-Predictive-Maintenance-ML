# Industrial-Predictive-Maintenance-ML
7th-semester Machine Learning project built for Bahria University featuring SMOTE, K-Means clustering, and ensemble classifiers.
# Industrial IoT Predictive Maintenance Platform
* **Course:** Machine Learning (AIC301) - Bahria University Lahore Campus[cite: 1]
* **Degree Program:** Bachelor of Science in Information Technology (BSIT)[cite: 1]

## Project Overview
An end-to-end machine learning system designed to ingest industrial IoT sensor telemetry, handle class imbalance, segment machine health states via unsupervised learning, and predict equipment failures using ensemble classification models[cite: 1].

## Key Pipeline Components
1. **Data Preprocessing & Scaling:** Handled raw sensor logs and normalized continuous features using `StandardScaler` (Weeks 3, 7)[cite: 1].
2. **Class Imbalance Handling:** Applied **SMOTE** to balance rare machine failure events against normal operating data (Week 3)[cite: 1].
3. **Unsupervised Clustering:** Implemented **K-Means Clustering** to segment machine operational health profiles (Week 6)[cite: 1].
4. **Supervised & Ensemble Learning:** Trained base classifiers and an **Ensemble Soft Voting Classifier** yielding high predictive accuracy (Weeks 4, 8, 14)[cite: 1].
5. **Rigorous Evaluation:** Evaluated performance using Confusion Matrices, Precision, Recall, F1-Score, and ROC-AUC curves (Week 9)[cite: 1].
6. **Deployment Readiness:** Serialized model pipelines into `.pkl` artifacts for Flask web integration (Week 16)[cite: 1].
