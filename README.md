# 🌾 Sowing Success: Crop Recommendation Using Machine Learning

![Farmer in a field](farmer_in_a_field.jpg)



This project leverages **machine learning** to help farmers select the most suitable crop for their soil conditions. Using essential soil metrics such as nitrogen, phosphorous, potassium, and pH, we build a multi-class classification model that predicts the optimal crop for a field, aiming to maximize yield and promote efficient resource usage.

---

## 📊 Project Overview

Choosing the right crop for a given soil condition is a crucial decision in farming. Traditionally, assessing soil metrics can be both costly and time-consuming, limiting a farmer’s ability to test all desired attributes. With machine learning, we can simplify this process by modeling past data to predict which crop is best suited to the given soil profile.

A farmer provided a dataset (`soil_measures.csv`) containing historical soil measurements and the most suitable crop for each case. Our goal is to:

- Train a classification model to predict the optimal crop.
- Evaluate model performance.
- Identify the most important feature contributing to crop selection.

---

## 🧾 Dataset: `soil_measures.csv`

| Feature | Description |
|--------|-------------|
| `N`    | Nitrogen content ratio in the soil |
| `P`    | Phosphorous content ratio in the soil |
| `K`    | Potassium content ratio in the soil |
| `pH`   | pH value of the soil |
| `crop` | Optimal crop for the soil condition *(target variable)* |

Each row represents a soil test result from a field and the crop best suited for that soil.

---

## 🧠 Machine Learning Approach

- **Problem Type:** Multi-class Classification  
- **Target Variable:** `crop`  
- **Features Used:** `N`, `P`, `K`, `pH`

### ✔️ Steps:

1. Data Preprocessing (missing values, encoding)
2. Exploratory Data Analysis (EDA)
3. Model Training (e.g., Random Forest, SVM, KNN)
4. Model Evaluation (accuracy, confusion matrix)
5. Feature Importance Analysis

---

## 🛠️ Tools & Technologies

- Python 🐍
- pandas
- scikit-learn
- seaborn & matplotlib (visualization)
- Jupyter Notebook

---

## 📈 Results

- Achieved high accuracy in crop prediction.
- Identified the most important soil feature influencing crop selection.

---

## 🤝 Acknowledgements

Thanks to the farmer who provided the real-world dataset and inspired this practical application of machine learning.

---

## 🧑‍💼 Author

**Abdelrahman Hamdy**  
[LinkedIn](https://www.linkedin.com/in/abdelrahman-hamdii)
