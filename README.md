# Book-Recommendation-System
This project is a Book Recommendation System built using the Amazon Book Reviews dataset (from Kaggle).
It suggests books of the same genre or similar interest based on what a user has read, using collaborative filtering with K-Nearest Neighbors (KNN).

**Features**
Analyzes Amazon book review dataset (books + ratings).
Preprocesses data (filtering active users/books, encoding).
Builds a utility matrix (books × users).
Uses KNN (cosine similarity, brute-force search) for recommendations.
Recommends top N similar books for any given book.
Saves trained model using pickle for reuse.

**Dataset**
Dataset used: https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data
books_data.csv → Contains book details (Title, Authors, Categories, Image).
Books_rating.csv → Contains user ratings (User ID, Title, Score).

**Tech Stack**
Python
Pandas, NumPy → Data preprocessing
Matplotlib, Seaborn → Data visualization
Scikit-learn → Machine learning (KNN)
SciPy → Sparse matrices

**Installation**
**Clone this repository and install required dependencies:**
git clone https://github.com/your-username/book-recommendation-system.git
cd book-recommendation-system
pip install -r requirements.txt
