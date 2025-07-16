# 📧 Email Spam Detection using Machine Learning

This project is a simple and interactive **Email Spam Classifier** built using **Python**, **Scikit-learn**, and **Streamlit**. It allows users to enter a message and instantly find out if it is spam or not using a trained Naive Bayes model.

---

## 🚀 Features

- Classifies emails/messages as **Spam** or **Not Spam**
- Clean UI built with **Streamlit**
- Trained on the popular **SMS Spam Collection Dataset**
- Preprocessing includes cleaning, stopword removal, and TF-IDF vectorization

---

## 📂 Project Structure

email-spam-classifier/
-│
-├── spam.csv # Dataset used for training (SMS Spam Collection)
-├── train_spam_model.py # Script to train and save the model
-├── spam_model.pkl # Trained model (generated after training)
-├── vectorizer.pkl # TF-IDF vectorizer (generated after training)
-├── app.py # Streamlit web app
-├── requirements.txt # Python dependencies
-└── README.md # Project documentation


---

## 🧠 How the Model Works

- The dataset consists of labeled SMS messages (spam or ham).
- The messages are cleaned using regex and NLTK stopwords.
- Features are extracted using **TF-IDF Vectorization**.
- A **Multinomial Naive Bayes** classifier is trained on the data.

---

## ✅ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/email-spam-classifier.git
cd email-spam-classifier
```

## 2. Install Required Packages
```bash
pip install -r requirements.txt
```

## 3. Train the Model (Optional)
```bash
python train_spam_model.py
```

## 4. Run the Streamlit App
```bash
streamlit run app.py
```



## 📦 Dataset
SMS Spam Collection Dataset – UCI

## 🛠 Built With
- Python
- Scikit-learn
- Streamlit
- NLTK

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

##  👩‍💻 Author
Rabail Fiaz
GitHub: RabailFiaz

