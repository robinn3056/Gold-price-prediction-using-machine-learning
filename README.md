# Gold-price-prediction-using-machine-learning

This repository contains code for predicting gold prices using a machine learning model based on random forest regression. The project includes data loading, preprocessing, model training, evaluation, and visualization of results.

## Dataset
The dataset used for gold price prediction is stored in data/gold_prices.csv. This dataset contains historical gold prices along with relevant features such as date, high, low, open, close, volume, and adjusted close prices.

##Getting Started
To run the code in this repository, follow these steps:

Clone the repository:

bash-

git clone https://github.com/your-username/gold-price-prediction.git

Install the required dependencies:

"pip install -r requirements.txt"

Run the Jupyter notebooks:

1_data_preprocessing.ipynb: Data loading, preprocessing, and exploratory data analysis.
2_model_training.ipynb: Model training using random forest regression.
3_model_evaluation.ipynb: Model evaluation and visualization of results.

Data Preprocessing:

The dataset is loaded using pandas and preprocessed to handle missing values, outliers, and feature engineering.
Exploratory data analysis (EDA) techniques are applied to gain insights into the dataset and understand the relationships between features and target variable.

Model Training:

Random forest regression is used to train the machine learning model.
The dataset is split into training and testing sets to evaluate the model's performance on unseen data.

Model Evaluation:

Evaluation metrics such as R-squared (R2) score is used to assess the model's performance.
Visualizations such as scatter plots and line plots are generated to compare actual vs. predicted gold prices.

Results:
The trained model achieves R-square (R2) score on the test set.

Contributing:
Contributions to this project are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
