# NLP Spam Detection

## Description
This project uses Natural Language Processing (NLP) techniques to detect spam messages from a dataset of SMS phone messages. The dataset contains over 5,000 messages labeled as 'ham' (non-spam) or 'spam'. The project involves data preprocessing, feature extraction, and classification using machine learning models.

## Dataset
The dataset used in this project is the 'SMSSpamCollection' from the UCI Machine Learning Repository. It contains a collection of SMS messages labeled as 'ham' or 'spam'.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- `nltk`
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## Results
The project uses two classifiers: Naive Bayes and Random Forest. The performance of these models is evaluated using precision, recall, and F1-score.

### Naive Bayes Classifier
- **Precision**: 0.95 (ham), 1.00 (spam)
- **Recall**: 1.00 (ham), 0.67 (spam)
- **F1-score**: 0.97 (ham), 0.80 (spam)
- **Accuracy**: 0.95
## Random Forest Classifier
- **Precision**: 0.96 (ham), 0.97 (spam)
- **Recall**: 1.00 (ham), 0.78 (spam)
- **F1-score**: 0.98 (ham), 0.87 (spam)
- **Accuracy**: 0.96

## License
This project is licensed under the MIT License.
