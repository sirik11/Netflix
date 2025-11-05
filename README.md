Data Loading and Inspection
Imported essential Python libraries (NumPy, Pandas, Matplotlib, Seaborn).
Loaded netflix_titles.csv and examined its structure using df.head(), df.info(), and df.describe() to understand the columns, data types, and null distributions.
Data Cleaning and Preprocessing
Identified missing values in key columns such as director, cast, country, date_added, and rating.
Dropped irrelevant columns (director, cast, date_added) for simplicity.
Replaced missing country values with “United States” and rating values with “TV-MA”, based on dataset patterns.
Verified data integrity ensuring no null values remained.
Exploratory Data Analysis (EDA)
Created a pie chart to visualize the proportion of Movies vs. TV Shows on Netflix.
Used count plots to analyze the distribution of ratings (e.g., TV-MA, PG-13, TV-PG).
Explored the relationship between content type and ratings through grouped bar plots.
Identified the Top 5 countries producing the most content, showing the U.S. and India as leading contributors.
Found the Top 5 years with the highest number of releases (2015–2019), indicating Netflix’s rapid content expansion.
Visualized the Top 10 genres (e.g., International TV Shows, Dramas, Documentaries) using Seaborn bar plots.
Key Findings
Movies dominate the catalog, but TV content has grown significantly since 2016.
TV-MA is the most common maturity rating, reflecting Netflix’s focus on adult-oriented shows.
The United States, India, and the U.K. lead in content production.
Genres like International Dramas, Documentaries, and Comedies are consistently popular.
