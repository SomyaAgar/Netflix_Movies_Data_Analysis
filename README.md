# Netflix Movies Data Analysis
## **Project Overview**
The project involves an end-to-end data analysis of movies released on Netlix till 2024. With Python and major data science libraries like Pandas, Matplotlib, and Seaborn, meaningful insights from the dataset were derived. The main objective is exploratory data analysis and visualization to understand movie popularity, their genre and viewer's reviews.

## **About Netflix**
Launched in 2007, nearly a decade after Netflix, Inc. began its pioneering DVD-by-mail movie rental service, Netflix is the most-subscribed video on demand streaming media service, with 301.6 million paid memberships in more than 190 countries as of 2025.By 2022, "Netflix Original" productions accounted for half of its library in the United States and the namesake company had ventured into other categories, such as video game publishing of mobile games through its flagship service. As of 2025, Netflix is the 18th most-visited website in the world, with 21.18% of its traffic coming from the United States, followed by the United Kingdom at 6.01%, Canada at 4.94%, and Brazil at 4.24%.

## **Dataset Summary**
Total Records: 9,827
Source: Netflix movies data (Kaggle)

### Features:
#### Column	Description
                                   
##### Data columns (total 9 columns)
Release_Date     : Date at which movie was released 
Title            : Title of the Movie        
Overview         : Short description abount movie  
Popularity       : total reviews of the movie
Vote_Count       : number of people voted for the movie
Vote_Average     : average voting on the movie   
Original_Language: the original language in which movie was released  
Genre            : Genre of movie (Action, Thriller, Suspense, etc)  
Poster_Url       : Url of the movie poster  

## Data Preprocessing & Feature Engineering
### Initial Exploration: 
Loaded and explored dataset structure.

### Data Cleaning:
- Removed irrelevant/missing rows.
- Standardized date-time formats.
- Dropping unimportant data colums.
- Handled multiple genres that were found for one movie.

### Feature Extraction:
- Derived new time-based features (year).
- Categorized popularity based labels: "Popular", "Average", "Below_agv", "Not popular".

## Data Visualization Techniques
Utilized Python visualization libraries to reveal patterns:
- Catplot
- Histplot

## Key Insights
- Drama genre is most frequent genre in our dataset and has appeared more than 14% of the times amoung 19 other genres.
- We have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the highest popularity amoung fans by having more than 18.5% of movies.
- Spider-May no way home has the highest popularity rate in our dataset and it has genres of Ation, Adventure and Silence Fiction.
- United States, Thred has the lowest rate in our dataset and it has genre of Music, Drama, War, Sci-fi and History.
- Year 2020 has the highest filming rate in our dataset.

## Libraries Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- NumPy

## Project Outcomes:
- Real-world data wrangling
- Time-based feature engineering
- Handling missing data
- Data-driven storytelling
- Business insight visualization
