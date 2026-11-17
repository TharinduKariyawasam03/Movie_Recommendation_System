# 🎬 Movie Recommendation System

An intelligent **Content-Based Movie Recommendation System** developed using Python and Machine Learning. This project uses movie metadata from TMDB to recommend movies similar to a user's selected movie through **TF-IDF Vectorization** and **Cosine Similarity**.

## 🚀 Project Overview

Finding movies that match personal interests can be challenging. This project addresses that problem by analysing movie descriptions and identifying movies with similar content.

The recommendation engine uses Natural Language Processing (NLP) techniques to compare movie overviews and generate relevant recommendations.

## ✨ Key Features

- Content-Based Movie Recommendation
- Movie Data Exploration and Preprocessing
- TF-IDF Vectorization
- Cosine Similarity Calculation
- Similarity-Based Movie Ranking
- Top 10 Movie Recommendations
- Saved Machine Learning Model using Joblib

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computations |
| Scikit-learn | Machine Learning and NLP |
| TF-IDF | Text feature extraction |
| Cosine Similarity | Movie similarity measurement |
| Joblib | Model serialization |
| Jupyter Notebook | Development environment |
| TMDB Dataset | Movie information and metadata |

## 🧠 Machine Learning Approach

This project implements **Content-Based Filtering**.

### 1. Data Collection
Used the TMDB 5000 Movies and Credits datasets to obtain movie information and metadata.

### 2. Data Preprocessing
- Explored and prepared the movie datasets.
- Merged movie information and credits.
- Cleaned and selected relevant features.
- Prepared movie descriptions for text processing.

### 3. TF-IDF Vectorization

Applied Term Frequency–Inverse Document Frequency (TF-IDF) to transform movie overviews into numerical feature vectors.

This allows the system to represent movie descriptions mathematically.

### 4. Cosine Similarity

Calculated cosine similarity between movie feature vectors to measure how closely movie descriptions are related.

### 5. Movie Recommendations

- Identify the selected movie.
- Retrieve its similarity scores.
- Rank movies based on similarity.
- Exclude the selected movie.
- Return the top 10 recommended movies.

## 📂 Repository Structure

```text
Movie_Recommendation_System/
│
├── Movie_Recommendation_System.ipynb
├── Recc_system_tmdb.ipynb
├── UI.ipynb
│
├── movie_recommendation_model.pkl
│
└── README.md
```

## ⚙️ Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/TharinduKariyawasam03/Movie_Recommendation_System.git
```

### 2. Navigate to the Project Folder

```bash
cd Movie_Recommendation_System
```

### 3. Install Dependencies

```bash
pip install pandas numpy scikit-learn joblib jupyter
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks to explore the data preprocessing, model development, and recommendation process.

## 💾 Saved Model

The repository includes a saved model:

`movie_recommendation_model.pkl`

It stores the movie recommendation data and cosine similarity matrix used by the recommendation application.

## 🔮 Future Improvements

- Develop a fully interactive web application.
- Improve the user interface and movie discovery experience.
- Integrate movie posters and additional movie information.
- Explore hybrid recommendation techniques.
- Improve recommendation quality using additional movie features.

## 👨‍💻 Author

**Tharindu Kariyawasam**

Data Science Undergraduate | Sri Lanka Institute of Information Technology (SLIIT)

- [GitHub](https://github.com/TharinduKariyawasam03)
- [LinkedIn](https://www.linkedin.com/in/tharindu-kariyawasam-b63227345/)

---

⭐ If you find this project interesting, consider giving this repository a star!

**MATRIX CINE - Discover. Match. Watch.**