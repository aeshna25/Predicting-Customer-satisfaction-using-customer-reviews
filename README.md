# Predicting-Customer-satisfaction-using-customer-reviews
Predicting whether customers are satisfied with the product based on their reviews and rating.  
For this project the object is to understand customers through there reviews on Amazon's famous voice assistant product-- Alexa. The dataset has more than 3000 reviews from actual customers having information like review, date, rating, alexa model and feedback.

The target feature is the feedback, which is a binary column where 1 means positive and 0 means negative. 
The project focuses on using **Natural language processing** capabilities to convert words into numbers and use them furture to create predictive models. 

Python's nltk library is a powerful tool which has capabilities such as removing stopwords,punctuations, lemmatization etc. It also gives an option to customize the stopwords list according to the dataset.

Before feeding the word document to the model, it was converted into numerical format. The categorical column was converted using **Dummy variable** and the word document was **tokenized** using  **count vectorizer** technique. 

The newly prepared numerical dataset is than used for prediction the train test split is done is the ration 4:1, and is fed to **Naive Bayes classfier** which is great for multi-class problems and **Logistic regression**. Both the models were judged on the performance matrix: **Accuracy** and the results shows that on one hand where Naive bayes classfier gave a good accuracy of 94% , Logistic Regression stood victorious with close to perfect accuracy score. 


<img align="left" src="https://github.com/aeshna25/Predicting-Customer-satisfaction-using-customer-reviews/blob/main/Images/rating.png">
<img align="right" src="https://github.com/aeshna25/Predicting-Customer-satisfaction-using-customer-reviews/blob/main/Images/naivebayesaccuracy.png">
<img align="center" src="https://github.com/aeshna25/Predicting-Customer-satisfaction-using-customer-reviews/blob/main/Images/wordcloud.png">


