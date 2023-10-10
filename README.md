# Spam_classifier
This project focuses on developing a spam classifier using machine learning techniques to identify spam emails. The classifier is trained using a dataset that includes 5172 rows, each representing an email. The dataset has 3002 columns: the first column contains email names represented by numbers to preserve privacy, the last column contains labels for prediction (1 for spam, 0 for not spam), and the remaining 3000 columns represent the 3000 most common words in the emails after excluding non-alphabetical characters and words.

# Dataset Details
Dataset Size: 5172 rows × 3002 columns
Features: 3000 most common words in emails
Target: Binary labels (1 for spam, 0 for not spam)

# Models Utilized
In this project, we experimented with the following machine learning models for classifying spam emails:

Naive Bayes Classifier
Decision Tree Classifier
Random Forest
Logistic Regression
Support Vector Machine (SVM)

# Data Preprocessing
Text data was preprocessed to remove non-alphabetical characters and words.
Word counts for each email were computed and stored in the respective cells of the DataFrame.

# Model Evaluation
We evaluated the performance of each model using accuracy metrics and cross-validation scores. The accuracy was calculated based on the classification of emails into spam or non-spam, and cross-validation was performed to ensure robustness and minimize overfitting.

# Usage
To run the code and train the models:

Ensure you have the necessary Python libraries installed. You can install them using pip:

Copy code
pip install pandas scikit-learn
Run the script that implements the spam classifier using the specified models and the provided dataset.

