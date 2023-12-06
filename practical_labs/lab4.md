## Practical Lab 4 - Multivariate Linear and Polynomial Regression, and Evaluation using R-Squared, MAPE and MAE.

_Note: The submission should be done as a notebook inside your `/students_submissions/STUDENT-ID/` folder, and as an HTML file, accessible online. Please provide the link to the HTML in eConestoga. There is no need to update the PR_

In this lab, we will run multivariate linear model and two polynomial regression models, and evaluate them using [R-squared](https://en.wikipedia.org/wiki/Coefficient_of_determination), Mean Absolute Percentage Error ([MAPE](https://en.wikipedia.org/wiki/Mean_absolute_percentage_error)) and Mean Absolute Error ([MAE](https://en.wikipedia.org/wiki/Mean_absolute_error)) metrices. The dataset will be Scikit-Learn's Diabetes dataset - the same one used in Practical Lab 3.

1. Get the data, and run a train-validation-test split. Description of each column can be found in [sklearn documentation](https://scikit-learn.org/stable/datasets/toy_dataset.html#diabetes-dataset). Look at the [documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html#sklearn.datasets.load_diabetes) for the `load_diabetes` method to know what are `as_frame` and `scaled` arguments are for.
2. Run a multivariate linear regression on all variables **(1 point)**
3. Run a polynomial regression of the 2nd degree on the BMI feature alone **(0.5 point)**
4. Run a multivariate polynomial regression of the 2nd degree on all variables (Hint: set `include_bias=False` in `PolynomialFeatures`) **(0.5 points)**
5. Compare the three models by looking at R-squared, MAPE and MAE. Explain what the values mean for a non-expert and add your insight about the values of each model. Note: You can add any further comparisons and code (this is not necessary for a perfect score, but will be reviewed and evaluated)  **(2 points)**
6. Please answer the following questions:
    1. How many trainable parameters are we fitting for each of the three models? Explain these values. Hint: for explaining the number of the trainable parameters of the polynomial regression, you can use `poly.get_feature_names_out()` **(1 point)**
    2. Which model would you choose for deployment, and why? **(1 point)**