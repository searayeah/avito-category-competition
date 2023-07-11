# avito-category-competition

- Text classification competition: [Avito Category Prediction](https://www.kaggle.com/competitions/avito-category-prediction)
- Data: Russian products name with description
- Took __second place__ with accuracy=0.91686
- Text preprocessing: remove punctuation and extra symbols, to lowercase, lemmatize using __PyMystem3__, remove stopwords using __NLTK__, remove short words with length < 3
- Text embedding: __TfidfVectorizer(ngram_range=(1, 2))__
- Model: __SGDClassifier(n_jobs=-1, alpha=0.0000002, tol=1e-4)__
