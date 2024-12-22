# YouTube Comment Sentiment Analysis

This project focuses on extracting, analyzing, and visualizing sentiments from YouTube video comments using Machine Learning (ML) and Natural Language Processing (NLP) techniques. By leveraging data from the YouTube API, we aim to classify comments into positive, negative, or neutral sentiments.

---

## Project Overview

### Objectives
- Extract comments from multiple YouTube videos using the YouTube API.
- Clean and preprocess the data for analysis.
- Conduct sentiment analysis using VADER and classify comments into three sentiment categories: Positive, Negative, and Neutral.
- Train ML models and a Deep Learning (LSTM) model to classify sentiments.
- Visualize sentiment distribution and key metrics.

---

## Tools and Technologies

### Programming Languages and Libraries
- **Languages**: Python
- **Libraries**: 
  - `google-api-python-client` for YouTube API integration.
  - `pandas`, `matplotlib`, and `seaborn` for data analysis and visualization.
  - `nltk` and `textblob` for NLP and sentiment analysis.
  - `scikit-learn` for ML model development.
  - `TensorFlow` for Deep Learning (LSTM model).
  - `sqlite3` for storing data.

---

## Key Features

1. **Data Collection and Storage**
   - Comments extracted using the YouTube API.
   - Saved raw and cleaned data into SQLite databases and CSV files.

2. **Data Preprocessing**
   - Removed noise such as URLs and special characters.
   - Applied tokenization, stopword removal, and lemmatization to standardize text.

3. **Sentiment Analysis**
   - Performed sentiment analysis using the VADER sentiment analyzer.
   - Classified comments into Positive, Negative, and Neutral sentiments.

4. **Model Development**
   - Implemented ML models: Logistic Regression, SVM, and Naive Bayes.
   - Built an LSTM model for sentiment classification.

5. **Visualization**
   - Visualized sentiment distribution, likes distribution, and top channels by comment count.
   - Created a comparison of model accuracies and confusion matrices.

---

## Results

### Sentiment Distribution
- Positive: 60%
- Neutral: 25%
- Negative: 15%

### Model Comparison (Updated)
| Model                | Accuracy   |
|----------------------|------------|
| Logistic Regression  | 77.42%     |
| SVM                  | 76.63%     |
| Naive Bayes          | 63.75%     |
| LSTM                 | 77.51%     |

### Visualization: Model Accuracy Comparison
![Model Accuracy](https://github.com/snsamia/YT-Sentiment-Analysis/blob/main/accuracy_comparison_updated.png)

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/snsamia/YT-Sentiment-Analysis.git
