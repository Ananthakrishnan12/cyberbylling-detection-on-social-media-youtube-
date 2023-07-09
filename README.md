# Cyberbullying Detection on Social Networks Using Machine Learning Approaches::
Abstract: The use of social media has grown exponentially over time with the growth of the Internet and has become the most influential networking platform in the 21st century. However, the enhancement of social connectivity often creates negative impacts on society that contribute to a couple of bad phenomena such as online abuse, harassment cyberbullying,cybercrime and online trolling. Cyberbullying frequently leads to serious mental and physical distress, particularly for women and children, and even sometimes force them to attempt suicide. Online harassment attracts attention due to its strong negative social impact. Many incidents have recently occurred worldwide
due to online harassment, such as sharing private chats, rumours, and sexual remarks. Therefore, the identification of bullying text
or message on social media has gained a growing amount of attention among researchers. The purpose of this research is to
design and develop an effective technique to detect online abusive and bullying messages by merging natural language processing
and machine learning. Two distinct freatures, namely Bag-of - Words (BoW) and term frequency-inverse text frequency (TFIDF),
are used to analyse the accuracy level of four distinct machine learning algorithms


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