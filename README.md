NAME: ANANDA SURYA SRAVAN
ID:CT12ML179
DOMAIN: MACHINE LEARNING
DURATION: MAY-JULY
MENTOR: SRAVANI GOURI
DESCRIPTION:
his repository implements movie sentiment analysis using a Random Forest Classifier from scikit-learn. It classifies movie reviews as positive or negative.

Preprocessing:

Natural Language Processing (NLP): Text data is cleaned and prepared for machine learning. This may involve:
Lowercasing text
Removing punctuation and stop words (common words like "the", "a", "an")
Lemmatization (converting words to their base form)
Machine Learning Model:

Random Forest Classifier: This is a supervised learning algorithm that trains a model on labeled data (reviews with known sentiment) to classify new, unseen reviews.
Count Vectorizer: Converts preprocessed text data into numerical features. It counts the occurrences of each word in the vocabulary.
Implementation:

Load Data: Load a movie review dataset with labeled sentiment (positive or negative).
Preprocess Text: Clean and prepare the text data using NLP techniques.
Feature Extraction: Convert the preprocessed text into numerical features with Count Vectorizer.
Train-Test Split: Split the data into training and testing sets. The training set is used to build the model, and the testing set is used to evaluate its performance.
Model Training: Train the Random Forest Classifier on the training data.
Evaluation: Evaluate the model's performance on the testing set using metrics like accuracy, precision, and recall.

CONCLUSION:
This approach utilizes scikit-learn's Random Forest Classifier and Count Vectorizer for movie sentiment analysis. By training the model on labeled data and evaluating its performance, you can gain insights into audience sentiment towards movies.
