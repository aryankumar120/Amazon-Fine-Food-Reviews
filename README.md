# 🛒 Amazon Review Sentiment Analysis

A Natural Language Processing (NLP) project comparing NLTK’s VADER and Hugging Face’s RoBERTa Transformer for sentiment classification on Amazon Fine Food Reviews.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python"/>
  <img src="https://img.shields.io/badge/NLP-Sentiment_Analysis-green"/>
  <img src="https://img.shields.io/badge/Transformers-HuggingFace-yellow?logo=huggingface"/>
  <img src="https://img.shields.io/badge/Notebook-Kaggle-orange?logo=jupyter"/>
</p>

# 📖 Project Overview

This project walks through a complete Sentiment Analysis pipeline using Amazon Customer Reviews.
We implement two different approaches:

	1.	🧩 Traditional Method → VADER (Valence Aware Dictionary and sEntiment Reasoner) from NLTK
	•	Lexicon + rule-based
	•	Fast and interpretable
	•	Doesn’t capture context
 
	2.	🤗 Modern Deep Learning Method → RoBERTa Transformer from Hugging Face
	•	Pre-trained contextual embeddings
	•	Better at handling sarcasm, negations, and nuanced text
	•	Transfer learning for sentiment classification

We compare the outputs, evaluate their strengths & weaknesses, and visualize results.

# 📂 Dataset

We use the Amazon Fine Food Reviews dataset 🍽️:
	•	~500,000 reviews (subset of 500 for demo, can scale up)
	•	Columns include: Id, ProductId, UserId, Score (1–5), Text

 # 🚀 Workflow

##🔎 1. Exploratory Data Analysis (EDA)
	•	Plot distribution of review scores ⭐
	•	Analyze bias (majority are 5-star reviews)
	•	Visualize sentiment word clouds
 
<img width="830" height="466" alt="image" src="https://github.com/user-attachments/assets/caad5e7c-afe7-4928-b3de-3d6ce2425b1d" />

##📝 2. Traditional Sentiment Analysis with VADER
	•	Tokenization & POS tagging with NLTK
	•	Apply VADER to extract sentiment scores.

 <img width="581" height="462" alt="image" src="https://github.com/user-attachments/assets/99e1c79a-bb18-41df-b429-5eed9868881b" />
                 
 ##📝 3. Advanced Sentiment Analysis with RoBERTa (Hugging Face)
 
 <img width="1121" height="273" alt="image" src="https://github.com/user-attachments/assets/76ab385c-b4a4-47df-b39b-8eb150a40b57" />
           
 ## ⭐4. Model Comparison

 <img width="751" height="712" alt="image" src="https://github.com/user-attachments/assets/3dc49bd4-373b-48d8-856e-3480b34ede45" />






