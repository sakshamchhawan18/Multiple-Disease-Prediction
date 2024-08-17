### README  📖✨

# 🩺 Multiple Disease Prediction System

Welcome to the **Multiple Disease Prediction System** repository! This project uses machine learning models to predict the likelihood of three critical diseases: **Diabetes**, **Heart Disease**, and **Parkinson's Disease**. By leveraging healthcare data, we aim to provide early detection that can help in the timely treatment of these conditions. 🚑

## 🎯 Project Overview

This project includes three separate models to predict the following diseases:

1. **Diabetes Prediction** 🍬
2. **Heart Disease Prediction** ❤️
3. **Parkinson's Disease Prediction** 🧠

## 🛠️ Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on various health metrics like glucose levels, BMI, etc.
- **Heart Disease Prediction**: Evaluates risk factors such as cholesterol levels, age, and more to predict heart disease.
- **Parkinson's Disease Prediction**: Detects early signs of Parkinson's disease using vocal measurements and other health indicators.


## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `seaborn`, `matplotlib`, `pickle`

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/multiple-disease-prediction.git
   cd multiple-disease-prediction
   ```

2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download and prepare the datasets** (if not included).

## 🔍 Model Details

### 1. **Diabetes Prediction** 🍬

- **Model**: SVM (Support Vector Machine)
- **Accuracy**: Training - ~78%, Testing - ~77%

### 2. **Heart Disease Prediction** ❤️

- **Model**: Logistic Regression
- **Accuracy**: Training - ~85%, Testing - ~83%

### 3. **Parkinson's Disease Prediction** 🧠

- **Model**: SVM (Support Vector Machine)
- **Accuracy**: Training - ~89%, Testing - ~87%

## 🧪 How to Use

1. **Run the prediction script**:
   You can run the prediction scripts located in the `notebooks/` directory for each disease.

2. **Input your data**:
   - Enter the relevant health metrics for the disease you want to predict.
   - The model will output a prediction indicating the likelihood of the disease.


## 📈 Data Sources

- **Diabetes Dataset**: Pima Indians Diabetes Database
- **Heart Disease Dataset**: UCI Heart Disease Dataset
- **Parkinson's Disease Dataset**: Parkinson’s Disease Data Set

## 📊 Results

- The models are evaluated using accuracy scores, confusion matrices, and classification reports.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

🚀 **Start predicting now and help make early disease detection accessible to all!** 🙌 🩺
