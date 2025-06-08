# 📰 News Article NLP Application

## 🧠 Project Title
**Development and Performance Evaluation of an Application for News Article Summarization, Classification, and Sentiment Analysis using Deep Learning Models**

---

## 📘 Description
This project is a Python-based NLP application that automates the summarization, classification, and sentiment analysis of news articles using deep learning models like **DistilBERT** and **DistilBART**. Designed for edge environments (like laptops), the system is optimized for performance and accuracy with minimal resource consumption.

---

## 🎯 Key Features
- 📝 **Summarization**: Extracts concise summaries using DistilBART.
- 📚 **Classification**: Categorizes news into topics using DistilBERT.
- 😊 **Sentiment Analysis**: Analyzes emotional tone (positive/neutral/negative).
- 📊 **Performance Evaluation**: Measures accuracy, inference time, and RAM usage.
- 🖥️ **Web Interface**: Built using Streamlit for real-time input/output.
- 📈 **Visualizations**: Includes WordClouds and charts via Matplotlib.

---

## 🔧 Tech Stack
- **Languages**: Python 3.8+
- **Front-end**: Streamlit
- **Back-end**: Hugging Face Transformers, PyTorch
- **Libraries**: NLTK, Pandas, Matplotlib, OpenPyXL, WordCloud
- **Models**: DistilBERT, DistilBART (fine-tuned)
- **Data Source**: [Kaggle - The Star Malaysia News Dataset](https://www.kaggle.com/datasets)

---

## 🚀 Installation & Setup
```bash
# Clone the repository
git clone https://github.com/your-username/news-nlp-app.git
cd news-nlp-app

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

