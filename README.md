# 📚 Study Hours vs Exam Score Prediction  
### Linear Regression from Scratch

A simple Machine Learning project that predicts **student exam scores based on study hours** using **Linear Regression implemented from scratch in Python**.

This project focuses on understanding the **mathematics behind machine learning**, including cost functions and gradient descent.

---

# 🚀 Project Overview

The goal of this project is to model the relationship between:

```
Study Hours → Exam Score
```

Using a **Linear Regression model**, the algorithm learns a line that best fits the training data.

The implementation **does not use machine learning libraries** like `scikit-learn`.  
Instead, the model is built manually using **NumPy and Gradient Descent**.

---

# 🧠 Machine Learning Concepts Used

This project demonstrates the core concepts behind linear regression:

• Linear Model  
• Cost Function (Mean Squared Error)  
• Gradient Descent Optimization  
• Model Training  
• Prediction on unseen data  

---

# 📊 Dataset

Example dataset used:

| Study Hours | Exam Score |
|-------------|------------|
| 1 | 35 |
| 2 | 40 |
| 3 | 50 |
| 4 | 55 |
| 5 | 65 |
| 6 | 70 |
| 7 | 80 |
| 8 | 88 |

---

# 📈 Linear Regression Model

The prediction function follows:

```
ŷ = w ⋅ x + b
```

Where:

| Symbol | Meaning |
|------|------|
| x | Study hours |
| ŷ | Predicted exam score |
| w | Weight (slope) |
| b | Bias (intercept) |

The parameters **w and b** are learned using **Gradient Descent**.

---

# ⚙️ Technologies Used

• Python 🐍  
• NumPy  
• Matplotlib  
• Jupyter Notebook  

---

# 📉 Training Visualization

The project includes visualizations such as:

• Dataset scatter plot  
• Linear regression best-fit line  
• Cost vs Iterations graph  

These help visualize how the model learns during training.

---

# 🔮 Example Prediction

Example prediction using the trained model:

```
Study Hours: 4.5
Predicted Score: ~60.37
```

---

# 📂 Project Structure

```
study-hours-exam-score-linear-regression
│
├── study_hours_exam_score_linear_regression.ipynb
└── README.md
```

---

# 🎯 Key Learning Outcomes

Through this project, we understand:

• How Linear Regression works internally  
• How Gradient Descent updates model parameters  
• How models learn patterns from data  
• How to visualize model performance  

---

# 📌 Future Improvements

Possible improvements:

• Use a larger real-world dataset  
• Add multiple features (sleep, attendance, assignments)  
• Implement feature scaling  
• Compare with `scikit-learn` implementation  

---

# 👨‍💻 Author

**Hemanth M**

Computer Science Student | Machine Learning Enthusiast
