# Embeddings

An embedding is just a numerical vector representation of something (a word, sentence, document, etc.) in a continuous, dense vector space. It allows machines to understand and compute similarity between linguistic elements.

This contains the implementation of different embeddings
- BoW
    - Implemented using `CountVectorizer` from `scikit`
- TF-IDF
    - Implemented using `TfidfVectorizer` from `scikit`
- Fasttext (better than Word2Vec)
    - Implemented using `fasttext`
- MiniLM (better than BERT) 
    - Implemented with model `all-MiniLM-L6-v2` using `sentence-transformers`
