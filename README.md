# 🛳️ Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of the Titanic dataset using Python. The goal is to extract insights from the data using statistical and visual exploration techniques.

---

## 📁 Project Structure


---

## 📌 Objective

Perform an in-depth EDA on the Titanic dataset to identify trends, patterns, and relationships in the data that may help in building predictive models later.

---

## 🔧 Tools Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Dataset Description

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Rows**: 891 passengers
- **Columns**: 12 features
- **Target**: `Survived` (0 = No, 1 = Yes)

### Columns:

- `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 🧪 Exploratory Steps

### 1. **Data Overview**
- `df.info()` and `df.describe()` used to get basic info and summary statistics.
- Checked for missing values.

### 2. **Univariate Analysis**
- Histograms for `Age`, `Fare`, etc.
- Count plots for `Survived`, `Sex`, `Embarked`

### 3. **Bivariate Analysis**
- Boxplots and scatterplots
- Correlation heatmap
- Pairplot for selected numerical variables

### 4. **Categorical Insights**
- Grouped survival rate by `Sex`, `Pclass`, and `Embarked`

### 5. **Key Visualizations**
- `sns.heatmap()`
- `sns.boxplot()`
- `sns.histplot()`
- `sns.countplot()`
- `sns.pairplot()`

---

## 💡 Key Findings

| Feature   | Insight |
|-----------|---------|
| Age       | Younger passengers had higher survival chances |
| Fare      | Passengers who paid more had better survival rates |
| Sex       | Females had much higher survival rates |
| Pclass    | First-class passengers were more likely to survive |
| Embarked  | Passengers from Cherbourg had higher survival probability |
| Cabin     | Majority of values missing — may not be useful without imputation |

---

## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda
