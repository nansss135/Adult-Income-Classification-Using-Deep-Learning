# Adult Income Classification Using Deep Learning

## Project Overview

This project focuses on predicting an individual's annual income using Deep Learning techniques, particularly Artificial Neural Networks (ANN) and Multi-Layer Perceptron (MLP).

The model uses demographic and employment-related information from the Adult Census Income Dataset to classify individuals into two income categories:

- **0:** Income <= $50K
- **1:** Income > $50K

The main objective is to understand how neural networks can be applied to binary classification problems using structured tabular data.

## Dataset

**Dataset Name:** Adult Census Income Dataset

**Dataset Information:**
- Approximately 48,842 records.
- 14 input features.
- Numerical and categorical attributes.
- Binary target variable: Income.

**Features include:**
- Age
- Workclass
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours Per Week
- Native Country
- Education Number

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Google Colab

## Project Workflow

### 1. Data Loading and Exploration
- Loaded the Adult Census Income Dataset.
- Explored dataset dimensions and data types.
- Analysed numerical and categorical features.
- Checked missing values and data distribution.

### 2. Data Preprocessing
- Replaced missing-value indicators (`?`) with NaN.
- Removed rows containing missing values.
- Dropped unnecessary and redundant columns.
- Encoded categorical variables using One-Hot Encoding.
- Converted the target variable into binary labels.
- Applied an 80:20 stratified train-test split.
- Standardized numerical features using StandardScaler.

### 3. Model Building

Implemented a Multi-Layer Perceptron (MLP) using TensorFlow and Keras.

**Baseline Model Architecture:**

| Layer | Configuration |
|---|---|
| Input Layer | Input features |
| Hidden Layer 1 | 64 neurons, ReLU |
| Hidden Layer 2 | 32 neurons, ReLU |
| Output Layer | 1 neuron, Sigmoid |

**Model Configuration:**
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy
- Epochs: 20
- Batch Size: 32

### 4. Model Evaluation

The project focuses on evaluating binary classification performance.

Evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

### 5. Visualization and Analysis

Visual analysis helps understand:
- Dataset distributions.
- Model training and validation performance.
- Classification performance.
- Comparison of model configurations.

## Repository Structure

```text
Adult-Income-Classification-Using-Deep-Learning/
│
├── DL_PR2.ipynb
├── DL_PR2.html
├── requirements.txt
├── README.md
│
└── plots/
    └── Model visualizations and results
```

## Installation and Setup

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd Adult-Income-Classification-Using-Deep-Learning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook using Jupyter Notebook or Google Colab.

## Results

The project demonstrates the application of Artificial Neural Networks to predict income categories using demographic and employment-related features.

Detailed training results, evaluation metrics and visualizations are available in the Jupyter Notebook.

## Conclusion

This project provides practical experience in applying Deep Learning to structured tabular data.

It covers data preprocessing, feature encoding, neural network architecture, binary classification and model evaluation.

## Future Scope

- Experiment with advanced neural network architectures.
- Improve model performance through hyperparameter tuning.
- Explore additional regularization techniques.
- Compare different optimizers and activation functions.
- Improve generalization on unseen data.

## Author

Deep Learning – Practical 2

**Project:** Adult Income Classification Using Deep Learning
