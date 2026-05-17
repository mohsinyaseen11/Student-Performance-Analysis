# 🎓 Student Performance & Attendance Analysis System

## 📌 Project Overview
This project is a Python and Pandas-based data analysis system that processes a real-world styled student dataset. The dataset contains missing values, inconsistent formats, and noisy data to simulate real-world scenarios.

The goal is to clean the data, perform analysis, and generate meaningful insights like grades, rankings, and performance metrics.

---

## 🚀 Features

### 1️⃣ Data Cleaning
- Handling missing values (NaN)
- Converting invalid values using `to_numeric`
- Removing `%` from attendance
- Replacing invalid entries like "N/A" and "absent"

### 2️⃣ Feature Engineering
New columns created:
- Total Marks
- Average Marks
- Percentage
- Performance Score
- Efficiency Score

### 3️⃣ Grade System
Grades assigned based on percentage:
- A: 85 and above
- B: 70–84
- C: 50–69
- Fail: Below 50

### 4️⃣ Analysis
- Top performing student
- Lowest performing student
- Highest attendance student
- Subject-wise averages
- Assignment performance analysis

### 5️⃣ Filtering
- Students with Attendance < 75
- Students with Average > 70
- Grade A students
- Fail students with good attendance

### 6️⃣ Ranking
- Top 5 students by percentage
- Lowest 5 students
- Top 3 efficiency students

---

## 🛠 Technologies Used
- Python 🐍
- Pandas 📊

---

## 📂 Project Structure
```
student-performance-analysis/
│
├── students_record.csv
├── Student_Performance_&_Attendance_Analysis_System.ipynb
└── README.md
```

---

## ▶ How to Run

### Step 1: Install requirements
```
pip install pandas
```

### Step 2: Run script
```
Student_Performance_&_Attendance_Analysis_System.ipynb
```

---

## 📊 Key Learning Outcomes
- Data cleaning in real-world datasets
- Handling missing and inconsistent data
- Feature engineering techniques
- Data analysis using Pandas
- Ranking and filtering data

---

## 👨‍💻 Author
Mohsin Ali

---

## ⭐ Future Improvements
- Add data visualization (Matplotlib / Seaborn)
- Build dashboard version
- Export results to Excel
- Add GUI interface

---

## 🔥 Note
This project is designed for learning and portfolio building purposes. It demonstrates practical data analysis skills using Python.

