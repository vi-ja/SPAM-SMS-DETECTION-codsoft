Project Overview
Spam SMS Detection Using Machine Learning

The Spam SMS Detection project is a Machine Learning and Natural Language Processing (NLP) application designed to automatically classify SMS messages as either Spam or Ham (Legitimate). The main objective of this project is to help users identify unwanted or fraudulent messages by analyzing the text content of SMS messages.

The project uses the Spam SMS Collection Dataset, where each message is labeled as spam or ham. During preprocessing, unnecessary columns are removed, duplicate messages are eliminated, missing values are checked, and the labels are converted into numerical values. Exploratory Data Analysis (EDA) is performed using various visualizations to understand the distribution of spam and legitimate messages and to analyze message characteristics.

To convert textual data into numerical features, the project uses the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique. These features are then used to train three Machine Learning models: Multinomial Naive Bayes, Logistic Regression, and Support Vector Machine (Linear SVM). The models are evaluated using Accuracy Score, Precision, Recall, F1-Score, Classification Report, and Confusion Matrix.

After comparing the performance of all models, the best-performing classifier is selected as the final prediction model. The trained model and TF-IDF vectorizer are saved using Joblib, allowing the system to classify new SMS messages without retraining the model.

Overall, this project demonstrates the practical application of Machine Learning and NLP in text classification. It provides an efficient, accurate, and scalable solution for spam message detection and can be further extended for deployment in mobile applications, messaging platforms, and cybersecurity systems.
