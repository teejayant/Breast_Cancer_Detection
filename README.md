# 🔬 Breast Cancer Detection

A **Streamlit-based** web application that predicts whether a breast tumor is **benign** or **malignant** using clinical inputs from the **Breast Cancer Wisconsin (Diagnostic) Dataset**.  
The app uses a trained **Logistic Regression** model and provides:
- A **confidence score**
- **Visual interpretation**
- **Consultation-style feedback** for better user clarity

---

## 🚀 Features

- ✅ Predicts diagnosis based on **top 10 selected features** (`SelectKBest`)
- 📊 Shows **prediction probabilities** and **confidence levels** with visual indicators
- 🧠 Provides **advisory messages** based on model confidence
- 🔍 Uses **feature selection pipeline** for better accuracy and interpretability
- 💡 Built with **Streamlit** for a responsive and interactive interface

---

## 🧠 Tech Stack

- **Frontend/UI**: Streamlit  
- **Machine Learning**: Scikit-learn (Logistic Regression)  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Deployment**: Localhost / GitHub  

---

## 💻 How to Run the App Locally

### Step 1: Clone the Repository

```bash
git clone https://github.com/teejayant/Breast_Cancer_Detection.git
cd Breast_Cancer_Detection
```

---

### Step 2: Install Dependencies


 Install required packages manually:

```bash
pip install pandas numpy scikit-learn streamlit matplotlib seaborn joblib
```

---

### Step 3: Ensure Required Files Are Present

Make sure the following files exist in the project folder:

- `data.csv` – Breast Cancer Wisconsin (Diagnostic) Dataset  
- `model.pkl` – Trained Logistic Regression model  
- `scaler.pkl` – Scaler used during training  
- `selected_features.pkl` – Top 10 selected features used in training

> 🔄 These files are generated if you run the training notebook.

---

### Step 4 (Optional): Retrain or Customize the Model

To modify the model or regenerate the `.pkl` files:

- Open the Jupyter Notebook in the project
- Run all cells
- This will recreate `model.pkl`, `scaler.pkl`, and `selected_features.pkl`

---

### Step 5: Run the Streamlit App
Run the below command in terminal of main.py
```bash
streamlit run main.py
```

This will open a local URL in your terminal (usually `http://localhost:8501`).  
Open it in your browser to interact with the app.

---

## ✅ Quick Tips

- To **use the app only**: Follow **Steps 1, 2, and 5**
- To **retrain or update the model**: Also complete **Step 4**

---

## 📌 Prerequisites

- Python 3.7 or higher  
- Required libraries installed ( manually)  
- All necessary data and model files in the project directory

---
