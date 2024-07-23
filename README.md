# IMDB Movie Reviews : Sentiment Analysis
Classifying movie reviews as expressing positive or negative sentiment, based on the text content of the reviews.

## Introduction
Sentiment analysis of IMDB movie reviews is a fascinating area of natural language processing and machine learning. It involves the task of automatically determining the sentiment or emotional tone expressed in user-generated movie reviews on the Internet Movie Database (IMDB). IMDB is a popular platform where users share their thoughts and opinions about movies, making it a valuable source of sentiment-rich text data. IMDB movie review sentiment analysis is the process of classifying movie reviews as expressing positive or negative sentiment, based on the text content of the reviews.

## Comparison of 2 models
My initial curiosity was to compare a generative and discriminative model in this scenario. Going by that I trained and tested two models - Logistic Regression and Multinomial Naive Bayes. F1 score is usually considered as the most trusted metric for text classification. Even though both the models performed decent on the problem, the F1 score of Logistic Regression is clearly larger than Naive Bayes. Logistic Regression has a remarkable 89% test accuracy and F1 score, when compared to the 86% of Naive Bayes model. The confusion matrix has also documented the number of misclassifications and right classifications by the two models. A comparison of the test accuracy is drawn by the graph below.

## Challenges Faced
- Punctuations and tags: There are lot of punctuation marks and html tags which do not impart any information to the classifier.
- Noise and Spelling Errors: Noise in text data, including spelling errors, typos, or nonstandard language, can challenge sentiment analysis models. Preprocessing and cleaning are essential.
- Negation Handling: Negations in text, where a negative word is used to express a positive sentiment or vice versa, are tricky for models. For instance, "not bad" is a positive statement and it was present in a lot of records.

## Conclusion
It has been concluded that among the two models that we have chosen, Logistic Regression works better for this text classification problem. However, we may be able to improve the performance using LSTM and other deep learning models. Movie review analysis has a wide variety of applications which includes building accurate movie recommendation systems, quality control of the movies, award predictions and box-office predictions. This is a strong area in today's digital era, which can be explored further for deeper and more meaningful analysis
