Load datasets: Fake.csv, True.csv
Label each dataset (Fake, Real)
Merge datasets into one
Preprocess text:
Lowercasing
Removing punctuation/symbols
Tokenization
Stopword removal
Stemming
Store results in a new column: clean_text
🟩 Part 2: Feature Extraction & Model Training

Use TfidfVectorizer(max_features=5000) to convert text to numbers
Analyze top keywords using average TF-IDF scores
Train classifier models:
Multinomial Naive Bayes (Fake/Real)
Evaluate models with accuracy score, classification report
