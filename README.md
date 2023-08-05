# Netflix Data Analysis

The project is a data analysis and visualization project focused on the [Netflix dataset]([url](https://www.kaggle.com/datasets/shivamb/netflix-shows)). It aims to explore and gain insights into the content available on Netflix, including movies and TV shows, genres, countries contributing to the content, content ratings, and prominent actors and directors.

The project starts by importing necessary Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The Netflix dataset is loaded using Pandas' read_csv() function, and an initial data overview is provided by displaying the first few rows and checking the number of rows and columns.

The project then performs data cleaning and preparation. Missing values in certain columns (e.g., 'director', 'cast', 'country') are handled by imputing them with appropriate default values. Rows with missing values in 'date_added' and 'rating' columns are dropped, as they are not relevant for the analysis.

After data preparation, exploratory data analysis (EDA) is conducted using various data visualization techniques. The project visualizes the count of movies and TV shows on Netflix, the most popular genres, the top countries contributing content, and the content distribution based on ratings.

The project also answers specific questions related to the dataset. It identifies the top 10 movie actors and TV show actors on Netflix, based on the number of titles they appear in. Additionally, it determines the top 10 directors with the most releases on the platform.

The project provides valuable insights into the Netflix dataset, revealing patterns and trends in the content available on the streaming platform. The data analysis and visualizations help understand the distribution of content, the preferences of Netflix viewers, and the significant contributors to the platform's content library. The project demonstrates how data analysis and visualization can be used to gain meaningful insights from large datasets and aid in decision-making and understanding user behavior in the entertainment industry.
