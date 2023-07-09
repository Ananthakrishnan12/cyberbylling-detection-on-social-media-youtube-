# Cyberbullying Detection on Social Networks Using Machine Learning Approaches::



# Create an working environment for the Project:
Type conda create -p cyberbylling python==3.8 -y (on Cmd prompt)

To Activate the working Environment Type conda activate cyberbylling/ (on cmd prompt)

# To install Required Dependency:
Type pip install -r requirnments.txt in (cmd prompt)

# Steps which are Implemented in this Model:
1.Data collection...

2.Data Description

3.Data Preprocessing: a) check duplicates in the data b) Removing specials characters,shorthands....

4.Data Transformation: a) Converting Text into Numerical using TFIDF vectorizer

5.Resampling Method: a) converting Imbalanced data into Balanced data using SMOTE

6.Model Training: a) Logistic Regression b) DecisionTreeClassifier c)RandomForestClassifier

7.Evaluation Metrics: a)ConfusionMatrix,precision score,recall score,accuracy score

8.Formatting to Pickle.

9.Prediction.