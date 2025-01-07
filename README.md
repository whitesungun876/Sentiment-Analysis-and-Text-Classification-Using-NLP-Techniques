# Sentiment-Analysis-and-Text-Classification-Using-NLP-Techniques
Part 1: Sentiment Analysis

Compared VADER and fine-tuned BERT (distilbert-base-uncased-finetuned-sst-2-english) models on an English corpus.

Classified 100 sentences and logged results in sent_comp.txt (format: Sentence, ResVADER, ResBERT).

Analyzed agreement rates between models.

Part 2: Text Classification

Built Logistic Regression models using:

Bag of Words with CountVectorizer.

TF-IDF normalization for improved performance.

Named Entity Recognition (NER) to enhance feature representation.

Evaluated models with the fetch_20newsgroups dataset and compared results.

Technologies Used

Python: NLTK, Hugging Face Transformers, Scikit-learn, SpaCy.

Setup Instructions

Results
BERT outperformed VADER for sentiment analysis, highlighting model differences.
NER-enhanced features improved text classification accuracy.

