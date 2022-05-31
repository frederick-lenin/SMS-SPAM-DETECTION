# SMS-SPAM-DETECTION

Have used Logistic Regression and MultinomialNB

### LOGISTICS REGRESSION:
   A process of modeling the probability of a discrete outcome given an input variable.The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on.
   
### MultinomialNB:
  The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts. However, in practice, fractional counts such as tf-idf may also work.
  
  
First download the dataset "SMS.csv" 
And use the spam messages that to be predicted in code line 19 and run the program with logistic regression with command lr.predict(text).
The accuracy will be nearly 97%. But the expected output is not been Displayed.

Now run the program with MultinomialNB. Predict the data with clf.predict(text) command.The accuracy will be nearly 97% and the output will be nearly as we expected.

