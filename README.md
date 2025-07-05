# 🏠 Linear Regression on Boston Housing Dataset – From Scratch to scikit-learn

This project provides a **hands-on introduction to linear regression** by building the algorithm from the ground up and applying it to the **Boston Housing dataset**. You will go through multiple stages of implementation — from manually coding gradient descent to comparing with `scikit-learn` — while gaining valuable experience in machine learning workflows.

---

## 📌 Assignment Structure

This assignment is divided into **three parts**:

### Part 1 – Linear Regression from Scratch (No ML Libraries)
- Use only:
  - `numpy`
  - `scipy`
  - `pandas`
  - `matplotlib`
- Tasks:
  - Load and inspect the **Boston Housing dataset**
  - Implement linear regression manually using the **normal equation**
  - Evaluate the model on training and testing data

### Part 2 – Gradient Descent Optimization
- Extend Part 1 by using **gradient descent** to estimate linear regression parameters
- Visualize the **loss curve** over iterations
- Compare accuracy and convergence to closed-form solution

### Part 3 – scikit-learn Implementation
- Use `scikit-learn` to build a linear regression model
- Compare results, accuracy, and efficiency with your custom models
- Evaluate model performance using multiple metrics

---

## 🏠 Dataset Overview: Boston Housing

The **Boston Housing dataset** contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts. It includes **13 features** and **a target variable (`MEDV`)** which represents the **median house value** in $1000s.

Key features include:

- `RM`: Average number of rooms per dwelling  
- `LSTAT`: % lower status of the population  
- `PTRATIO`: Pupil-teacher ratio  
- `DIS`: Distance to employment centers  
- `CRIM`: Per capita crime rate  
- ... and more

---

## 🎯 Learning Objectives

- Understand the mathematics behind **linear regression**
- Implement and train a model using **gradient descent**
- Compare your custom model with `scikit-learn`'s implementation
- Interpret regression coefficients and residual errors
- Visualize and evaluate the model using key performance metrics

---

## 🧰 Tools & Libraries

### Allowed in Parts 1 & 2:
- `numpy` – numerical calculations
- `scipy` – optimization and math utilities
- `pandas` – data manipulation
- `matplotlib` – visualization

### Added in Part 3:
- `scikit-learn` – regression model and evaluation

---


## 📊 Evaluation Metrics

- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- R² Score  
- Residual plots  
- Gradient descent convergence curves

---


## 📜 License

- The Boston Housing dataset is publicly available and used here for educational purposes.
- This project is licensed under the MIT License.

---

## 💡 Final Thoughts

This assignment gives you a strong foundation in **machine learning by building a model from first principles**. Implementing linear regression manually not only deepens your understanding of optimization but also helps you appreciate the tools and abstractions provided by modern ML libraries.
