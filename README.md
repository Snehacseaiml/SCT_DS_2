# SCT_DS_2

# 🚢 Titanic Survival Prediction

## 💼 Task - Titanic ML Challenge | CodeSoft / SkillCraft Internship

This project aims to build a **machine learning model** to predict whether a passenger survived the Titanic shipwreck based on features such as age, sex, class, fare, and more. It is a classic binary classification problem widely used to learn data science workflows and modeling.

---

## 🎯 Objective

To predict survival on the Titanic using machine learning algorithms. The dataset contains features that describe each passenger and the goal is to classify them as:

- `1` – Survived  
- `0` – Did not survive

---

## 📁 Files Included

| File Name                  | Description                                               |
|---------------------------|-----------------------------------------------------------|
| `Task_02.ipynb`  | Jupyter Notebook with code, visualizations, and modeling. |
| `titanic.csv`             | Dataset containing passenger information.                 |
| `README.md`               | Project overview and documentation.                       |

---

## 📊 Dataset Overview

The dataset includes the following features:

- `PassengerId` – Passenger ID
- `Pclass` – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`, `Sex`, `Age` – Personal information
- `SibSp`, `Parch` – Family aboard
- `Ticket`, `Fare` – Ticket info
- `Cabin`, `Embarked` – Cabin and port
- `Survived` – Target variable (0 or 1)

📌 **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## ⚙️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** – Data preprocessing
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Machine Learning models

---

## 🛠️ Machine Learning Pipeline

1. **Data Cleaning**
   - Handling missing values
   - Converting categorical to numerical

2. **Exploratory Data Analysis (EDA)**
   - Survival rate by gender, class, age
   - Correlation heatmaps and distributions

3. **Feature Engineering**
   - Title extraction from names
   - Family size creation
   - Binning and encoding

4. **Modeling**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - KNN (optional)

5. **Evaluation**
   - Accuracy score
   - Confusion Matrix
   - Cross-validation

---

## 📈 Sample Results

| Model              | Accuracy  |
|-------------------|-----------|
| Logistic Regression | 80%+      |
| Random Forest       | 83%+      |
| Decision Tree       | ~78%      |

> Note: Results may vary depending on train-test split and hyperparameters.

---

## 🧠 Key Learnings

- How to clean and preprocess real-world datasets.
- Visualize data to gain insights.
- Use classification models and tune them.
- Apply proper validation and avoid overfitting.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Snehacseaiml/SCT_DS_2/blob/main/TASK_02.ipynb 
