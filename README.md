# Data Mining Project 1
This is the first project in the course Data Mining in National Kapodistrian University of Athens

This project explores the relationship between the IMDb ratings and Netflix titles. The dataset used for this project includes Netflix titles and their IMDb ratings. The project analyzes this dataset using boolean bag of words and tf-idf techniques.

## Dataset

The dataset used in this project includes the following files:

- `netflix_titles.csv`: This file contains a list of Netflix titles and their attributes such as type, title, director, cast, country, date added, release year, rating, duration, and listed in.
- `imdb_titles.csv`: This file contains a list of IMDb titles and their attributes such as title, year, genre, duration, and average vote.
- `imdb_ratings.csv`: This file contains the IMDb ratings for the titles listed in `imdb_titles.csv`.

## Methodology

The project used the following techniques to analyze the dataset:

- **Boolean Bag of Words**: This technique involves representing a document as a set of binary values that indicate whether a particular word is present or not. It is useful for identifying which words are common across multiple documents.
- **TF-IDF**: This technique involves assigning a weight to each word in a document based on its frequency in the document and its rarity across all documents in the dataset. It is useful for identifying which words are unique to a particular document.

## Files

- `Data_Mining_Project1.ipynb`: This Jupyter notebook contains the code used in this project, including data cleaning, preprocessing, and analysis.
- `netflix_titles.csv`: This file contains the original dataset of Netflix titles.
- `imdb_titles.csv`: This file contains the original dataset of IMDb titles.
- `imdb_ratings.csv`: This file contains the IMDb ratings for the titles listed in `imdb_titles.csv`.
- `README.md`: This file contains information about the project.

## Conclusion

The project explores the relationship between IMDb ratings and Netflix titles using boolean bag of words and tf-idf techniques. These techniques provide insights into which words are common across multiple documents and which words are unique to a particular document. The project can be further expanded to explore other text mining techniques or to analyze other datasets related to the entertainment industry.
