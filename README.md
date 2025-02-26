# AI-Powered Fake News Detection using NLP & Multi-Modal Learning

## Overview
This project focuses on detecting **fake news** using **Natural Language Processing (NLP)** and **Multi-Modal AI** by analyzing both **textual content and accompanying images**. The goal is to combat misinformation by integrating **deep learning models** for news classification and image verification.

## Features
- **Fake News Classification**: Uses **BERT/RoBERTa/GPT models** to analyze and classify news articles.
- **Multi-Modal Verification**: Implements **CLIP (Contrastive Language-Image Pretraining)** to cross-check images with their captions.
- **Fact-Checking API Integration**: Compares claims with **Google Fact Check API, Politifact, and Snopes** for authenticity.
- **Explainability (XAI)**: Uses **SHAP/LIME** to explain why an article is classified as fake.
- **Real-Time Browser Extension**: Highlights fake news in real-time with a **Chrome extension**.

## Technologies Used
- **Python**
- **Hugging Face Transformers (BERT, RoBERTa, GPT)**
- **TensorFlow / PyTorch**
- **CLIP (for Image Verification)**
- **Google Fact Check API**
- **SHAP/LIME for Explainability**
- **Flask/FastAPI (for deployment)**

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/Fake-News-Detection.git
cd Fake-News-Detection

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
python detect_fake_news.py --input "path_to_news_article" --output results.json
```

## Dataset
- **LIAR Dataset**: A labeled dataset for fake news detection.
- **FakeNewsNet**: A dataset containing textual and visual fake news samples.
- **Custom Data Collection**: Scraped real-time misinformation from news sources.

## Results (Undergoing)
| Real News | Fake News |
|-----------|----------|
| ![Real](images/real_news.jpg) | ![Fake](images/fake_news.jpg) |

## Future Work
- Improve **fact-checking accuracy** with **knowledge graphs**.
- Enhance **generalization across multiple languages**.
- Develop **mobile applications for real-time misinformation detection**.
- Publish findings in **ACL, EMNLP, or AI Ethics conferences**.

## Contributing
Feel free to contribute by submitting **pull requests** or opening **issues**.



## Contact
For inquiries, contact **Md Hamid** at mdhamid1752002@gmail.com.
