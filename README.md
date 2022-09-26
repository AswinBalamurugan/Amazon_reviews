# Amazon Reviews

# Objective
To apply the NLP concepts learnt through self-study.

# Dataset
The dataset is available on kaggle - "Amazon Alexa Reviews".  
Link to the website - https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews
## Description of Dataset
This dataset consists of a nearly 3000 Amazon customer reviews (input text), star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots, Alexa Firesticks etc. for learning how to train Machine for sentiment analysis.

There are 4 columns:
* Date
* Variation
* Verified Reviews
* Feedback

# Solution
To use a Random Forest Classifier model to predict if a given review is positive or negative. To apply NLP techniques to prepare the text for model evaluation.

# Models
Accuracy scores:
* For n_estimators = 2 : 0.886
* For best_params from GridSearchCV : 0.935

# Conclusion
Applied NLP techniques like removing stop words, using Lemmatization and Count Vectorizer to the 'verified reviews' to covert it to a more useful form. Using Random Forest Classifier with n_estimator as 2 and then using GridSearchCV to improve the accuracy of the model. This model can be used to predict whether a given review is positive or negative.
