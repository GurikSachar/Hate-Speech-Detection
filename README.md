Hate Speech Detection

1. Introduction
   This project consists of a Natural Language Processing model which is capable of classifying the given input text as either hateful, offensive or neutral.

2. Libraries Used
   NumPy, Pandas, Scikit-Learn, NLTK, Re

3. Methodology
   The dataset used is "Hate Speech and Offensive Language Dataset" by Andrii Samoshyn and consists of roughly 10000 tweets which contains tweets of all 3 categories.
   First, the dataset is cleaned using the regular expression library available in Python. Then the common english stopwords are removed using the NLTK toolkit. Then stemming is performed using the
   snowball stemmer. Second, CountVectorizer is used to keep a count of the words occuring in the cleaned dataset. Next, using the train test split function available in SciKit-Learn to divide the given
   dataset into training and testing data accordingly. Lastly, using the DecisionTreeClassifier available as a part of the same library, the given data is fitted and the model is trained.

4. Observation
   The accuracy was found to be 86% for the given model.
