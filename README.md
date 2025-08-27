# Netflix Originals Data Exploration and SQL Analysis

## 📌 Overview
This repository contains SQL queries and analysis performed on the **Netflix Originals** dataset. The goal is to extract meaningful insights about movies and shows produced by Netflix, including trends in genres, runtime, IMDb scores, languages, and release dates.

## 📊 Dataset
The dataset `Netflix_Originals` includes the following columns:
- `Title`: Name of the Netflix Original
- `GenreID`: Genre identifier
- `Runtime`: Duration in minutes
- `IMDBScore`: IMDb rating
- `Language`: Language of the content
- `Premiere_Date`: Release date

## 🎯 Objectives
The SQL queries are designed to perform:
- Advanced filtering
- Aggregation and grouping
- Sorting and ranking
- Constraint enforcement via table creation

## 🛠️ Queries Included
1. Filter by IMDb > 7, Runtime > 100, Language in (English, Spanish)
2. Count titles per language (only languages with >5 titles)
3. Top 3 longest Hindi movies by IMDb score (descending)
4. Titles containing "House" with IMDb > 6
5. Titles released between 2018–2020 in English, Spanish, or Hindi
6. Movies with runtime < 60 or IMDb < 5, sorted by premiere date
7. Average IMDb per genre (only genres with ≥10 movies)
8. Top 5 most common runtimes
9. 2020 releases grouped by language with count
10. Create a new table with IMDb and runtime constraints
