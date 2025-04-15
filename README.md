# Data-Science-Internship-Tasks
Sentiment Analysis Report on IMDB Dataset

1. Introduction
In this project, I analyzed movie reviews from the IMDB dataset to predict whether a review is positive or negative. The goal was to use machine learning to understand the sentiment behind each review.

2. Data Preprocessing
Text Processing:
I split the reviews into individual words.
Removed common words (stopwords) like "the", "and", etc., which don't add much meaning.
Changed words to their base forms (e.g., "running" becomes "run").
Feature Engineering:
I converted the text into numbers using TF-IDF. This method turns words into numeric values, so the model can understand them.


3. Model Training
Model Used: I used Logistic Regression to predict whether a review is positive or negative.
Data Split: 80% of the data was used to train the model, and 20% was used to test it.


4. Model Evaluation
Here’s how the model performed:

Precision: The model was good at correctly identifying positive and negative reviews.
Recall: The model was also good at finding most of the positive and negative reviews.
F1-Score: Overall, the model had an F1-score of 0.86, showing a good balance between precision and recall.

5. Conclusion

The model worked well with an accuracy of 86%. There are ways to improve it, such as:
Trying different models or adjusting the settings.
Using advanced techniques like word embeddings (which capture more meaning from words).
