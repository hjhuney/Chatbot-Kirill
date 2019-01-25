# Chatbot-Kirill
Notes and code from Kirill Eremenko's NLP / Chatbot Course

# Bag of Words Model
* Sparse vector (e.g. 20K words, assign value for number of time each word used)
* Special words are last element
* Train examples with sparse vectors to create model
* Model examples: logistic regression (e.g. predict "yes" or "no" response), neural network
* SOS = start of sentence
* EOS = end of sentence

## Issues with Bag of Words Model
* Fixed vector size input
* Order of words not taken into account
* Fixed sized output

# Seq2Seq
* Uses RNNs
** Options: One-to-One, One-to-Many, Many-to-One, Many-to-Many
* Create a vector as long as our text; replace word with numerical version
* Dense vector
* For output, neural network will spit out probability score for words
