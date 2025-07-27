# 🧹 Prodigy Infotech – Data Science Internship (Task 2)

<img src="Prodigy_task_02.jpg" alt="Banner" style="width:100%; max-width:700px;">

Hey there 👋  
I'm **Uthandam**, and this repository contains my submission for **Task 2** of the **Prodigy InfoTech Data Science Internship**.

In this task, I performed **Data Cleaning** and **Exploratory Data Analysis (EDA)** on a real-world dataset from Kaggle to discover insights, relationships, and trends hidden in the data.

---

## 📜 Task Description

> Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

📌 **Dataset Reference:**  
[https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)

---

## 🌍 About the Dataset

For this task, I used the famous [**Titanic - Machine Learning from Disaster**](https://www.kaggle.com/c/titanic/data) dataset — a classic for data scientists and machine learning practitioners. It provides details of passengers aboard the Titanic and aims to predict survival based on their attributes.

The dataset includes three files:

- `train.csv` – Training data with known survival outcomes
- `test.csv` – Test data for prediction (used in this task)
- `gender_submission.csv` – Sample submission file

🧩 I focused on the **`test.csv`** file for EDA. Key features include:

- `PassengerId`  
- `Pclass` (Ticket Class)  
- `Name`  
- `Sex`  
- `Age`  
- `SibSp` (Siblings/Spouses aboard)  
- `Parch` (Parents/Children aboard)  
- `Fare`  
- `Embarked` (Port of Embarkation)

---

## 🧰 Tools & Libraries

This project was developed using **Python** in a **Jupyter Notebook** environment with the following libraries:

- `pandas` and `numpy` – Data handling and preprocessing  
- `matplotlib` and `seaborn` – Visualization and plotting  
- `missingno` – To visually inspect missing data  
- Jupyter Notebook – For documenting analysis step-by-step

---

## 🔍 What I Did – A Quick Walkthrough

### 1. 📂 Understanding the Data
- Loaded the `test.csv` file  
- Explored shape, columns, and types  
- Used `.info()` and `.describe()` for basic insights

### 2. 🧼 Cleaning the Data
- Detected and handled missing values (`Age`, `Fare`, `Embarked`)  
- Filled nulls using techniques like median imputation  
- Converted data types where needed  
- Ensured consistency for analysis

### 3. 📊 Visualizing Patterns
- Countplots for `Pclass`, `Sex`, and `Embarked`  
- Boxplots for fare distribution across classes  
- Histograms to visualize age spread  
- Heatmaps to identify correlation between numeric variables  
- Pie charts to understand categorical proportions

---

## 💡 Key Takeaways

- **Class Difference**: Ticket class impacts features like fare and likely survival  
- **Gender Balance**: Slightly more males than females in the dataset  
- **Missing Values**: Age was the most common missing feature — median-based imputation worked well  
- **Fare Outliers**: Found some extreme fare values that were visualized and analyzed  
- **Age Distribution**: Passengers span a wide age range, with clustering around young adults

---

## 🎯 Conclusion

This task allowed me to practice and demonstrate core data science steps:
- Data ingestion  
- Cleaning and preprocessing  
- Exploratory Data Analysis  
- Visual storytelling using plots

I enjoyed exploring the Titanic dataset and surfacing insights from raw data. This task sharpened my understanding of EDA and reinforced the importance of prepping data before diving into modeling.


---

Thanks for checking out my work! 🙌  
Feel free to explore the notebook and reach out for any feedback or collaboration 🚀
