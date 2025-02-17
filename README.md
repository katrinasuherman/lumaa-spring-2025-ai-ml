# Content-Based Movie Recommendation System

## Overview
This system recommends movies based on a user's input description using TF-IDF vectorization and cosine similarity. It ranks and returns the top 5 most relevant movies by comparing the user's query to movie descriptions.

## Dataset
- The dataset is sourced from Kaggle: [500 Best Movies IMDb](https://www.kaggle.com/datasets/moazeldsokyx/the-500-best-movies-imdb).
- It contains movie titles and descriptions.
- The dataset file `Top_Movies.csv` is included in my forked repository under the `data/` directory.

## Setup
### **Prerequisites**
- Python 3.7+
- Install dependencies:

```sh
pip install -r requirements.txt
```

## Running the Recommendation System
To run the recommender, open the Jupyter Notebook and execute the provided cells.

### **Testing with Custom Queries**
Users can test the recommendation system by modifying the `query_description` variable in the notebook and running the `recommend_movies` function.

Example:
```python
query_description = "I love romance comedy movies."
recommend_movies(query_description, df, vectorizer, tfidf_matrix)
```

This will return a list of the top recommended movies based on the given description.

### Example Output
```sh
Top Recommendations:
1. Crazy Heart (Similarity: 0.1698)
2. Clerks (Similarity: 0.1553)
3. Todo sobre mi madre (Similarity: 0.1459)
4. The Apartment (Similarity: 0.1412)
5. Roman Holiday (Similarity: 0.0708)
```

## Project Structure
```
.
├── data
│   ├── Top_Movies.csv
├── recommend.ipynb
├── requirements.txt
├── README.md
├── demo.md
```

## Salary Expectation
- Monthly salary expectation: **[$2,100 – $2,400]**

## Short Video Demo
A demonstration video showcasing how to run the recommendation system, use a sample query, and view the results has been provided.

**Demo Link:** [Insert your video link here]  

## Dependencies
- `pandas`
- `numpy`
- `scikit-learn`

