# Iris Plants Classification - Machine Learning

## Project Overview
This project focuses on processing the **Iris Plants** dataset using the **Random Forest** algorithm in **machine learning**, where various features of iris flowers are analyzed to explore patterns and relationships within the data. The dataset consists of measurements such as sepal length, sepal width, petal length, and petal width, which serve as key attributes in building a robust model.

## Dataset Characteristics
- **Number of Instances:** 150  
- **Number of Attributes:** 4 numeric, predictive attributes, and the class  
### **Attribute Information:**  
  - Sepal length (cm)  
  - Sepal width (cm)  
  - Petal length (cm)  
  - Petal width (cm)  
### **Class:**  
  - *Iris Setosa*  
  - *Iris Versicolour*  
  - *Iris Virginica*

**Dataset from scikit-learn** : [Iris Plants](https://scikit-learn.org/1.4/auto_examples/datasets/plot_iris_dataset.html)
  
## Goals
This project aims to analyze patterns in the *Iris Plants* dataset and develop a machine learning model using *Random Forest* to accurately classify flower species based on their size characteristics.

## Model Evaluation
● Confusion Matrix to measure prediction accuracy  
● Feature Importance Analysis to identify the most influential features  
● Correlation Matrix to understand relationships between features

## Insight
✔ **High Accuracy** – The *Random Forest* algorithm effectively classifies the three iris flower species (*Iris setosa, Iris versicolor,* and *Iris virginica*) with high accuracy.  

✔ **Most Influential Features** – *Feature Importance* analysis reveals that **petal length** and **petal width** are the most significant attributes in distinguishing iris species.  

✔ **Feature Relationships** – Correlation analysis indicates that petal features have a stronger relationship with species classification than sepal features, enhancing the efficiency of the classification process.  

✔ **Stable and Reliable Model** – Compared to single decision tree models, *Random Forest* minimizes the risk of *overfitting*, ensuring a more stable and reliable model for predicting new data.

