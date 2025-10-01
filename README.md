# Misinfo-Detector-HybridMLDL
A hybrid machine learning and deep learning approach for automated misleading information detection on social media platforms.This project leverages traditional ML classifiers (KNN, Gradient Boosting, Decision Tree) alongside a CNN-LSTM deep learning model to analyze both content and social context. The system evaluates user behavior patterns, message structure, and engagement styles to improve the accuracy of fake news detection.

Download the GloVe embeddings from the official Stanford NLP website:  
   [GloVe 6B Pre-trained Word Vectors - glove.6B.100d.txt](https://nlp.stanford.edu/projects/glove/) 
   
Download the Dataset from kaggle:
    -Fake.csv
    -True.csv
    
Run the scripts in the following order:
   - CNN-LSTM Model - CNNLSTM.ipynb
   - Machine Learning Models (KNN, GB, DT) - FakeNews.ipynb
   - Evaluation Metrics - r test.ipynb
   - Main file - main.ipynb

## Future Work
- Expand dataset with multilingual fake news sources  
- Explore transformer-based models (BERT, RoBERTa) for comparison  
- Improve social-context based detection features  

Thank you for exploring this project!  
