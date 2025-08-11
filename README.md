# Real vs. Fake News - A Deep Learning Approach
The rapid spread of misinformation online has made fake news detection a critical challenge. This project aims to classify news articles as **Real** or **Fake** using **Deep Learning techniques**. It demonstrates end-to-end development, from data preprocessing to model evaluation, leveraging modern NLP techniques.

## Project Overview
This project focuses on detecting **fake news** using advanced **Deep Learning** and **NLP techniques**. The pipeline includes thorough data preprocessing, class balancing strategies, and training multiple models, including neural networks and transformer-based architectures.

---

## Key Features
- **Data Preprocessing:**
  - Merged and labeled datasets (`Fake.csv`, `True.csv`)
  - Cleaned text (removed duplicates, handled missing values)
  - Performed **Exploratory Data Analysis** **(EDA)** to analyze real vs. fake news distribution
  - Applied **data augmentation** for class diversity
  - Tokenization and padding for neural network compatibility
  - Addressed class imbalance using **SMOTE** and other strategies

- **Models Implemented:**
  - **MLP (Multi-Layer Perceptron):** Multiple hyperparameter tuning experiments
  - **CNN (Convolutional Neural Network):** Deep text feature extraction
  - **DistilBERT Fine-Tuning:** Transfer learning on a subset (10%) of the dataset for improved performance

- **Evaluation Metrics:**
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix visualization

---

## Tech Stack
- **Programming Language:** Python
- **Deep Learning Frameworks:** TensorFlow, Keras
- **NLP Tools:** NLTK, HuggingFace Transformers
- **Other Libraries:** Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

## Evaluation Metrics:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix visualization