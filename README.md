# 🩺 Breast Cancer Prediction Web Application

This project provides a machine learning web application that predicts breast cancer diagnosis (malignant/benign) using clinical measurements from the Wisconsin Breast Cancer Dataset. Built with Flask and Scikit-learn, it offers medical professionals an intuitive tool for preliminary assessment.


## 🚀 Key Technologies

- **Flask** – Lightweight web framework for Python  
- **Scikit-learn** – For training the Random Forest model  
- **Pandas & NumPy** – Data preprocessing and input handling  
- **HTML (Jinja2)** – For rendering the frontend form and output  
- **Random Forest** – Model used for classification  
- **Remote CSV** – Dataset is fetched from a public GitHub URL

## 1️⃣ Input Features

The model uses these 5 features entered by the user:

- `radius_mean`  
- `texture_mean`  
- `perimeter_mean`  
- `smoothness_mean`  
- `compactness_mean`

These values are passed to the model to classify the tumor as malignant or benign.

## 2️⃣ Running the Application

### 🧾 Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/breast-cancer-predictor.git
cd breast-cancer-predictor
```

### 📦 Install Required Libraries
```bash
pip install flask pandas scikit-learn numpy
```

### 🚀 Start the Flask Server
```bash
python app.py
```

The app will start at:  
[http://127.0.0.1:5000](http://127.0.0.1:5000)

