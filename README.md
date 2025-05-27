Task 2 : - Exploratory Data Analysis (EDA) : Data visualization, descriptive statistics, pattern recognition.
# AI & ML Internship - Task 2: Exploratory Data Analysis (EDA)

## 📌 Objective
To explore and understand the structure, patterns, and relationships within the Titanic dataset using descriptive statistics and data visualization techniques.

---

## 🗂️ Dataset Used
- `cleaned_titanic.csv` (generated from Task 1)
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🧠 What I Did

### 1. Summary Statistics
- Used `.describe()` to get an overview of the dataset.
- Observed distributions, means, medians, standard deviations, etc.

### 2. Visualizations
- **Histograms** for numeric features like `Age`, `Fare`.
- **Boxplots** to detect outliers and understand spread.
- **Countplots** to visualize survival based on `Sex` and `Pclass`.
- **Correlation Matrix** to check relationships between features.
- **Pairplots** for pairwise feature interactions.
- Checked for **skewness** in numeric features.

---

## 📊 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional)

---

## 🔍 Key Insights
- Females had higher survival rate.
- Passengers in higher classes (`Pclass=1`) survived more.
- `Age` and `Fare` were slightly skewed and had outliers.
- `Fare` and `Pclass` were inversely correlated.

---

## 📁 Files Included
- `Task2_EDA_Titanic.ipynb`: Colab notebook with all EDA steps.
- `README.md`: Documentation of what was done.

---

## ✅ Status
✔️ Task Completed and Submitted.
