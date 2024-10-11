# Text Summarization and Classification


## Overview
This project implements a news article summarization system using extractive summarization techniques. The core algorithm is TextRank, used for ranking and extracting key sentences. Additionally, K-Means Clustering is applied to group similar sentences for better summarization. For topic modeling and dimensionality reduction, Latent Semantic Analysis (LSA) is employed. The system further integrates various classification algorithms such as Logistic Regression, Random Forest, and SVM to evaluate the summarization quality.

### Key achievements:
1. Summarization performance: 85% precision, 80% recall, and 82% F1-score.
2. Tested on datasets containing 1,000+ news articles from BBC News and Reuters.
3. Implemented using libraries like NLTK, Scikit-learn, and Gensim.
   
### Features
1. Extractive Text Summarization: Generates concise summaries by extracting the most important sentences.
2. Topic Modeling with LSA: Analyzes the main topics in the dataset using Latent Semantic Analysis.
3. Sentence Clustering: Groups similar sentences to improve summary coherence using K-Means Clustering.
4. Classification Models: Tests summarization quality using Logistic Regression, Random Forest, and SVM.
5. Performance Evaluation: Calculates precision, recall, and F1-score for summarization quality.

### Dataset
The project uses datasets from BBC News and Reuters, consisting of over 1,000 news articles. The dataset file (news_articles.csv) should contain the following columns:

text: The news article text.
label: Classification labels (for testing classification models).
