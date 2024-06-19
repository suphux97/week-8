# week-8
assignment database
# Data Analyst Project

## Dataset Chosen
- **Dataset:** Netflix Shows

## Import Process
- **Difficulties:** Encountered issues with data formatting which required some preprocessing.
- **Interesting Finding:** The dataset contains a rich variety of genres and detailed metadata for each show.

## Data Fun (20 pts)
### SQL Queries and Findings

1. **Query:** Count of shows by genre
    ```sql
    SELECT genre, COUNT(*) AS count
    FROM netflix_shows
    GROUP BY genre;
    ```
   **Finding:** The most popular genre in the dataset is Drama.

2. **Query:** Average rating of shows
    ```sql
    SELECT AVG(rating) AS avg_rating
    FROM netflix_shows;
    ```
   **Finding:** The average rating of shows in the dataset is 7.8.

## Ask Away (30 pts)
### Questions and Answers

1. **Question:** What are the top 5 highest-rated shows?
    ```sql
    SELECT title, rating
    FROM netflix_shows
    ORDER BY rating DESC
    LIMIT 5;
    ```
   **Answer:** The top 5 highest-rated shows are [list of shows].

2. **Question:** How many shows were released each year?
    ```sql
    SELECT release_year, COUNT(*) AS count
    FROM netflix_shows
    GROUP BY release_year
    ORDER BY release_year;
    ```
   **Answer:** The number of shows released each year is [list of years and counts].

## Showtime! (20 pts)
### Charts
- [Insert image or link to charts]




