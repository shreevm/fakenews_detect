# fakenews_detect
The project aims to develop a data science solution to predict fake news using predictive analytics techniques.

This project focuses on developing a data science solution for detecting fake news using machine learning and natural language processing techniques. The goal is to build a model that can classify news articles into two categories: fake or genuine. By automating the detection process, we aim to assist users in making informed decisions and promote reliable information dissemination.

Using sklearn, we build a TfidfVectorizer on our dataset. Then, we initialize a PassiveAggressive Classifier and fit the model. In the end, the accuracy score and the confusion matrix tell us how well our model fares.

The fake news Dataset:
 news.csv -> dataset is been used. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. The dataset takes up 29.2MB of space.
