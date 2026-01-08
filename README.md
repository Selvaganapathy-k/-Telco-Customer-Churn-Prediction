Subject: README.md – Telco Customer Churn Prediction

# 📡 Telco Customer Churn Prediction

## 📌 Project Description

This project implements a **Telco Customer Churn Prediction system** using Machine Learning.
The model predicts whether a telecom customer is **likely to churn (leave the service)** or **stay**, based on customer demographics, service usage, and billing information.

The project includes:

* Data analysis and model training
* A trained **Random Forest Classifier**
* A **Streamlit web application** for real-time churn prediction

This project is developed as a **mini project** for academic learning and practical exposure to machine learning and deployment.

---

## 📁 Dataset Information

* **Dataset Name:** Telco Customer Churn Dataset
* **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains customer information such as:

* Gender and senior citizen status
* Tenure
* Monthly and total charges
* Internet service type
* Contract type
* Payment method
* Churn status (target variable)

---

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

---

## 📂 Project Structure

```
-Telco-Customer-Churn-Prediction
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Telco Customer Churn.ipynb
├── random_forest_model.pkl
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Selvaganapathy-k/-Telco-Customer-Churn-Prediction
cd -Telco-Customer-Churn-Prediction
```

---

### 2️⃣ (Optional) Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 🌐 Live Application

🔗 **Streamlit App URL:**
[https://apf6ppbm22fstsebbi8q9t.streamlit.app/](https://apf6ppbm22fstsebbi8q9t.streamlit.app/)

---

## 🔍 Model Details

* Problem Type: **Binary Classification**
* Algorithm Used: **Random Forest Classifier**
* Input Features:

  * Gender
  * Senior Citizen
  * Tenure
  * Monthly Charges
  * Total Charges
  * Internet Service
  * Contract
  * Payment Method
* Output:

  * `1` → Customer will churn
  * `0` → Customer will stay

---

## 📈 Features

* Interactive and user-friendly Streamlit interface
* Real-time churn prediction
* Displays churn probability
* Handles categorical features using one-hot encoding
* Robust ensemble-based prediction model

---

## 🎓 Learning Outcomes

* Understanding customer churn problems
* Feature encoding and preprocessing
* Training and evaluating ensemble models
* Saving and loading ML models using Pickle
* Deploying ML models using Streamlit
* Structuring end-to-end ML projects on GitHub

---

## 📌 Notes

* Virtual environment folders (`venv`, `myvenv`) are not included in the repository.
* All required dependencies are listed in `requirements.txt`.

---

## ✍️ Author

**Selvaganapathy K**
Computer Science Student

---

## 🏁 Conclusion

This project demonstrates how machine learning techniques can be applied to telecom data to predict customer churn and help businesses take proactive retention measures.
