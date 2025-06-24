# Task_2_Iris_Classification

# 🌸 Iris Flower Classification using Machine Learning

This project focuses on classifying **Iris flowers** into three species using classical machine learning algorithms. It utilizes the well-known **Iris dataset** and aims to develop a robust classification model based on flower measurements.

---

## 📌 Project Objective

To build a machine learning model that:

- Accepts numerical features (sepal length/width and petal length/width)
- Classifies iris flowers into one of three categories:
  - **Setosa**
  - **Versicolor**
  - **Virginica**
- Achieves high accuracy and generalizes well to unseen data

---

## 🗃️ Dataset Overview
IRIS Dataset(https://drive.google.com/file/d/1j3am9Qo7yXXdQRGEhVj7Cfa1b0qakhKR/view?usp=sharing)

The dataset used is the **Iris dataset** from scikit-learn, containing:

- 150 total samples
- 4 features per sample:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 target classes (species)
- Balanced number of samples per class (50 each)

---

## 🧠 Model Summary

Multiple models were evaluated for performance:

- **Logistic Regression** – Simple linear classifier
- **Decision Tree** – Rule-based decision learning
- **Support Vector Machine (SVM)** – Powerful classification with hyperplane separation

All models were evaluated to determine the best performing one based on accuracy and robustness.

---

## 🧪 Workflow

### Data Preprocessing

- Loaded data from sklearn’s `load_iris()`
- Converted into a Pandas DataFrame
- Visualized data using pair plots and heatmaps
- Split dataset into **training (80%)** and **testing (20%)**

### Model Training

- Trained 3 classifiers: Logistic Regression, Decision Tree, and SVM
- Used default hyperparameters initially
- Compared results across models

### Evaluation

- Evaluated using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **Confusion Matrix**
- SVM provided the highest classification accuracy on test data

---

## 📈 Results

- All three models showed good performance; **SVM performed the best**
- Classification accuracy exceeded **95%**
- Confusion matrix confirmed strong model generalization
- Minimal misclassification across all three species

---

## 🔍 Prediction

The trained model can now be used to classify new flower samples by inputting the four numerical features (sepal/petal length & width).

---

## 🖥️ Demo Video

🎥 [Click here to watch the project demo](https://drive.google.com/file/d/1R4HtCWupA0uZepAwHOgeghFLLRSZpcs1/view?usp=sharing)

---

## 🔗 LinkedIn Post

🔗 [Click here to view my LinkedIn post](https://www.linkedin.com/posts/lahari-kodali-0828822b3_futureintern-task2-machinelearning-activity-7342884558964453376-H2aC?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEtp5eIBhoKqVvYHZHwtQ-dbov8KpB9raLc)

---

## 🧰 Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 📌 Tags

#IrisDataset #MachineLearning #Classification #SVM #Python #FutureIntern #InternshipTasks #AI #DataScience #ScikitLearn
