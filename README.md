# airline-delay-prediction-logreg
Logistic regression analysis of U.S. airline delay data (1990–1999). Includes custom MCMC sampling, Bayesian diagnostics, and predictive feature engineering for flight delay classification.

# ✈️ Flight Delay Prediction & Operational Insights

This project explores and predicts U.S. domestic flight delays using a dataset of over 50,000 records. I applied data cleaning, feature engineering, logistic regression modeling, and insights generation using Python and Scikit-learn.

## 📊 Project Goals
- Identify factors influencing flight delays.
- Predict flight diversions using logistic regression (achieved **78% accuracy**).
- Derive insights to optimize scheduling and reduce disruptions.

## 🧠 Key Contributions
- Engineered features like plane age and delay duration.
- Evaluated model performance using cross-validation and ROC AUC.
- Found weak correlation between plane age and delays.
- Delivered data-driven scheduling recommendations.

## 🛠 Tools Used
- Python (Pandas, Scikit-learn, Matplotlib)
- Jupyter Notebooks
- Logistic Regression, Data Cleaning, EDA

## 🔍 Results Summary
| Metric | Result |
|--------|--------|
| Records Analyzed | 50,000+ |
| Model Used | Logistic Regression |
| Accuracy | 78% |
| Key Insight | Older aircraft ≠ higher delay probability |

## 📁 File Structure
- `01_data-cleaning-aggregation.ipynb`: Merged flight & aircraft data
- `02_eda-feature-engineering.ipynb`: Feature selection and exploration
- `03_modeling-logistic-regression.ipynb`: Logistic regression modeling
- `04_model-evaluation-analysis.ipynb`: Cross-validation & performance
- `05_insights-recommendations.ipynb`: Final insights and conclusions

## 🚀 Author
[Ethan Choo](https://www.linkedin.com/in/ethanchoo5)
