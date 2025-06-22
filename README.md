🩺 Breast Cancer Prediction using Flask & Machine Learning
This project empowers users to predict breast cancer using a machine learning model trained on the Breast Cancer Wisconsin (Diagnostic) dataset. It utilizes a Flask backend to handle user input and prediction logic, and renders a simple web interface for user interaction.

🔑 Key Technologies
Flask: A lightweight Python framework used to build the web server and handle API routes.

Scikit-learn: A machine learning library used to train and evaluate the Random Forest Classifier.

Pandas & NumPy: For data loading, preprocessing, and manipulation.

HTML (Jinja2 templating): Used for creating a basic web interface for user input.

GitHub Dataset: The cancer dataset is fetched directly from a public GitHub repository.

🔍 Core Functionality
Accepts five user-input features:

radius_mean

texture_mean

perimeter_mean

smoothness_mean

compactness_mean

Predicts Malignant or Benign diagnosis

Displays prediction confidence score

Supports real-time prediction through a web form

🗂 Project Structure
bash
Copy
Edit
breast_cancer_predictor/
├── app.py                  # Main Flask application
├── templates/
│   └── home.html           # Frontend form for user input
├── requirements.txt        # Python dependencies
├── .gitignore              # Git ignore file (optional)
└── README.md               # This documentation
⚙️ 1. Environment Setup
1.1. Clone the repository
bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/breast-cancer-predictor.git
cd breast-cancer-predictor
1.2. (Optional) Create a virtual environment
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate       # On Windows
# OR
source venv/bin/activate    # On Linux/macOS
1.3. Install required libraries
bash
Copy
Edit
pip install -r requirements.txt
🚀 2. Running the Application
2.1. Run the Flask server
bash
Copy
Edit
python app.py
The app will run locally at http://127.0.0.1:5000

🧪 Basic Workflow
Start the server as shown above

Open your browser and go to http://127.0.0.1:5000

Enter the 5 input values related to the tumor

Click Submit

View the predicted diagnosis and confidence score

🧬 Example Use Case
Input:

radius_mean = 17.99

texture_mean = 10.38

perimeter_mean = 122.8

smoothness_mean = 0.1184

compactness_mean = 0.2776

Output:

🟠 The patient is diagnosed with Breast Cancer

Confidence: 94.28%

🖼️ Screenshots
Input Form:

Prediction Result:
