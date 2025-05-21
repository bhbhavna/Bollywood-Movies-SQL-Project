🎬 Bollywood Movies Database & Ranking Project
A SQL project that models a Bollywood movies database using MySQL. It includes a normalized schema, sample data for popular movies, and a ranking query based on IMDb ratings and box office revenue.

📁 Project Structure
bollywood_movies_db.sql: Main SQL script that:

Drops existing tables (if any)

Creates genres and bollywood_movies tables

Inserts sample data

Executes a ranking query to list top movies by IMDb rating and revenue

🧱 Database Design
Table: genres

genre_id (Primary Key)

genre_name

Table: bollywood_movies

movie_id (Primary Key)

title

release_year

genre_id (Foreign Key → genres)

imdb_rating

box_office_revenue

📊 Features
Normalized schema (avoids redundancy)

Foreign key relationships

Clean insertions with real Bollywood movie data

Ranking logic using @rank variable for IMDb + revenue

Sorts movies by highest ratings, then revenue

✅ Sample Query Output
Rank	Title	Year	Genre	Rating	Revenue (Cr)
1	3 Idiots	2009	Comedy-Drama	8.4	460.00
2	Dangal	2016	Biographical Sports Drama	8.3	2024.00
...	...	...	...	...	...

🚀 How to Run
Open MySQL CLI or any MySQL GUI (like MySQL Workbench)

Execute the contents of bollywood_movies_db.sql

View ranked movie results in the final query output

📌 Note:
If you'd like to run this code without setting up a database locally, you can simply copy the SQL code from the file or PDF and paste it into an online SQL compiler like OneCompiler. It will produce the same output as shown here.

📌 Requirements
MySQL 5.7+ or compatible

Basic knowledge of SQL

📚 Learnings
How to design relational databases

Use of auto-incremented keys and foreign keys

SQL sorting and ranking logic

Clean and maintainable SQL scripts

📝 Author
Made with ❤️ for learning SQL and database design.
Want to extend it? Try adding actors, awards, or user reviews!
