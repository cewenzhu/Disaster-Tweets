# Disaster-Tweets
Used RoBERTa to identify disaster tweets, achieved a 84% precision rate, placed top 3% among 1200+ teams
- Preprocessed tweets by removing irrelevant elements, tokenizing parsagraphs into list of words, and lemmatizing words into their root forms
- Developed a basline SVM model with bag-of-word vectorization, which scored 77% in precision
- Implemented RoBERTa with KFold CV for hyperparameter tunning, which improved precision to 84%
