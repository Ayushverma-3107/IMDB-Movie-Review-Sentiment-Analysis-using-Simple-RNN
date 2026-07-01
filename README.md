# 🎬 IMDB Movie Review Sentiment Analysis using Simple RNN

## 📌 Project Overview

This project performs **Sentiment Analysis** on IMDB movie reviews using a **Simple Recurrent Neural Network (RNN)** built with TensorFlow and Keras. The model predicts whether a movie review expresses a **Positive** or **Negative** sentiment.

A Streamlit web application is included for real-time sentiment prediction.

---

## 🚀 Features

* Sentiment classification of movie reviews
* Deep Learning model using Simple RNN
* Text preprocessing and sequence padding
* Interactive Streamlit interface
* Real-time predictions
* TensorFlow/Keras implementation

---

## 🛠️ Tech Stack

* Python
* TensorFlow/Keras
* NumPy
* Pandas
* Scikit-learn
* Streamlit
* Matplotlib

---

## 📂 Project Structure

```text
├── main.py                  # Streamlit application
├── simple_rnn_imdb.h5       # Trained RNN model
├── embedding.ipynb          # Embedding layer experiments
├── simplernn.ipynb          # Model training notebook
├── prediction.ipynb         # Prediction notebook
├── requirements.txt         # Dependencies
└── README.md                # Documentation
```

---

## 🧠 Model Architecture

```text
Input Review
      │
      ▼
Embedding Layer
      │
      ▼
Simple RNN Layer
      │
      ▼
Dense Layer (Sigmoid)
      │
      ▼
Positive / Negative Prediction
```

---

## 📊 Dataset

Dataset: IMDB Movie Reviews Dataset

* Binary Sentiment Classification
* Positive Reviews
* Negative Reviews
* Preprocessed and tokenized using Keras IMDB Dataset API

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/imdb-sentiment-rnn.git
cd imdb-sentiment-rnn
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

Open:

```text
http://localhost:8501
```

---

## 📈 Prediction Example

Input:

```text
This movie was amazing. The acting and story were fantastic.
```

Output:

```text
Sentiment: Positive
Prediction Score: 0.95
```

---

## ☁️ Deployment

### Streamlit Cloud

1. Upload project to GitHub
2. Visit https://share.streamlit.io
3. Connect GitHub Repository
4. Select:

   * Repository
   * Branch
   * main.py
5. Click Deploy

---

## 🎯 Future Enhancements

* LSTM Implementation
* GRU Implementation
* Attention Mechanism
* Transformer-based Models
* Docker Deployment
* Cloud Deployment

---

## 👨‍💻 Author

Ayush Verma

If you found this project useful, please give it a ⭐ on GitHub.
