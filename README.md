# 🎬 Netflix End-to-End Data Science Project

An **end-to-end data science project** analyzing Netflix content using **Python, Machine Learning, and Power BI** to uncover insights about streaming trends, content growth, and global distribution.

---

# 📌 Project Overview

Netflix hosts thousands of movies and TV shows from different countries and genres.
This project explores Netflix content data to discover important insights and build machine learning models.

The project includes:

* Data Cleaning & Exploration
* Machine Learning Models
* Data Visualization
* Interactive Power BI Dashboard

---

# ⚙️ Technologies Used

| Technology           | Purpose            |
| -------------------- | ------------------ |
| Python               | Data analysis      |
| Pandas               | Data manipulation  |
| Matplotlib & Seaborn | Visualization      |
| Scikit-learn         | Machine Learning   |
| Power BI             | Dashboard creation |
| GitHub               | Project hosting    |

---

# 📊 Dataset

Dataset used: **Netflix Movies and TV Shows Dataset**

Main features in the dataset:

| Column       | Description         |
| ------------ | ------------------- |
| show_id      | Unique ID           |
| type         | Movie / TV Show     |
| title        | Content title       |
| director     | Director name       |
| country      | Production country  |
| release_year | Year released       |
| rating       | Age rating          |
| listed_in    | Genre               |
| description  | Content description |

---

# 🔎 Project Workflow

## 1️⃣ Data Cleaning

* Removed missing values
* Converted date formats
* Created new features
* Prepared data for ML models

---

## 2️⃣ Exploratory Data Analysis

Important insights discovered:

• Netflix content increased rapidly after **2015**
• **Movies dominate Netflix content (~70%)**
• **United States produces the most Netflix titles**
• Drama and Documentary genres are highly popular

---

# 🤖 Machine Learning Models

Two machine learning approaches were implemented.

## Supervised Learning

A **classification model** was built to predict whether a title is:

* Movie
* TV Show

### Model Performance

* Accuracy: **100%**
* Precision: **1.00**
* Recall: **1.00**
* F1 Score: **1.00**

### Confusion Matrix

![Machine Learning Results](images/ml_model_results.png)

Class Labels:

* **0 → Movie**
* **1 → TV Show**

---

## Unsupervised Learning

**K-Means Clustering** was used to group similar Netflix content based on patterns such as:

* Release year
* Rating
* Genre
* Country

This helps identify **content clusters and viewing patterns**.

---

# 📈 Power BI Dashboard

An interactive Power BI dashboard was built to visualize key insights.

### Dashboard Features

* Total Movies
* Total TV Shows
* Netflix Content Growth Over Time
* Movies vs TV Shows Distribution
* Top Genres
* Rating Distribution
* Country-wise Content Production

---

# 🖥️ Dashboard Preview

![Netflix Dashboard](images/dashboard_preview.png)

---

# 📂 Project Structure

```
netflix
│
├── dataset
│   └── netflix_titles.csv
│
├── python_analysis
│   └── netflix_analysis.ipynb
│
├── machine_learning
│   └── netflix_ml_model.ipynb
│
├── powerbi_dashboard
│   └── netflix_dashboard.pbix
│
├── images
│   ├── dashboard_preview.png
│   └── ml_model_results.png
│
└── README.md
```

---

# 🚀 Key Skills Demonstrated

✔ Data Cleaning
✔ Exploratory Data Analysis
✔ Supervised Machine Learning
✔ Unsupervised Learning (Clustering)
✔ Data Visualization
✔ Power BI Dashboard Development

---

# 📬 Author

**Faizullah Alas**

Aspiring Data Scientist passionate about **Machine Learning, Data Analytics, and Business Intelligence**.

---

⭐ If you found this project useful, please consider **starring the repository**.
