# Text Classification using Naive Bayes


Multinomial Naive Bayes Text Classification is a text classifier with implementation of Multinomial   Naive Bayes. Reuters 21578 data set is used for training. 

Multinomial NB text classifier model assigns an input test document into classes, which are the five most common topics in the Reuters-21578 corpus: 

-	earn 
-	acq 
-	money-fx 
-	grain 
-	crude 

Training and test sets consist of the news articles that belong to one of the above five topics. The news stories that belong to more than one of these topics are eliminated. The news stories that belong to only one of the above five topics, even if they belong to more than one topic is included. Stop words is removed. 

After creating the training and test sets, the parameters of Multinomial Naive Bayes model using the training set with using all words in the lexicon are learned. For comparison, the program was first run with the library, then it was run without the library.

Frequency-based feature selection was used instead of mutual information for the most repeated word, and the 50 most repeated words were printed for each topic. Retraining the data set according to the most words failed.

