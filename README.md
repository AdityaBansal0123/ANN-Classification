# Customer Churn Prediction using Artificial Neural Network (ANN)

This project is a **customer churn prediction application** built using **Streamlit**. The app uses an Artificial Neural Network (ANN) to predict whether a bank customer will stay or leave based on their details. The model takes various inputs, such as **tenure, gender, geography, balance, age, credit score, estimated salary**, and more, to make predictions.

---

## Features

- **User-Friendly Interface**: Built with Streamlit for ease of use and interactivity.
- **Real-Time Prediction**: Enter customer details to get instant predictions.
- **Customizable Input Fields**: Accepts a variety of customer attributes for prediction.
- **Neural Network Backend**: Powered by a pre-trained Artificial Neural Network for accurate predictions.

---

## Input Features

The model requires the following inputs:

1. **Gender**: Male or Female  
2. **Geography**: Country of residence (e.g., France, Germany, Spain)  
3. **Credit Score**: Numeric value representing the creditworthiness of the customer  
4. **Age**: Customer's age  
5. **Tenure**: Number of years the customer has been with the bank  
6. **Balance**: Account balance  
7. **Number of Products**: Total products used by the customer  
8. **Has Credit Card**: Boolean (1 = Yes, 0 = No)  
9. **Is Active Member**: Boolean (1 = Yes, 0 = No)  
10. **Estimated Salary**: Customer's approximate annual salary  
11. **Exited** (Optional for training purposes): Whether the customer has churned (1 = Yes, 0 = No) 

---

## How It Works

1. **Data Input**: Users provide customer information through the Streamlit app interface.  
2. **Model Prediction**: The ANN processes the input data and predicts whether the customer will leave or stay.  
3. **Output**: The prediction is displayed in real-time as "the customer is likely to churn" or "the customer is not likely to chuurn"

---

## Installation and Setup

### Prerequisites

- Python 3.8+
- Streamlit
- TensorFlow/Keras
- Pandas
- Numpy
- Scikit-learn (for data preprocessing)

## Example of web page
![Screenshot](https://github.com/AdityaBansal0123/ANN-Classification/blob/main/WhatsApp%20Image%202024-11-15%20at%204.06.13%20PM.jpeg)
