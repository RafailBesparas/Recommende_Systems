# Content-Based Course Recommender System

This project demonstrates how to build a content-based recommendation system that suggests online courses to users based on their preferences. The system uses user profiles (constructed from historical interaction data) and course metadata (such as genres) to generate personalized course recommendations.

### How It Works
1. User Profile Construction:
- Each user is represented as a vector derived from their historical engagement with various course genres (e.g., views, ratings, clicks).

2. Course Representation:
- Each course is represented by a vector of features such as genres or tags.

3. Similarity Scoring:
- The recommendation score is computed using a dot product (or optionally cosine similarity) between the user profile vector and the course feature vector.

4. Recommendation Filtering:
- Courses the user hasn’t interacted with are scored, and the top-N most relevant are returned as recommendations.

## Files
- Content_Based_System.ipynb:
- The main notebook with the full recommendation pipeline including:
1. Data preprocessing
2. User profile creation
3. Course vector encoding
4. Recommendation logic

- Content_Based_System_Example.ipynb:
1. A simplified or example version of the above with working code for smaller datasets or demo purposes.

