# Netflix Exploratory Data Analysis (EDA) 🍿

This repository contains an Exploratory Data Analysis (EDA) project on Netflix content, utilizing a dataset of Netflix titles as of November 2019. The goal of this project is to uncover interesting trends, patterns, and insights into the types of content available on the platform, its growth over time, and key contributors like directors and countries.

## 🎯 Project Goals

The main objectives of this EDA project are to:

* Understand the distribution of **content types** (Movies vs. TV Shows).

* Identify the **top countries** producing content for Netflix.

* Discover the most prolific **directors and cast members**.

* Analyze the distribution of **content ratings**.

* Examine the **trend of content additions** to Netflix over the years.

* Identify the **most popular genres**.

## 💾 Dataset

The dataset used for this analysis is `netflix_titles_nov_2019.csv`. It contains information about movies and TV shows available on Netflix, including:

* `show_id`: Unique identifier for each title.

* `title`: Title of the movie or TV show.

* `director`: Director(s) of the content.

* `cast`: Main cast members.

* `country`: Country of production.

* `date_added`: Date the content was added to Netflix.

* `release_year`: Original release year of the content.

* `rating`: Content rating (e.g., TV-MA, TV-14).

* `duration`: Duration (e.g., "93 min" for movies, "1 Season" for TV shows).

* `listed_in`: Genres/categories.

* `description`: Brief synopsis.

* `type`: Type of content (Movie or TV Show).

## 🛠️ Tools and Libraries

This project is developed using **Python** and leverages the following libraries:

* **pandas**: For data manipulation and analysis.

* **matplotlib**: For creating static, interactive, and animated visualizations.

* **seaborn**: For creating informative and attractive statistical graphics based on matplotlib.

## 🧹 Data Cleaning and Preparation

Before analysis, the raw data underwent several cleaning and preparation steps:

* **Handling Missing Values**: Rows with missing `date_added` and `rating` were dropped. Missing `director`, `cast`, and `country` values were imputed with 'Unknown'.

* **Date Transformation**: The `date_added` column was converted to datetime objects, and `year_added` and `month_added` columns were extracted for time-series analysis.

## 📈 Exploratory Data Analysis (EDA) & Key Insights

The EDA revealed several interesting insights into Netflix's content library:

### Content Type Distribution

The analysis clearly shows that **Movies** comprise the vast majority of content on Netflix compared to TV Shows.

### Top Content-Producing Countries

The **United States** 🇺🇸 and **India** 🇮🇳 are the leading countries in terms of content production on Netflix, highlighting the platform's focus on content from these regions.

### Top Directors and Cast Members

Directors like **Jan Suter** and **Raúl Campos** (often associated with comedy specials) appear frequently, while actors like **Anupam Kher** and **Shah Rukh Khan** (prominent in Indian cinema) are among the most featured cast members.

### Content Ratings Distribution

**TV-MA** and **TV-14** are the most prevalent content ratings, indicating a significant portion of Netflix's offerings are targeted towards mature audiences.

### Content Additions Over Time

Netflix has shown a remarkable growth in content additions, particularly between **2015 and 2019**, reflecting its aggressive expansion strategy.

### Most Popular Genres

**International Movies**, **Dramas**, and **Comedies** are the most common genres, showcasing the diversity and global appeal of Netflix's content.

## 📊 Visualizations

The project includes several visualizations to illustrate the findings:

* **`content_type_distribution.png`**: A bar chart showing the breakdown of Movies vs. TV Shows.

* **`top_10_countries.png`**: A horizontal bar chart displaying the top 10 content-producing countries.

* **`top_10_directors.png`**: A horizontal bar chart showcasing the top 10 directors.

* **`top_10_cast.png`**: A horizontal bar chart illustrating the top 10 cast members.

* **`rating_distribution.png`**: A bar chart visualizing the distribution of content ratings.

* **`content_added_over_time.png`**: A line plot showing the trend of content added to Netflix each year.

* **`top_10_genres.png`**: A horizontal bar chart depicting the top 10 most popular genres.

These images are generated automatically when the Python script is run.

## 🚀 How to Run the Code

To run this EDA project locally, follow these steps:

1. **Clone the repository** (or download the files):
2. **Ensure you have Python installed** (preferably Python 3.x).

3. **Install the required libraries**

4. **Place the dataset** (`netflix_titles_nov_2019.csv`) in the same directory as the Python script.

5. **Run the Python script**:
