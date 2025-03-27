# Timely Delivery Time Estimation using Machine Learning and Streamlit

## 1. Introduction
Timely and accurate delivery time estimation is crucial in supply chain management. This project aims to develop a web-based machine learning application using Streamlit that predicts the estimated delivery time of an order based on user-inputted details such as product category, customer location, and shipping method.

---

## 2. Machine Learning Model Overview
### Dataset Used
The model was trained on a dataset containing historical order records, including order details, shipment method, and actual delivery time.

### Feature Engineering
Key features such as:
- Product category
- Customer location
- Shipping method  
were extracted and used to train the model.

### Model Selection
A regression-based machine learning model was employed to predict the expected delivery time.

### Performance Metrics
The model was evaluated using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

---

## 3. Streamlit Deployment & Features
The trained machine learning model was deployed using Streamlit, providing an intuitive interface for users to input order details and receive real-time delivery time predictions.

### User Interface Features
- **Input Fields:** Users can enter order details such as:
    - Product Category
    - Customer Location
    - Shipping Method
- **Prediction Output:** Displays the estimated delivery time based on the input data.
- **User-Friendly Interface:** Ensures easy navigation and usability.

---

## 4. Code & Implementation
### Key Technologies Used
- **Python Libraries:** Streamlit, Pandas, Scikit-learn, NumPy, Joblib
- **Backend:** Machine learning model trained using Scikit-learn
- **Deployment:** Hosted on Streamlit Cloud

### How It Works
1. User inputs order details into the Streamlit web application.
2. The application processes the input and passes it to the trained ML model.
3. The model predicts the expected delivery time.
4. The result is displayed in the UI.

---

## 5. Challenges & Solutions
### Challenges Faced
- **Model Deployment Issues:** Faced dependency errors while deploying the model on Streamlit.
- **UI Optimization:** Ensured a simple and interactive interface for users.

### Solutions Implemented
- Resolved dependency errors by specifying correct versions in `requirements.txt`.
- Used Streamlit’s widgets for easy data input and result visualization.

---

## 6. Conclusion
This project successfully demonstrates an AI-driven approach to predicting order-to-delivery time, improving supply chain efficiency.
