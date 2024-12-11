# 📊 Big Data Analytics for Business: Sentiment Analysis on IMDB Reviews

## 📝 Project Description
This project focuses on analyzing sentiment from IMDB movie reviews scraped from the web. Utilizing various machine learning techniques and natural language processing (NLP) methods, we classify user reviews into Positive, Neutral, or Negative categories. The goal is to derive insights into user sentiment towards a particular film and compare the performance of Support Vector Machines (SVM) and Logistic Regression models for sentiment classification.

## 📌 Objectives
- **Data Collection**: Gather IMDB movie review data through web scraping.
- **Data Preprocessing**: Clean and preprocess textual data for analysis.
- **Sentiment Classification**: Assign sentiment labels using a lexicon-based approach (VADER Sentiment Analyzer).
- **Model Training**: Train and evaluate SVM and Logistic Regression models.
- **Model Comparison**: Compare the performance of the two models using accuracy, confusion matrices, and classification reports.
- **Visualization**: Provide visual insights through heatmaps and bar plots to illustrate model performance and sentiment distribution.

## 🛠️ Technologies Used
- **Python**: Core programming language for data analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-Learn**: Machine learning library for training SVM and Logistic Regression models.
- **NLTK (VADER)**: Lexicon-based sentiment analysis tool for labeling data.
- **Seaborn & Matplotlib**: For creating insightful visualizations of model performance.

## 📈 Results

### Accuracy:
- **SVM**: ~79.52%
- **Logistic Regression**: ~81.93%

### Visualization:
- **Confusion Matrices**: Show prediction results for both models. These matrices help to understand how the models perform in terms of true positives, true negatives, false positives, and false negatives.
- **Bar Plot**: Compares the accuracy of the two models side by side, allowing for easy comparison of their performance.

## ✅ Conclusion
- **Logistic Regression** slightly outperformed **SVM** for sentiment classification in terms of accuracy.
- The **VADER Sentiment Analyzer** effectively labeled data for training, providing a strong starting point for sentiment classification.
- **Visualization** played a crucial role in gaining valuable insights into model performance and sentiment distribution, helping to identify misclassifications and areas for improvement.

## 🚀 Future Enhancements
- **Use Advanced Models**: Incorporate deep learning models such as **LSTM (Long Short-Term Memory)** or **BERT (Bidirectional Encoder Representations from Transformers)** to improve performance by better capturing the context and relationships within the text.
- **Expand Dataset**: Collect and analyze reviews from multiple movies across different genres to provide broader insights and ensure the model generalizes well.
- **Additional Preprocessing**: Implement more sophisticated text preprocessing techniques like **lemmatization**, **stopword removal**, and **TF-IDF (Term Frequency-Inverse Document Frequency)** to improve text representation and enhance model accuracy.

## 🎥 Link youtube : https://youtu.be/18hbHEv9Ezk
