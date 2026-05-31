# 🚫📧 Email Spam Detection using Machine Learning

## NLP-Based Spam Classification System

An intelligent Machine Learning and Natural Language Processing (NLP) project developed using **Python**, **Scikit-learn**, **NLTK**, and **Streamlit** to classify messages as **Spam** or **Ham (Not Spam)**.

The project leverages text preprocessing, feature extraction, and machine learning techniques to automatically detect unwanted messages and provide real-time spam prediction through an interactive dashboard.

---

# 🏆 Oasis Infobyte Internship Task

This project was completed as part of the **Oasis Infobyte Data Science Internship Program (OIBSIP)**.

### Task Details

| Field              | Details                                         |
| ------------------ | ----------------------------------------------- |
| Internship Program | Oasis Infobyte Data Science Internship (OIBSIP) |
| Task Number        | Task 4                                          |
| Task Name          | Email Spam Detection                            |
| Domain             | Natural Language Processing (NLP)               |
| Model Type         | Text Classification                             |
| Deployment         | Streamlit Dashboard                             |

---

# 🎯 Project Objective

The objective of this project is to build a Machine Learning system capable of automatically classifying messages as Spam or Ham based on their textual content.

The project demonstrates:

* Text Data Processing
* Natural Language Processing (NLP)
* Feature Extraction
* Machine Learning Classification
* Model Evaluation
* Interactive Dashboard Development

The final solution helps users quickly identify potentially harmful or unwanted messages.

---

# 🌍 Problem Statement

Spam messages are one of the most common forms of unwanted communication across emails, SMS, and messaging platforms.

Manual identification of spam messages is inefficient and prone to errors.

This project aims to automate spam detection using Natural Language Processing and Machine Learning techniques that analyze message content and classify messages accurately.

The solution can assist:

* Email Service Providers
* Businesses
* Mobile Applications
* Security Systems
* Individual Users

in filtering unwanted messages and improving communication security.

---

# 🚀 Project Features

* 🚫 Spam vs Ham Classification
* 📧 Real-Time Message Analysis
* 🤖 Machine Learning-Based Prediction
* 🧹 Text Cleaning and Preprocessing
* 🔤 TF-IDF Feature Extraction
* 📊 Exploratory Data Analysis (EDA)
* 📈 Spam Distribution Visualization
* 🌐 Interactive Streamlit Dashboard
* ⚡ Instant Prediction Results

---

# 📊 Dataset Information

The dataset contains labeled messages used to train the spam classification model.

## 📌 Dataset Features

| Feature | Description         |
| ------- | ------------------- |
| v1      | Label (Spam or Ham) |
| v2      | Message Text        |

### Dataset Purpose

The dataset helps train a machine learning model capable of distinguishing between legitimate and spam messages based on textual patterns.

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* Streamlit
* Joblib

---

# 📊 Exploratory Data Analysis (EDA)

The project performs detailed analysis including:

* Dataset inspection
* Class distribution analysis
* Message length analysis
* Word frequency analysis
* Spam vs Ham comparison
* Text preprocessing

### EDA Objectives

* Understand message characteristics
* Identify spam-related patterns
* Analyze message length distributions
* Discover frequently occurring spam keywords
* Improve classification performance

---

# 📈 Key Insights

* Most messages in the dataset are non-spam.
* Spam messages usually contain promotional words.
* Spam texts are generally longer than ham messages.
* Words like "Free", "Win", and "Prize" appear frequently in spam messages.
* Text preprocessing significantly improves prediction performance.
* TF-IDF effectively captures important textual features.

---

# 🤖 Machine Learning Model

## ✅ Model Used

* Multinomial Naive Bayes

### Why Multinomial Naive Bayes?

Multinomial Naive Bayes is widely used for text classification because it performs efficiently on word-frequency-based features and provides strong results for spam detection tasks.

---

## 🔧 NLP Techniques Used

* Text Cleaning
* Lowercasing
* Tokenization
* Stopword Removal
* Punctuation Removal
* Stemming/Lemmatization
* TF-IDF Vectorization

---

## ⚙️ ML Workflow

```text
1. Data Loading
2. Text Cleaning
3. Tokenization
4. Stopword Removal
5. TF-IDF Vectorization
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Real-Time Prediction
```

---

# 📉 Model Evaluation

The spam detection model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

### Results

The model successfully learned textual patterns associated with spam messages and provided reliable classification results for unseen messages.

---

# 🚀 Streamlit Dashboard

The interactive dashboard allows users to:

* Enter custom messages
* Detect spam instantly
* View prediction results in real time
* Test different message samples
* Explore spam classification outcomes

### Dashboard Capabilities

✔ Real-Time Spam Detection

✔ User-Friendly Interface

✔ Instant Predictions

✔ Text-Based Analysis

✔ Interactive Experience

---

# 🔒 Practical Applications

The spam detection system can be applied in:

* Email Filtering Systems
* SMS Spam Detection
* Customer Support Platforms
* Messaging Applications
* Cybersecurity Solutions

to improve communication quality and reduce unwanted content.

---

# 📸 Project Screenshots

The repository contains screenshots demonstrating:

* Dataset Overview
* Spam vs Ham Distribution
* Message Length Analysis
* Text Processing Results
* Prediction Output
* Streamlit Dashboard Interface

Example folder structure:

```text
screenshots/
├── Message_Length_Comparison.png
├── Message_Length_Distribution.png
├── Dashboard.png
├── Statistical Summary.png
├── Dataset Preview.png
├── Prediction Output 1.png
├── Prediction Output 2.png
└── Spam_VS_Ham.png
```

---

# 📂 Project Structure

```text
Task4_Email_Spam_Detection/
│
├── Spam_Project/
│     ├── app.py
│     ├── spam.csv
│     ├── spam_model.pkl
│     ├── vectorizer.pkl
│     ├── Message_Length_Comparison.png
│     ├── Message_Length_Distribution.png
│     └── Spam_VS_Ham.png
│
├── Task4/
│     ├── PanthiniPatel_Task4.ipynb
│     ├── spam.csv
│     ├── spam_model.pkl
│     ├── vectorizer.pkl
│     ├── Message_Length_Comparison.png
│     ├── Message_Length_Distribution.png
│     └── Spam_VS_Ham.png
│
├── screenshots/
│     ├── Message_Length_Comparison.png
│     ├── Message_Length_Distribution.png
│     ├── Dashboard.png
│     ├── Statistical Summary.png
│     ├── Dataset Preview.png
│     ├── Prediction Output 1.png
│     ├── Prediction Output 2.png
│     └── Spam_VS_Ham.png
│
└── README.md
```

---

# ▶️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/panthinipatel5/OIBSIP_DataScience_Task4.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd Task4_Email_Spam_Detection
```

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

## 4️⃣ Run Streamlit Application

```bash
streamlit run app.py
```

---

# 💾 Model Saving

The trained model and vectorizer are saved using Joblib:

```python
joblib.dump(model, "spam_model.pkl")
joblib.dump(tfidf, "vectorizer.pkl")
```

This allows the application to perform predictions instantly without retraining the model.

---

# 🎓 Skills Learned

During the development of this project, the following skills were strengthened:

✔ Natural Language Processing (NLP)

✔ Text Cleaning and Preprocessing

✔ Feature Extraction using TF-IDF

✔ Machine Learning Classification

✔ Data Visualization

✔ Model Evaluation Techniques

✔ Streamlit Dashboard Development

✔ Text Analytics

✔ Spam Detection Systems

✔ End-to-End Project Documentation

---

# 📌 Conclusion

This project successfully demonstrates how Natural Language Processing and Machine Learning can be combined to solve real-world spam detection problems.

By applying text preprocessing, TF-IDF vectorization, and classification techniques, the system accurately identifies spam messages and provides instant predictions through an interactive dashboard.

The project highlights practical applications of NLP in communication security and automated message filtering systems.

---

# 🌟 Future Improvements

* Deep Learning Models (LSTM, GRU, Transformers)
* Better UI/UX Design
* Live Email Integration
* Multi-Language Spam Detection
* Deployment on Streamlit Cloud
* Real-Time Email Monitoring
* Advanced NLP Techniques
* Integration with Messaging Platforms

---

# 📜 License

This project is open-source and available for educational and learning purposes.

---

# 👨‍💻 Author

### Panthini Patel

Data Science • Machine Learning • Analytics

Developed as part of the **Oasis Infobyte Data Science Internship Program (OIBSIP)**.

⭐ If you found this project useful, consider giving it a star.
