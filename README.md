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

- **Training Set**: Used for data exploration, feature engineering, and training the models.
- **Test Set**: A separate dataset that undergoes the same transformation pipeline for unbiased evaluation.

> ℹ️ If your dataset is domain-specific (e.g., housing prices, medical data, retail sales), consider replacing this section with specific feature/column explanations.

## ⚙️ Installation & Requirements

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/yourproject.git
cd yourproject
pip install -r requirements.txt
