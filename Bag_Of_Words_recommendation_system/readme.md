# Bag of Words Feature Extraction for Course Recommender Systems
This project demonstrates how to preprocess, tokenize, and transform course descriptions into numerical features using the Bag-of-Words (BoW) model, a key step in building intelligent course recommendation systems and other machine learning models.

# Overview
- Textual data like course titles and descriptions carry rich semantic meaning, but must be converted into numeric form before being used by machine learning algorithms. This project provides two pipelines:

- One for exploratory learning using nltk
- One for production-ready feature extraction using scikit-learn and gensim (without nltk)

# Notebooks
| Notebook                     | Purpose                                                                       |
| ---------------------------- | ----------------------------------------------------------------------------- |
| `Bag_of_words_example.ipynb` | Educational walkthrough using `nltk` for tokenization and POS tagging         |
| `bag_of_words_system.ipynb`  | Clean, scalable pipeline using `scikit-learn` and regex, ideal for production |

## Features
- Custom tokenizer using regex + stopwords (no NLTK dependency)
- Converts text data (course titles & descriptions) into token lists
- Builds Gensim Dictionary and BoW doc2bow corpus
- Adds BoW-based features (e.g. number of unique words)
- Visualizes most frequent tokens across all courses
- Ready for extension into TF-IDF, topic modeling (LDA), or similarity-based recommendations

