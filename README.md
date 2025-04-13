# Knowledge Discovery and Data Mining – Computer Exercises (Spring 2025)

This repository contains my completed Computer Exercises (CEs) and project work from the **Knowledge Discovery and Data Mining** course at Claremont Graduate University.

## Contents

| File Name | Description |
|-----------|-------------|
| `Data Preprocessing & Outlier Detection` | CE1 – Data Preprocessing and Outlier Detection |
| `Classification Models & Confusing Matrix Evaluation` | CE2 – Classification and Decision Trees (Model Evaluation, Confusion Matrix, ROC) |
| `Clustering with K-Means & Hierarchial Methods` | CE3 – Clustering with K-means and Hierarchical methods |
| `Model Evaluation- Accuracy, Lift, and Stability Analysis` | CE4 – Model Evaluation: Accuracy, Lift, Stability |
| `Association Rule Mining with Apriori Algorithm` | CE5 – Association Rule Mining using Apriori Algorithm |
| `HR_Attrition_Analysis_Rohini_Vishwanathan.ipynb` | Bonus Project – HR Attrition Analysis using Python |

## 📌 Model Parameters & Settings

| CE | Parameters & Settings Used |
|----|----------------------------|
| **CE1** | **Dataset:** German Credit Data<br>**Target:** GOOD_BAD ('GOOD', 'BAD')<br>**Tree Criteria:** Gini, Entropy<br>**Min Samples per Leaf:** 3% or 6% of training set<br>**Max Depth:** 3<br>**Evaluation Weights:** Accuracy (0.60), Simplicity (0.20), Lift (0.10), Stability (0.10) |
| **CE2** | **Dataset:** Heart Data<br>**Target:** TARGET (Interval)<br>**Split Criteria:** Entropy, Gini, Squared Error, Absolute Error<br>**Min Samples per Leaf:** 2–6% of training set<br>**Max Depth:** 3–4<br>**Evaluation Weights:** Accuracy/Loss (0.55–0.60), Simplicity (0.25–0.30), Stability (0.10–0.20), Lift at 2nd decile |
| **CE3** | **Dataset:** ASIA (Asia Magazine)<br>**Clustering Methods:** Lloyd, Elkan, MacQueen<br>**Cluster Centers:** Random or K-Means++<br>**Distance:** Euclidean, Manhattan, Chi-square<br>**Normalization:** Z-score, Range<br>**No. of Clusters:** 2–4<br>**Outliers:** Defined as clusters with <10% of data |
| **CE4** | **Dataset:** ASIA & German Credit Data<br>**Clustering Algorithms:** Lloyd, Elkan, MacQueen<br>**Normalization:** Range or Z-score<br>**Cluster Count:** 2 or 3<br>**DT Criteria:** Entropy, Gini<br>**Min Leaf Size:** 6% of smallest cluster<br>**Max Depth:** 3<br>**Evaluation Weights:** Accuracy (0.60), Simplicity (0.40), or Accuracy (0.60), Lift (0.30), Stability (0.10) depending on question |
| **CE5** | **Dataset:** Crime Activities, Zoo, ASSOCS<br>**Algorithm:** Apriori<br>**Support Thresholds:** 15%, 25%<br>**Confidence Thresholds:** 60%, 70%, 75%<br>**Lift Thresholds:** 2.0–2.5<br>**Sequential Rules:** Support ≥ 20%, Confidence ≥ 50%<br>**Zoo Rules:** Support > 10%, Confidence ≥ 65%, Lift > 1.6 |
| **CE6** | **Dataset:** German Credit Data<br>**Target:** GOOD_BAD = 'BAD'<br>**Sampling:** Train 85%, Test 15% (Stratified)<br>**Models:** 6+ Neural Networks<br>**Hyperparameters:** Learning rate, optimizer, scheduler, loss function, regularization, batch size, epochs<br>**Evaluation Weights:** Accuracy (0.45), Lift (0.30), Stability (0.25)<br>**Thresholds:** Accuracy > 0.60, Lift > 0.25, Stability > 0.00 |


## Tools & Libraries
- Python (Google Colab)
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- mlxtend (for association rules)

---

These exercises cover the full data mining pipeline—from preprocessing to classification, clustering, association rules, and performance evaluation.

