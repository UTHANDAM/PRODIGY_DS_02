#PRODIGY_DS_02

#  Prodigy Infotech – Data Science Internship (Task 2)

<img src="Prodigy_task_02.jpg" alt="Banner" style="width:100%; max-width:700px;">

Hello world   
I'm **Uthandam**, and this is my submission for **Task 2** of the **Prodigy InfoTech Data Science Internship**.

In this task, I performed **data cleaning** and **exploratory data analysis (EDA)** on a real-world dataset, drawing insights from its patterns and visualizing the relationships between various variables.

---

## 🗂️ Task Description

> “Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.”

📎 **Sample Dataset Reference:**  
[Click to View Dataset Repository](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202)

---

## 📁 Dataset Used

For this task, I used the **Titanic Dataset**, a classic dataset used to predict survival based on features like age, gender, ticket class, and more. The dataset is rich with patterns and perfect for EDA practice.

📄 **Filename:** `test.csv`  
🧩 **Features include**:
- `PassengerId`
- `Pclass` (Ticket class)
- `Name`
- `Sex`
- `Age`
- `SibSp` (Siblings/Spouses aboard)
- `Parch` (Parents/Children aboard)
- `Fare`
- `Embarked` (Port of Embarkation)
- And more...

---

## ⚙️ Tools & Libraries Used

The following Python libraries were used for cleaning, analyzing, and visualizing the dataset:

- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` – for basic plotting
- `seaborn` – for enhanced data visualization
- `missingno` – to visualize missing values (optional but cool!)

---

## 🔎 My EDA Process

### 1. **Understanding the Data**
- Loaded the CSV
- Displayed shape, types, and column info
- Used `.describe()` to get summary stats

### 2. **Cleaning the Data**
- Detected and handled missing values (e.g., imputed `Age`, dropped or filled `Embarked`)
- Converted categorical values into readable formats
- Handled duplicates and outliers

### 3. **Visualizing Relationships**
- Countplots for `Survived`, `Sex`, and `Pclass`
- Age distribution histograms
- Heatmaps for correlation
- Boxplots for Age across different passenger classes
- Pie charts to explore survival percentages

---

## 📊 Key Insights

- **Gender Matters:** Females had a higher survival rate compared to males.
- **Class Counts:** Passengers in higher classes had better chances of survival.
- **Age Trends:** Young children and adults had different survival patterns.
- **Embarkation Influence:** Port of embarkation had a minor impact on survival trends.

---

## ✅ Conclusion

Through this task, I dove deep into the Titanic dataset and uncovered some fascinating patterns. This hands-on EDA task sharpened my skills in:

- Data cleaning and preprocessing  
- Visual storytelling through plots  
- Understanding real-world data challenges

It’s amazing how raw CSV files can unfold stories when decoded with the right tools!

---

## 💬 Let's Connect

If you'd like to discuss this project or collaborate on something new, feel free to reach out on [LinkedIn](https://linkedin.com/) or drop a ⭐ on the repo!

---

> “Behind every number, there’s a story. EDA helps us find it.”

