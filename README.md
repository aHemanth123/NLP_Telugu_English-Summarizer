# NLP_Telugu_English-Summarizer  
Telugu Summarizer and English Summarizer  


This project builds a bilingual summarization system that generates **Telugu abstractive summaries** using **mT5** and provides **English translations** using **NLLB-200**. The system is designed for multilingual NLP tasks, especially for low-resource Indian languages.

# Improvement 1
Adding Each Stage as a graph 

# Improvement 2
Visualizing using Langsmith

---

## 🚀 Features
- Telugu abstractive summarization using **mT5**
- Optional English translation using **NLLB-200**
- Metrics used: **BERTScore**, **ChrF**, **ROUGE**
- Supports HuggingFace `datasets`, `evaluate`, and `transformers`
- Complete multilingual pipeline for summarization + translation

---

## 📦 Installation
Install the required libraries:

```bash
pip install -U datasets==3.2.0

pip install -U evaluate transformers sentencepiece
pip install bert-score sacrebleu rouge-score sumy indic-nlp-library
```

## 🧠 Model Workflow

### 1️⃣ Telugu Summarization (mT5)
- Uses **mT5-base** for abstractive summarization  
- Handles **tokenization, preprocessing, and generation**  
- Produces **compact and semantically accurate Telugu summaries**  

### 2️⃣ English Translation (NLLB-200)
- Converts **Telugu summary → English**  
- Uses **NLLB-200 (600M / 1.3B)** for high-quality translation  
- Enhances accessibility for **non-Telugu readers**  

---

## 📊 Evaluation

The model performance is validated using the following metrics:

| Metric      | Purpose                               |
|-------------|----------------------------------------|
| **BERTScore** | Semantic similarity check             |
| **ChrF**      | Character-level translation quality   |
| **ROUGE**     | Summary overlap & relevance           |


 
