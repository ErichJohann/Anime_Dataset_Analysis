# Anime Data Analysis

## Objective
Perform **Exploratory Data Analysis (EDA)** using statistical and visualization tools to understand patterns and relationships in an anime dataset.

---

## Authors
- Erich Johann Costa de Carvalho  
- Erick Andrade Borba  
- Milena Caroline da Silva Soares  
- Sarah Stephany da Cruz Souza Campos  

---

## Dataset
- Source: [Kaggle - Anime Database 2022](https://www.kaggle.com/datasets/harits/anime-database-2022)  
- Rows: 21,460  
- Columns: 28  
- Origin: Extracted from MyAnimeList and Anime Background  

---

## Libraries Used
- **Pandas**: data manipulation and cleaning  
- **Matplotlib**: basic visualizations  
- **Seaborn**: advanced visualizations (boxplots, histograms, scatterplots)  
- **NumPy**: statistical calculations  

---

## Data Cleaning and Processing

- Removed duplicate rows  
- Dropped rows with null essential values (`Ranked`, `Score`, `Episodes`, `Genres`)  
- Excluded animes with **Unknown** genres  
- Fixed **Ranked** column (extra digit issue)  
- Filled missing **Ratings** based on mode per genre  
- Adjusted **Duration** for types `Movie`, `Special`, and `ONA`  
- Removed elements of type **Music**  

---

## Analyses Performed

- **Releases by season and year**  
- **Genre frequency distribution**  
- **Comparison between popularity and ranking**  
- **Demographic distribution among the most frequent themes**  
- **Average popularity by anime type**  
- **Average popularity by demographics**  
- **Number of works per studio**  
- **Average popularity by studio**  
- **Number of animes by source**  
- **Average popularity by source**  
- **Favorites by source**  
- **Average ranking by source**  

---

## How to Run
1. Download the dataset from the Kaggle link  
2. Save the `Anime.csv` file in the same directory as the notebook  
3. Execute the notebook cells sequentially in **Google Colab** or **Jupyter Notebook**  

---

## Notebook Structure
1. Data import and initial inspection  
2. Data cleaning and preprocessing  
3. Exploratory analysis with visualizations
4. Graph generation
5. Conclusion 

---
