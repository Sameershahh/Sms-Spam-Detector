📱 SMS Spam Classifier
A machine learning model that detects whether an SMS (text message) is spam or not spam (ham) using Natural Language Processing (NLP) and machine learning — with a simple Streamlit web interface to test messages instantly.

🔍 Features
Text Preprocessing

Lowercasing

Removing punctuation and stopwords

Stemming (e.g., running → run)

TF-IDF Vectorization to convert text into numbers

Naive Bayes Classifier (trained on 5,000+ SMS messages)

Streamlit Web App for instant classification

🛠️ Tech Stack
Backend: Python, Scikit-learn, NLTK

Frontend: Streamlit

ML Algorithms: TF-IDF Vectorizer, Naive Bayes Classifier

Version Control: Git & GitHub

🚀 How to Run This Project
1️⃣ Clone the Repository
git clone https://github.com/yourusername/SMS-Spam-Detector.git
cd SMS-Spam-Detector

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Download NLTK Data
python -m nltk.downloader punkt stopwords

4️⃣ Run the Web App
streamlit run app/app.py

➡ A browser window will open to test the model!


📊 Model Performance
Metric	Score
Accuracy	98%
Precision	97%
Recall	96%

Tested on a dataset of 1,000 SMS messages.

💡 Future Improvements
Expand training dataset for better generalization

Integrate Deep Learning models (LSTM, Transformers)

Deploy publicly on Streamlit Cloud
