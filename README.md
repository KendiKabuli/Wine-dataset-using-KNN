#  Wine Quality Prediction using Machine Learning

This project predicts the **quality of wine** based on various physicochemical properties using **machine learning**.  
The dataset used is the popular **Wine Quality Dataset**, which contains both red and white wine samples with quality ratings.

---

##  Dataset Overview

The dataset includes several features such as:
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Quality (target variable)

The goal is to build a model that can accurately predict the **wine quality** score (typically between 0–10).

---

## Technologies that i Used

- Language = Python
- Libraries include:
- Pandas for data manipulation  
- NumPy for numerical operations  
- Matplotlib & Seaborn for data visualization  
- Scikit-learn for model building and evaluation

- Google Colab for experimentation and model training

---
## Project Workflow

1. Data Exploration: Understand features and target labels.  
2. Data Splitting: 70% training data, 30% testing data.  
3. Model Training: KNN classifier (`n_neighbors=5`).  
4. Prediction: Predict wine class for test data and new samples.  
5. Evaluation: Accuracy score and classification report.  
6. Visualization: Scatter plot of features with color-coded classes and predicted new sample.

## Performance Metrics

**Model Accuracy:** 0.8056 (≈81%)  

**Classification Report:**

| Class     | Precision | Recall | F1-Score | Support |
|----------|-----------|--------|----------|---------|
| class_0  | 0.86      | 0.86   | 0.86     | 14      |
| class_1  | 0.92      | 0.79   | 0.85     | 14      |
| class_2  | 0.60      | 0.75   | 0.67     | 8       |

**Weighted Average:**  
- Precision: 0.82  
- Recall: 0.81  
- F1-Score: 0.81

> The model performs best on class_0 and class_1, and slightly lower on class_2 due to fewer samples.

## Learnings

- KNN relies on **distance-based classification** — closer neighbors determine the class.  
- The number of neighbors (`k`) affects performance; 5 worked reasonably well here.  
- Visualizing high-dimensional data helps understand class separation.  
- Weighted averages are useful to assess performance when class sizes differ.

---
 **Joy Kabuli**
