# Using Machine Learning to Classify a Song's Popularity

Analyzed a dataset (https://www.kaggle.com/datasets/danield2255/data-on-songs-from-billboard-19992019) of songs over a 20 year period.

Spotify rates each songs popularity on a 0 to 100 scale and designates any song 50 or greater as being popular. Over 91% of songs over the course of the 20 years were deemed not popular. This resulted in an imbalanced classes. 

I utilized a Random Forest Model, a Balanced Random Forest Model, Random Forest/Smote Model, XGB Boost/Smote model and an Ensemble Model. I produced a classification report for each model which displayed precision, recall and f1-scores. I then compiled each models result in an easily digestible table matrix. 

Ultimately, the best performing model was the Random Forest Model utilizing Smote which is an oversampling technique to help offset an imbalance in classes. This allows the model to train and learn on more examples of the minority class and produce stronger predcition results. The Random Forest Smote produced a Precision score of 88.65%, a Recall score of 91.71% and an F1-Score of 90.15%.

Let me know your thoughts and what I could have done differently!
