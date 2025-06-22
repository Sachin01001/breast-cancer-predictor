# 🩺 Breast Cancer Predictor

This project is a simple web app that predicts if a tumor is malignant or benign using a machine learning model trained on the Wisconsin Breast Cancer Dataset. It is built using Flask and Scikit-learn.

## 🚀 Key Technologies

- **Flask** – Lightweight web framework for Python  
- **Scikit-learn** – For training the Random Forest model  
- **Pandas & NumPy** – Data preprocessing and input handling  
- **HTML (Jinja2)** – For rendering the frontend form and output  
- **Random Forest** – Model used for classification  
- **Remote CSV** – Dataset is fetched from a public GitHub URL

## 1️ Input Features

The model uses these 5 features entered by the user:

- `radius_mean`  
- `texture_mean`  
- `perimeter_mean`  
- `smoothness_mean`  
- `compactness_mean`

These values are passed to the model to classify the tumor as malignant or benign.

## 2️ Running the Application

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

## 3️ Basic Workflow

- Launch the app using `python app.py`  
- Open browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000)  
- Enter 5 input values  
- Click **Submit**  
- View prediction (Malignant/Benign) and confidence level

## 4 Dataset Reference

This app uses the Breast Cancer Wisconsin (Diagnostic) Dataset:  
🔗 https://github.com/apogiatzis/breast-cancer-azure-ml-notebook/blob/master/breast-cancer-data.csv


