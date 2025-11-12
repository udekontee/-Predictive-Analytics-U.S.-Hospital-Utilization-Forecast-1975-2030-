# Predictive-Analytics-U.S.-Hospital-Utilization-Forecast-1975-2030
A time series and regression-based analysis of U.S. hospital admissions and average length of stay, featuring dual predictive modeling and confidence interval visualization.
---
# 📄 Project Overview
This project examines national hospital utilization patterns in the United States from 1975 to 2020, utilizing data from the Centers for Disease Control and Prevention (CDC).
Two predictive models were developed to forecast future healthcare utilization trends through 2030:
1) **Hospital Admissions Forecast** — Predicts changes in the number of inpatient admissions.
2) **Average Length of Stay Forecast** — Estimates shifts in patient stay durations (days per admission).

---

# 🎯 Objectives
- Analyze long-term trends in U.S. hospital admissions and inpatient length of stay.
- Build predictive models (linear & polynomial regression) to forecast future utilization.
- Visualize results through a dual-dashboard design including confidence intervals.
- Assess model accuracy using **R² and Mean Absolute Error (MAE)** metrics.

---

| Category            | Tools                                                 |
| ------------------- | ----------------------------------------------------- |
| Data Processing     | `pandas`, `numpy`, `pandas`, `numpy`, `sqlite3`, `sqlalchemy`                                   |
| Visualization       | `matplotlib`, `seaborn`, `plotly`                     |
| Predictive Modeling | `scikit-learn` (LinearRegression, PolynomialFeatures) |
| Statistical Metrics | `r2_score`, `mean_absolute_error`                     |
| Environment         | Jupyter Notebook, Python 3.11                         |

---

# 📊 Key Visualizations
<img width="781" height="446" alt="image" src="https://github.com/user-attachments/assets/bfe8222b-c329-4e7f-a864-e3fc504210d0" />

<sub>**Figure 1.** **Average duration of hospital stays per decade in the U.S. (1970–2020)**<sub>

<img width="722" height="446" alt="image" src="https://github.com/user-attachments/assets/b1296423-bda5-4f57-a6ca-d2d5d04623f1" />

<sub>**Figure 2.**  **Year-over-year trend in U.S. hospital admissions.**<sub> (Shows fluctuations tied to policy and population health shifts.)

<img width="886" height="411" alt="image" src="https://github.com/user-attachments/assets/2be4a270-0779-4c89-8687-de5a81a812c7" />

<sub>**Figure 3.**  **Combined dashboard comparing hospital admissions and average length of stay**<sub> 

- **Reveals parallel declines in utilization intensity and patient-stay duration.**

<img width="814" height="526" alt="image" src="https://github.com/user-attachments/assets/edfad7fa-9f82-4391-a4a8-908bf683ed7f" />


<sub> **Figure 4.**  **Comparison of admission volumes by hospital ownership category**<sub>
- **Nonfederal community hospitals dominate utilization**

<img width="840" height="511" alt="image" src="https://github.com/user-attachments/assets/919dc632-b786-464d-b3e8-332ca06b6778" />

<sub>**Figure 5.**  **Outpatient care shows exponential growth relative to inpatient admissions**<sub>


<img width="748" height="497" alt="image" src="https://github.com/user-attachments/assets/5b1b542d-41c4-45aa-a894-f91878241da9" />

<sub>**Figure 6**:  **Forecast of U.S. hospital admissions (1975–2030) using linear regression**<sub>

- Predicts a slight downward trend in admissions through 2030.
- Model: Linear Regression
- Interpretation: Gradual efficiency improvements in healthcare may reduce overall inpatient volumes.
  
<img width="780" height="508" alt="image" src="https://github.com/user-attachments/assets/10bf659f-a8d6-46b7-8e5c-a9ca112b9168" />

<sub>**Figure 7:**  **Forecast of U.S. average hospital stay duration (1975–2030) using polynomial regression/<sub>**

- Shows continuous decline and stabilization post-2020.
- Model: Polynomial Regression (Degree 2)
- **R² = 0.963, MAE = 0.13**

<img width="892" height="403" alt="image" src="https://github.com/user-attachments/assets/1357ac7f-0fab-4712-8ec4-aad490ee69a1" />

<sub>**Figure 8.**  **Dual forecast of hospital admissions and average length of stay (1975–2030) with 95% confidence intervals**<sub>

- Model: Polynomial Regression (Degree 2)
- R² (Admissions) = 0.071, MAE = 326,757
- R² (Length of Stay) = 0.963, MAE = 0.13 days

# 🧾 Combined Dashboard

***📁 File: Hospital_Utilization_Forecast_Dashboard_v2.png***

Features side-by-side forecast plots with 95% confidence intervals.

# 📈 Results Summary

| Metric             | Admissions Forecast | Length of Stay Forecast  |
| --------------     | ------------------- | ------------------------ |
| **R²**             |     0.071           | 0.963                    |
| **MAE**            | 326,757             | 0.13 days                |
| **Forecast Range** | 1975–2030           | 1975–2030                |
| **Trend**          | Stabilization       | Slight rebound post-2025 |

# 🧩 Insights

- Hospital admissions show cyclical variation with a minor decline over time.
- Average hospital stay duration has sharply decreased, aligning with healthcare digitization, improved outpatient care, and efficiency programs.
- Predictive modeling supports the trend toward **higher patient throughput and shorter inpatient stays nationwide.**

# 📚 Data Source

**Centers for Disease Control and Prevention (CDC)**
National Center for Health Statistics (NCHS) – National Hospital Utilization Data (1970–2020)

# 🧑‍💻 Author

**Dekky Analytics (2025)**
📧 udekontee@gmail.com
🔗 GitHub Profile
