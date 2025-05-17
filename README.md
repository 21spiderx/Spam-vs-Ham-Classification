# Spam-vs-Ham-Classification
An NLP project using Word2Vec, SMOTE and Ensemble ML models.
It focuses on one of the classic classification problems in Natural Language Processing (NLP): detecting whether a given SMS message is **spam** or **ham** (not spam). The solution integrates text preprocessing, word embeddings and ensemble models to classify messages effectively.

I. Overview

- **Dataset**: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Techniques Used**:
  - Text cleaning, tokenization, lemmatization and stopword removal
  - Word embeddings using **Google’s pretrained Word2Vec model**
  - Feature representation using average word vectors
  - Class balancing using **SMOTE**
  - Classification using: **Random Forest**, **XGBoost** and **LightGBM**
 
II. Models Trained

- **Random Forest Classifier**
- **XGBoost Classifier**
- **LightGBM Classifier**

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

III. Key Challenges

- **Class Imbalance**: Handled using SMOTE to synthetically oversample the minority (spam) class
- **High-Dimensional Text Data**: Solved using dense vector representations (Word2Vec)

IV. How to Use

1. Clone the repository
2. Open the Jupyter Notebook (`.ipynb`)
3. Run each cell to follow the entire preprocessing and model training pipeline

V. Dependencies

Install required packages using:
```bash
pip install -r requirements.txt



