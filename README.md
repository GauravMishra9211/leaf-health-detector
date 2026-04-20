# leaf-health-detector
# 🌿 Leaf Health Detector

An AI-powered web application that detects plant leaf diseases using Deep Learning and provides supplement recommendations for better crop health.

---

## 🚀 Features

- Upload plant leaf images for instant disease detection
- Detect diseases using a trained CNN model
- View disease description and prevention steps
- Get fertilizer and supplement recommendations
- Responsive modern UI
- Camera support for direct image capture
- Supplement market section
- Contact page with project details

---

## 🛠️ Tech Stack

- Python
- Flask
- PyTorch
- Pandas
- NumPy
- HTML
- CSS
- Bootstrap
- JavaScript

---

## 📂 Project Structure

```bash
leaf-health-detector-main/
│
├── app.py
├── CNN.py
├── disease_info.csv
├── supplement_info.csv
├── plant_disease_model_1_latest.pt
├── requirements.txt
├── Procfile
├── runtime.txt
│
├── static/
│   ├── style.css
│   ├── manifest.json
│   ├── sw.js
│   └── uploads/
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── index.html
│   ├── submit.html
│   ├── market.html
│   ├── contact.html
│   └── 404.html
│
└── README.md

⚙️ Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/leaf-health-detector.git
cd leaf-health-detector

Create virtual environment:

python3 -m venv venv
source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Run the project:

python3 app.py

Open in browser:

http://127.0.0.1:5001
🌱 Model File

The trained model file is too large for GitHub.

Download the model separately and place it in the root project folder:

plant_disease_model_1_latest.pt
📸 Screenshots

Add screenshots of:

Home Page
AI Engine
Disease Result Page
Supplement Market
Contact Page
🌍 Deployment

You can deploy this project easily on:

Render
Railway
Replit
PythonAnywhere

Recommended:

Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app
👨‍💻 Author

Gaurav Mishra
B.Tech Student | AI & Data Analytics Enthusiast
GL Bajaj Institute of Technology and Management

📜 License

This project is for educational and research purposes only.
