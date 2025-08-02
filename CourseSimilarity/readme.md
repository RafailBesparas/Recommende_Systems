## Course Recommendation System Using NLP & Cosine Similarity

I built a course similarity engine that identifies related courses using Natural Language Processing and Bag-of-Words vectorization.

## Compared course descriptions using:
- Horizontal BoW vectors
- Cosine similarity for measuring semantic closeness
- Found that courses like ML0151EN and excourse47 share strong content overlap with ML0101ENv3 (Machine Learning) – similarity scores above 0.6!

## Technologies used:
- Python, Pandas, Scikit-learn
- Cosine Similarity
- Feature Engineering (Pivoting BoW)
- Data-driven filtering (threshold-based)
- This approach can be extended to recommend courses, detect duplicates, or even cluster course catalogs in ed-tech platforms.