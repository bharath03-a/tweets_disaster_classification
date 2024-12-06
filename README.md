# 🚀 Disaster Tweet Classification Project

![Twitter Logo](https://upload.wikimedia.org/wikipedia/commons/6/6f/Logo_of_Twitter.svg)

## 📝 Overview
This project focuses on **Natural Language Processing (NLP)** techniques to classify tweets into two categories:
1. **Disaster Tweets**: Tweets indicating an actual disaster.
2. **Non-Disaster Tweets**: Tweets unrelated to disasters.

The data is sourced from the [Kaggle Competition - NLP Getting Started](https://www.kaggle.com/competitions/nlp-getting-started/overview).

---

## 📂 Project Structure
- **Exploratory Data Analysis (EDA)**: Visualizations to understand the dataset better.
- **Text Preprocessing**: 
  - Removing stopwords, special characters, and emojis.
  - Lemmatization.
  - Custom feature engineering (e.g., word count, hashtag count).
- **Modeling**:
  - Leveraging TF-IDF vectorization to extract features.
  - Training multiple classification models (e.g., Random Forest, XGBoost, Logistic Regression).
  - Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.

---

## 📊 Features
### Data
- **Training Dataset**: 7613 tweets, each labeled as either disaster (`1`) or non-disaster (`0`).
- **Test Dataset**: Used to evaluate the model's generalization capability.

### Custom Features
- Word Count
- Unique Word Count
- URL Count
- Character Count
- Hashtag and Mention Count

### Machine Learning Models
- **Baseline Models**: Naive Bayes, Logistic Regression.
- **Advanced Models**: Random Forest, Gradient Boosting, XGBoost.

---

## 🔧 Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/bharath03-a/disaster-tweet-classification.git


## 🛠 Tools and Technologies

- **Programming Language**: Python  
- **Libraries**:  
  - **NLP**: `spacy`, `TfidfVectorizer`  
  - **Machine Learning**: `sklearn`, `xgboost`  
  - **Visualization**: `matplotlib`, `seaborn`  
- **Platform**: Google Colab