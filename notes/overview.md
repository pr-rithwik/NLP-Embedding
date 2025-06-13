### What is FastText?
FastText is an improvement over `Word2Vec` by Facebook Research.

Like `Word2Vec`, it has `Skip-gram` and `CBOW` architectures.

But it adds something powerful: it breaks words into character **n-grams**.

So even if a word is rare or unseen, its parts (like subwords in `"running"`: `run`, `unn`, `nni`, etc.) help form a meaningful vector.

#### Skip-gram
Skip-gram is a model architecture used in Word2Vec (by Mikolov et al., 2013).

- The goal is to predict surrounding context words given a target word.
- For example, in the sentence:
    - "The cat sat on the mat"
    - If target = "sat", the model tries to predict "cat" and "on" (its neighbors).