# web_scraping_using_BeautifulSoup 
# imdb_web_scraping
- This file contains a single python script to extract imdb Top Movies of 2024
## The Libraries used are
- Pandas
- numpy
- requests
- BeautifulSoup
## The flow 
- Used request to send request to the page
- Made a beautifulsoup object and passed the response got from requests
- Used soup.find_all() to find all the tags
- Used pandas to convert the extarcted data into a dataframe
## The Shortcomings
- This script was able to get only top 25 movies

# web_scraping_coursera
- This file contains a single python script to extract the courses related to data science in coursera
# The Libraries used are
- Pandas
- numpy
- request
- BeautifulSoup
# The Flow
- Used request to send request to the page
- Used the soup.find_all() to find the desired tags
- Used Pandas to convert into DataFrame

# The Shortcomings
- The script was only able to scrape 11 courses
