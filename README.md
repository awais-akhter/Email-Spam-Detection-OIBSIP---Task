# Email Spam Detection Oasis Infobyte Task

A machine learning project for detecting spam and non-spam emails using the Multinomial Naive Bayes model.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Building the Model](#building-the-model)
- [Learn the Model](#learn-the-model)
- [Prediction](#prediction)
- [Testing the Model](#testing-the-model)

## Introduction

This project aims to detect whether an email is spam or not using machine learning techniques. It utilizes the Multinomial Naive Bayes model and CountVectorizer to transform text data into numerical features for classification.

## Dataset

The project uses the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) from Kaggle. The dataset contains text messages labeled as spam or non-spam.

## Data Preprocessing

The data preprocessing steps include:
- Removing duplicate entries
- Handling missing values
- Labeling spam mails as 1 and non-spam mails as 0

## Data Visualization

Data visualization includes generating histograms to understand the distribution of spam and non-spam emails in the dataset.

## Building the Model

The project uses the Multinomial Naive Bayes model for classification.

## Learn the Model

The model is trained using the CountVectorizer to convert text data into numerical features. It is fitted on the training data.

## Prediction

The model is used to predict whether emails in the test dataset are spam or non-spam.

## Testing the Model

The model's performance is evaluated using various metrics, including accuracy, precision, recall, and F1 score.

### Metrics
- Accuracy Score: Measures the proportion of correctly classified instances.
- Precision Score: Measures the ability of the model to correctly classify spam emails.
- Recall: Measures the percentage of true positives predicted by the model.
- F1 Score: A harmonic mean of precision and recall.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- Muhammad Awais Akhter

---

Feel free to adapt and expand this `README.md` to suit your project's specific details and requirements. You can also include information on how to run the code, dependencies, and any other relevant information.
