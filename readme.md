Customer Churn Prediction Using ANN
📌 Project Overview

This project predicts whether a customer will stay or leave a company using an Artificial Neural Network (ANN) model.
The model is trained on a churn dataset and deployed using Streamlit for visualization and user interaction.

The project is divided into three main parts:

🔹 Part 1: Model Training

Load and preprocess churn dataset

Handle missing values

Encode categorical variables

Feature scaling

Build ANN using TensorFlow/Keras

Train model and evaluate performance

Save trained model

🔹 Part 2: Model Prediction

Load saved trained model

Accept new customer inputs

Preprocess inputs

Predict churn result

Display prediction (Stay / Leave)

🔹 Part 3: Streamlit App (Deployment)

User-friendly web interface

Input customer details

Show real-time prediction

Deploy model for end users

⚙️ Tech Stack

Programming Language: Python

Libraries & Frameworks:

TensorFlow / Keras

NumPy

Pandas

Scikit-learn

Streamlit

Model Type: Artificial Neural Network (ANN)

IDE/Tools: Jupyter Notebook, VS Code

🚀 Features

✔ Customer churn prediction
✔ Trained ANN model
✔ Interactive Streamlit UI
✔ Real-time results
✔ Easy deployment

📂 Project Structure
├── model_training.py
├── prediction.py
├── app.py   (Streamlit app)
├── model.h5
├── dataset.csv
├── README.md

▶ How to Run

Install dependencies

pip install -r requirements.txt


Train the model

python model_training.py


Run Streamlit app

streamlit run app.py

📊 Output

Predicts whether customer will Stay or Leave

Displays result on Streamlit web app

👤 Author

Name: Yash Rajput
Role: Data science
Project: Customer Churn Prediction using ANN

⭐ Acknowledgement

Thanks to open-source community and dataset providers for support.