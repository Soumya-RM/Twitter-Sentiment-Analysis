# Twitter-Sentiment-Analysis
* Dataset: Sentiment140 (Kaggle)
* Task: Classify tweets as positive or negative
* Model: LSTM (Keras) with Embedding + Dense layers
* Accuracy: ~78% on test set

Workflow
* Cleaned tweets (removed URLs, mentions, hashtags, etc.)
* Tokenized and padded sequences
* Built and trained LSTM model
* Evaluated with accuracy, F1-score, and confusion matrix
* Deployed function to predict sentiment on custom text
