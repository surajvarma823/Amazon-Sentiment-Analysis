# Amazon Sentiment Analysis

## Sentiment Analysis with Multinomial Naive Bayes

This project demonstrates sentiment analysis using the **Multinomial Naive Bayes** classifier. It analyzes the sentiment of Amazon product reviews and classifies them into **Positive**, **Negative**, or **Neutral** categories.

---

## Dataset

The dataset used in this project contains Amazon product reviews with sentiment labels. 

### Requirements:
- The dataset should be in **CSV format**.
- It must contain at least two columns:
  - **`Text`**: Contains the text of the reviews.
  - **`Sentiment`**: Contains the sentiment labels (e.g., 'Positive', 'Negative', 'Neutral').

---

## Features

- Sentiment classification of Amazon product reviews.
- Model training and evaluation using **Multinomial Naive Bayes**.
- Performance metrics include:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Support for each sentiment class.

---

## Usage

### Prerequisites
Ensure the following are installed:
- Python 3.x
- Required libraries:
  - `scikit-learn`
  - `pandas`

### Steps to Run the Project

1. **Prepare the Dataset**:
   - Replace `'your_dataset.csv'` in the script with the path to your dataset file.
   - Ensure the dataset includes the columns **`Text`** and **`Sentiment`**.

2. **Run the Code**:
   - Execute the Python script to train and evaluate the Multinomial Naive Bayes model.

3. **View Results**:
   - The code will display:
     - **Model accuracy**.
     - A detailed **classification report** that includes precision, recall, F1-score, and support for each sentiment category.

4. **Customize**:
   - Experiment with:
     - Different hyperparameters.
     - Feature extraction techniques.
     - Other machine learning models to improve performance.

---

## Dependencies

- **Python 3.x**
- **scikit-learn**: For machine learning algorithms and evaluation metrics.
- **pandas**: For data manipulation and preprocessing.

Install the required libraries using:
```bash
pip install scikit-learn pandas
