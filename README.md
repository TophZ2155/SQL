# Tophe Zuelke's SQL Portfolio
Welcome to my SQL Portfolio! This code repository contains past and ongoing SQL I've written. Feel free to take a look and reach out via email if you have any questions.

> [!NOTE] 
> Some of this code, if in-progress, will not be entirely complete or accurate as I work through projects and make changes/corrections to code. I'll do my best to indicate this in the title of the project.

# Contact Information
toph.zuelke@gmail.com

---
# Project List Details
### Project 1: Superstore Database[^1]
This project demonstrates basic SQL functionality by querying data from a distributor / retail database. Detailed tasks included in the code but encompass: 
1. ordering items by specific details,
2. descriptive statistics of specific items,
3. stock amount, etc.
> Includes queries:  `SUM`, `AVG`, `MAX`, `MIN`, `COUNT`, `WHERE`, `GROUP BY`, `ORDER BY`.

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%201%3A%20Superstore%20Database)

### Project 2: Fortune 500 Analysis[^1]
This project demonstrates advanced SQL functionality by querying data from a descriptive database of Fortune 500 companies. Detailed tasks included in the code but encompass:
1. determining industry leaders,
2. placing companies within a work-life balance category,
3. determining true- and relative-company size, and individual industry ratio as a whole of the the total revenue across industries.
> Includes queries: `SUM`, `MAX`, `ROUND`, `OVER`, `CASE`, `AND`, `OR`, `GROUP BY`, `HAVING`, `ORDER BY`

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%202%3A%20Fortune%20500%20Analysis)

### Project 3: Employee Reporting, Wages, and Hiring[^1]
This project demonstrates relational querying with SQL "join" functions using a self-made database that includes employee information, department information, and company organization information. Detailed tasks are included in the code but encompass:
1. using a single join to display complete employee information by last name,
2. using multiple joins to display direct-superior-reporting using two unique tables in which one is self-joined,
3. displays a department's remaining hiring budget, indicates whether an additional hire is allowed, and how many additional employees can be hired based on a base salary estimate.
> Includes queries: `JOIN~ON`, `AS`, `CASE`, `GROUP BY`, `ORDER BY`

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%203%3A%20Employee%20Reporting%2C%20Wages%2C%20and%20Hiring)

### Project 4: PostgreSQL and Movies
This project demonstrates the various basic and advanced SQL functionality in the PostgreSQL dialect using a database of Netflix movies and TV shows. Detailed tasks are included in the code but encompass:
1.  counting and ordering movies based on specific details,
2.  narrowing query results for specific information,
3.  subquerying.
> Includes queries: `COUNT`, `MAX(DATE()`, `JOIN~ON`, `AND`, `WHERE`, `ORDER BY`

> SQL Dialect: `PostgreSQL`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%204%3A%20PostgreSQL%20and%20Movies)

### Project 5: Customer and Order Analytics[^2]
This project demonstrates statistical queries using multiple tables within a singular database using SQLite Studio. Detailed tasks are included in the code but encompass:
1.  counting the number of orders within a specific month and/or product,
2.  narrowing query results for a specific month's product cost,
3.  revenue of items within a specific month, at a specific location, or for accounts above certain purchase quantities.
> Includes queries: `COUNT`, `DISTINCT`, `JOIN~ON`, `LIKE~%`, `AND`, `WHERE`, `LENGTH~<>`, `IN`, `GROUP BY`, `ORDER BY`

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%205%3A%20Customer%20and%20Order%20Analytics)

### Project 6: Spotify Data Exploration[^3]
This project uses real data from Spotify's Top 50 Songs in 2021 database. It demonstrates primarily my ability to follow both prescribed tasks as well as explore data in self-generated analysis. Detailed tasks are included in the code but encompass:
1.  averaging stastical properties of songs, artists, etc.,
2.  categorizing songs, artists, etc. based on parameters to provide recommendations,
3.  generating "snapshot" statistics or playlists for hypothetical clientele requests.
> Includes queries: `COUNT`, `CASE`, `AND`, `WHERE`, `IN`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%206%3A%20Spotify%20Data%20Exploration) 

### Project 7: Digital Media Store | Part1--Fulfilling Analysis Requests[^4]
This project uses a digital media store database with 11 tables connecting various sales details including product information (e.g artist, track, genre), invoice information (billing, pricing, order information), and customer and employee information. It demonstrates my ability to fulfill company- or client-requested analyses of a database. It also contains heavy use of joining and can be seen as exemplifying of it. Detailed tasks are included in the code but encompass:
1.  filtering customer information (e.g. by country, specific invoices, etc.),
2.  compiling information (e.g. total orders in a year, total sales of an employee, etc.),
3.  combining information across tables to create item descriptions.
> Includes queries: `SUM`, `JOIN~ON`, `WITH~AS`(CTEs), `OVER~PARTITION BY`, `||`, `WHERE`, `LIKE~%`, `BETWEEN`, `GROUP BY`, `ORDER BY`, `LIMIT`

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%207%3A%20Digital%20Media%20Store%20%7C%20Part%201--Fulfilling%20Analysis%20Requests)

### Project 8: Digital Media Store | Part2--Self-generated Analysis[^4]
This project continues the analysis from Project 7 which uses a digital media store database with 11 tables connecting various sales details including product information (e.g artist, track, genre), invoice information (billing, pricing, order information), and customer and employee information. It demonstrates my ability to generate my own ideas and analyses from a dataset which may either be 1) helpful to the company department that needs it and/or 2) allows me to particpate in discussions about needed analyses with department individuals. Detailed tasks are included in the code but encompass:
1.  **HR**: company hierarchies, employee contact information, and hiring- and legacy-datetime information,
2.  **Marketing**: regional customer-base distributions, filtered email lists for new campaigns, and collaborative statistics,
3.  **Sales**: product and item details, year-to-year revenue report with percent proportions, determining revenue-based tiers for implementing a tier-based system.
> Includes queries: `COUNT`, `DISTINCT`, `CASE`, `NTILE`, `STRFTIME`, `JOIN~ON`, `WITH~AS`(CTEs), `OVER~()`, `||`, `NOT LIKE~%`, `GROUP BY`, `ORDER BY`, `LIMIT`

> SQL Dialect: `Standard`

> Full Query: [View](https://github.com/TophZ2155/SQL/blob/main/Project%208%3A%20Digital%20Media%20Store%20%7C%20Part%202--Self-generated%20Analysis)

[^1]: Data in this project is fabricated and may not reflect actual names, values, or other included information.
[^2]: Database too large to include within the code. 
[^3]: Database can be found at [this link](https://www.kaggle.com/datasets/equinxx/spotify-top-50-songs-in-2021)
[^4]: Data pulled from the "Chinook" database.
