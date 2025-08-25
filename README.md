# 📊 Data Analysis Assignment — BMI & Grip Strength Study

## 🎯 Project Aim

The goal of this assignment was to apply **Exploratory Data Analysis (EDA)** and **statistical modeling** techniques to a dataset of **BMI (Body Mass Index) and Grip Strength measurements**. The study explores growth patterns, gender differences, and develops predictive models for health-related insights.

---

## ⚙️ Methodology

* **Data Cleaning & Preparation**

  * Checked for missing values and anomalies.
  * Standardized variable names and ensured consistent data types.

* **Exploratory Data Analysis (EDA)**

  * Univariate analysis of BMI and Grip Strength distributions.
  * Bivariate analysis across **age groups** and **gender**.
  * Visualizations: histograms, scatterplots, correlation matrices.

* **Statistical Modeling**

  * Applied **GAMLSS (Generalized Additive Models for Location, Scale, and Shape)**.
  * Fitted **centile curves** to capture growth and strength variations.
  * Compared models on metrics such as AIC, BIC, and RMSE.

---

## 📊 Results & Insights

* **Gender Differences:**

  * Males generally displayed higher grip strength across age ranges.
  * BMI patterns showed less pronounced gender differences.

* **Age Trends:**

  * Grip strength increased with age up to adulthood, then plateaued.
  * BMI steadily increased, with slight differences by gender.

* **Model Performance:**

  * GAMLSS centile models effectively captured **nonlinear growth patterns**.
  * Chosen models achieved a good balance between accuracy and interpretability.

---

## 🛠️ Tools & Libraries

* **Languages:** R (primary), Python (EDA validation)
* **Key Packages:**

  * `gamlss` (centile curve modeling)
  * `ggplot2`, `dplyr` (visualizations & data wrangling)
  * `readr`, `tidyr` (data import/cleaning)

---

## 📂 Repository Structure

```
Data_analysis_assignment/
├─ Data_analysis_assignment.html   # Full analysis report
├─ Data_analysis_assignment.ipynb  # Jupyter version (if applicable)
├─ data/                           # Raw and cleaned datasets
├─ plots/                          # Exported figures
└─ README.md                       # Project summary
```

---

## 🔮 Future Work

* Expand dataset with more demographic variables.
* Incorporate **machine learning regression models** for BMI prediction.
* Explore **causal inference** methods for lifestyle-health relationships.

---

👉 This README positions the project as a **data-driven statistical study with real-world applications in health analytics**.

---

Do you want me to **embed some actual plots or numerical results** (like mean BMI, R² values, etc.) into the README so it looks more evidence-based, or keep it abstract and professional like this?
