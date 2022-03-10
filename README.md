# BBC-News-Classification
Multi-class Classification for bbc news dataset

Contains multiple folder wherein there are text files.
Total 2225 news articles, divided in 5 categories(Business, Entertainment, Politics, Sports, Tech)
Dataset(datasets) should be in the same folder as python file.

Methodology:
1. Read data using 'os' and 'pandas', transform to data frame.
2. Pre-Process using regular expression and lemmatization.
3. Feature Extraction techniques : Bag of words, TF-IDF unigrams, TF-IDF bigrams. Select best features using SelectKBest and chi2 methods.
4. Stack features together.
5. Use K-Fold Cross Validation to get stable LinearSVC model.
