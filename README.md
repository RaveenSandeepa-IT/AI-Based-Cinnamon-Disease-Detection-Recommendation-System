# 🌿 AI-Based Cinnamon Disease Detection & Recommendation System

An intelligent agricultural web application designed to detect diseases in cinnamon plants using Deep Learning and provide AI-generated treatment recommendations. The system helps farmers, agricultural officers, and researchers diagnose plant diseases quickly and improve crop management through data-driven insights.

---

## 📌 Project Overview

Cinnamon is one of Sri Lanka’s most valuable agricultural exports. However, plant diseases such as Leaf Spot, Leaf Gall, Rough Bark, Stripe Canker, and Black Sooty Mold can significantly reduce crop quality and yield.

This project introduces an AI-powered solution that allows users to upload images of cinnamon leaves or stems. The system analyzes the image using a trained Convolutional Neural Network (CNN) model and predicts the disease in real time. It then generates treatment and prevention recommendations using Generative AI.

---

## 🚀 Key Features

- 🌱 Cinnamon leaf and stem disease detection
- 🤖 Real-time AI predictions using Deep Learning
- 📊 90%+ classification accuracy
- 💡 AI-generated treatment & prevention recommendations
- 🔐 Secure user registration and login
- 📁 Detection history tracking
- 📄 Downloadable PDF diagnostic reports
- 📈 Admin analytics dashboard
- 📱 Responsive web-based interface

---

## 🦠 Detectable Diseases

The system can identify the following conditions:

- Leaf Spot
- Leaf Gall Forming
- Rough Bark
- Stripe Canker
- Black Sooty Mold
- Healthy Plant
- Others / Invalid Input Detection

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Flask REST API

### Artificial Intelligence
- TensorFlow
- Keras
- MobileNetV2
- CNN (Convolutional Neural Network)

### Database
- MySQL

### Generative AI
- Groq API
- Llama 3

### Other Libraries
- Pandas
- NumPy
- OpenCV
- Plotly
- ReportLab
- bcrypt

---

## 🏗️ System Architecture
User Upload Image
       ↓
Streamlit Frontend
       ↓
Flask API Backend
       ↓
CNN Model (MobileNetV2)
       ↓
Disease Prediction
       ↓
Groq LLM Recommendation Engine
       ↓
PDF Report + Database Storage

⚙️ Installation Guide
cd ai-cinnamon-disease-detection-system

2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Setup Database
Import the SQL file into MySQL:
database/schema.sql

5️⃣ Run Backend
python api.py

6️⃣ Run Frontend
streamlit run streamlit_app.py

📈 Results
Achieved 90%+ prediction accuracy
Real-time disease detection in seconds
Reduced dependency on manual expert inspection
Improved accessibility for rural farmers
Supports preventive crop management

🔒 Security Features
Password hashing using bcrypt
Role-based access control
Secure login sessions
Protected admin dashboard

🌍 Future Improvements
Mobile App Version
Offline Prediction Support
Multi-language Support (Sinhala / Tamil / English)
IoT Sensor Integration
Expansion to Tea / Pepper / Rubber Disease Detection

👨‍💻 Author
Raveen Sandeepa Pathirana
Data Science Undergraduate | AI & Machine Learning Enthusiast

📜 License
This project is licensed under the MIT License.

⭐ Support
If you like this project, give it a ⭐ on GitHub.

If you like this project, give it a ⭐ on GitHub.
