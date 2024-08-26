# 🎬 Movie Recommendation System

Discover movies you'll love with our content-based recommendation system, powered by the cosine similarity algorithm. Built using Python, this tool helps you find movies similar to your favorites.

## 📁 Dataset

We use the `movies.csv` file, which contains information about movies such as:
- **Title**
- **Genre**
- **Keywords**
- **Tagline**
- **Crew**
- **Director**

Proper data formatting and cleaning are essential before using this dataset to ensure accurate recommendations.

## 🔍 Features

The recommendation system analyzes the following features:
- **Genre**
- **Keywords**
- **Tagline**
- **Crew**
- **Director**

These features are combined and converted into a numerical format that the algorithm can understand, enabling effective movie comparisons.

## 🧠 Algorithm

Our system uses the **cosine similarity** algorithm to measure how closely two movies relate based on their features. The movies with the highest similarity to your favorite are recommended.

### Why Cosine Similarity?
Cosine similarity is a great choice for comparing movies because it focuses on feature similarity, making it ideal for text-based data like movie descriptions.

## 🚀 How It Works

1. **Input Your Favorite Movie**: Tell the system your favorite movie.
2. **Get Recommendations**: The system suggests movies that are similar, helping you discover new favorites.

## 🛠️ Requirements

To run the movie recommendation system, you'll need the following Python libraries:
- **pandas**
- **numpy**
- **scikit-learn**
- **difflib**

## 💻 Installation

Install the required libraries using `pip` in your terminal or command prompt:

```bash
pip install pandas numpy scikit-learn
```
