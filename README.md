# VVIT_ML_WORKSHOP
# 🚖 Taxi Fare Prediction App (End-to-End ML)

## 📌 Project Overview
This project is an end-to-end Machine Learning application that predicts taxi fare based on trip distance using a Linear Regression model.

It also includes a Streamlit web app where users can input trip details and get fare predictions instantly.

---

## ⚙️ Features
- Data loading and preprocessing
- Machine Learning model (Linear Regression)
- Model evaluation (R² Score & RMSE)
- Interactive Streamlit web app
- Real-time fare prediction

---

## 🗂️ Project Structure
ML_TAXI_APP/
│── ml_taxi_app.py
│── taxis.csv
│── README.md
│── requirements.txt

---

## 📊 Dataset
The dataset (taxis.csv) contains:
- distance → Trip distance (km)
- fare → Taxi fare

---

## 🧠 Machine Learning Model
- Algorithm: Linear Regression
- Input Feature: distance
- Target Variable: fare

Evaluation Metrics:
- R² Score
- RMSE (Root Mean Squared Error)

---

## 🚀 Installation & Setup

1. Clone Repository
git clone https://github.com/your-username/ML_TAXI_APP.git
cd ML_TAXI_APP

2. Install Dependencies
pip install -r requirements.txt

3. Run the App
streamlit run ml_taxi_app.py

---

## 💻 Usage
1. Enter trip distance (km)
2. Enter number of passengers (currently not used)
3. Enter hour of the day (currently not used)
4. Click "Predict Fare"
5. View predicted fare

---

## ⚠️ Note
- The model currently uses only distance for prediction.
- Other inputs are not used in training.

---

## 🔮 Future Improvements
- Use multiple features (passengers, time, etc.)
- Try advanced models (Random Forest, XGBoost)
- Deploy on cloud platforms
- Improve UI/UX

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Streamlit

---

## 👨‍💻 Author
Prashanth Gowda

---

## ⭐ Acknowledgement
This project is built to understand end-to-end Machine Learning deployment.
