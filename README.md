# Music Library System | Sql Analysis

## Project Overview

This project focuses on designing and analyzing a relational Music Library database using SQL and MySQL.

The database contains information about customers, invoices, tracks, albums, artists, genres, employees, playlists, and media types. SQL queries were used to explore customer purchasing behavior, music preferences, artist performance, and country-level trends.

## Database Structure

The project includes the following relational tables:

- Customer
- Employee
- Invoice
- InvoiceLine
- Track
- Album
- Artist
- Genre
- MediaType
- Playlist
- PlaylistTrack

Primary keys and foreign keys were used to establish relationships between the tables.

## SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- Primary Keys
- Foreign Keys
- SELECT
- WHERE
- ORDER BY
- LIMIT
- JOINs
- GROUP BY
- HAVING
- Aggregate Functions
- Subqueries
- CTEs
- Window Functions
- RANK()

## Analysis Performed

The project answers business-oriented questions such as:

- Which country has the highest number of invoices?
- Which city generates the highest invoice revenue?
- Who is the highest-spending customer?
- Which artists have the most Rock tracks?
- Which tracks are longer than the average song length?
- How much does each customer spend on different artists?
- What is the most popular music genre in each country?
- Who is the highest-spending customer in each country?

## Key Findings

Some of the analysis identified:

- The USA has the highest number of invoices in the dataset.
- Prague has the highest total invoice revenue among the cities analyzed.
- A highest-spending customer was identified using customer-level invoice aggregation.
- The top 10 Rock artists were identified based on track count.
- Tracks longer than the average song duration were identified using a subquery.
- The most popular genre for each country was determined using CTEs and the RANK() window function.
- The highest-spending customer for each country was identified using ranking.

## Tools & Technologies

- SQL
- MySQL
- Relational Database
- Database Management System (DBMS)

## Project Structure

``text
music-library-system-sql-analysis/
│
├── README.md
└── music_library_system.sql

## How to Run

1. Install MySQL or MySQL Workbench.
2. Download or clone this repository.
3. Open `music_library_system.sql` in MySQL Workbench.
4. Execute the SQL script to create the database and tables.
5. Run the analysis queries to explore the data and generate insights.

## Author

**Tarun_Aditya**

B.Tech – Electronics and Communication Engineering

Aspiring Data Analyst | SQL | MySQL | Python | Excel | Power BI
