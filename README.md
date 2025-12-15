# 🧠 Sentiment Analysis Web App using BERT (Flask)

A full-stack **Sentiment Analysis Web Application** built using **Flask** and a **pretrained BERT model** to analyze customer reviews.

The application allows users to:
- ✍️ Enter a **single review manually**
- 📂 Upload a **CSV file containing multiple mixed reviews**

and instantly receive sentiment predictions.

#### 🔗 Demo 
Check it out 👉🏻 https://moodify2-o.vercel.app

---

## 🚀 Features

- ✅ Single review sentiment prediction
- ✅ Batch sentiment analysis using CSV upload
- ✅ Pretrained **BERT Transformer model**
- ✅ Supports **Positive / Negative / Neutral** sentiments
- ✅ RESTful backend using **Flask**
- ✅ Real-world NLP application

---

## 🛠️ Tech Stack

### Backend
- Flask
- Python
- Pandas (CSV handling)
- PyTorch
- Hugging Face `transformers`

### Machine Learning
- BERT (Bidirectional Encoder Representations from Transformers)
- BERT Tokenizer
- Pretrained sentiment classification model

### Frontend
- HTML
- CSS
- JavaScript

---

## 🧩 How the Application Works

### 1️⃣ User Input
The user can:
- Type a **customer review** directly into the input field  
- Upload a **CSV file** with multiple reviews

Expected CSV format:
```csv
review
"The product quality is excellent"
"Delivery was very slow"
"It works fine, nothing special"

User Input / CSV Upload
        ↓
Flask Route
        ↓
BERT Tokenizer
        ↓
BERT Model
        ↓
Sentiment Prediction
        ↓
Response to Frontend

# Clone the repository
git clone <repository-url>
cd Moodify-WebApp

# Backend setup
cd Backend
pip install -r requirements.txt
# Run Flask app
python app.py
```
---

# 📸 Screenshot

## Home Page

<img width="1898" height="977" alt="image" src="https://github.com/user-attachments/assets/ea9c34fb-d50e-493c-b43c-65768f1894a1" />

### Screenshot showing sentiment result 
<img width="1625" height="825" alt="image" src="https://github.com/user-attachments/assets/00046ec3-a9f4-43cd-8668-2beda80ddb01" />

### Screenshot showing table of reviews and sentiments
<img width="1899" height="986" alt="image" src="https://github.com/user-attachments/assets/c8cd5510-7b1d-482b-b0e5-a4f96841abe3" />




