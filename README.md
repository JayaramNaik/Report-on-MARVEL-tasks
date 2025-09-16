# Report-on-MARVEL-tasks By JAYARAM
A collection of MARVEL website tasks and resource articles completed as part of the course, including HTML projects, AI/ML reflections, and electronics experiments.
  
  ### Task 2: ***Building API*** 

I built a simple API that fetches and displays the "Astronomy Picture of the Day" using NASA's APOD API. This project helped me understand how to make API calls, handle JSON data, and manage asynchronous operatIons.   [Assignment 02 API](
https://jayaramnaik.github.io/Assignment-02-API-/)

### TASK 3:           **GitHub Repository:** 

For this task, I gained practical experience with essential Git workflows by cloning a repository, creating a new branch, and fixing an error. I then used a pull request to contribute my changes, which provided hands-on experience with **GitHub Actions**, **Issues**, and **Pull Requests**.

# ![WhatsApp Image 2025-08-21 at 12 51 32_68b7f06b](https://github.com/user-attachments/assets/c30183a2-043d-4072-9cee-3efa4e1e3e81)


### TASK 4: ###
### **Command Line Operations**

### **Command Line Operations Report**

I familiarized myself with commands and Ubuntu by completing a series of fundamental tasks. This included **directory and file management**, **efficiently creating 2600 subdirectories** using a loop, and **concatenating two text files** to display their content. The project demonstrates a practical understanding of core command-line operations. 
# ![WhatsApp Image 2025-08-21 at 12 53 09_c8b52049](https://github.com/user-attachments/assets/61b6f843-bac3-4795-9ee3-2da46341c809)



# 📊 Task 5: Build Your Own Brain – Linear Regression from Scratch

## 1. Objective
The aim of this task was to understand and implement the concept of **Linear Regression** from scratch using **Gradient Descent**, and to **compare its performance** with the inbuilt `LinearRegression` model from **scikit-learn** on the **California Housing dataset**.

---

## 2. Introduction
Linear Regression is one of the simplest and most fundamental supervised machine learning algorithms used for predicting continuous values. It establishes a linear relationship between the input features (X) and the target variable (y).

**Gradient Descent** is an optimization algorithm used to minimize the cost function by iteratively updating the model weights in the opposite direction of the gradient.

---

## 3. Methodology

### 3.1 Dataset
- Dataset used: **California Housing Dataset** from `sklearn.datasets`
- It consists of various housing-related features like:
  - Median income
  - House age
  - Average number of rooms, bedrooms, population
  - Latitude and longitude  
- Target variable: **Median House Value**

### 3.2 Data Preprocessing
- Loaded the dataset and converted it into a Pandas DataFrame
- Split data into training and testing sets (80:20)
- Applied **feature scaling (Standardization)** to improve gradient descent convergence speed

### 3.3 Custom Linear Regression Implementation
- Implemented the hypothesis function:  
  \[
  \hat{y} = XW + b
  \]
- Defined the cost function (Mean Squared Error):
  \[
  J(W,b)=\frac{1}{n}\sum_{i=1}^{n} (\hat{y}_i - y_i)^2
  \]
- Used **Gradient Descent** algorithm to update weights:
  \[
  W := W - \alpha \frac{\partial J}{\partial W}
  \]
  \[
  b := b - \alpha \frac{\partial J}{\partial b}
  \]
- Iteratively updated weights until convergence (for around 1000 epochs, learning rate ≈ 0.01)

### 3.4 Scikit-learn Linear Regression
- Imported `LinearRegression` from `sklearn.linear_model`
- Trained the model using the same training data
- Predicted target values on the test set
