# MovieAlchemist – Movie Project Success Analysis and Prediction System

## Project Overview
The project is an advanced decision support system that leverages data analysis and machine learning techniques to predict the commercial potential of film projects. Based on parameters provided by the user—such as genre, keywords, cast, or director—the system analyzes underlying correlations and estimates the percentage chance of a production's success.

The primary objective of the system is to assist creators and producers in the concept development stage and to optimize business decisions through the analysis of historical cinematographic data.

## Data Source
The analytical models in this project were trained using historical cinematographic data sourced from the Kaggle platform:
[TMDB Movie Metadata Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## Key Features
* **Success Prediction:** Evaluating a film's commercial potential based on a selected set of features.
* **Combination Analysis:** Investigating how combinations of different elements (e.g., specific genres paired with specific directors) impact the final success.
* **Recommendation System:** Deploying machine learning algorithms (including TF-IDF vectorization and Logistic Regression) for text analysis and recommendation delivery.
* **Data Processing:** Advanced engineering, cleaning, and preprocessing of large datasets.

## User Interface
As part of the project, a modern, interactive user interface was designed to facilitate seamless data entry and intuitive reading of prediction results.

The application prototype can be viewed at the following link:
[UI Prototype (Figma)](https://doll-debug-75782524.figma.site/)

## Tech Stack
* **Programming Language:** Python
* **Data Libraries:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Environment:** Jupyter Notebook
* **Interface / Design:** Figma

## Repository Structure
* `MovieAlchemist.ipynb` – The main notebook containing the final predictive model and scripts that allow users to input and test their own film concepts.
* `System_rekomendacji.ipynb` / `System_rekomendacjiCD.ipynb` – Analytical notebooks dedicated to exploratory data analysis (EDA), data cleaning, feature engineering, and training the recommendation models.
* `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` – Raw input datasets containing historical data regarding movies and their respective cast/crew.
* `system_rekomendacji_final_clean.csv` – Preprocessed, cleaned, and ready-to-analyze dataset powering the machine learning model.
* `Dokumentacja_projektu.docx` – Comprehensive technical documentation covering system architecture, requirements, and use-case scenarios.

## Setup and Installation

1. Clone this repository to your local machine.
2. Ensure you have Python (version 3.8+) and Jupyter Notebook installed.
3. Install the required project dependencies by running the following command in your terminal:
   ```bash
   pip install pandas numpy scikit-learn
