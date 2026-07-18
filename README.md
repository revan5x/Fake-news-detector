# 📰 Fake News Detector

A machine learning–powered web application that identifies whether a news article is **real or fake** using **natural language processing (NLP)** techniques.

Built with digital literacy in mind, this tool empowers users to make informed decisions about online information credibility in an era of misinformation.

---

## 🎯 Problem Statement

The proliferation of misinformation poses significant challenges to public discourse. Our detector helps address this by providing users with a quick, reliable way to assess article authenticity before sharing or trusting news content.

---

## ✨ Key Features

- **Text Analysis**: Paste article text directly for instant credibility assessment
- **URL Processing**: Extract and analyze news articles from direct links
- **Confidence Scores**: Probability-based predictions with transparency
- **User-Friendly Interface**: Intuitive design accessible to non-technical users
- **Real-time Classification**: ML model delivers predictions within seconds

---

## 🏗️ Product Architecture

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Frontend** | HTML, CSS, JavaScript | User interface & interaction |
| **Backend** | Python (Flask) | API & business logic |
| **ML Pipeline** | scikit-learn, NLTK | NLP preprocessing & model inference |
| **Data Processing** | pandas, NumPy | Feature engineering |
| **Classification Model** | Logistic Regression / Naive Bayes | Binary classification (Real/Fake) |
| **Deployment** | Docker / Heroku / Local | Production & development environments |

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- pip package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/revan5x/Fake-news-detector.git
cd Fake-news-detector

# Set up virtual environment
python -m venv venv

# Activate environment
venv\Scripts\activate     # Windows
source venv/bin/activate  # macOS/Linux

# Install dependencies
pip install -r requirements.txt
```

### Running Locally

```bash
# Start the Flask development server
python app.py

# Access the application
# Open http://localhost:5000 in your browser
```

---

## 📋 Requirements

See `requirements.txt` for full dependency list. Key packages:
- `flask` — Web framework
- `scikit-learn` — ML model & utilities
- `nltk` — NLP preprocessing
- `pandas` — Data manipulation
- `numpy` — Numerical computing

---

## ⚡ Important Notes

- **First Run**: NLTK stopwords are downloaded automatically on first execution
- **Production Deployment**: Set `debug=False` in `app.py` before deploying
- **Model Accuracy**: Performance varies based on training dataset; test with your use cases
- **Data Privacy**: Text submitted through the app is processed locally (configure as needed)

---

## 🔄 User Workflow

1. User inputs article text or URL
2. Backend extracts & preprocesses text
3. ML model classifies as "Real" or "Fake"
4. Confidence score returned with reasoning
5. Results displayed to user with actionable insights

---

## 📊 Success Metrics

- Article classification accuracy
- User engagement & sessions
- Average prediction confidence
- Feature usage (text vs. URL)

---

## 🛠️ Development

### Stop the Server
```bash
Ctrl+C
```

### Troubleshooting
- Verify Python 3.8+ installation: `python --version`
- Ensure virtual environment is activated before installing packages
- Check that port 5000 is available (or configure alternative in `app.py`)

---

## 📝 License

[Add your license information here]

---

## 🤝 Contributing

Contributions welcome! Please open an issue or submit a pull request with improvements.

---

**Last Updated**: 2026  
**Maintained By**: revan5x
