# Movie-Recommand-System-
Content-based movie recommendation engine using TF-IDF &amp; cosine similarity | Python, NLP, Scikit-learn, Pandas
# 🎬 Movie Recommendation System

A content-based movie recommendation engine that suggests similar movies 
using TF-IDF vectorization and cosine similarity.

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (TF-IDF, Cosine Similarity)
- NLP (Tokenization, Stopword Removal)
- Jupyter Notebook

## ⚙️ How It Works
1. Movie metadata (genre, cast, keywords) is preprocessed using NLP
2. TF-IDF vectorizer converts text data into numerical vectors
3. Cosine similarity finds closest matching movies
4. Top N similar movies are returned as recommendations

## 🚀 How to Run
```bash
pip install pandas numpy scikit-learn
```
Open `movie_recommendation.ipynb` in Jupyter Notebook and run all cells.

## 📊 Example Output
Input: recommand("Thor")
Output: Thor,Thor: The Dark World,The Incredible Hulk,The World Is Not Enough,Avengers: Age of Ultron
