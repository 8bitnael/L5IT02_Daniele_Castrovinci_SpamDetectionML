# Assignment: L05IT02 
# TASK SPAM DETECTION using TENSORFLOW and AI (Machine Learning)
# Learner: DANIELE CASTROVINCI

 
The provided code involves  a classic machine learning algorithm known as Naive Bayes, to perform a spam detection.
Machine learning is a subset of artificial intelligence and it involves creating algorithms and models that enable computers
to learn and make predictions  based on data without explicit programming. 
This code contains:
1) Data Preprocessing:
The text data is transformed into a numerical representation using CountVectorizer where words are converted into numerical vectors.
2) Model Training:
The MultinomialNB classifier, a type of Naive Bayes model, is instantiated and trained on the transformed text data to learn patterns
that distinguish between 'spam' and 'ham' messages.
3) Prediction: A new message is processed in the same way as the training data and then classified as 'spam' or 'ham' using the trained model.


POST SCRIPTUM:
This code uses machine learning to determine if a message is spam or not. While it is not as advanced as deep learning or neural networks, it still falls under the umbrella of artificial intelligence because it uses algorithms to learn from data and make decisions based on that learning, although in a more traditional and simpler way compared to other AI techniques.
