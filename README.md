# movie_review
IMDB Dataset source : **https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews**


The provided code conducts sentiment analysis on an IMDb dataset using natural language processing (NLP) techniques and machine learning algorithms. Here is a step-by-step breakdown:

Data Exploration:
The IMDb dataset is loaded using pandas, and initial exploratory data analysis is performed.
Duplicates are removed from the dataset.

Text Analysis:
Various text features are extracted, including word count, unique word count, stop words count, URL counts, and mean word length.
Visualizations, such as a bar plot and histograms, are created to explore the distribution of sentiment and text features.

Text Preprocessing:
Text data undergoes a comprehensive preprocessing pipeline, including the removal of HTML tags, URLs, emojis, punctuations, and stop words.
Lemmatization and handling of negations and special characters are also performed.
Text Vectorization:
The preprocessed text is transformed into numerical representations using both Bag-of-Words (BoW) and TF-IDF vectorization techniques.
Word clouds are generated to visualize the most frequent words in both BoW and TF-IDF representations.

Machine Learning Models:
A variety of machine learning algorithms, including Decision Trees, Logistic Regression, Random Forest, AdaBoost, Bagging, XGBoost, and CatBoost, are applied to predict sentiment.
The models are trained and evaluated using accuracy scores on both training and testing datasets.

Evaluation:
Model performance is evaluated using classification reports and confusion matrices for each algorithm.
Results show the accuracy, precision, recall, and F1-score for positive and negative sentiment predictions.

Conclusion:
The code provides a comprehensive analysis of sentiment in IMDb reviews, showcasing the application of various NLP and machine learning techniques.
Users can refer to the classification reports and confusion matrices to understand the performance of different algorithms on sentiment prediction.
