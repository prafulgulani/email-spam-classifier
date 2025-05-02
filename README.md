# Spam Email Classification

This project explores the effectiveness of two distinct approaches to text classification: statistical models and embedding-based models. The goal is to evaluate how well these methods perform in the context of spam email detection.

## Overview

Spam email detection is a critical task in natural language processing (NLP) and cybersecurity. This project aims to compare statistical models (such as Naive Bayes and logistic regression) and embedding-based models (like BERT) to classify emails as spam or ham (non-spam). 

### Approaches

1. **Statistical Models**  
   - Naive Bayes: A probabilistic classifier that assumes independence between features.  
   - Logistic Regression: A regression model that outputs probabilities for multiple classes.

   These models rely on word frequency patterns and basic statistical methods to classify text.

2. **Embedding-Based Models**  
   - BERT (Bidirectional Encoder Representations from Transformers): A transformer-based model that captures deeper semantic and contextual relationships in the text. BERT has been trained on a large corpus of text, allowing it to understand the meaning of words in relation to the entire sentence.

   Embedding-based models like BERT provide rich, dense vector representations of text, which improves the model's ability to capture nuances in language, making them ideal for complex classification tasks like spam detection.

### Model Comparison
- Statistical Models are faster and less computationally intensive but struggle with more complex language structures.
- Embedding-Based Models provide state-of-the-art performance in NLP tasks, leveraging the power of pre-trained models for deeper contextual understanding but require more computational resources.

### Features
- Implementation of Naive Bayes and Logistic Regression classifiers for spam detection.
- Pre-trained BERT model fine-tuned on a spam email dataset.
- Comparison of the two model types in terms of performance metrics such as accuracy, precision, recall, and F1-score.

### Results

The project compares model performance based on several metrics, such as:

- Accuracy: Measures the overall percentage of correctly classified emails.
- Precision: The proportion of true positives among all the emails classified as spam.
- Recall: The proportion of actual spam emails that were correctly classified.
- F1-score: The harmonic mean of precision and recall, balancing the two metrics.

### Conclusion

In this project, embedding-based models like BERT outperform statistical models (Naive Bayes and logistic regression) in spam email classification tasks. The results showcase the power of transformer-based architectures in handling complex NLP tasks, including spam detection.

