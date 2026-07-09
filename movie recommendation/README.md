# Movie Recommendation System

## 📌 Project Overview
This project implements a Content-Based Movie Recommendation System using the TMDB 5000 Movies dataset. The system recommends similar movies based on genres, keywords, and movie overviews by applying Natural Language Processing (NLP) techniques and Cosine Similarity.

## 🎯 Objective
Build a recommendation system that suggests movies similar to a user's selected movie using content-based filtering techniques.

## 📂 Dataset
- Dataset: TMDB 5000 Movie Dataset
- File: `tmdb_5000_movies.csv`

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 📚 Libraries Used
- Pandas
- NumPy
- CountVectorizer (Scikit-learn)
- Cosine Similarity (Scikit-learn)

## 📊 Project Workflow
1. Import required libraries
2. Load the dataset
3. Select important features
4. Handle missing values
5. Combine movie metadata
6. Convert text into numerical vectors using CountVectorizer
7. Calculate Cosine Similarity
8. Build a recommendation function
9. Test the recommendation system

## 🔍 Features Used
- Movie Title
- Genres
- Keywords
- Overview

## 🤖 Machine Learning Technique
- Content-Based Filtering
- CountVectorizer
- Cosine Similarity

## 📈 Output
The recommendation system returns the **Top 10 movies** that are most similar to the selected movie based on their content.

### Example

**Input**

```text
Avatar
```

**Output**

```text
Top 10 Recommended Movies

1. Aliens
2. John Carter
3. Guardians of the Galaxy
4. The Abyss
5. Titan A.E.
6. Star Trek
7. Interstellar
8. Star Wars
9. Jupiter Ascending
10. Ender's Game
```

## 🚀 How to Run

1. Clone the repository.

2. Install the required libraries:

```bash
pip install pandas numpy scikit-learn
```

3. Place the dataset in the project folder:

```
tmdb_5000_movies.csv
```

4. Open `Movie_Recommendation_System.ipynb`.

5. Run all notebook cells.

6. Call the recommendation function:

```python
recommend("Avatar")
```

## 📁 Project Structure

```
Movie_Recommendation_System/
│── Movie_Recommendation_System.ipynb
│── tmdb_5000_movies.csv
└── README.md
```

## 📌 Key Features
- Data preprocessing
- Missing value handling
- Feature engineering
- Content-based recommendation
- NLP using CountVectorizer
- Cosine Similarity
- Top 10 movie recommendations

## 📊 Skills Demonstrated
- Python Programming
- Data Preprocessing
- Natural Language Processing (NLP)
- Machine Learning
- Recommendation Systems
- Feature Engineering
- Data Analysis

## 🎯 Conclusion
This project demonstrates how a content-based recommendation system can suggest similar movies by analyzing movie metadata. Using CountVectorizer and Cosine Similarity, the system efficiently identifies movies with similar genres, keywords, and story descriptions.

## 👨‍💻 Author

**Sunil Jadhav**

B.Tech – Data Science

Vardhaman College of Engineering