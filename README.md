# 🧠 Regression ML Project

This project demonstrates a complete end-to-end regression machine learning pipeline — from raw data preprocessing to model specification and evaluation — using Python and Jupyter Notebooks.

## 📂 Project Structure

The project is structured into modular Jupyter Notebooks:

- `Data_wrangling.ipynb` – Loads the raw dataset and performs cleaning and transformation.
- `EDA_Feature_Engineering.ipynb` – Explores the data visually and statistically, and creates new features to improve model performance.
- `Testset_featureeng.ipynb` – Applies the same feature engineering steps to the test dataset to ensure consistency and prevent data leakage.
- `Model_specification.ipynb` – Trains various regression models, evaluates their performance, and compares results using different metrics.

## 📊 Dataset Description

The dataset used in this project includes structured tabular data containing both numerical and categorical features. Each row represents a sample (such as a product, house, customer, etc.), and the target variable is a continuous value we aim to predict using regression.

- **appartments_train**: Orginal train data from the teachers
- **aparts_train**: Used for data exploration, feature engineering, and training the models.
- **aparts_test**: Test subset with raw data (before handling missing values, feature engineering...)
- **aparts_train_ready**: aparts_train ready for modelling (after data preprocessing, feature engineering...)
- **aparts_test_ready**: Test subset after exactly the same processing pipeline as the train subset
- **appartments_test** : Orginal test data from the teachers. The only dataset not to be in the Datasets folder



