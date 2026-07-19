# 🎬 Hybrid Movie Recommendation System

A Hybrid Movie Recommendation System that combines **Content-Based Filtering** and **Collaborative Filtering** to provide personalized and accurate movie recommendations. By leveraging both user preferences and movie metadata, the system overcomes the limitations of individual recommendation techniques and delivers better suggestions.

---

# 📌 Project Overview

Recommendation systems are widely used in streaming platforms such as Netflix, Amazon Prime Video, and Disney+ to personalize user experiences.

This project implements a **Hybrid Recommendation System** by integrating content-based and collaborative filtering approaches, resulting in more relevant and diverse movie recommendations.

---

# 🚀 Features

- Personalized movie recommendations
- Hybrid recommendation approach
- Content-Based Filtering
- Collaborative Filtering
- Movie similarity search
- User preference modeling
- Movie metadata analysis
- Top-N recommendations
- Scalable recommendation pipeline

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Surprise (Collaborative Filtering)
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

# 🧠 Recommendation Architecture

```
                     User Input
                         │
        ┌────────────────┴────────────────┐
        │                                 │
        ▼                                 ▼
Content-Based Filtering        Collaborative Filtering
        │                                 │
 TF-IDF / Cosine Similarity      Matrix Factorization
        │                                 │
        └────────────────┬────────────────┘
                         ▼
                Hybrid Recommendation
                         │
                         ▼
              Top-N Movie Suggestions
```

---

# 📂 Project Structure

```
Hybrid-Movie-Recommender/
│
├── data/
│   ├── movies.csv
│   ├── ratings.csv
│   ├── links.csv
│   ├── tags.csv
│
├── notebooks/
│   ├── hybrid_recommender.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── content_based.py
│   ├── collaborative.py
│   ├── hybrid_model.py
│   ├── recommend.py
│
├── models/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 📊 Dataset

The project can be trained using the **MovieLens** dataset.

Dataset includes:

- Movie titles
- Genres
- User ratings
- Tags
- Movie IDs

Example:

| User | Movie | Rating |
|------|--------|--------|
| 1 | Toy Story | 5 |
| 2 | Avatar | 4 |
| 3 | Interstellar | 5 |

---

# ⚙️ Recommendation Methods

## 1️⃣ Content-Based Filtering

Recommends movies based on similarities in movie features.

Uses:

- Genres
- Keywords
- Tags
- Movie descriptions
- TF-IDF Vectorization
- Cosine Similarity

Example:

```
Input Movie:
Interstellar

Recommended:
The Martian
Gravity
Arrival
The Prestige
```

---

## 2️⃣ Collaborative Filtering

Recommends movies based on user behavior and rating patterns.

Uses:

- User-item interaction matrix
- Matrix Factorization (SVD)
- Similar user preferences

Example:

```
User 120

Highly Rated:
Inception
The Dark Knight
Interstellar

Recommended:
Tenet
Shutter Island
Memento
```

---

## 3️⃣ Hybrid Recommendation

The final recommendation combines:

- Content similarity score
- Collaborative filtering score

This improves recommendation quality, especially for users with limited interaction history.

---

# ▶️ Running the Project

Clone the repository

```bash
git clone https://github.com/yourusername/Hybrid-Movie-Recommender.git
```

Navigate to the project directory

```bash
cd Hybrid-Movie-Recommender
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
python recommend.py
```

or open

```
hybrid_recommender.ipynb
```

---

# 💬 Example

### Input

```
Favorite Movie:
Interstellar
```

### Recommended Movies

```
The Martian
Gravity
Arrival
The Prestige
Inception
```

---

# 📈 Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- Precision@K
- Recall@K
- F1-Score
- Hit Rate
- Coverage

---

# 📌 Advantages

- Combines strengths of multiple recommendation methods
- Improves recommendation accuracy
- Handles cold-start scenarios better than standalone approaches
- Produces more personalized recommendations
- Scalable for large datasets

---

# 🔮 Future Improvements

- Deep Learning-based Recommendation Models
- Neural Collaborative Filtering (NCF)
- Transformer-based Recommendation
- Session-Based Recommendation
- Explainable AI Recommendations
- Real-Time Recommendation Pipeline
- Streamlit Web Application
- FastAPI Deployment
- User Authentication and Profiles
- Personalized Recommendation Dashboard

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Vallarasu M**

Final Year B.E. Computer Science and Engineering

Government College of Engineering, Thanjavur

### Interests

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Recommendation Systems
- Natural Language Processing
- Large Language Models (LLMs)
- Agentic AI
- AI Research

---

# ⭐ Support

If you found this project useful, please consider giving the repository a ⭐. Your support helps improve and maintain the project.
