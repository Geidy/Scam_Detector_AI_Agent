# Scam_Detector_AI_Agent

1. Data Collection
To train your AI, you'll need examples of both legitimate and scam emails.
Sources for Scam Emails:
Phishing Email Datasets: Enron Spam Dataset
Sources for Legitimate Emails:
Enron Email Dataset

2. Preprocessing
Clean and prepare data for analysis.

3. Feature Engineering
Some useful features might include:

NLP-based features:

4. Model Training
Use a combination of models:

Classical ML: Logistic Regression, Random Forest, XGBoost (with hand-crafted features)
Deep Learning: LSTM, BERT, RoBERTa (especially for analyzing email body content)
Hybrid: Use ML for language, and a rule-based system for technical metadata
