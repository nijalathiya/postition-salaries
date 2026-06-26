## How the Project Works

### 1. Data Collection
The project starts by loading the dataset containing **Position Level** and **Salary** values. This data is used to train the regression models.

### 2. Data Preparation
The dataset is divided into:
- **Independent Variable (X):** Position Level
- **Dependent Variable (y):** Salary

This allows the models to learn the relationship between position level and salary.

### 3. Linear Regression
Linear Regression is applied to determine whether a straight-line relationship exists between the position level and salary.

**Why it is used:**
- It is simple and easy to understand.
- It works well when the relationship between variables is approximately linear.
- It serves as a baseline model for comparison.

### 4. Polynomial Regression
Polynomial Regression transforms the input data into higher-degree features before training the model.

**Why it is used:**
- It captures non-linear relationships.
- It produces a curved line that can better fit complex datasets.
- It generally provides more accurate predictions when the data does not follow a straight-line pattern.

### 5. Model Visualization
The predictions from both models are plotted along with the original data points.

**Purpose:**
- To compare how each model fits the dataset.
- To visually observe the difference between a linear fit and a polynomial curve.

### 6. Prediction
After training, both models are used to predict the salary for a new position level.

**Purpose:**
- To estimate salary values for positions that are not present in the dataset.
- To compare the prediction accuracy of Linear Regression and Polynomial Regression.

## Conclusion

This project demonstrates the difference between Linear Regression and Polynomial Regression. While Linear Regression fits a straight line, Polynomial Regression can model curved relationships and often provides more accurate predictions for non-linear datasets.
