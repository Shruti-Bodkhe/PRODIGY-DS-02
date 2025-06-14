# PRODIGY-DS-02
Exploratory Data Analysis of the Titanic dataset using pandas, seaborn, and matplotlib
# 🚢 Titanic EDA (Exploratory Data Analysis)

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset from Kaggle. The main goal is to uncover patterns related to survival using various data visualization and cleaning techniques in Python.

---

## 📂 Dataset Details

- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **File used**: `train.csv`
- The dataset contains information about passengers such as age, gender, ticket class, and whether they survived.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- **pandas** – data handling
- **numpy** – numerical operations
- **matplotlib** – data visualization
- **seaborn** – advanced visualizations

---

## 🧪 Project Workflow

### 1. Data Loading
- Loaded `train.csv` into a pandas DataFrame

### 2. Handling Missing Values
- **Age**: filled using median value
- **Embarked**: filled using mode
- **Cabin**: dropped due to excessive missing values

### 3. Data Cleaning
- Converted `Sex` to numeric (male: 0, female: 1)
- Removed irrelevant features like `Ticket` and `Name` for clarity

### 4. Exploratory Visualizations
- Survival distribution
- Class vs Survival bar plots
- Age distribution (histogram)
- Correlation heatmap
- Gender-based survival insights

---

## 📊 Visual Outputs

Some of the visualizations included:
- 🔥 Correlation Heatmap
- 👨‍👩‍👧‍👦 Gender-wise Survival Rate
- 🛳️ Passenger Class vs Survival
- 🎂 Age Distribution
- ⚰️ Countplot of Survivors

These visuals help understand which factors had more influence on survival.

---

## 📁 File Structure

Titanic-EDA/
├── Titanic_EDA.ipynb # Jupyter notebook with all code and plots
├── train.csv # Titanic dataset
├── README.md # Project documentation


---

## 💻 How to Run This Project

### Option 1: Using Git
```bash
git clone https://github.com/Shruti-Bodkhe/Titanic-EDA.git
cd Titanic-EDA
jupyter notebook Titanic_EDA.ipynb
