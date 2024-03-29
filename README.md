# ihlt-paraphrase-similarity

Deadline: 10/11/2017
A pair of texts is a paraphrase when both texts describe the same
meaning with different words.

1. Implement at least three approaches to detect paraphrase using sentence similarity metrics. Explore one lexical dimension per metric.
3. Evaluate each approach using the provided evaluation framework (Raco).
4. Compare and comment the results achieved by the approaches.

p1-[Student1]-[Student2].ipynb
p1-[Student1]-[Student2].pdf

Words, mottos, synsets are examples of elements of lexical dimension (i.e., of lexical order). Therefore, I mean that you use words or mottos or synsets or combinations of these elements (eg bigrams of words, that is, consecutive word pairs), depending on what you think is the most appropriate.

Lexical dimensions
1. words (original tokens)
2. lemmas (lemmatised tokens)
3. correct senses (words plus synsets)
4. Words plus NEs

Sentence similarity metrics
1. Jaccard - compares the sets

2. TF-IDF
  - "Term Frequency, Inverse Document Frequency"
  - If a word appears frequently in a document, it's important. Give the word a high score.
  - But if a word appears in many documents, it's not a unique identifier. Give the word a low score

3. Word order similarity

4. Sentence semantic similarity
5. Semantic matrix
