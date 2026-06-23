# PhishShield

**Phishing Email Classification Using BERT**

🚀 Detecting phishing emails using BERT-based models (DistilBERT & TinyBERT).

<img width="1470" height="763" alt="image 1" src="https://github.com/user-attachments/assets/8d7fc934-4daf-4d25-be05-226d0e5ab93b" />


## 📌 Overview

Phishing attacks have become a significant cybersecurity threat, tricking users into revealing sensitive information. This project utilizes BERT-based models (DistilBERT & TinyBERT) for phishing email classification, helping to distinguish between phishing and legitimate emails with high accuracy.

## 🚀 Features

- **✔️ Fine-tuned BERT, DistilBERT, and TinyBERT for email classification**
- **✔️ Preprocessing using NLP techniques (tokenization, stopword removal, etc.)**
- **✔️ Model evaluation with Precision, Recall, and F1-score**
- **✔️ Model compression techniques for improved efficiency**
- **✔️ Scalable & deployable as a real-world phishing detection tool**

## 📂 Project Structure

📦 PhishShield
    
    │── 📂 static/               # Static files (CSS, JS)
    │    ├── styles.css          # Styling for frontend
    │    ├── script.js           # JS functions for frontend
    │── 📂 templates/            # HTML templates
    │    ├── index.html          # Home page
    │    ├── Main.html           # Results page
    │── 📜 LICENSE               # License details
    │── 📜 Model.ipynb           # Jupyter Notebook for model training
    │── 📜 Part_A.ipynb          # Data preprocessing and analysis
    │── 📜 Part_B.ipynb          # Model evaluation & fine-tuning
    │── 📜 README.md             # Project documentation
    │── 📜 app.py                # Flask web application
    │── 📜 requirements.txt      # Required libraries
    │── 📜 test_request.py       # API testing script

## 🔧 Installation & Setup

1️⃣ Clone the Repository
      
    git clone https://github.com/prasanth5629/PhishShield
    cd PhishShield

2️⃣ Create & Activate a Virtual Environment

    python -m venv env
    source env/bin/activate   # On macOS/Linux
    env\Scripts\activate      # On Windows

3️⃣ Install Dependencies

    pip install -r requirements.txt

4️⃣ To deploy the model using Flask / FastAPI, run:

    python app.py

Access the API at: http://127.0.0.1:5000/

## 📌 Technologies Used

- **🟢 Machine Learning & NLP:**
	- BERT, DistilBERT, TinyBERT
	- Transformers (Hugging Face)
	- Scikit-Learn, Pandas, NumPy

- **🟢 Deep Learning Frameworks:**
  - PyTorch / TensorFlow
  - Hugging Face 🤗 Transformers

- **🟢 Other Tools & Libraries:**
  - Matplotlib, Seaborn (for visualization)
  - Flask / FastAPI (for API deployment)

## 🏆 Results & Performance

<img width="317" alt="Screenshot 2025-02-13 at 12 30 17 PM" src="https://github.com/user-attachments/assets/6ecce9e6-923c-4196-9b5a-ce7d91ead5e8" />

(Results may vary based on dataset quality.)

## 🔗 Live Demo

https://github.com/user-attachments/assets/eedd28fe-7e60-40e2-a155-27827ba88538

## 📩 Contact & Acknowledgements

If you have any questions, feel free to reach out:

- **📧 Email**: kotayaswanthkumar2004@gmail.com
- **💼 LinkedIn**: www.linkedin.com/in/yaswanthkumarkota
- **📌 GitHub**: https://github.com/Yaswanthkumar111

If you found this project useful, don’t forget to ⭐ the repo! 😊
