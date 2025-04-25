# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs a basic **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** to uncover insights about the passengers and their chances of survival. The analysis was done in **Google Colab** using Python, Pandas, Matplotlib, and Seaborn.

---

## 📂 Dataset

- Dataset Name: `titanic.csv`
- Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- Description: Includes information about Titanic passengers such as age, sex, class, fare, and whether they survived.

---

## 📊 Steps Covered in the Notebook

### 🔹 1. Data Loading and Overview
- Loaded CSV file
- Displayed dataset info and first few rows

### 🔹 2. Summary Statistics
- Used `.describe()` and `.info()` to summarize data

### 🔹 3. Handling Missing Values
- Filled missing values in:
  - `Age` with **median**
  - `Embarked` with **mode**
- Dropped `Cabin` due to excessive missing values

### 🔹 4. Visualizations
- **Histograms** for Age
- **Boxplots** for Fare
- **Correlation matrix** and **pairplots** for numerical relationships
- **Bar plots** to analyze survival rate by:
  - Gender
  - Class (Pclass)

### 🔹 5. Feature-Level Inferences
- Observed patterns like:
  - Higher survival for females
  - 1st class passengers had higher chances
  - Younger passengers had better survival rates

---

## 📦 Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib

You can install them using:

```bash
pip install pandas seaborn matplotlib
🚀 Run this in Google Colab
You can open the Colab notebook and upload titanic.csv to start exploring.

🧠 Author
Sreeleka Manickam

