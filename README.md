# 🌸 Iris Flower Classification Model

This machine learning model predicts the **species of an Iris flower** based on four key features:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

## 🌿 About the Iris Dataset

The **Iris** genus includes over **310 accepted species** of flowering plants known for their vibrant and showy blooms. Each Iris flower typically has:

- 3 sepals  
- 3 petals  
- 3 broad stigma branches (pollen-receptive)  
- Hidden anthers beneath the stigma branches  

Among these, the dataset focuses on **three major species**:

| Species Name       | Description                          |
|--------------------|--------------------------------------|
| *Iris-setosa*      | Small petals, easily distinguishable |
| *Iris-versicolor*  | Medium-sized petals                  |
| *Iris-virginica*   | Largest petals among the three       |


<img src="images/iris-dataset.png" alt="iris-flowers">

## 📊 Features Used

| Feature         | Description                         |
|-----------------|-------------------------------------|
| Sepal Length    | Length of the flower’s outer part   |
| Sepal Width     | Width of the flower’s outer part    |
| Petal Length    | Length of the inner petal           |
| Petal Width     | Width of the inner petal            |

## 🧠 Model Overview: Logistic Regression

This project uses **Logistic Regression**, a supervised learning algorithm commonly used for classification tasks. Although originally designed for binary classification, Logistic Regression can be extended to **multiclass classification** using techniques like **one-vs-rest (OvR)**.

### Why Logistic Regression?

- Simple and effective for linearly separable data  
- Fast training and prediction  
- Provides probability estimates for each class  

### Model Workflow

1. **Data Preprocessing**: Load and clean the Iris dataset  
2. **Feature Scaling** *(optional)*: Normalize input features  
3. **Model Training**: Fit Logistic Regression on training data  
4. **Prediction**: Predict species based on input features  
5. **Evaluation**: Assess accuracy and performance metrics  

## 📈 Evaluation Metrics

| Metric              | Value     |
|---------------------|-----------|
| **Accuracy**        | 0.9667    |
| **Model Type**      | Multiclass Logistic Regression |
| **Classes Predicted** | *Iris-setosa*, *Iris-versicolor*, *Iris-virginica* |

> The model achieved an impressive **96.67% accuracy**, indicating strong performance on the Iris dataset.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yashwanths814/Iris-Model.git
   cd Iris-Model

   
