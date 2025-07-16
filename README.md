# Netflix - Exploratory Data Analysis (EDA)

This project dives deep into the Netflix Titles dataset to uncover patterns, trends, and insights about the global catalog of Movies and TV Shows available on the platform. Using Python's data analysis and visualization tools, we clean the dataset, explore various attributes, and answer key business and content-related questions.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:

🔗 [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

This dataset contains detailed information about Netflix content including TV shows and movies from different countries, genres, and time periods.

### Features/Columns:

- **show_id**: Unique identifier for every show
- **type**: Movie or TV Show
- **title**: Title of the show
- **director**: Director of the show
- **cast**: Actors appearing in the show
- **country**: Country where the show was produced
- **date_added**: Date the show was added to Netflix
- **release_year**: Year of release
- **rating**: TV rating (e.g., TV-MA, PG, R)
- **duration**: Duration of the show (in minutes or number of seasons)
- **listed_in**: Genre(s) of the show
- **description**: Brief description of the content

---

## Project Objectives

- Load and clean the dataset
- Handle missing or inconsistent data
- Perform exploratory data analysis (EDA)
- Visualize key insights using charts and plots
- Answer business-relevant questions such as:
  - What is the ratio of TV Shows to Movies?
  - Which years saw the most content added to Netflix?
  - What genres are most common?
  - Who are the most featured directors and actors?
  - What is the distribution of content ratings?
  - Which countries produce the most content?

---

## Key Insights and Visualizations

- Bar charts comparing the number of Movies vs TV Shows
- Line plots showing how content has been added over the years
- Heatmaps for correlations (e.g., release year vs date added)
- Pie charts showing content distribution by country or rating
- Word clouds for titles and genres (optional enhancement)

---

## Requirements

To run this project, you’ll need the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
