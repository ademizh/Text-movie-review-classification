### Movie Review Classification Pipeline

This repository contains a pipeline for text movie review classification. The pipeline is constructed using Python and scikit-learn library for machine learning.
#### Dataset: http://ai.stanford.edu/~amaas/data/sentiment/

#### Features:

- **CountVectorizer and TF-IDF Vectorizer**: The pipeline integrates both CountVectorizer and TF-IDF Vectorizer to convert text data into numerical features suitable for machine learning algorithms.

- **Multinomial Naive Bayes (MultinomialNB)**: One of the implemented models in the pipeline is Multinomial Naive Bayes, a popular algorithm for text classification tasks.

- **Linear Support Vector Classifier (LinearSVC)**: Another model used in the pipeline is Linear Support Vector Classifier, known for its effectiveness in binary classification tasks.

#### Usage:

1. Clone the repository: `git clone [repository-url]`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the pipeline: `python movie_review_classification.py`
