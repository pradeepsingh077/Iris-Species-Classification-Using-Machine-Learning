
# 🌸 Iris Species Classification Using Machine Learning

This project demonstrates how machine learning can be used to classify iris flowers into their respective species: *Setosa*, *Versicolor*, and *Virginica*, using the classic Iris dataset. It is a beginner-friendly project for exploring supervised classification algorithms and understanding basic data science workflows.

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Modeling Techniques](#modeling-techniques)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 🚀 Project Overview

The goal of this project is to accurately predict the species of an Iris flower based on four input features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

By applying various machine learning classification techniques, this project evaluates model performance, visualizes data relationships, and identifies the most effective classifier for this task.

---

## 📊 Dataset Description

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Attributes**:
  - `SepalLengthCm`
  - `SepalWidthCm`
  - `PetalLengthCm`
  - `PetalWidthCm`
  - `Species` (Target)

The dataset contains **150 samples** equally divided among **three classes** (50 samples each).

---

## 🛠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (sklearn)
- Jupyter Notebook

---

## 🔄 Project Workflow

1. **Import Libraries**
2. **Load Dataset**
3. **Exploratory Data Analysis (EDA)**
4. **Data Visualization**
5. **Preprocessing (if required)**
6. **Model Training**
7. **Model Evaluation**
8. **Conclusion and Results**

---

## 🤖 Modeling Techniques

The following ML classifiers were implemented and evaluated:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

---

## 📈 Evaluation Metrics

To compare model performance, the following metrics were used:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**
- **Cross-Validation Score**

---

## ✅ Results

| Model             | Accuracy |
|------------------|----------|
| K-Nearest Neighbors | 96.67%   |
| Logistic Regression | 97.33%   |
| Support Vector Machine | 98.00%   |
| Decision Tree     | 96.00%   |
| Random Forest     | 98.00%   |

📌 **Best Model**: Support Vector Machine & Random Forest achieved the highest accuracy.

---

## 💻 How to Run

1. **Clone the repository**:
```bash
   git clone https://github.com/pradeepsingh077/Iris-Species-Classification-Using-Machine-Learning.git
```

# Install the required libraries:
```bash
pip install -r requirements.txt
```
# Run the Jupyter Notebook:
```bash
jupyter notebook iris_classification.ipynb
```

# 🔮 Future Improvements
Deploy the model using Flask or Streamlit for interactive use.

Add hyperparameter tuning (GridSearchCV or RandomizedSearchCV).

Explore feature importance visualization.

Convert the notebook into a standalone Python script or web app.

# 📄 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Pradeep Singh
📍 Noida, India
Linked: https://www.linkedin.com/in/pradeep-singh-585931230/



