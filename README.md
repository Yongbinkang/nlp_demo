# 📌 UHK Seminar Demo - NLP Analysis using Python

## 📖 Overview  
This Jupyter Notebook demonstrates **Natural Language Processing (NLP) techniques** using Python. It covers **syntactic analysis, sentiment analysis, emotion extraction, semantic analysis, and topic modelling**, providing structured insights into text.

## 📂 Contents of the Notebook  

### 1. Syntactic Analysis  
- **Tokenization**: Extracts words and sentences.  
- **Stopword Removal**: Filters out common words that do not contribute meaning.  
- **Lemmatisation**: Converts words to their base form.  
- **POS Tagging**: Identifies the grammatical role of words.  
- **Word Importance**: Computes word frequency and significance.  
- **Sentence Importance**: Ranks sentences based on word importance.  

### 2. Semantic Analysis  
- **Named Entity Recognition (NER)**: Identifies **entities** such as people, locations, and objects.  
- **Word Similarity**: Measures similarity scores between words (e.g., *cat vs. mouse*).  
- **Relationship Extraction**: Identifies word interactions (e.g., *who did what to whom*).

### 3. Sentiment & Emotion Analysis  
- **Word-Level Sentiment**: Assigns sentiment polarity scores (-1 to 1) to words.  
- **Sentence-Level Sentiment**: Classifies sentences as **positive, negative, or neutral**.  
- **Emotion Extraction**: Categorises words into a emotion category: **joy, anger, sadness, fear, trust, anticipation, surprise, and disgust**.  


### 4. Topic Modeling  
- Extracts **dominant topics** from a text corpus.  
- Identifies key **themes** in AI, finance, and other domains.

### 5. Use of ChatGPT Prompts   
- Promtp for Syntantic Analysis  
- Prompt for Semantic Analysis
- Prompt for Emotion Extraction
- Prompt for Topic Modelling

## 📦 Dependencies & Installation  
To run this notebook, install the required Python libraries:  
```bash
pip install spacy nltk gensim matplotlib seaborn textblob
python -m spacy download en_core_web_sm
