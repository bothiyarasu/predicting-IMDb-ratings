# Film Development for PProductions: Predicting IMDb Ratings

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
![Status](https://img.shields.io/badge/Status-Completed-green.svg)

**Author:** Letícia Zorzi Rama  

## Project Goal
The goal of this project is to perform an analysis on a film database to guide **PProductions** in deciding which type of film should be developed next by predicting IMDb ratings.  

## Project Summary
This project is organized into two main parts, implemented in separate Jupyter notebooks:  

1. **Project Setup, pt. 1 & Exploratory Data Analysis (EDA)**  
   - Notebook: `PProductions_EDA.ipynb`  

2. **Project Setup, pt. 2 & Prediction**  
   - Notebook: `PProductions_Prediction.ipynb`
  
## Report notebook
Focuses insights and answers to questions raised in the project.

## Datasets
The project uses an enriched version of the IMDb dataset:  

1. **IMDb Dataset**  
   - Initial dataset: `desafio_indicium_imdb.csv` containing general information about films.  

2. **Data Augmentation**  
   - The IMDb dataset is enriched with budget and revenue features obtained from **The Movie Database (TMDb)**.  
   - The resulting dataset is named `imdb_tmdb.csv` and serves as the main dataset for both exploratory analysis and prediction.  

## Project Structure
```text
├── PProductions_EDA.ipynb # Exploratory data analysis
├── PProductions_Prediction.ipynb # IMDb rating prediction
├── Report.ipynb # Focuses insights and answers to questions raised in the project
├── desafio_indicium_imdb.csv # Initial IMDb dataset
├── imdb_tmdb.csv # Enriched dataset used in the project
├── model.pkl # Trained predictive model
├── requirements.txt # dependencies versions
└── README.md # Project documentation
```

<p align="center"> Thank you for taking the time to explore this project. I hope you enjoy reviewing the analysis and insights as much as I enjoyed developing them! <br><br> 💬 I’d be glad to connect and talk about projects like this — feel free to reach out! </p> 
