# Cyberchase SQL Queries

## Project Overview

Cyberchase is an educational TV series aimed at teaching kids math and problem-solving skills. The `cyberchase.db` database tracks episodes of the show but was not optimized for querying. This project focuses on writing SQL queries to efficiently extract and analyze information from this database.

## Problem and Solution Overview

### Problem to Solve

The `cyberchase.db` database contains a table named `episodes` with columns such as `id`, `season`, `episode_in_season`, `title`, `topic`, `air_date`, and `production_code`. The challenge was to write SQL queries to handle various questions about the episodes efficiently.

### How I Used My Database Skills to Solve It

To address these challenges, I created SQL queries for the following:

1. **Listing Titles of Season 1 Episodes**
   - Query to list all episode titles from Cyberchase’s original Season 1.

2. **Finding the First Episode of Every Season**
   - Query to identify the season number and title of the first episode in each season.

3. **Retrieving Production Code for a Specific Episode**
   - Query to find the production code for the episode titled “Hackerized!”.

4. **Identifying Episodes Without Topics**
   - Query to find episode titles that do not have a listed topic.

5. **Finding a Specific Holiday Episode**
   - Query to locate the title of the holiday episode aired on December 31st, 2004.

6. **Listing Early Released Episodes from Season 6**
   - Query to find titles of Season 6 episodes released in 2007 instead of their expected 2008 release.

7. **Finding Episodes Teaching Fractions**
   - Query to list episode titles and topics related to teaching fractions.

8. **Counting Episodes Released in Recent Years**
   - Query to count episodes released between 2018 and 2023.

9. **Counting Episodes from Cyberchase’s First 6 Years**
   - Query to count episodes released from 2002 to 2007.

10. **Listing Episode Details Ordered by Production Code**
    - Query to list episode IDs, titles, and production codes, ordered by production code.

11. **Listing Season 5 Episodes in Reverse Alphabetical Order**
    - Query to list titles of episodes from Season 5 in reverse alphabetical order.

12. **Counting Unique Episode Titles**
    - Query to count the number of unique episode titles.

13. **Exploring a Custom Query**
    - Custom query exploring a question of choice with conditions.

## Files

- `cyberchase.db`: Database file containing the episodes data.
- `1.sql`: Query to list titles of all episodes in Season 1.
- `2.sql`: Query to list the first episode of every season.
- `3.sql`: Query to find the production code for “Hackerized!”.
- `4.sql`: Query to find titles of episodes without a listed topic.
- `5.sql`: Query to find the holiday episode aired on December 31st, 2004.
- `6.sql`: Query to list titles of early-released Season 6 episodes.
- `7.sql`: Query to list titles and topics of episodes teaching fractions.
- `8.sql`: Query to count episodes released from 2018 to 2023.
- `9.sql`: Query to count episodes from 2002 to 2007.
- `10.sql`: Query to list episode IDs, titles, and production codes, ordered by production code.
- `11.sql`: Query to list titles of Season 5 episodes in reverse alphabetical order.
- `12.sql`: Query to count the number of unique episode titles.
- `13.sql`: Custom query exploring a question of choice.

## How to Test

To test the queries, you can execute them in SQLite or redirect the output to a text file:

1. **Using SQLite:**
   - Run `.read FILENAME` in the SQLite command line (e.g., `.read 1.sql`).

2. **Redirecting Output:**
   - Use `$ cat FILENAME | sqlite3 cyberchase.db > output.txt` to redirect output to `output.txt`.

3. **Using Check50:**
   - Run `check50 cs50/problems/2024/sql/cyberchase` to verify correctness.

## How to Submit

Submit your work using:

```sh
submit50 cs50/problems/2024/sql/cyberchase
