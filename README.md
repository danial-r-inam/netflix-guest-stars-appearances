# Netflix Data Analysis Project

## Overview

This project involves exploring a dataset containing information on movies and series available on Netflix, one of the largest entertainment/media companies. The goal is to investigate the claim that the average duration of movies on Netflix has been declining over the years.

## Project Structure

### 1. Loading Data into a Dictionary
- Initialized a Python dictionary with data provided on average movie durations from 2011 to 2020.
- Data loaded captures the trend of movie durations over these years.

### 2. Creating a DataFrame from the Dictionary
- Imported the `pandas` library and converted the `movie_dict` dictionary to a `pandas` DataFrame.
- Conducted initial inspection of the DataFrame for correctness and consistency.

### 3. Visual Inspection of Data
- Created a line plot visualization using `matplotlib.pyplot` to observe the trend in average movie durations.
- This visualization helped in visually confirming the initial hypothesis of declining movie durations.

### 4. Loading Additional Data from CSV
- Loaded the original CSV file 'netflix_data.csv' into a DataFrame for a more detailed analysis.
- Inspected the first few rows of the DataFrame to understand the dataset's structure and contents.

### 5. Filtering for Movies
- Filtered the dataset to separate movies from TV shows.
- Created a new DataFrame `netflix_movies` with selected columns: `title`, `country`, `genre`, `release_year`, and `duration`.

### 6. Creating a Scatter Plot
- Generated a scatter plot to visualize individual movie durations against their release years.
- Adjusted the plot size for better clarity and visibility of the data points.

### 7. Digging Deeper into the Data
- Investigated movies with a duration of less than 60 minutes.
- Analyzed the genres of these short-duration movies to understand their influence on the overall average duration.

### 8. Marking Non-feature Films
- Identified and marked non-typical genres like "Children", "Stand-Up", and "Documentaries" in the dataset.
- Used a loop to generate a list of colors based on the `genre` column, which was then used for plot visualization.

### 9. Plotting with Color
- Created a color-coded scatter plot to distinguish between typical and non-typical movie genres.
- Enhanced the plot with additional labels and a custom style using `plt.style.use()`.

### 10. Conclusion and Next Steps
- Concluded that non-typical genres might be responsible for the decline in average movie duration.
- Discussed potential further analyses and advanced data manipulation techniques with `pandas`.

## Technologies Used
- Data analysis and manipulation: `pandas`
- Data visualization: `matplotlib.pyplot`


## Contributors
- Danial Rashid Inam

*This project was a deep dive into Netflix's movie duration trends, combining data manipulation and visualization skills learned in Python.*
