# Assignment: L05IT02 
# TASK SPAM DETECTION using TENSORFLOW and AI (Machine Learning)
# Learner: DANIELE CASTROVINCI

 
The provided code involves  a classic machine learning algorithm known as Naive Bayes, to perform a task—spam detection.
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
While this code utilizes machine learning to classify messages as 'spam' or 'ham', it's not considered a part of the most advanced forms of artificial intelligence, 
like deep learning or neural networks. 
It falls under the broader umbrella of artificial intelligence by virtue of employing algorithms that enable a system to learn patterns from data and make decisions or predictions based on that learning, albeit in a more traditional and simpler form compared to some other AI techniques.
