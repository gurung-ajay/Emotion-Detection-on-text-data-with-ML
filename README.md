# Emotion-Detection-on-text-data-with-ML
In this project I built Emotion Detection models and evaluated using two following Machine Learning approaches for comparison.
## 1) Classical Machine Learning 
Models created using pipeline: LogisticRegression, KNeighborsClassifier, SVC, DecisionTreeClassifier, RandomForestClassifier, MultinomialNB

Out of these models, Random Forest model performed the best with f1 score(macro) of 0.87 and accuracy of 89% on validation data

On test data, it got f1 score(macro) of 0.83 and accuracy of 89%.

Models built using: Scikit Learn

## 2) Deep Learning 
Models created: Simple RNN, LSTM, Bidirectional LSTM

Out of these models, Simple RNN and LSTM were underfit whereas Bidirectional LSTM performed well with accuracy of 87.94% on validation data

Models built using: Tensorflow
