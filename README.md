# Sentiment_Classifier
For classification of the positive / negative responses from the newspaper articles, it is a sub-project under a Big Data project, which using the large scale datasets from different newspapers' website like CNN, BBC, FoxNews and etc. To make a statistic about these giant newspaper companies' viewpoints on different fields like business, health, and politics with a timeline visualization.

Please run the Trainning_classifiers.py to train the five classifier models first.  
The five classifiers are Naive Bayes, MultinomialNB, BernoulliNB, LogisticRegression, and LinearSVC.  
Then adding the test.txt file in /testing_files folder or entering the testing sentence inside the Test_Senti.py file.  
Run the Test_Senti.py file and the output means the five classifiers' results and the final voting result among these five classifiers with showing the confidential rate (1.0: 100% believe, 0.6: 60% believe)  
