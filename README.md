# Natural-Language-Processing-Project

Analysis of an unstructured text dataset using NLTK and Sci-kit Learn to pull out 'actionable' items.

'Actionable' was defined as key unmet needs, concerns, and requests for support from the company that arose within the medical community.

Main steps involved:
- Preprocess (clean) data
- Tag data as Actionable/Not Actionable
- TF-IDF vectorization for each comment
- Under-sample to account for class imbalance
- Train machine on Actionability based on TF-IDF scores using 70% of the dataset for training and 30% for testing, using Logistic Regression
- Generate list of actionable items

