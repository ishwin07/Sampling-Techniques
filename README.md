# Sampling Techniques on Imbalanced Credit Card Dataset

## Objective
The objective of this assignment is to study the effect of different sampling techniques on imbalanced datasets and analyze how they influence the accuracy of multiple machine learning models.

---

## Dataset
- Dataset: Credit Card Dataset
- Target Variable: Class
- Problem: Highly imbalanced classification problem

---

## Data Preprocessing
- The original dataset was highly imbalanced.
- Random Under Sampling was first applied to create a balanced dataset.
- This balanced dataset was used as a base for further sampling.

---

## Sampling Techniques Used

| Sampling Name | Technique |
|--------------|----------|
| Sampling1 | Random Under Sampling |
| Sampling2 | Random Over Sampling |
| Sampling3 | SMOTE |
| Sampling4 | NearMiss |
| Sampling5 | Tomek Links |

---

## Machine Learning Models

| Model Code | Model |
|-----------|-------|
| M1 | Logistic Regression |
| M2 | K-Nearest Neighbors |
| M3 | Decision Tree |
| M4 | Random Forest |
| M5 | Support Vector Machine |

---

## Accuracy Comparison Table

| Model | Best Sampling Technique | Accuracy (%) |
|------|------------------------|--------------|
| Logistic Regression | Sampling1 | 66.67 |
| KNN | Sampling1 | 66.67 |
| Decision Tree | Sampling5 | 100.00 |
| Random Forest | Sampling5 | 60.00 |
| SVM | Sampling1 | 66.67 |

Detailed accuracy results for all combinations are available in `sampling_model_accuracy.csv`.

---

## Observations
- Decision Tree achieved the highest accuracy using Tomek Links sampling.
- Sampling technique significantly impacts model performance.
- Under-sampling techniques performed well for simpler models.

---

## Conclusion
Different sampling techniques influence machine learning models differently. Selecting an appropriate sampling strategy is critical when dealing with imbalanced datasets.

---

## How to Run
1. Open the notebook in Google Colab
2. Upload `Creditcard_data.csv`
3. Run all cells sequentially
4. Results and plots will be generated automatically

---

## Author
**ISHWIN**
