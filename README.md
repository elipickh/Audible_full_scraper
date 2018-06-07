# Audible full scraper
Scrape all of the information available for Audible's audiobooks using Python/Selenium

Python code that iterates over Audible's search results and scrapes information on the audiobooks, including:
* URL
* Title
* Author
* Narrator
* Price
* Publisher
* Release date
* Length
* Language
* Ratings (separately for each of the 1- to 5-star ratings):
  * Overall
  * Performance
  * Story
* Audio sample (mp3 URL), including the option to download the sample directly

TODO:
* Scrape the ratings and text of user comments (which can then be processed by NLP etc.)
