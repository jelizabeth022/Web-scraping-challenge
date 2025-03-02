# Web-Scraping-Challenge

![image](https://github.com/user-attachments/assets/64946b3a-069a-4e96-9f54-87885b6a865b)

# Mars Web Scraping and Data Analysis Project

# Background
This project involves extracting and analyzing data from various websites related to Mars. Through this project, we will strengthen our skills in identifying HTML elements, automated browsing with Splinter, and HTML parsing with Beautiful Soup. We will also gain experience in collecting, organizing, storing, and analyzing data, ultimately presenting our insights visually.

# Project Overview

The project consists of two main parts:

1. Scraping titles and preview text from Mars news articles.

2. Scraping and analyzing Mars weather data from an HTML table.

# Deliverables

The project will produce the following deliverables:

1. Mars News Articles: Scraped titles and preview text.

2. Mars Weather Data: Scraped and analyzed weather data from Mars.

Files Provided

To help you get started, the following files are provided:

Module 11 Challenge files.

# Instructions

# Part 1: Scraping Mars News

1. Open the Jupyter Notebook named part_1_mars_news.ipynb.

2. Use Splinter to navigate to the Mars news site. Inspect the page to identify elements to scrape.

3. Create a Beautiful Soup object to extract text elements from the site.

4. Extract and store the titles and preview text of news articles in a list of dictionaries:

- Each dictionary should have two keys: title and preview.

- Print the list in your notebook.

- Optionally, export the data to a JSON file for easier sharing.

# Part 2: Scraping and Analyzing Mars Weather Data

1. Open the Jupyter Notebook named part_2_mars_weather.ipynb.

2. Use Splinter to visit the Mars Temperature Data Site. Identify the elements to scrape.

3. Create a Beautiful Soup object to scrape the data from the HTML table. Organize the data into a Pandas DataFrame with the same column headings as the table.

4. Ensure the data types for each column are appropriate (e.g., datetime, int, float).

5. Analyze the dataset with Pandas to answer the following questions:

- How many months are there on Mars?

- How many Martian days' worth of data are in the dataset?

- Identify the coldest and warmest months on Mars. Plot the average minimum daily temperature for each month as a bar chart.

- Determine the months with the lowest and highest atmospheric pressure. Plot the average daily atmospheric pressure for each month as a bar chart.

- Estimate the length of a Martian year by plotting the daily minimum temperature and visually estimating the result.

6. Export the DataFrame to a CSV file.

# Analysis Details

# Minimum Temperature
- The minimum temperatures measured on Mars between 2012 and 2018 vary by up to 10 degrees Celsius.

- The lowest minimum temperature on Mars corresponds to December (terrestrial month) on Earth.

- The highest minimum temperature corresponds to July (terrestrial month) on Earth.

# Atmospheric Pressure
- There is a large variance (approximately 72) in atmospheric pressure by terrestrial month as measured on Mars.

- The terrestrial month with the lowest atmospheric pressure is May.

- The terrestrial month with the highest atmospheric pressure is November.

# Year Length
- By visually estimating the length of a year on Mars using a line chart, we find it to be within 650-700 terrestrial days.

- Research indicates that a Martian year is approximately 687 terrestrial days.

# Saving the Data

Finally, export your analyzed DataFrame to a CSV file:

# Save the DataFrame to a CSV file
df.to_csv('mars_weather_data.csv', index=False)

# Confirm the CSV file was saved
print("DataFrame saved to 'mars_weather_data.csv'")

