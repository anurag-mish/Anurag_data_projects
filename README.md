# Movie Recommendation System – GCP + PySpark

A multi-stage recommendation system project for CIS 415 focused on building a scalable pipeline for collaborative filtering using user rating data. The pipeline includes data cleaning, Google Cloud integration, and a PySpark-based KNN similarity model.

## 🚀 Tech Stack
- Python
- PySpark
- Google Cloud Platform (GCP)
- Google Colab
- Pandas

## 🔄 Workflow Overview
1. **Data Cleaning (Assignment 3):** Cleaned raw movie rating data in Colab using pandas and custom functions.
2. **Cloud Integration (Assignment 4):** Uploaded and accessed data via Google Cloud buckets for distributed processing.
3. **Processing + Modeling (Assignment 5):**
   - Computed user-user similarity with **Pearson correlation**.
   - Filtered statistically significant relationships (p < 0.05).
   - Built a KNN-based recommender system using PySpark.

## 📁 Files
- `Assignment_3_Colab_Framework.ipynb`: Initial data preprocessing
- `Assignment_4_GCP_Framework.ipynb`: GCP setup and access
- `Assignment_5_KNN_Framework.ipynb`: Final modeling pipeline
- `Assignment_5_GCP_notebook.ipynb`: Intermediate steps
- `Data_Munging_2KMH56HAU.zpln`: Raw data transformation logic

## 📂 Data Files
The following datasets are used in this project and are available in the root directory:

- `ratings.csv`
- `movie_ratings(1).csv`
- `missionImpossible_ratings.csv`
- `data_for_GCP_labs.csv`

These CSV files were used throughout different stages of the project for user behavior analysis, collaborative filtering, and GCP-based processing with PySpark. The datasets were either created or accessed during CIS 415 lab assignments.



## 📌 Notes
This project was completed for Arizona State University's CIS 415 course on Big Data & AI in Business.
