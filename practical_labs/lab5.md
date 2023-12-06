## Lab 5 - Cross-Validation for Model Selection

**There are no changes to the regular submission process. Simply provide a link to a live HTML through eConestoga**

### Task

1. Utilize the diabetes dataset from lab 4. Perform cross-validation on nine polynomial models, ranging from degree 0 to 8 (2 points). consider using the `cross_validate` function as it provides a list of scoring functions as an input. Don't forget to have a test set aside.
2. Construct a table summarizing the cross-validation results: Each model should have a separate row in the table. Have the mean and standard deviation of the R-Squared, Mean Absolute Error (MAE) and MAPE metrics for each model. (2 points)
3. Identification of the Best Model: Identify the model that exhibits the highest performance based on the R-Squared, MAE and MAPE metrics. Provide an explanation for choosing this specific model. run the model on the test set and provide results (R-Squared, MAPE, MAE) (1 points)
4. Additional analysis and interpretation of the models' performances. Explore further findings beyond the required metrics. The analysis should provide at least one relevant insight about the choice of the best model (for example - an analysis of in which instances does it fail), or further insights comparing the models (1 point).