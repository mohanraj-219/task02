# Task-02 – Exploratory Data Analysis (EDA)

## 📌 Objective
Perform data cleaning and exploratory data analysis (EDA) on a dataset of my choice.  
For this task, I used the *Titanic dataset* from Kaggle / Prodigy InfoTech GitHub.

Dataset Link:  
https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202

---

## 📊 Steps Performed

### 🔹 1. Import Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 🔹 2. Load Dataset
Loaded the Titanic dataset using Pandas and inspected:
- Head & Tail  
- Shape  
- Info  
- Missing values  

### 🔹 3. Data Cleaning
Performed:
- Handling missing values (Age, Cabin, Embarked)
- Converting categorical values to numeric (Sex, Embarked)
- Removing unnecessary columns (Ticket, Cabin, Name)

### 🔹 4. Exploratory Data Analysis (EDA)
Created visualizations to explore relationships:
- Age Distribution  
- Survival Count (Bar Plot)  
- Survival By Gender  
- Survival by Passenger Class (Pclass)  
- Fare Distribution  
- Correlation Heatmap  

All graphs are stored in the *output_plots/* folder.

---

## 📈 Key Insights
- Females had a much higher survival rate than males.  
- First-class passengers survived more compared to lower classes.  
- Younger passengers had a higher chance of survival.  
- Fare had a positive correlation with survival.

---

## 📁 Files Included
| File | Description |
|------|-------------|
| task02.ipynb | Jupyter Notebook with full EDA |
| task02.py | Python script version |
| dataset.csv | Titanic dataset |
| output_plots/ | Folder containing all plots |
| README.md | Documentation |

---

## ▶ How to Run
```bash
pip install pandas numpy matplotlib seaborn
python task02.py
