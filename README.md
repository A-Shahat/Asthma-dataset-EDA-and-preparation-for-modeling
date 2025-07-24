# 🫁 Asthma Dataset Analysis

This project explores and analyzes an **asthma patient dataset** to uncover insights and patterns that relate to asthma control levels, emergency visits, and medication adherence. The notebook includes data cleaning, exploratory data analysis (EDA), and statistical evaluations using Python's data stack.

---

## 📁 Files Included

- `Asthma.ipynb` — Jupyter Notebook containing the full analysis workflow.
- `Asthma.csv` — dataset used for the analysis.

---

## 📊 Project Objectives

- Clean and preprocess the asthma dataset
- Handle missing values logically using conditional imputation
- Explore trends and relationships between key health metrics
- Visualize relationships to understand asthma control levels
- Apply statistical tests to verify assumptions and correlations

---

## 📌 Main Steps

1. **Data Cleaning**
   - Dropped unnecessary columns
   - Filled missing values in `Asthma_Control_Level` based on:
     - `Number_of_ER_Visits`
     - `Medication_Adherence`

2. **Data Inspection**
   - Reviewed shape, column data types, and missing values
   - Displayed unique value counts for each feature

3. **Exploratory Data Analysis (EDA)**
   - Visualizations using:
     - `seaborn.pairplot`
     - KDE plots
     - Boxplots and countplots grouped by asthma control levels
   - Checked correlations between numerical variables

4. **Statistical Analysis**
   - Used **scipy** to perform:
     - ANOVA
     - T-tests
     - Chi-square tests (where applicable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- SciPy
- Jupyter Notebook

---

## 📈 Key Insights

- Patients with **0 ER visits** and **high medication adherence** are typically *well-controlled*.
- High number of ER visits with low adherence likely indicates *poor control*.
- Visual trends suggest strong links between medication adherence and asthma outcomes.

---

## 🙋‍♂️ Author

**Ahmed El-Shahat**  
Data Analyst | Aspiring Data Scientist  
📍 Cairo, Egypt

---

## ✅ License

This project is open source and available under the [MIT License](LICENSE).
