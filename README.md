# 🫁 Asthma Dataset Analysis

This project explores and analyzes an **asthma patient dataset** to uncover insights and patterns that relate to asthma control levels, emergency visits, and medication adherence. The notebook includes data cleaning, exploratory data analysis (EDA), and statistical evaluations using Python's data stack.

---

## 📁 Files Included

- `Asthma.ipynb` — Jupyter Notebook containing the full analysis workflow.
- `Asthma.csv` — (Expected) dataset used for the analysis. *(Ensure this is included in your repository.)*

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

## 📌 How to Use

```bash
# Clone the repository
git clone https://github.com/your-username/asthma-analysis.git
cd asthma-analysis

# Open the notebook
jupyter notebook Asthma.ipynb
```

Ensure `Asthma.csv` is in the same directory as the notebook.

---

## 🙋‍♂️ Author

**Ahmed El-Shahat**  
Pharmacist | Data Analyst | Aspiring Data Scientist  
📍 Cairo, Egypt

---

## ✅ License

This project is open source and available under the [MIT License](LICENSE).