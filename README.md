# 🔬 Breast_Cancer_Detection

A Streamlit-based web application that predicts whether a breast tumor is **benign** or **malignant** using key features from the Breast Cancer Wisconsin dataset. The app leverages a trained **Logistic Regression** model and provides a confidence score, visual insights, and basic consultation advice.

---

## 🚀 Features

- Predicts breast cancer diagnosis using **top 10 selected features** based on feature importance analysis
- Implements a **Logistic Regression classifier** trained on the Breast Cancer Wisconsin dataset
- Displays prediction probabilities and **confidence levels** visually using progress bars
- Provides **consultation-style advice** based on model confidence
- Includes **feature selection pipeline** using techniques like `SelectKBest` and `f_classif`
- Built with Streamlit for an interactive and user-friendly frontend

---

## 🧠 Tech Stack

- **Frontend**: Streamlit
- **Machine Learning**: Scikit-learn (Logistic Regression)
- **Data Processing**: NumPy, Pandas
- **Deployment**: Localhost / GitHub


---

## 💻 How to Run the App Locally

1. Clone the repository:

```bash
git clone https://github.com/yourusername/breast-cancer-prediction.git
cd breast-cancer-prediction
