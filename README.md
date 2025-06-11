# 🎬 Netflix SQL Data Analysis Project

This project showcases SQL-based data analysis using the Netflix dataset from Kaggle. The aim is to answer business-relevant questions such as content trends, director insights, actor appearances, and genre distributions using PostgreSQL.

---

## 📁 Dataset Source

[Kaggle Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🛠 Tools & Technologies

- PostgreSQL
- SQL
- Kaggle Dataset
- Data Cleaning & Analysis

---

## 📈 Business Questions Solved

1. Count the number of Movies vs TV Shows  
2. Find the most common rating for movies and TV shows  
3. List all movies released in a specific year (e.g., 2020)  
4. Find the top 5 countries with the most content on Netflix  
5. Identify the longest movie  
6. Find content added in the last 5 years  
7. Find all the movies/TV shows by director 'Rajiv Chilaka'  
8. List all TV shows with more than 5 seasons  
9. Count the number of content items in each genre  
10. Find each year and the average numbers of content release in India on Netflix  
11. List all movies that are documentaries  
12. Find all content without a director  
13. Find how many movies actor 'Salman Khan' appeared in last 10 years  
14. Find the top 10 actors who have appeared in the highest number of movies produced in India  
15. Categorize the content as 'Good' or 'Bad' based on keywords ('kill' and 'violence') in the description  

---**
## 📊 Key Insights from the Netflix SQL Analysis:
1.Movies vs TV Shows:
Netflix hosts more Movies than TV Shows, showing its preference for short-form content.

2.Most Common Ratings:
TV Shows are most commonly rated TV-MA (for mature audiences).
Movies most often receive a TV-14 rating, suitable for teens.

3.Recent Movie Releases:
In 2020, Netflix added a significant number of new movie titles, indicating active content expansion.

4.Top Countries with Most Content:
The United States leads, followed by India, United Kingdom, Canada, and Japan.

5.Longest Movie:
The dataset includes an unusually long film, which may represent a documentary or special extended edition.

6.Content Added in Last 5 Years:
A significant portion of the content has been added recently, showing Netflix’s rapid content growth.

7.Director Rajiv Chilaka:
Known for Indian animation, he has contributed several titles to Netflix — mostly for children.

8.TV Shows with >5 Seasons:
A smaller segment of shows have long runs, indicating audience commitment and strong series development.

9.Genres:
Dramas, Comedies, and Documentaries are the most common genres.
Many titles span multiple genres.

10.India-specific Trends:
Years like 2018–2020 had the highest average content additions for India, showing Netflix's regional strategy.

11.Documentary Movies:
A notable number of documentaries highlight Netflix’s effort in providing informative content.

12.Content Without Director:
Many titles have missing director info, suggesting data gaps or non-directorial formats like stand-up or reality shows.

13.Salman Khan’s Appearances:
He appeared in a few titles in the last decade, indicating limited availability of his content on Netflix.

14.Top Indian Actors:
The most featured actors in Indian Netflix content include stars with broad filmographies and appeal.

15.Content Categorization:
A small percentage of titles were flagged as "Bad" based on keywords like kill and violence.
Most of the content is labeled "Good", showing Netflix’s family-friendly lean.

----
## 🚀 How to Use

1. Clone this repository or download the files  
2. Load the `netflix_dataset.csv` into a PostgreSQL environment  
3. Run the queries from `netflix_analysis.sql`  
4. Analyze the output and derive insights  

---

## 📄 Project Files

- `netflix_analysis.sql` → All queries used in analysis  
- `netflix_titles.csv` → Source dataset (upload it yourself)  
- `Netflix_SQL_Project_Report.docx` → A business-friendly report version  

---
