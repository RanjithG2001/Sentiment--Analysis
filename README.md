💬 Sentiment Analysis Web App
A simple web application that analyzes the sentiment of user-input text (Positive or Negative) using a machine learning model. Built using Python, Flask, HTML/CSS, and scikit-learn.

🚀 Features
User-friendly web interface

Predicts sentiment in real-time

Trained Logistic Regression model with TF-IDF vectorization

Clean UI using HTML and CSS

Lightweight and easy to deploy

🛠️ Tech Stack
Frontend: HTML, CSS

Backend: Python, Flask

Machine Learning: Scikit-learn (Logistic Regression)

Vectorization: TF-IDF (Term Frequency–Inverse Document Frequency)

Model Persistence: Joblib

🧠 How It Works
User inputs a sentence in the web form.

The app processes the input and vectorizes it using a pre-trained TF-IDF model.

The vectorized text is fed into a trained Logistic Regression classifier.

The predicted sentiment (Positive/Negative) is displayed on the page.

▶️ Getting Started
Prerequisites
Python 3.x

pip

# Install dependencies
pip install -r requirements.txt

# Train model (optional, if model.pkl not provided)
python train_model.py

# Run the app
python app.py

Open http://localhost:5000 in your browser to use the app.

🔍 Example
Input:
I love the new design of your product!

Output:
✅ Positive Sentiment

📈 Future Enhancements
Add multilingual sentiment support

Integrate live social media data

Use deep learning models (e.g., LSTM, BERT)

Deploy on cloud platforms like Heroku or Render

