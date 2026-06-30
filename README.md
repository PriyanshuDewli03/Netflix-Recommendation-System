# 🎬 Netflix Movie Recommendation System using SVD

An end-to-end recommendation system built using the **Netflix Prize Dataset** and **Singular Value Decomposition (SVD)** to generate personalized movie recommendations. The project leverages collaborative filtering techniques to predict user ratings and recommend movies based on historical user preferences.

---

# 📌 Project Overview

This project develops a movie recommendation system using **SVD (Singular Value Decomposition)** on a subset of the Netflix Prize dataset. The objective is to predict how users would rate unseen movies and provide personalized recommendations based on their past rating behavior.

The project follows a complete machine learning workflow, including:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- User & Movie Activity Benchmarking
- Matrix Factorization using SVD
- Recommendation Generation
- Model Evaluation

---

# 🎯 Business Problem

Streaming platforms rely on personalized recommendations to improve user engagement and retention.

This project addresses the challenges of sparse user-item interactions by applying collaborative filtering with **SVD**, enabling the system to estimate missing ratings and recommend movies that align with user preferences.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Surprise
- Jupyter Notebook

---

# 📂 Project Workflow

```text
Data Loading & Cleaning
          │
          ▼
Data Benchmarking
(Filtering Inactive Users & Movies)
          │
          ▼
Creating Ratings Matrix
          │
          ▼
SVD Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Recommendation Generation
```

---

# 📊 Exploratory Data Analysis

The project includes:

- Data inspection and preprocessing
- Handling missing values
- Rating distribution analysis
- User activity analysis
- Movie popularity analysis
- Benchmarking active users and frequently rated movies
- Dataset filtering to improve recommendation quality

---

# 🤖 Recommendation Model

The recommendation engine was developed using **Singular Value Decomposition (SVD)** from the **Scikit-Surprise** library.

### Model Features

- Matrix Factorization (SVD)
- Collaborative Filtering
- Rating Prediction
- Personalized Movie Recommendations

### Model Evaluation

The model was evaluated using **3-fold Cross Validation** with:

- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)

---

# 📈 Key Insights

- The Netflix Prize dataset required preprocessing to separate movie IDs from user ratings.
- Filtering inactive users and infrequently rated movies improved model performance.
- Matrix factorization effectively captures latent user preferences and movie characteristics.
- SVD provides accurate rating predictions for sparse recommendation datasets.

---

# 💼 Business Impact

This recommendation system can help streaming platforms:

- Deliver personalized movie recommendations
- Increase customer engagement
- Improve user retention
- Enhance user experience
- Discover hidden user preference patterns

---

# 🚀 Future Improvements

- Implement Hybrid Recommendation Systems
- Compare SVD with SVD++, KNN, and ALS
- Deploy the recommendation engine as a REST API
- Build a web application using Streamlit
- Incorporate content-based filtering for improved recommendations

---

# 📁 Repository Structure

```text
netflix-recommendation-system/
│
├── README.md
├── Netflix_Recommendation_System.ipynb
├── requirements.txt
├── images/
└── data/
```

---

# ⭐ Skills Demonstrated

- Data Cleaning & Manipulation
- Exploratory Data Analysis (EDA)
- Recommendation Systems
- Collaborative Filtering
- Matrix Factorization (SVD)
- Model Evaluation
- Python Programming
- Machine Learning

---

# 👨‍💻 Author

**Priyanshu Dewli**

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.
