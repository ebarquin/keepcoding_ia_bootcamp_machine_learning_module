# 📖 Machine Learning Practice - Bootcamp IA

This repository contains the solution for the Machine Learning practice as part of the Artificial Intelligence Bootcamp. The objective is to predict the price of Airbnb listings using real-world data. The project follows a structured ML workflow including data preprocessing, exploratory data analysis, feature engineering, model selection, and evaluation.

## 📌 Project Description

The goal of this practice is to build a predictive model for Airbnb prices. The dataset is obtained through web scraping and requires thorough preprocessing before applying machine learning models. The practice involves:

- Data cleaning and preprocessing.
- Feature engineering and selection.
- Model training and evaluation.
- Interpretation of results and insights.

## 🔧 Prerequisites

To run the notebook, you need:

- Python 3.8+ installed.
- Jupyter Notebook or a compatible execution environment (e.g., Google Colab, VS Code, PyCharm).
- The following Python libraries installed:
  ```bash
  pip install -r requirements.txt
  ```

## 📚 Module Topics

In this module, we have worked with **Python** and **Machine Learning**, exploring different techniques for data processing and predictive modeling. Topics covered include:

### 🔹 Data Preprocessing
- Handling missing values and outliers.
- Encoding categorical variables (One-Hot Encoding, Target Encoding).
- Feature scaling and transformation.

### 🔹 Exploratory Data Analysis (EDA)
- Descriptive statistics and visualization.
- Correlation analysis and feature selection.
- Distribution analysis of key variables.

### 🔹 Model Training & Evaluation
- Regression models: Linear Regression, Random Forest, XGBoost.
- Cross-validation and hyperparameter tuning.
- Performance metrics: RMSE, R².

## 📂 Repository Structure

```
📦 ML-Practice-Repo
├── 📁 data
│   ├── airbnb-listings-extract.csv          # Raw dataset
│   ├── airbnb-listings-extract_train.csv    # Training dataset
│   ├── airbnb-listings-extract_test.csv     # Testing dataset
├── practica_machine_learning.ipynb      # Jupyter  
├── 📄 README.md                              
```

## 🚀 Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ebarquin/keepcoding_ia_bootcamp_machine_learning_module
   cd ML-Practice-Repo
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and execute the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/practica_machine_learning.ipynb
   ```

## 📌 Authors
- Eugenio Barquin (https://github.com/ebarquin)

## 📜 License
This project is licensed under the MIT License.
