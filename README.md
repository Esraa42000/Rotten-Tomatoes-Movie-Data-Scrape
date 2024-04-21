# Rotten Tomatoes Web Scraping Project
This Python script scrapes movie data from Rotten Tomatoes, focusing on the "140 Essential Action Movies to Watch Now" list.
It extracts information such as movie title, year, score, critics' consensus, synopsis, starring actors, and director for each movie on the list.

Website URL: https://editorial.rottentomatoes.com/guide/140-essential-action-movies-to-watch-now/

# Content
The script uses the requests library to fetch the HTML content of the Rotten Tomatoes page and BeautifulSoup for parsing the HTML. It then extracts relevant information from the page, such as movie title, year, score, and additional details.

# Output
The extracted data is stored in a structured format using the pandas library. The script creates two output files:

* movies_info.xlsx: An Excel file containing the scraped movie data.
* movies_info.csv: A CSV file containing the scraped movie data.
