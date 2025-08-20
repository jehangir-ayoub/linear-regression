# linear-regression
this is linear regression model where it is build from scratch and tested on salary and work experience dataset .this is the basic building model where we have one input feature and one target column 


---

# Linear Regression from Scratch

This project demonstrates a simple implementation of **Linear Regression using Gradient Descent** in Python, without relying on built-in machine learning libraries like `scikit-learn`. It is applied on a **Salary Prediction Dataset** (Years of Experience vs Salary).

---

##  Project Structure

```
linear_regression.py   # Main Python script
salary_data.csv        # Dataset (YearsExperience, Salary)
README.md              # Project documentation
```

---

##  What is Linear Regression?

Linear Regression is a supervised machine learning algorithm used for predicting continuous values.
It assumes a linear relationship between **independent variable (X)** and **dependent variable (Y)**:

$$
Y = wX + b
$$

* **w** → weight (slope)
* **b** → bias (intercept)
* **Gradient Descent** is used to minimize the loss and update parameters.

---

##  Workflow

1. Initialize learning rate and number of iterations.
2. Start with weights and bias as **zero**.
3. Compute predictions using the equation $Y = wX + b$.
4. Calculate gradients (dw, db) using the loss function.
5. Update parameters with gradient descent.
6. Repeat steps 3–5 until convergence.
7. Evaluate model on test data and visualize results.

---

## 🚀Installation & Requirements

Make sure you have Python 3.x installed.
Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

##  How to Run

1. Place the dataset file `salary_data.csv` in the same folder.
   Example dataset format:

   ```csv
   YearsExperience,Salary
   1,30000
   2,35000
   3,40000
   ...
   ```
2. Run the script:

   ```bash
   python linear_regression.py
   ```
3. The program will:

   * Train a linear regression model.
   * Print learned weight `w` and bias `b`.
   * Predict salaries for test data.
   * Plot actual vs predicted values.

---

##  Sample Output

* Learned Parameters:

  ```
  Weight (w): 9360.26
  Bias (b): 26771.45
  ```
* Prediction Visualization:

Scatter plot of **actual salaries** vs **predicted regression line**.

---

##  Key Functions

* **`fit(X,Y)`** → Train model using gradient descent.
* **`predict(X)`** → Predict target values for given inputs.
* **`update_weights()`** → Update `w` and `b` based on gradients.

---

##  Learning Concepts

* Linear Regression basics.
* Gradient Descent optimization.
* Splitting dataset into training & testing.
* Visualizing regression line vs actual data.

---

##  Next Steps
* Extend to multiple linear regression (multiple features).
* Add performance metrics (MSE, R² score).
* Deploy using Flask/FastAPI.

---

 **Author**: jehangir ayoub
 **Dataset**: Salary Data  needed (Years of Experience vs Salary)



