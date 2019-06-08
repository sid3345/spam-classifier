# Spam Classifier

Classifies text as "spam" or "ham" (non-spam) using the Naïve Bayes Classifier. 

The Naïve Bayes Classifier is very simple and efficient method for spam classification. 

Email dataset is provided along to train- test.

 

Function description:

readFiles(path): Opens dataset files from directory paths mentioned, reads it and extracts message from it and closes it.

dataFrameFromDirectory(path, classification): Takes directory path and classification as input parameters to form a dataframe and arranges it as "message" and "class" in the dataframe.



CountVectorizer() is used to convert a messages to a matrix of token counts.
Finally, MultinomialNB() is used to train the model using "message" and "target".

An example input is given to classify text as "spam" and "ham".


In future, I will intergrate it with a streaming input (probably real-time email) to classify real time.

Also, train- test split will be used.
