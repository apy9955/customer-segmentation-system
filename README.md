# 🛍️ Customer Segmentation System

A Machine Learning web application that predicts customer segments using **K-Means Clustering**.

## 📌 Project Overview

Customer segmentation is an important business strategy that helps companies understand different types of customers based on their purchasing behavior.

This project uses the **Mall Customers Dataset** and applies the **K-Means Clustering Algorithm** to divide customers into meaningful groups based on:

- Annual Income (k$)
- Spending Score (1-100)

The trained model is deployed using **Streamlit**.

---

## 🚀 Features

- 📊 Data Analysis and Visualization
- 🤖 K-Means Clustering
- 📈 Elbow Method for Optimal K Selection
- 🎯 Customer Segment Prediction
- 🌐 Interactive Streamlit Web Application

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Streamlit
- Pickle

---

## 📂 Project Structure

```text
customer-segmentation-system/
│
├── app.py
├── kmeans_model.pkl
├── Mall_Customers.csv
├── requirements.txt
└── README.md
```

---

## 🧠 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Handle Missing and Duplicate Values
5. Data Visualization
6. Feature Selection
7. Elbow Method
8. K-Means Clustering
9. Cluster Visualization
10. Customer Segment Prediction
11. Streamlit Deployment

---

## 🎯 Customer Segments

The model identifies different customer categories, such as:

- ⭐ Regular Customers
- 💎 Premium Customers
- 🎯 Target Customers
- 💰 Potential Customers
- 🛒 Budget Customers

---

## ▶️ Run the Project

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit App

```bash
streamlit run app.py
```

---

## 📷 Application Preview

The application allows users to:

- Enter Annual Income
- Enter Spending Score
- Predict Customer Segment

---

## 📊 Dataset

**Dataset:** Mall Customers Dataset

Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## 💡 Business Applications

- Customer Segmentation
- Targeted Marketing
- Customer Relationship Management
- Personalized Recommendations
- Business Decision Making

---

## 🔮 Future Improvements

- Add customer recommendations
- Improve UI design
- Deploy online using Streamlit Cloud
- Add cluster visualization inside the app
- Store prediction history

---

## 👨‍💻 Author

**Aman Kumar**

Machine Learning Enthusiast 🚀

---

## ⭐ If you like this project, give it a star!
