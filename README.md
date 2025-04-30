# 🚀 ANN Classification - Churn Prediction

## 📖 Description
This project is a neural network-based classifier that predicts whether a customer will churn (i.e., exit) based on various customer attributes. The model was trained using a dataset containing customer demographic and account information.

---

## 🎯 Objective
The goal of this project is to predict the **Exited** column, which indicates whether a customer will churn or not.

---

## 🌐 Hosted App
You can test the model using the Streamlit app here:  
👉 [**ANN Classification App**](https://ann-classification-dacafmrvgmrmvtbpqwfses.streamlit.app/)

---

## 📊 Dataset Overview
| Column Name | Description |
|------------|-------------|
| CustomerId | Unique customer ID |
| Surname | Customer's surname |
| CreditScore | Customer's credit score |
| Geography | Customer's location (France, Spain, Germany) |
| Gender | Customer's gender |
| Age | Customer's age |
| Tenure | Number of years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of products held by the customer |
| HasCrCard | Whether the customer has a credit card |
| IsActiveMember | Whether the customer is an active member |
| EstimatedSalary | Estimated salary of the customer |
| **Exited** | Whether the customer churned (1) or not (0) |

---

## 🏗️ Model Architecture
- **Input Features**: Customer demographic and financial data  
- **Hidden Layers**:  
   - First Layer: 64 neurons  
   - Second Layer: 32 neurons  
- **Activation Function**: ReLU  
- **Output Layer**: 1 neuron (Sigmoid activation for binary classification)  
- **Loss Function**: Binary Cross-Entropy  

---

## ✅ Features
- Neural Network with 2 hidden layers  
- One-hot encoding and label encoding for categorical features  
- Data scaling using a scaler  
- 85% accuracy on the test set  

---
## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- Streamlit
- Scikit-learn
- NumPy
- Pandas

---



