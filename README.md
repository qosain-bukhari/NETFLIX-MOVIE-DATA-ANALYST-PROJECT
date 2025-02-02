# Netflix Movie Data Analysis

## Overview
This project involves analyzing a dataset of over 9,000 movies released on Netflix. The goal is to derive insights to support data-driven business decisions, including determining popular genres, identifying movies with the highest/lowest popularity, and analyzing trends in movie releases over the years.

## Key Questions Addressed
1. What is the most frequent genre of movies released on Netflix?
2. Which movie has the highest votes in the `vote_avg` column?
3. What movie has the highest popularity, and what is its genre?
4. What movie has the lowest popularity, and what is its genre?
5. Which year has the most filmed movies?

## Dataset
- The dataset contains information about 9,000+ movies, including columns for:
  - `genre` (e.g., Comedy, Drama, etc.)
  - `popularity`
  - `vote_avg`
  - `release_year`
  - Additional metadata (e.g., title, cast, etc.)

## Approach

1. **Data Preparation**
   - Load the dataset using Python (e.g., pandas).
   - Clean and preprocess the data, handling missing or inconsistent values.

2. **Analysis**
   - **Frequent Genre:** Count the occurrences of each genre and identify the most frequent.
   - **Highest Votes:** Find the maximum value in the `vote_avg` column and retrieve the corresponding movie.
   - **Highest and Lowest Popularity:** Determine the movies with the highest and lowest popularity scores and their genres.
   - **Yearly Trends:** Analyze the number of movies released per year and identify the year with the highest count.

3. **Tools Used**
   - Python
   - Libraries: pandas, matplotlib, seaborn (for visualization)

## Results
The analysis yields the following insights:
1. Drama's The most frequent genre of movies released on Netflix.
2. Average movie with the highest `vote_avg`.
3. The most popular and least popular movies, along with their genres.
More Popular
  Spider-Man: No Way Home	Action	5083.954
	Spider-Man: No Way Home	Adventure	5083.954
	Spider-Man: No Way Home	Science Fiction	5083.954
Less Popular
  25545	The United States vs. Billie Holiday	Music	13.354
  25546	The United States vs. Billie Holiday	Drama	13.354
  25547	The United States vs. Billie Holiday	History	13.354
  25548	Threads	War	13.354
  25549	Threads	Drama	13.354
  25550	Threads	Science Fiction	13.354
5. 2020 The year with the most filmed movies.

## Usage

1. Clone the repository:
  git git clone (https://github.com/qosain-bukhari/NETFLIX-MOVIE-DATA-ANALYST-PROJECT).git
  

2. Install the required Python libraries:
   bash
   pip install -r requirements.txt
  
## Files
- `analyze_netflix_data.py`: Python script for analyzing the dataset.
- `movies_dataset.csv`: Dataset containing details of the movies.
- `requirements.txt`: List of required Python libraries.

## Visualizations
- Catplot charts for the most frequent genres.
- Hist graphs for yearly trends.etc

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional analyses, feel free to create a pull request or open an issue.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- Dataset sourced from [Netflix Movie Dataset Source].
- Inspired by Netflix’s innovative use of data science and machine learning.

