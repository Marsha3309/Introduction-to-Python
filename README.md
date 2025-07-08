# Introduction-to-Python
# 🎓 Introduction to Python: Student Grade Evaluation Project

This project is a beginner-friendly Python notebook that introduces basic concepts using a practical example: evaluating student grades. It’s built and executed using **Google Colab**, making it easy to access and modify for learning purposes.

---

## 📌 Project Background

As a beginner in Python, it’s essential to understand how to:
- Store and handle input data using **variables**
- Identify the **data types**
- Apply **logical decision-making** using if-elif-else
- Format and display readable **outputs**

This project simulates a small system that accepts student information (name, student ID, and exam score), processes the score, categorizes it into a grade, and finally displays the result.

---

## 🔍 Learning Objectives

By exploring this notebook, you'll learn how to:
- Use variables and assign different data types
- Use `type()` to check variable types
- Use `if`, `elif`, and `else` to control flow based on conditions
- Format output using **f-strings** for clear presentation

---

## 💡 Code Walkthrough & Insights
```python
### 🟢 Step 1: Define Input Variables

# Input data stored directly into variables
name = "Disudrin"
student_id = "0554327122"
score = 98

### 🟢 Step 2: Check Variable Data Types

# Displaying the data type of each input
print(f"\nName: {name} (type: {type(name)})")
print(f"Student ID: {student_id} (type: {type(student_id)})")
print(f"Score: {score} (type: {type(score)})")

### 🟢 Step 3: Grade Categorization with If-Elif-Else

# Determining the score category using if-elif-else
if 85 <= score <= 100:
    grade = "A (Excellent)"
elif 75 <= score <= 84:
    grade = "B (Good)"
elif 60 <= score <= 74:
    grade = "C (Average)"
elif 40 <= score <= 59:
    grade = "D (Poor)"
else:
    grade = "E (Very Poor)"

###🟢 Step 4: Display the Final Evaluation

# Displaying the evaluation result
print("\nEvaluation Result:")
print(f"Student: {name} (ID: {student_id})")
print(f"Exam Score: {score} Grade: {grade}")












