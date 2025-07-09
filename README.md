# Flipkart Customer Service Satisfaction Analysis


📈 **Final F1 Score:** `0.78  
🎓 **Grade Achieved:** ~7.5 / 10  
⭐ **Level:** Intermediate Machine Learning Project

## 🔍 Project Overview

- **Objective**: Predict whether a customer is satisfied based on delivery time, product rating, customer type, and product quality.
- **Dataset**: Synthetic data generated using the Faker library (~1,000 rows)
- **Target variable**: `satisfied_customer` (1 = satisfied, 0 = not satisfied)

---

## 🤖 Model Performance Summary

| Model                   | Accuracy | F1 Score | Hyperparameter Tuning |
|------------------------|----------|----------|------------------------|
| Logistic Regression     | 75%      | 0.72 → **0.74**     | ✅ GridSearchCV         |
| Random Forest Classifier| 80%      | 0.76     | ✅ GridSearchCV         |
| **SVM (Final Model)**   | **81%**  | **0.78** | ✅ GridSearchCV         |

✅ **Best Model Used**: **SVM**  
📈 **Final F1 Score Achieved**: `0.78`



## Run in GitHub Codespaces
1. Click the "Code" button
2. Select "Open with Codespaces"
3. Create new codespace
4. Open `satisfaction_analysis.ipynb`
5. Run all cells

## Run Locally
```bash
git clone https://github.com/<your-username>/flipkart-satisfaction-analysis.git
cd flipkart-satisfaction-analysis
pip install -r requirements.txt
jupyter notebook
```

## Key Outputs
- EDA visualizations in `plots/` directory
- Model evaluation metrics in notebook output
- Business insights in final cell output
