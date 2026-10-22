# SMS Spam Detection Using Machine Learning

## 1. Introduction

SMS Spam Detection is a Machine Learning project that identifies whether a text message is spam or not spam.

Spam messages may contain unwanted advertisements, fake offers, or suspicious links. In this project, I used Python and Machine Learning to classify messages into two categories: Spam and Not Spam.

## 2. Project Objectives

- To understand the basics of Machine Learning.
- To analyze an SMS message dataset.
- To convert text messages into numerical features.
- To train a Machine Learning model.
- To evaluate the model's performance.
- To predict whether a message is spam or not spam.

## 3. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Multinomial Naive Bayes

## 4. Dataset

This project uses the SMS Spam Collection dataset from the UCI Machine Learning Repository.

The dataset contains text messages labelled as:
- **Ham:** Normal messages.
- **Spam:** Unwanted messages.

## 5. Project Workflow

1. Import the required libraries.
2. Load the dataset.
3. Explore and analyze the data.
4. Prepare the message text and labels.
5. Split the dataset into training and testing data.
6. Convert text messages into numerical features using TF-IDF.
7. Train the Multinomial Naive Bayes model.
8. Evaluate the model.
9. Test the model with new messages.

## 6. Machine Learning Algorithm

The Multinomial Naive Bayes algorithm is used to classify messages. TF-IDF converts the text messages into numerical features that the model can process.

## 7. Model Accuracy

The model achieved **96.56% accuracy** on the test dataset.

Accuracy shows the percentage of test messages classified correctly. The model may still make incorrect predictions.

## 8. Sample Predictions

The model was tested with sample messages, including messages containing prize offers and normal everyday conversations.

It predicted whether each message was Spam or Not Spam.

## 9. How to Run the Project

1. Open the notebook in Google Colab.
2. Run the code cells from top to bottom.
3. Allow the dataset to load.
4. Train and evaluate the model.
5. Test the model using sample messages.

## 10. Conclusion

This project helped me understand how Machine Learning can be used for text classification. I learned how to prepare text data, use TF-IDF, train a Naive Bayes model, and evaluate its performance.

This project improved my understanding of Python and the basic concepts of Machine Learning.

## Author

Sandesh Shinde

Created as a Machine Learning learning project.
