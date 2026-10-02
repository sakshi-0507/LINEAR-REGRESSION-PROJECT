# Water Quality Prediction

This project is a simple **Machine Learning regression project** that predicts water quality based on different water parameters.

### Features Used

* pH
* Temperature
* Turbidity
* Conductivity

### Models Used

* Linear Regression
* Ridge Regression
* ElasticNet Regression

### Model Performance

The models performed very well on the test data.

**Linear Regression**

* Training R²: 0.9992
* Testing R²: 0.9991

**ElasticNet**

* R² Score: 0.9989
* RMSE: 1.12
* MAE: 0.87

I also tested the model with new water parameter values:

```text
pH: 6.7
Temperature: 15
Turbidity: 4
Conductivity: 250
```

The predictions were around **82**, depending on the model used.

### Tools & Libraries

Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook

### Project Goal

The main goal of this project is to understand how regression models can be used to predict water quality from basic water parameters.
