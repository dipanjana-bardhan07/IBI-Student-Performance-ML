# 🎓 Student Performance Prediction System

## Machine Learning Internship Project — IBI

A Machine Learning based regression project developed during the **IBI Machine Learning Internship Program**.

The objective of this project is to analyze student academic factors and build a predictive model that estimates a student's **Final Exam Score** based on attendance, study patterns, previous performance, and other relevant attributes.

---

# 📌 Project Objective

The goal of this project is to develop an end-to-end Machine Learning workflow that includes:

- Data collection and preparation
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training
- Model evaluation
- Real-time prediction

This project demonstrates the application of Machine Learning techniques to solve a real-world educational analytics problem.

---

# 📊 Problem Statement

Student academic performance depends on multiple factors such as:

- Attendance
- Study hours
- Assignment completion
- Previous exam scores
- Classroom participation
- Parent education level
- Availability of learning resources

The task is to build a regression model that can predict the expected final exam score of a student using these features.

---

# 📁 Dataset Description

The dataset contains student-related academic information.

## Features:

| Feature | Description |
|---|---|
| StudentID | Unique student identifier |
| Age | Student age |
| Gender | Student gender |
| AttendancePercentage | Attendance percentage |
| StudyHoursPerWeek | Weekly study hours |
| AssignmentCompletionRate | Assignment completion percentage |
| PreviousExamScore | Previous exam performance |
| ParticipationScore | Classroom participation score |
| ExtracurricularActivities | Activity participation |
| InternetAccessAtHome | Home internet availability |
| ParentEducationLevel | Parent education level |

### Target Variable:

`FinalExamScore`

The model predicts this value.

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

✔ Checked dataset structure  
✔ Removed duplicate records  
✔ Handled missing values  

Numerical columns:
- Filled missing values using median

Categorical columns:
- Filled missing values using mode

Feature transformation:
- Converted categorical values into numerical format

---

# 🔎 Exploratory Data Analysis

The project includes:

## 📈 Attendance vs Final Score

Analyzed the relationship between attendance and academic performance.

## 📚 Parent Education Analysis

Studied how parent education level impacts student scores.

## 🔥 Correlation Analysis

Identified relationships between important academic features.

## 📊 Score Distribution

Visualized the distribution of final exam scores.

---

# 🤖 Machine Learning Model

## Random Forest Regressor 🌲

The model used:

```
RandomForestRegressor
```

### Why Random Forest?

- Handles complex relationships
- Works well with tabular datasets
- Reduces overfitting
- Provides stable predictions

---

# 📏 Model Evaluation

The model performance is measured using:

### MAE
Mean Absolute Error

### MSE
Mean Squared Error

### RMSE
Root Mean Squared Error

### R² Score
Measures how well the model explains the variation in target values.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Seaborn | Data Analysis |
| Scikit-Learn | Machine Learning |

---

# 📂 Project Structure

```
IBI-Student-Performance-ML

│
├── data/
│   └── student_performance_dataset.csv
│
├── Notebook/
│   └── student_performance_analysis.ipynb
│
├── models/
│
├── src/
│
├── requirements.txt
│
└── README.md
```

---

# ▶️ How To Run

Clone the repository:

```bash
git clone https://github.com/dipanjana-bardhan07/OIBSIP.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```
Notebook/student_performance_analysis.ipynb
```

Run all cells.

---

# 🔮 Future Improvements

Future enhancements:

- Deploy model using Streamlit
- Create web-based prediction interface
- Compare multiple ML algorithms
- Add automated student performance recommendations

---

# 👩‍💻 Author

**Dipanjana Bardhan**

Machine Learning Intern  
IBI Internship Program

---

⭐ This project demonstrates practical implementation of Machine Learning concepts on real-world educational data.