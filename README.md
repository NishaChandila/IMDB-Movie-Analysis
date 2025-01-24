# Movie Dataset Analysis - Power BI Dashboard

> "Film is a wonderful way to look at the world, and the world is a great place to make a film about." 

## INTRODUCTION
As a data analyst, I’ve worked with a comprehensive movie dataset containing over **26,000 rows** of detailed information, ranging from financial figures to audience engagement metrics. This dataset includes key data points such as revenue, budget, vote counts, average ratings, popularity scores, release years, and genres. My analysis of this data offers valuable insights into the financial performance of movies, their popularity, and audience preferences, helping to identify trends and patterns in the entertainment industry.

Through visualizations and detailed analysis, I aim to highlight correlations between budget, revenue, runtime, and ratings, as well as offer a deeper understanding of the most successful genres and movie characteristics. The goal is to empower stakeholders with actionable insights to optimize movie production strategies, marketing, and investment decisions.

- IMDB Movie [**Power BI Dashboard**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movie-analysis-dashboard.pdf)
- IMDB Movie [**Data Cleaning & EDA**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movies_analysis.ipynb)
- IMDB Movie [**Dataset**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movies.csv)

## DATA STRUCTURE

### Dataset Overview
The dataset comprises detailed information about movies, containing over **26,000 rows** and numerous columns that capture various attributes related to the financial performance, popularity, and characteristics of movies. This rich dataset offers valuable insights into the entertainment industry, helping to understand how different factors such as budget, genre, runtime, and ratings impact a movie’s success.

Dataset Preview
![Dataset](https://github.com/NishaChandila/project-assets/blob/main/movie-data.PNG)

### Columns in the Dataset:
- **ID**: A unique identifier for each movie in the dataset.
- **IMDb ID**: The IMDb identifier linking the movie to its IMDb page for further details and cross-referencing.
- **Original Title**: The original title of the movie as released in its primary market.
- **Genres**: A list of genres associated with each movie (e.g., Action, Drama, Comedy, etc.).
- **Release Date**: The official release date of the movie in theaters.
- **Release Year**: The year in which the movie was released.
- **Budget**: The production budget of the movie, reflecting how much was spent to create the film.
- **Budget Adjusted**: The budget value adjusted for inflation or other factors to provide a more accurate financial comparison over time.
- **Revenue**: The total revenue generated by the movie, including box office earnings and other income streams.
- **Revenue Adjusted**: The revenue figure adjusted for inflation, giving a better understanding of its financial success across different time periods.
- **Vote Count**: The total number of votes cast by viewers on platforms like IMDb, reflecting audience engagement.
- **Vote Average**: The average rating given by users, typically on a scale of 1 to 10, providing insight into the movie’s overall reception.
- **Popularity**: A numerical score indicating the movie’s popularity, which could be based on social media mentions, search trends, or other factors.
- **Overview**: A brief description or synopsis of the movie’s plot.
- **Runtime**: The total runtime of the movie in minutes, indicating its length.
- **Tagline**: A short, catchy phrase used in marketing the movie, often used to capture the essence of the film.
- **Production Companies**: A list of production companies that were involved in creating the movie.
- **Keywords**: A set of keywords or phrases associated with the movie, often used for search and categorization purposes.

This dataset provides a comprehensive snapshot of each movie’s attributes, offering valuable data for trend analysis, financial forecasting, and audience sentiment analysis. By analyzing these columns, data-driven insights can be derived to understand what contributes to a movie’s success in terms of revenue, popularity, and critical reception.

- IMDB Movie [**Dataset**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movies.csv)

## EXECUTIVE SUMMARY

![Home](https://github.com/NishaChandila/project-assets/blob/main/music1.PNG)

This Power BI dashboard presents a thorough analysis of a movie dataset containing over 26,000 rows of detailed information, providing valuable insights into key financial metrics, movie popularity, genre distribution, and runtime analysis. The dashboard is organized into two main pages, each focusing on different aspects of the dataset to support informed decision-making in the entertainment industry.

### Page 1: **Financial Overview & Popularity Insights**
The first page of the dashboard focuses on financial performance and popularity insights of movies. Key metrics such as total revenue, total budget, vote count, and average rating are presented as KPIs, offering a snapshot of the overall financial health and audience reception of movies.

![Financial](https://github.com/NishaChandila/project-assets/blob/main/movie2.PNG)

- **Revenue vs. Budget**: A comparison of movie budgets and revenues reveals that high-budget films generally generate higher revenue, though some low-budget films also exceed expectations.
- **Top 10 Movies by Revenue**: The top-performing movies are highlighted, with *Avatar* leading the pack with over $11.3 billion in revenue.
- **Revenue by Genre**: Drama, Action, and Adventure are the top genres contributing to the overall revenue, with Drama accounting for 31.05%, Action for 35.31%, and Adventure for 33.64%.
- **Popularity vs. Ratings**: This scatter plot explores the relationship between movie popularity (based on social and search data) and audience ratings, showing that movies with higher ratings tend to have stronger popularity.

This page provides a clear overview of how movie financials and popularity are interrelated, offering valuable insights for stakeholders looking to optimize production and marketing strategies.

### Page 2: **Genre, Runtime & Movie Details Analysis**
The second page dives deeper into genre distribution, runtime analysis, and movie details. It focuses on exploring how different genres and runtimes influence movie performance and audience engagement.

![Movie](https://github.com/NishaChandila/project-assets/blob/main/movie3.PNG)

- **Movies per Genre**: The number of movies within each genre is displayed, helping to identify trends and popular categories.
- **Runtime Distribution by Genre**: A visualization of runtime distribution by genre highlights the most common runtimes within different categories.
- **Revenue vs. Runtime**: The analysis reveals that movies within the 90-120 minute range generate the most revenue, while shorter movies (under 60 minutes) also show strong financial returns.
- **Average Vote by Movie Title**: The analysis of average ratings by movie title shows that films with higher ratings consistently perform better in terms of audience engagement.

- IMDB Movie [**Power BI Dashboard**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movie-analysis-dashboard.pdf)

## EDA and Data Cleaning
In our movie dataset analysis, we performed several key data cleaning steps to ensure accuracy and relevance. Irrelevant columns were dropped, and data was processed to focus on critical metrics. We created an **ROI visualization** to evaluate the relationship between budget and revenue, helping to identify the most profitable movies.

A **scatter plot** was used to explore the correlation between vote average and popularity, revealing how audience ratings influence a movie’s popularity. We also analyzed movie genres, splitting them to examine the performance of each genre individually. This allowed us to assess the popularity of each genre and determine which ones contribute the most to revenue.

Finally, we checked **monthly revenue trends** to uncover patterns and identify peak revenue periods. These analyses provide a comprehensive view of how different factors such as genre, ratings, and popularity impact a movie’s financial performance.

- IMDB Movie [**Data Cleaning & EDA**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movies_analysis.ipynb)

## RECOMMENDATIONS
Based on the insights from the movie dataset analysis, here are key recommendations for improving movie performance and profitability:

1. **Focus on High-Performing Genres**: Genres like Action, Adventure, and Drama have shown to generate the highest revenue. It is advisable for production teams to prioritize these genres or create hybrid movies combining elements from these categories.
2. **Optimize Movie Runtime**: Movies within the 90-120 minute range tend to yield the best financial results. Shorter films (under 60 minutes) also perform well, so experimenting with runtime in these ranges could be beneficial for maximizing profitability.
3. **Leverage Audience Ratings and Popularity**: There is a clear relationship between audience ratings and popularity. A strong focus on improving the quality of storytelling and production could drive higher ratings, leading to increased audience engagement and stronger box-office performance.
4. **Consider Monthly Revenue Trends**: Monthly revenue trends show peaks during certain periods. Identifying these trends could help in planning release schedules, focusing marketing efforts during high-revenue months, and optimizing box office performance.

## CONCLUSION
In conclusion, this analysis of the movie dataset has provided actionable insights into how factors like genre, runtime, audience ratings, and popularity influence a movie’s financial success. By focusing on high-performing genres, optimizing runtimes, and enhancing content quality to drive better ratings, movie producers and studios can significantly improve their profitability. The dashboard’s visualizations and trend analysis offer a clear view of these factors, enabling data-driven decision-making that can guide both production and marketing strategies for future movie releases.

- IMDB Movie [**Power BI Dashboard**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movie-analysis-dashboard.pdf)
- IMDB Movie [**Data Cleaning & EDA**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movies_analysis.ipynb)
- IMDB Movie [**Dataset**](https://github.com/NishaChandila/Movies-Analysis/blob/main/movies.csv)
