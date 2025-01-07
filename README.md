# Breast Cancer Prediction using Logistic Regression

This project focuses on predicting whether a breast cancer tumor is malignant or benign using machine learning techniques. The model is implemented using Python and the Logistic Regression algorithm.

## Dataset
The dataset used for this project is the Breast Cancer dataset from the UCI Machine Learning Repository. It consists of 569 samples with 30 features for each sample, describing various characteristics of the cell nuclei present in breast cancer biopsies.

### Features:
- `diagnosis`: The target variable (M = Malignant, B = Benign)
- Various attributes of cell characteristics such as `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, and more.

## Dependencies
To run the project, you will need to install the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`

You can install them using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Data Preprocessing

1. **Loading Data**: 
   The data is loaded from a CSV file into a Pandas DataFrame.

2. **Cleaning Data**:
   - Dropped unnecessary columns like `id` and `Unnamed: 32`.
   - Encoded the target variable `diagnosis`, where `B` is labeled as `1` (Benign) and `M` as `0` (Malignant).

3. **Exploratory Data Analysis (EDA)**: 
   Basic statistics and analysis are performed on the dataset to understand its structure and detect any trends or patterns.

## Model Implementation

1. **Data Splitting**: 
   The dataset is split into training and testing sets (80% for training, 20% for testing).

2. **Logistic Regression**: 
   The model is trained using the Logistic Regression algorithm.

3. **Model Evaluation**: 
   The performance of the model is evaluated using the accuracy score on the test dataset.

## Results

The model's accuracy, along with other metrics, is calculated to measure its performance on the test data. The final model is able to classify the tumor as either malignant or benign with a high accuracy rate.

## License

This project is licensed under the [**MIT License**](LICENSE).
