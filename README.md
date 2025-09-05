# Netflix Movie-Recommender-System
Built a content-based recommender system using TF-IDF vectorization of movie genres and cosine similarity to suggest top-N similar movies. The system was tested on the MovieLens dataset and provides personalized recommendations such as finding movies similar to Jumanji. 
# Movie Recommender System (Content-Based Filtering)

##  Project Overview
This project implements a **content-based recommender system** using the MovieLens dataset.  
It leverages **TF-IDF vectorization of genres** and **cosine similarity** to suggest top-N similar movies.

##  Features
- Load and preprocess movie + rating datasets
- Extract and clean genres for feature engineering
- Build a TF-IDF matrix for genre representation
- Compute cosine similarity between movies
- Generate top-5 movie recommendations for a given title

##  Tools & Libraries
- Python
- Pandas
- Scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
- Jupyter Notebook

##  Results
- Successfully generated recommendations for movies (e.g., “Jumanji” → top 5 similar films).
- Demonstrates the power of content-based recommendation systems similar to those used by streaming platforms.

##  Skills Learned
- Data preprocessing and cleaning
- Natural Language Processing basics (TF-IDF)
- Similarity metrics for recommendations
- Applying machine learning concepts to real-world datasets

##  Usage
1. Clone the repository  
2. Install required libraries (`pip install -r requirements.txt`)  
3. Run the notebook:  
   ```bash
   jupyter notebook Phase2_proj1.ipynb


Input: "Jumanji"
Output: [Top 5 recommended similar movies with genres]
