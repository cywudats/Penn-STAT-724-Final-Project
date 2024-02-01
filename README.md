# Penn-STAT-724-Final-Project

**Project Topic**: NLP Application on Financial Topic

**Course**: STAT 7240 Text Analytics

**Term**: Fall 2023

**Author**: Cheng-Ying Wu

**Project Description:**

This project embodies the spirit of exploration and application of advanced text analysis techniques on novel datasets not covered in the course. Utilizing the FinancialPhraseBank dataset, the project aims to delve into the intricacies of financial news headlines by applying topic modeling to uncover underlying themes, sentiment analysis to gauge emotional undertones, and various classification models to categorize the data effectively. By employing word embeddings obtained from BERT and training new ones, the project seeks to unearth and map out the nuanced relationships between terms used in the financial lexicon. The ultimate goal is to construct models that can accurately predict the sentiment of financial news, providing valuable insights from the perspective of retail investors.

**Data Source:**

Sentiment Analysis for Financial News (FinancialPhraseBank)
*  Kaggle Link: https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news/data
*  Data Origin: The data originates from the FinancialPhraseBank, which is publicly available on Kaggle. The dataset specifically aims to reflect the sentiments found in financial news headlines from the perspective of a retail investor

**Project Result:**

The modeling experiments have shown that the use of different encoding techniques can have a substantial impact on the performance of predictive models. The XGBoost model, coupled with Tokenizer and texts_to_sequences encoding, yielded moderate results with an accuracy and recall of approximately 61.57% and a slightly lower F1 score of 51.67%. In contrast, the GRU model, which utilized BERT embeddings for text encoding, significantly outperformed the XGBoost model, achieving a consistent accuracy, precision, recall, and F1 score of 79%. The improvement with GRU could be attributed to BERT's sophisticated understanding of language context and nuances, especially beneficial for the complexity of financial texts.
