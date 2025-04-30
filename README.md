# Netflix-Data-Analysis

This project aims to analyze a dataset of movies available on Netflix and similar platforms 
to derive meaningful insights using data preprocessing, cleaning, and visualization 
techniques. By using Python libraries such as Pandas, Matplotlib, and Seaborn, the project 
performs operations like categorizing vote averages, handling multi-genre entries, and 
visualizing the distribution of genres and vote patterns. The final goal is to identify popular 
genres, voting trends, and the overall structure of the movie dataset for better 
recommendation and decision-making.
OBJECTIVES
• To clean and preprocess a real-world Netflix-like movie dataset.
• To categorize and analyze the popularity and average ratings of movies.
• To explore genre distribution and trends across years.
• To extract actionable insights using data visualization.
TOOLS AND TECHNOLOGIES USED
• Language: Python
• Libraries: Pandas, NumPy, Matplotlib, Seaborn
• IDE: Jupyter Notebook / VS Code
• Data Format: CSV
DATASET DESCRIPTION
The dataset contains information about 9827 movies with the following attributes:
• Release_Date – Original release date of the movie.
• Title – Name of the movie.
• Overview – A brief description of the movie.
• Popularity – A numerical value indicating popularity.
• Vote_Count – Number of votes received.
 
• Vote_Average – Average user rating.
• Original_Language – Original language of the movie.
• Genre – Comma-separated list of genres.
• Poster_Url – Image URL of the movie poster.
After cleaning and exploding the genre column, the dataset contains 25552 rows and 6 
columns.
DATA CLEANING AND PREPROCESSING
Key steps involved:
• Handled missing values in columns like popularity and genre.
• Converted release dates to year format.
• Split multiple genres for individual analysis.
• Filtered dataset to exclude null popularity or vote entries for accuracy.
EXPLORATORY DATA ANALYSIS
To uncover patterns and trends in the Netflix dataset, a comprehensive Exploratory Data 
Analysis (EDA) was conducted. This included data cleaning, visualization, and statistical 
analysis to derive insights related to genres, popularity, and temporal trends.
This project aims to address these challenges by performing data mining on the Netflix 
dataset to:
• Discover the most frequent genres on the platform.
• Analyze popularity and voting patterns across different genres.
• Identify the most and least popular movies.
• Determine which years saw the highest number of content releases.
By applying data analysis techniques to this dataset, the project seeks to provide actionable 
insights that can benefit stakeholders in content production, marketing, and 
recommendation systems.
 
INSIGHTS
Q1: What is the most frequent genre in the dataset?
The Drama genre is the most frequent in our dataset, appearing in over 14% of all entries 
among 19 other genres.
Q2: Which genre has the highest votes?
Approximately 25.5% of the dataset (6520 rows) falls under the "popular" vote category. 
Drama again leads with more than 18.5% of these popular movies.
Q3: What movie has the highest popularity, and what are its genres?
"Spider-Man: No Way Home" holds the highest popularity rating in the dataset. Its 
genres include Action, Adventure, and Science Fiction.
Q4: What movie has the lowest popularity, and what are its genres?
The movie "The United States, Thread" has the lowest popularity score. Its genres are 
Music, Drama, War, Sci-Fi, and History.
Q5: Which year had the most movies filmed?
The year 2020 had the highest number of movies produced in the dataset.
 
CONCLUSION
This project demonstrates a complete and structured data analysis pipeline applied to a 
Netflix-like movie dataset. From raw data preprocessing to generating insightful 
visualizations, the analysis offers meaningful findings that could help streaming platforms 
enhance their decision-making and strategic planning. The workflow began with data 
cleaning—removing null values, duplicates, and inconsistencies—to ensure high data 
quality. This was followed by transforming complex features such as multiple genres into a 
usable format for deeper analytical processing.
A major challenge addressed was parsing and analyzing multi-label genre columns. By 
converting genre strings into individual labels, we were able to accurately count the 
frequency of each genre, which revealed that Drama is the most frequent genre, appearing 
in more than 14% of titles. Moreover, genres like Action, Comedy, and Thriller were also 
popular, reflecting current global audience preferences. This granular breakdown allows 
streaming platforms to invest in content creation for in-demand genres, leading to better 
viewer engagement.
In summary, the project not only explored viewer preferences, genre popularity, and user 
ratings but also demonstrated the importance of structured data mining and warehousing 
techniques. The outcomes from this analysis can support streaming platforms like Netflix in 
making data-driven decisions to improve user satisfaction, retention, and overall content 
strategy
