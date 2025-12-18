# Skin-Cancer-Detection_Model
🩺 Skin Cancer Detection Web Application

A deep learning–based web application for skin cancer classification built using Flask and FastAI, leveraging transfer learning to detect different types of skin lesions from images.

🚀 Project Overview

This project aims to assist in early skin cancer detection by classifying dermatoscopic images into multiple lesion categories. The application uses a pretrained DenseNet169 model fine-tuned on the HAM10000 (Skin Cancer MNIST) dataset.

Key Highlights:

Deep learning image classifier using FastAI (PyTorch)

Flask-based web interface for image upload and prediction

Transfer learning with DenseNet169

Handles class imbalance using random undersampling

Deployed using Gunicorn & Heroku

🧠 Model Details

Dataset: HAM10000 (10,015 dermatoscopic images)

Number of Classes: 7 skin lesion categories

Architecture: DenseNet169 (pretrained)

Validation Accuracy: 91.2%

F1-Score: 91.7%

Framework: FastAI (built on PyTorch)

🏗️ Tech Stack

Backend: Flask (Python)

Deep Learning: FastAI, PyTorch

Web Server: Gunicorn

Deployment: Heroku

Containerization: Docker

📸 Screenshots




⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/skin-cancer-detection.git
cd skin-cancer-detection

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python app.py

4️⃣ Open in Browser
http://localhost:8008

🐳 Docker Support

To build and run using Docker:

docker build -t skin-cancer-detector .
docker run -p 8008:8008 skin-cancer-detector

🌐 Live Demo

🔗 Deployed App:
https://skin-cancer-detector.herokuapp.com

(Note: Heroku free tier may be discontinued)

📓 Notebook

The complete model training and experimentation process is available in:

Skin_cancer_Detection.ipynb

📌 Future Improvements

Improve model performance using data augmentation

Add Grad-CAM visual explanations

Support mobile-friendly UI

Deploy on AWS / GCP

🤝 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to fork the repository and submit a pull request.
