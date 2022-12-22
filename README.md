# News-Article-Classifier
A machine learning model to predict article category using some text of the article. Data from [BBC News Clssification | Kaggle](https://www.kaggle.com/competitions/learn-ai-bbc/data).

## Steps:
Using LSTM is not effcient for such a small data set, so replaced it with MultinomialNB.
1. Data Loading
2. Data Cleaning
3. Data Preprocessing
4. Model Training  
5. Testing

## Features:
- 1490 instances
- 3 columns(ArticleId, Article, Category)
- 5 Categories ('business', 'tech', 'politics', 'sport', 'entertainment')
