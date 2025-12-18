# 📈 Stock Price Prediction Web App

🔗 **Live Demo:** [https://pritamnath2025.streamlit.app/](https://pritamnath2025.streamlit.app/)

A machine learning-powered web application built with **Streamlit** that predicts future stock prices using trained models and historical data.

---

## 🚀 Project Overview

This project demonstrates a stock price prediction system using Python, data science libraries, and machine learning models. Users can input a stock ticker symbol and view predicted future prices along with historical trends.

---

## 🧠 Features

✔ Predicts stock prices using a pre-trained model
✔ Interactive, user-friendly interface via **Streamlit**
✔ Displays historical data and predicted trends
✔ No installation required — run live on Streamlit Cloud

---

## 🗂 Repository Contents

| File                            | Description                          |
| ------------------------------- | ------------------------------------ |
| `app.py`                        | Main Streamlit app code              |
| `requirements.txt`              | Python dependencies                  |
| `stock.ipynb`                   | Notebook used to build/train model   |
| `model.pkl` / `stock_model.pkl` | Pre-trained machine learning model   |
| `scaler.pkl`                    | Scaler for feature normalization     |
| `s2.jpg`                        | Example UI screenshot or image asset |

---

## 🛠 Technologies Used

* Python
* Streamlit
* scikit-learn / ML models
* pandas, numpy
* Joblib / pickle for model persistence

---

## 📌 Installation & Setup (Local)

> **Note:** This step is only needed if you want to run the project locally.

1. **Clone the repo**

```
git clone https://github.com/Pritam-Nath/Stock_Prediction-.git
```

2. **Navigate into project**

```
cd Stock_Prediction-
```

3. **Create virtual environment (optional but recommended)**

```
python3 -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
```

4. **Install dependencies**

```
pip install -r requirements.txt
```

5. **Run the Streamlit app**

```
streamlit run app.py
```

---

## 📊 How It Works

1. Historical stock data is loaded (e.g., from a CSV or API).
2. Features are preprocessed and normalized using `scaler.pkl`.
3. A machine learning model (`model.pkl` / `stock_model.pkl`) predicts future prices.
4. Predictions and trends are displayed interactively on the Streamlit UI.

---

## 📈 Screenshots
<img width="1919" height="870" alt="image" src="https://github.com/user-attachments/assets/bd62eceb-ea00-4332-98df-b3a469158c61" />



---

## 📬 Feedback / Issues

If you find bugs, have suggestions, or want to contribute enhancements, feel free to open an issue or a pull request.

---

## 🙌 Credits

Created by **Pritam Nath** — Software Developer & Computer Science Engineer.

🔗 Live App: [https://pritamnath2025.streamlit.app/](https://pritamnath2025.streamlit.app/)

---
