📱 SMS Spam Classifier
A Machine Learning Model to Detect Spam Messages

🔍 Overview
This project detects whether an SMS (text message) is spam or not spam (ham) using Natural Language Processing (NLP) and machine learning. It uses:
✔ Text preprocessing (cleaning, tokenization, stemming)
✔ TF-IDF vectorization (to convert text into numbers)
✔ Naive Bayes classifier (trained to predict spam/ham)
✔ Streamlit (for a simple web interface)

Try it out! Paste a message, and the model will instantly classify it.

🚀 How to Run This Project
1️⃣ Clone the Repository
git clone https://github.com/yourusername/SMS-Spam-Detector.git
cd SMS-Spam-Detector

2️⃣ Install Required Libraries
pip install -r requirements.txt

3️⃣ Download NLTK Data (Required for Text Processing)
python -m nltk.downloader punkt stopwords

4️⃣ Run the Web App
streamlit run app/app.py
➡ A browser window will open where you can test the model!

🛠️ How It Works
Text Preprocessing

Converts text to lowercase

Removes punctuation and stopwords (e.g., "the", "and")

Applies stemming (reducing words like "running" → "run")

Machine Learning Model

Trained on a dataset of 5,000+ SMS messages

Uses TF-IDF to convert words into numerical features

Naive Bayes algorithm for classification (98% accuracy)

Streamlit Web Interface

Simple, user-friendly design

Just paste a message → Get instant prediction

📂 Project Structure
SMS-Spam-Detector/
├── app/
│ ├── app.py — Streamlit application
│ ├── model.pkl — Trained ML model
│ └── vectorizer.pkl — TF-IDF vectorizer
├── notebooks/
│ └── spam_model.ipynb — Jupyter notebook (training code)
├── requirements.txt — Python dependencies
└── README.md — This file

📊 Model Performance
Metric	Score
Accuracy	98%
Precision	97%
Recall	96%

(Tested on a dataset of 1,000 messages.)

💡 Future Improvements
Add more training data for better accuracy

Include Deep Learning (LSTM/Transformers) for better NLP

Deploy on Streamlit Cloud for public access
