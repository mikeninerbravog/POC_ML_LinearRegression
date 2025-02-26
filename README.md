# Machine Learning - Linear Regression Proof of Concept (POC)

This repository demonstrates **Linear Regression** applied to real-world scenarios using **Google Colab**. The examples include:

1. **Predicting Student Grades**: Estimating final grades based on previous test scores.
2. **Estimating Car Prices**: Predicting the price of a used car based on its age.

## What is Linear Regression?

Linear Regression is a mathematical technique used to model relationships between a dependent variable and one or more independent variables. It finds the best-fit line that represents the pattern in the data and uses it to make predictions.

### How It Works:
1. **Collect Data**: Gather historical data of independent and dependent variables.
2. **Plot a Graph**: Place the independent variable (X-axis) and dependent variable (Y-axis) in a scatter plot.
3. **Find the Best-Fit Line**: Use a mathematical approach to minimize errors.
4. **Make Predictions**: Use the line to estimate values for new data points.

## Running on Google Colab

### Step 1: Open in Colab
Click the links below to open the examples directly in **Google Colab**:
- [Predicting Student Grades](https://colab.research.google.com/github/your-repo/student_grades_prediction.ipynb)
- [Estimating Car Prices](https://colab.research.google.com/github/your-repo/car_price_prediction.ipynb)

### Step 2: Install Dependencies (if needed)
Colab comes with most libraries pre-installed, but if necessary, run:
```python
!pip install numpy matplotlib scikit-learn
```

### Step 3: Run the Cells
Each notebook contains explanations, data, and visualizations. Simply **execute the cells** in order.

## Example 1: Predicting Student Grades

This example trains a **Linear Regression model** using historical student test scores. Given a student's previous test scores, the model predicts their final grade.

### Notebook Highlights:
- **Input**: Previous test scores
- **Output**: Predicted final grade
- **Visualization**: Scatter plot with regression line

## Example 2: Estimating Car Prices

This script predicts the selling price of a used car based on its age. The Linear Regression model identifies a trend between **car age** and **price**, allowing predictions for new data points.

### Notebook Highlights:
- **Input**: Car age (years)
- **Output**: Estimated price (in thousands)
- **Visualization**: Scatter plot with regression trendline

## Visualizing Results

Both notebooks generate a **scatter plot** showing:
- **Blue dots** representing actual data points
- **A red regression line** indicating the trend
- **Green markers (X)** for predicted values

## Conclusion

Linear Regression is a fundamental concept in Machine Learning, widely used in **predictive modeling**. These examples illustrate its application in **education analytics** and **automobile pricing**, but the technique is also useful in **finance, marketing, and many other fields**.

## License

This project is released under the MIT License.

