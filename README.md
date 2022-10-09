# Tcs_ion-Rio-45-Internship
Automate detection of different sentiments from textual comments and feedback
Project Title
----
Automate Detection of different Sentiments from Textual Comments and Feedback. 

Project Description:
---
**Project Objective & Brief**: To develop a deep learning algorithm to detect different types of sentiment contained in a collection of English Sentences or a large paragraph.



#### Expected Project Outcome:
1. Algorithms to detect different types of sentiment from a paragraph.
2. Detailed presentation with proof of reasonable accuracy.

#### Software Requirements to Implement the Project:
1. Google Collab
2. Python.

In Sentiment analysis, the data mainly focuses on whether the feedback to a product is :
 - negative
 - positive
 - neutral

This provides a top level review of the product and its acceptance in the market.
* Emotion Analysis provides a deeper insight of consumer emotions.
 - Analyzing textual feedback to the level of reading between lines.
 - Categorizing feedback and analyzing its emotion by picking up words, contexts, patterns, behaviors. This can be even taken to the level of individual’s expressive capability of a particular situation.

Approaches to Text Classification
---
* **Machine Learning based Systems:**
 1. Text classification based on past observations.
 2. By using training data, the algorithm can learn the different associations between pieces of text and that a particular output (i.e. tags) is expected for a particular input (i.e. text).
 3. Feature extraction: Transforms each text into a numerical representation in the form of a vector. E.g. bag of words [a vector represents the frequency in a predefined dictionary of words ]
 4. The algorithm is fed with training data consisting of feature sets.
 5. Once trained with enough training samples, the machine learning model can begin to make accurate predictions on unseen text with similar feature sets.

Text Classification Algorithms
---
Some of the most popular machine learning algorithms for creating text classification models include the naive bayes family of algorithms, support vector machines, Regressions, and deep learning algorithms with CNN and RNN. Metrics and Evaluation Cross-validation is a common method to evaluate the performance of a text classifier.
 1. It consists in splitting the training dataset randomly into equal-length sets.
 2. For each set, a text classifier is trained with the remaining samples (e.g. 75% of the samples).
 3. The classifiers make predictions on their respective sets and the results are compared against the human-annotated tags.
 4. With these results, a performance metrics is built, that are useful for a quick assessment on how well a classifier works.

#### Performance metrics normally includes:
* **Accuracy**: the percentage of texts that were predicted with the correct tag.
* **Precision**: the percentage of examples the classifier got right out of the total number of examples that it predicted for a given tag.
* **Recall**: the percentage of examples the classifier predicted for a given tag out of the total number of examples it should have predicted for that given tag.
* **F1 Score**: the harmonic mean of precision and recall.



#### Test Accuracy achieved using following algorithms:
Linear SVM : 0.8076923076923077
Decision Tree: 0.6370192307692307
Logistic Regression: 0.8052884615384616
