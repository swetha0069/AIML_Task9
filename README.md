💳 Project: Credit Card Fraud Detection (Task 9)


📌 Project Overview
This project focuses on identifying fraudulent credit card transactions. The primary challenge is the extreme class imbalance, as fraudulent transactions represent less than 0.2% of the total dataset.

⚙️ Methodology

Algorithm: Random Forest Classifier (Ensemble Learning).

Sampling: Used Stratified Splitting to ensure the model learns from a balanced representation of both fraud and legitimate cases.

Optimization: Implemented n_jobs=-1 for parallel processing to speed up training in the Colab environment.

📊 Performance Metrics

In fraud detection, Accuracy is often misleading. Instead, we focus on:

Recall: Our ability to catch all actual fraudulent transactions.

Precision: Ensuring we don't incorrectly flag legitimate customers as fraud.

F1-Score: The harmonic mean used to balance Precision and Recall.

💡 Key Insights from Feature Importance

The Random Forest model identified specific anonymized features (such as V17, V14, and V12) as the most significant indicators of fraudulent activity. These patterns allow the model to distinguish suspicious behavior from normal spending habits.

✅ Deliverables Included

Trained Model: Exported as fraud_model.pkl.

Visualization: Feature Importance horizontal bar chart.

Evaluation: Full classification report with Precision-Recall metrics.
