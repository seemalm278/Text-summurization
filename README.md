# AI Text Summarizer

An AI-powered web application that automatically summarizes large pieces of text into shorter, meaningful summaries using Natural Language Processing (NLP) and Transformer-based deep learning models.

## 📌 Project Overview

Reading and understanding large amounts of text such as articles, documents, reports, and research papers can be time-consuming. This project solves that problem by providing an intelligent text summarization system that extracts the most important information from long text and generates a concise summary.

The application uses a pre-trained Transformer model from Hugging Face to understand the context of the input text and produce human-like summaries while maintaining the main ideas.

---

## 🚀 Features

* ✅ AI-based automatic text summarization
* ✅ Uses Hugging Face Transformer model (`facebook/bart-large-cnn`)
* ✅ Converts long text into short, meaningful summaries
* ✅ Adjustable summary length
* ✅ Simple and user-friendly web interface
* ✅ Real-time communication between frontend and backend
* ✅ Flask REST API for processing requests
* ✅ Error handling for invalid inputs

---

## 🎯 Problem It Solves

With the growth of digital information, users often need to read large amounts of content within limited time.

This project helps by:

* Reducing reading time
* Extracting important information automatically
* Helping students, researchers, and professionals quickly understand documents
* Improving productivity when dealing with large text data

Instead of manually reading hundreds of lines, users can generate a summarized version within seconds.

---

## 🛠️ Technologies Used

### Backend

* Python
* Flask
* Flask-CORS

### AI / Machine Learning

* Hugging Face Transformers
* PyTorch
* BART Large CNN Summarization Model

### Frontend

* HTML
* CSS
* JavaScript

---

## ⚙️ How It Works

1. User enters text into the web interface.
2. The frontend sends the text to the Flask backend.
3. Flask processes the request.
4. The Transformer model analyzes the text.
5. Important information is extracted.
6. A summarized version is returned and displayed to the user.

---

## 📂 Project Structure

```
Text-Summarizer
│
├── main.py                  # Flask backend application
│
├── templates
│   └── index.html           # Frontend interface
│
├── static
│   ├── main.css             # Styling
│   └── main.js              # Frontend JavaScript logic
│
├── requirements.txt         # Required Python libraries
│
└── README.md
```

---

## 🔧 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Text-summurization.git
```

### 2. Open project directory

```bash
cd Text-Summarizer
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python main.py
```

### 5. Open in browser

```
http://127.0.0.1:5000
```

---

## 📖 Usage

1. Open the application.
2. Enter a paragraph or large text.
3. Select the required summary length.
4. Click the summarize button.
5. The AI-generated summary will appear.

---

## 🔮 Future Improvements

Possible improvements:

* Support for PDF and document uploads
* Multiple language summarization
* User authentication
* Cloud deployment
* Better UI/UX design
* Voice-to-text summarization

---

## 🤖 Machine Learning Model

This project uses:

**Model:** facebook/bart-large-cnn

BART is a Transformer-based sequence-to-sequence model designed for natural language generation tasks, including text summarization.

It is capable of understanding context and generating fluent summaries from large text inputs.

---

## 🙏 Acknowledgements

* Hugging Face Transformers
* Facebook AI Research (BART Model)
* Flask Framework
* PyTorch Community

---

## 📜 License

This project is licensed under the MIT License.
