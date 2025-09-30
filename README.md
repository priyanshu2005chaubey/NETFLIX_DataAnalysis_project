📺 Netflix Data Analysis Project
📌 Project Overview

 This project explores a dataset of Netflix movies to uncover trends and insights about genres, popularity, ratings, and release patterns. Using Python in Google    Colab, I performed data cleaning, preprocessing, and exploratory data analysis (EDA) to better understand viewing patterns and content distribution on Netflix.

🗂 Dataset

 Source: [mymoviedb.csv](mymoviedb.csv) with **9827 movies**. 
 Key columns: Title, Release_Date, Genre, Popularity, Vote_Count, Vote_Average.

🛠 Tools & Libraries

 Python
 Pandas, NumPy (data handling & preprocessing)
 Matplotlib, Seaborn (data visualization)

🔍 Key Steps

1. Data Preprocessing

  Converted release date to year format.
  Removed unnecessary columns (overview, language, poster URL).
  Handled duplicates and missing values.
  Categorized movies based on Vote_Average (popular, average, below average, not popular).
  Expanded multiple genres per movie into separate rows.
 
2. Exploratory Data Analysis (EDA)

  Most frequent movie genres on Netflix.
  Distribution of ratings (Vote_Average).
  Movies with highest and lowest popularity scores.
  Year-wise distribution of movies.

📊 Key Insights

1. Drama is the most frequent genre on Netflix.
2. Spider-Man: No Way Home (2021) has the highest popularity score.
3. Movies span across multiple genres like Action, Adventure, Comedy, and Thriller.
4. Popularity distribution shows clear outliers, indicating a few blockbuster titles dominate attention.
