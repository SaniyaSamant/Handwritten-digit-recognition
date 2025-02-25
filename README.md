# 📝 Handwritten Digit Recognition using Machine Learning with Hyperparameter Tuning

## 🚀 Overview
This project implements a **handwritten digit recognition** system using multiple machine learning models, including **Decision Tree, Random Forest, SVM, and KNN**, to compare their accuracy. The dataset used is the **Digit Recognizer dataset from Kaggle**, which is in **.csv format**.

## ✨ Features
- 🔍 **Multiple ML models:** Decision Tree, Random Forest, SVM, and KNN
- 🎯 **Hyperparameter tuning** using Grid Search and Randomized Search for better accuracy
- 📊 **Uses Kaggle's Digit Recognizer dataset** (CSV format) for training and testing
- 🐍 **Implemented using Python and Jupyter Notebook**

## 📂 Dataset
The **Digit Recognizer dataset** from Kaggle contains labeled images of handwritten digits (0-9) in CSV format. It consists of pixel values that represent grayscale images.

## ⚙️ Installation
To run this project, install the required dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## ▶️ Usage
1. 📥 Download the dataset from Kaggle and place it in the project folder.
2. 📜 Open the Jupyter Notebook.
3. ▶️ Run the notebook to train and evaluate different models.

## 🔧 Hyperparameter Tuning
The project applies **GridSearchCV** and **RandomizedSearchCV** to optimize model parameters such as:
- 🌳 `max_depth`
- 🔢 `min_samples_split`
- 🍃 `min_samples_leaf`
- 🌲 `n_estimators` (for Random Forest)
- ⚙️ `C` and `kernel` (for SVM)
- 📏 `n_neighbors` (for KNN)

## 📈 Results
The models are compared based on their accuracy, and the best parameters are selected to achieve higher accuracy.

## 📊 Interactive Visualizations
- 📌 Accuracy comparison of models
- 📌 Hyperparameter tuning results
- 📌 Confusion matrices for model evaluation

## 🤝 Contributing
Feel free to fork this repository and improve the models, add new techniques, or enhance visualization.


