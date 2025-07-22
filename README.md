# Advanced NLP for Real-World Sustainability Applications 🌍

This repository showcases advanced Natural Language Processing (NLP) techniques applied to real-world sustainability data. The project covers end-to-end pipelines for sentiment analysis, topic modeling, named entity recognition, and text summarization using state-of-the-art models like RoBERTa and spaCy.

## 🧠 Tasks Implemented

1. **Sentiment Analysis with RoBERTa**  
   Fine-tuned RoBERTa model to classify 1.6M+ tweets into positive, negative, or neutral sentiments.

2. **Topic Modeling using LDA**  
   Applied Latent Dirichlet Allocation (LDA) to uncover dominant topics in sustainability-related tweets.

3. **Named Entity Recognition (NER)**  
   Extracted entities like products, organizations, and locations using spaCy’s pre-trained NER pipeline.

4. **Text Summarization**  
   Fine-tuned a transformer model on BBC articles to generate human-like abstractive summaries.

## 💾 Dataset Sources

- **Twitter Dataset:** 1.6M tweets filtered by sustainability-related keywords.
- **BBC News Dataset:** News articles with human-written summaries for fine-tuning the summarizer.

## 🚀 How to Run

```bash
git clone https://github.com/elprofessor-15/Advanced-NLP
cd Advanced-NLP
pip install -r requirements.txt
jupyter notebook
