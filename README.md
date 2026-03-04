# Sentiment Analysis Model Comparison (NLP)

This project presents a comparative study of traditional machine learning and deep learning models for sentiment classification using the IMDB Movie Reviews dataset.

The aim of this study is to evaluate how different NLP models perform on the same dataset and identify the most effective approach for sentiment classification.

---

## Project Overview

Natural Language Processing (NLP) enables machines to understand and analyze human language. One of the most common NLP tasks is **sentiment analysis**, where text is classified based on emotional tone.

In this project, multiple models were implemented and compared to determine which performs best on movie review sentiment classification.

The study evaluates:

- Traditional Machine Learning models
- Deep Learning models
- Transformer-based architectures

---

## Dataset

Dataset used: **IMDB Movie Reviews Dataset**

Features:

- 50,000 movie reviews
- Balanced dataset
- 25,000 positive reviews
- 25,000 negative reviews

The dataset is commonly used as a benchmark for sentiment classification tasks.

---

## Models Implemented

The following models were trained and evaluated:

### Traditional Machine Learning
- Naive Bayes
- K-Means Clustering

### Deep Learning Models
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)

### Transformer Model
- Transformer-based architecture for contextual language understanding

---

## Preprocessing Steps

The dataset was preprocessed before model training using several NLP techniques:

- Tokenization
- Stop-word removal
- Text normalization
- TF-IDF vectorization (for traditional ML models)
- Sequence padding (for deep learning models)

---

## Evaluation Metrics

Models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

These metrics provide a comprehensive assessment of classification performance.

---

## Results Summary

| Model | Accuracy |
|------|------|
| Naive Bayes | ~87% |
| RNN | ~89% |
| LSTM | **~91%** |
| Transformer | ~89.7% |

Key findings:

- **LSTM achieved the highest accuracy**
- Deep learning models outperform traditional ML models
- Transformer models capture contextual relationships effectively

---

## Visualizations

The project includes several visual analyses:

- Confusion matrices
- ROC curves
- Precision–recall curves
- Model accuracy comparison

These visualizations help interpret model performance.

---

## Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

---

## Project Structure

## Future Improvements

Potential improvements for future work include:

- Using pre-trained models such as **BERT or GPT**
- Applying hyperparameter optimization
- Evaluating models on additional text datasets
- Implementing cross-domain sentiment analysis
