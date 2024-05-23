# Diabetes Prediction Project

This project aims to develop a machine learning model for predicting the likelihood of a person having diabetes based on various health factors. The model is trained using the Diabetes dataset, which includes features such as glucose level, blood pressure, age, and body mass index (BMI).

## Dataset

The [Diabetes dataset](https://archive.ics.uci.edu/ml/datasets/Diabetes) is a commonly used dataset for machine learning tasks related to diabetes prediction. It contains several medical predictor variables and one target variable (Outcome) indicating whether the patient has diabetes or not.

## Requirements

- Python 3.6 or later
- NumPy
- Pandas
- Scikit-learn

## Usage

1. Clone the repository:

```
git clone https://github.com/MdZaid27/diabetes-prediction.git
```

2. Navigate to the project directory:

```
cd diabetes-prediction
```

3. Install the required dependencies:

4. Run the Jupyter Notebook:

```
jupyter notebook
```

This will open the Jupyter Notebook interface in your default web browser.

5. Open the `Diabetes Prediction.ipynb` notebook and follow the instructions provided.

## Project Structure

```
diabetes-prediction/
├── Diabetes Prediction.ipynb   # Jupyter Notebook containing the code
├── diabetes.csv                # Diabetes dataset
├── README.md
```

## Methodology

The project follows these steps:

1. **Data Collection**: Load the diabetes dataset from the CSV file.
2. **Exploratory Data Analysis**: Analyze the dataset to understand its characteristics and identify any potential issues.
3. **Data Preprocessing**: Split the dataset into features (X) and target variable (y), and standardize the feature data using StandardScaler.
4. **Model Training**: Train a Support Vector Machine (SVM) classifier on the training data.
5. **Model Evaluation**: Evaluate the trained model's performance on the test data using accuracy score.
6. **Prediction**: Use the trained model to make predictions on new, unseen data.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
