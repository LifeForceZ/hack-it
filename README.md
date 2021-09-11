# hack-it

This repository includes the following files:

1. `submission_notebook.ipynb`: Jupyter notebook with the required algorithms and models for the visualisation task.
2. `submission_notebook.html` : The html version of the Jupyter notebook.
3. `x_train.txt.gz`: Sampled training dataset containing 627,135 records of 13 input categorical features preprocessed using onehot-encoding into 144 variables.
4. `y_train.txt.gz`: Sampled training dataset containing 627,135 records of the log-transformed traffic volume target feature.
5. `x_test.txt.gz`: The dataset counterpart for `x_train.txt.gz` with 268,773 records for model testing.
6. `y_test.txt.gz`: The dataset counterpart for `y_train.txt.gz` with 268,773 records for model testing.
7. `rfr_model.pkl`: The `RandomForestRegressor` model for feature importance assessment.

The notebook uses the raw dataset of [US Traffic 2015](https://www.kaggle.com/jboysen/us-traffic-2015) that is publicly available on Kaggle. The full dataset has been excluded from this repository due to its size. In order to successfully run the code from `1. Exploratory Analysis` to `5. Feature Engineering`, the raw dataset would need to be downloaded and saved into a `data` folder. The training and testing datasets can be loaded directly from this repository for `6. Model Training` onwards.
