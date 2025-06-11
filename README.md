# 🎬 Streaming Shows Analytics and Recommendation System

This Jupyter Notebook presents a complete data science and analytics workflow applied to a dataset of streaming shows. It highlights strong data handling, visualization, and entry-level machine learning application skills relevant to data analyst and data scientist roles.

---

## 🎯 Project Objective

To clean, explore, and extract insights from streaming platform data and build a simple content-based recommendation tool based on user preferences and IMDB ratings.

---

## 🧠 Data Science & Analytics Highlights

### 📥 Data Loading & Initial Exploration

- Loaded dataset using `pandas` and inspected structure via `.head()`, `.info()`, and `.isna().sum()`
- Assessed missing data and data types — essential for defining next steps in data preparation

### 🧹 Data Cleaning & Preparation

- Cleaned categorical columns: filled missing values in **Content Rating**, **IMDB Rating**, and **Streaming Platform**
- Extracted numerical values from mixed-format fields like **No of Seasons**
- Mapped and encoded content ratings into numeric categories
- Split and normalized multi-entry columns (e.g., platforms and genres)

> This step-by-step cleaning process reflects careful data preprocessing and attention to ensuring consistent and usable data for analysis and modeling.

---

## 📊 Exploratory Data Analysis & Visualization

### 📈 Visual Tools Used:
- `seaborn.countplot`: For categorical distribution analysis
- `plotly.express`: For interactive charts of platform and genre popularity
- `matplotlib`: For static summaries and bar plots

### 🔍 Key Insights Generated:
- Distribution of content ratings
- Most frequent streaming platforms and genre appearances
- Breakdown of compound genre/platform entries for deeper granularity
- Correlation analysis between IMDB rating and number of seasons

---

## 🤖 Machine Learning: Basic Recommendation System

Implemented a **content-based filtering function** `interactive_recommendation()`:

- Takes mood, platform, and genre as input
- Returns top-rated recommendations using filtered dataset
- Leverages prior cleaning and EDA steps to build a basic real-world application

> Demonstrates foundational knowledge of ML concepts and practical use of filtering logic for user-driven predictions.

---

## 🧰 Tech Stack

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Python           | Core programming                 |
| Pandas           | Data loading and manipulation    |
| Seaborn          | Static visualization             |
| Plotly Express   | Interactive data visualization   |
| Matplotlib       | Traditional plotting             |

