# avito-category-competition

- Text classification competition: __[Avito Category Prediction](https://www.kaggle.com/competitions/avito-category-prediction)__
- Data: 2 text features: Russian products name and their description; target: category (50 classes)
- Text preprocessing: remove punctuation and extra symbols, to lowercase, lemmatize using __PyMystem3__, remove stopwords using __NLTK__, remove short words with length < 3
- Text embedding: __TfidfVectorizer(ngram_range=(1, 2))__
- Model: __SGDClassifier(n_jobs=-1, alpha=0.0000002, tol=1e-4)__
- Tuned the hyper-parameters using __Grid Search__
- Got __second place__ with accuracy=0.91686
