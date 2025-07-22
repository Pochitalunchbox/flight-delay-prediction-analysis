# ✈️ Flight Delay Prediction & Operational Optimization

**Logistic Regression, Bayesian Modeling, and Operational Analytics on U.S. Domestic Flights (1990–1999)**

This project explores over a decade of U.S. airline data to understand, predict, and optimize around flight delays. By combining machine learning and Bayesian inference, it generates actionable recommendations for airlines and operations teams.

---

## 💼 Problem Context

**Business Problem:** Flight delays cost airlines billions annually in fuel, scheduling, labor, and customer dissatisfaction. Can we predict diversions and identify controllable delay drivers?

**Goal:** Use logistic regression and probabilistic diagnostics to:
- Predict delay-related diversions.
- Identify delay factors (e.g., aircraft type, carrier, time-of-day).
- Recommend optimal flight scheduling windows.

---

## 🎯 Project Goals

- Clean and engineer features from flight and aircraft metadata.
- Train a **logistic regression model** to predict diversions.
- Validate model reliability using **Bayesian diagnostics (Metropolis-Hastings, R-hat)**.
- Deliver **real-world insights** for operations optimization.

---

## 🧠 Key Contributions

- Merged and cleaned 50,000+ flight records.
- Created engineered features: **aircraft age**, **scheduled time buckets**.
- Built interpretable models to identify **delay contributors**.
- Identified **best departure times** and **airline-specific delay patterns**.
- Applied **Bayesian MCMC sampling** and **R-hat convergence** to validate model stability.

---

## 🛠️ Tech Stack

| Category            | Tools/Methods                                      |
|---------------------|----------------------------------------------------|
| Programming         | Python                                             |
| Libraries           | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  |
| ML Techniques       | Logistic Regression, ROC AUC, Cross-Validation     |
| Bayesian Methods    | Metropolis-Hastings, Gelman-Rubin (R-hat), KDE     |
| Visualization       | Coefficient Plots, Bar Charts, KDE, Delay Trends   |

---

## 📊 Results Summary

| Metric              | Value                                                  |
|---------------------|---------------------------------------------------------|
| Dataset Size        | 50,000+ flight records                                  |
| Best Model          | Logistic Regression                                     |
| Accuracy            | 70–78%                                                  |
| Key Operational Insight | **Fly at 6 AM on Mondays** to minimize delays       |
| Top Feature Insight | **Aircraft age has no major delay impact**             |

---

## 🌟 Highlights & Visual Insights

### ✈️ Delay by Aircraft Age
![Delay by Age](results/Avg_Delay_By_Aircraft_Age_BarChart.PNG)  
> Older planes do not correlate strongly with delays, suggesting maintenance isn’t a primary factor.

### ⏳ Delay Trends Over Time
![Delay Over Time](results/Avg_Delay_By_Aircraft_Age_Over_Time.PNG)  
> Delays remained consistent across years, showing that age effect is stable.

### 🕒 Best Times to Fly
![Best Times Table](results/Best_Day_Hour_To_Minimize_Delays_Table.PNG)  
> Mondays at 6 AM have the lowest delay probability—ideal for critical travel.

### 🏢 Airline-Specific Impact
![Carrier Coefficients](results/Carrier_Impact_On_Delay_Coefficients_Over_Time.PNG)  
> Some carriers have consistently higher delay coefficients across time—insightful for benchmarking.

### 🔍 Model Coefficients
![LR Coefficients](results/Logistic_Regression_Coefficients_Over_Time.PNG)  
> Time of day and carrier are more predictive than aircraft age or route.

### 📈 Bayesian Diagnostics
![KDE](results/Kernel_Density_vs_Target_.PNG)  
![MCMC](results/MCMC_Rhat_Convergence_Diagnostic.PNG)  
> R-hat values show stable convergence across all model parameters.

---

## 📁 Repository Structure

| File / Folder                             | Description                                         |
|------------------------------------------|-----------------------------------------------------|
| `1_metropolis_hastings_sampling.ipynb`   | Custom MCMC sampling for logistic model             |
| `2_mcmc_diagnostics_gelman_rubin.ipynb`  | R-hat convergence validation and KDE plots          |
| `3_data_setup_directory_structure.ipynb` | Folder setup and data prep                          |
| `4_airline_delay_data_ingestion.ipynb`   | Dataset integration and cleaning                    |
| `5_feature_engineering_metadata_merge.ipynb` | Custom features (age, time buckets)             |
| `/results/`                              | Output visuals, tables, plots                       |

---

## 🔮 Limitations & Next Steps

- Model currently only handles binary classification (diversion vs. non-diversion); multiclass delay severity modeling is a future enhancement.
- Data only spans 1990–1999; insights may evolve with modern airline logistics and tech.
- A Tableau or Streamlit-based visualization dashboard would improve stakeholder access.

---

## 🔗 Author

**Ethan Choo**  
📍 Singapore | 🎓 Data Science & Business Analytics Graduate (SIM-UOL)  
🔗 [LinkedIn](https://www.linkedin.com/in/ethanchoo5/) | 🔗 [GitHub](https://github.com/ethan-analytics)

---

> For recruiters, hiring managers, or collaborators—feel free to ⭐ this project or reach out for a demo!

📍 Singapore | 🎓 Data Science & Business Analytics Graduate (SIM-UOL)  
🔗 [LinkedIn](https://www.linkedin.com/in/ethanchoo5/)  
