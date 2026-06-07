# Real vs. Fake News Detection using Deep Learning

## Overview

Fake news has become a significant challenge in the digital age, influencing public opinion and accelerating the spread of misinformation. This project investigates the application of Deep Learning and Transformer-based Natural Language Processing (NLP) techniques to automatically classify news articles as **Real** or **Fake**.

Three different architectures were developed and compared:

- Multi-Layer Perceptron (MLP)
- Convolutional Neural Network (CNN)
- DistilBERT (Transformer-based Model)

The primary goal is to determine the most effective approach for fake news classification while evaluating predictive performance, generalization capability, and computational efficiency.

---

## Business Problem

The rapid dissemination of misinformation through online platforms poses serious risks to society, politics, and public trust. Manual fact-checking is time-consuming and difficult to scale.

This project addresses the challenge by developing an AI-powered classification system capable of automatically identifying fake news articles with high accuracy, helping organizations and users detect misinformation more efficiently.

---

## Dataset

The project utilizes the **Fake and Real News Dataset** available on Kaggle.

### Dataset Characteristics

- Real news articles
- Fake news articles
- Binary classification task
- Thousands of labeled records

### Target Labels

| Label | Description |
|--------|-------------|
| 0 | Fake News |
| 1 | Real News |

---

## Project Workflow

### 1. Data Preparation

- Data loading and inspection
- Data cleaning
- Label assignment
- Dataset merging
- Missing value verification

### 2. Exploratory Data Analysis (EDA)

- Distribution of fake vs. real news
- Text length analysis
- Word frequency exploration
- Dataset balance verification

### 3. Text Preprocessing

- Lowercasing
- Tokenization
- Stopword removal
- Text normalization
- Sequence padding
- Train / Validation / Test split

### 4. Model Development

#### Multi-Layer Perceptron (MLP)

A feed-forward neural network trained on vectorized text representations.

#### Convolutional Neural Network (CNN)

A deep learning architecture that captures local textual patterns and semantic relationships through convolutional layers.

#### DistilBERT

A pre-trained Transformer model fine-tuned for fake news detection. DistilBERT leverages transfer learning and contextual language understanding to achieve superior classification performance.

---

## Evaluation Metrics

Model performance was assessed using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Loss

---

## Results

| Model | Test Accuracy |
|--------|---------------|
| MLP Tuned v2 | 99.04% |
| CNN Tuned v2 | 98.81% |
| DistilBERT | 99.66% |

### Best Performing Model: DistilBERT

#### Performance Highlights

- **Test Accuracy:** 99.66%
- **Precision:** ~1.00
- **Recall:** ~1.00
- **Lowest Test Loss**

DistilBERT achieved the highest overall performance and demonstrated superior generalization compared to both MLP and CNN architectures.

---

## Key Insights

- Transformer-based architectures significantly outperform traditional deep learning approaches for fake news classification.
- DistilBERT captures contextual meaning more effectively than CNN and MLP models.
- Lightweight Transformer models can achieve near-perfect performance on news credibility classification tasks.
- Transfer learning substantially improves NLP performance while reducing training requirements.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-Learn
- PyTorch
- Hugging Face Transformers
- DistilBERT

---

## Future Improvements

- Evaluate RoBERTa and DeBERTa architectures
- Perform advanced hyperparameter optimization
- Implement Explainable AI techniques (SHAP, LIME)
- Deploy the solution using Streamlit
- Develop a real-time fake news detection API

---

## Conclusion

This project demonstrates the effectiveness of Deep Learning and Transformer-based NLP models for fake news detection. Among the evaluated architectures, DistilBERT delivered the strongest performance with **99.66% test accuracy**, highlighting the power of transfer learning and contextual language understanding for misinformation classification tasks.

---

```
