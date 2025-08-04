#  Project Title: Personalized Course Recommendation System using Content-Based Filtering

### Project Description:
This capstone project, part of the IBM Machine Learning Professional Certificate, involved building a content-based course recommendation system for an online learning platform. The goal was to help users discover new courses based on the similarity of course content to those they had already taken.

Using a combination of natural language processing, Bag-of-Words vectorization, and cosine similarity, we developed a personalized recommender that scores and ranks courses for each user based on textual metadata (title + description). The recommendations were filtered by a similarity threshold and optimized to return top-K results per user.

### Key Components:
1. Data Preprocessing: Cleaned and vectorized course titles and descriptions using NLP techniques.
2. Feature Engineering: Created Bag-of-Words vectors from course metadata.
3. Similarity Calculation: Computed pairwise course similarity using cosine similarity.
4. Recommendation Engine: Implemented personalized, threshold-filtered course suggestions.
5. Evaluation: Provided top-5 recommended courses per user based on historical course enrollment data.

### Tech Stack:
- Python, Pandas, NumPy
- Scikit-learn (for vectorization and similarity)
- Jupyter Notebook
- Matplotlib / Seaborn (for data visualization)

### Outcome:
- Successfully delivered a scalable and explainable content-based recommender system.
- Demonstrated how machine learning techniques can improve user engagement in educational platforms.
- Gained hands-on experience in NLP, similarity metrics, and real-world recommender system design.

