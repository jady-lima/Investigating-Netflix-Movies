# Investigating Netflix Movies

## Project from Data Camp

Perform exploratory data analysis on the `netflix_data.csv` data to understand more about movies from the 1990s decade.

What was the most frequent movie duration in the 1990s? Save an approximate answer as an integer called `duration` (use 1990 as the start year of the decade).

A movie is considered short if it is less than 90 minutes. Count the number of short action movies released in the 1990s and save this integer as `short_movie_count`.

Feel free to experiment after submitting the project!

### Description

**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex your exploratory data analysis skills and dive into the entertainment industry.

You work for a production company that specializes in nostalgic styles. You want to do some research on movies released in the 1990s. You'll delve into Netflix data and perform exploratory data analysis to better understand this awesome movie decade!

You have been supplied with the dataset `netflix_data.csv`, along with the following table detailing the column names and descriptions. Feel free to experiment further after submitting!

### The Data

#### **netflix_data.csv**

| Column       | Description                     |
|--------------|---------------------------------|
| `show_id`    | The ID of the show             |
| `type`       | Type of show                   |
| `title`      | Title of the show              |
| `director`   | Director of the show           |
| `cast`       | Cast of the show               |
| `country`    | Country of origin              |
| `date_added` | Date added to Netflix          |
| `release_year`| Year of Netflix release       |
| `duration`   | Duration of the show in minutes |
| `description`| Description of the show        |
| `genre`      | Show genre                     |

### Problem

1. **Filter the data for movies released in the 1990s**:
   You'll want to subset the DataFrame to keep only the movies and then filter the years to ensure that you are working with rows where the release year is between 1990 and 1999.

2. **Find the most frequent movie duration**:
   Visualize the data to view the distributions of durations for movies released in the 1990s.

3. **Count the number of short action movies from the 1990s**:
   First, subset the data again to keep only movies of the correct genre. Then, iterate through the data and count the number of movies based on the condition that the duration is less than 90 minutes.
