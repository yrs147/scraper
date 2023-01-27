# Golang Web Scraper

Golang Web Scraper is a tool that allows users to scrape search results from Google for a specific search term, country, and language. The results include the ranking, link, title, and description of each search result.

## Project Architecture
![Web scraper architecture](https://user-images.githubusercontent.com/98258627/215043416-0dc7180c-a55d-4dbc-abac-425de7b115ce.jpg)


## Features

-   Scrape search results from Google for a specific search term, country, and language
-   Results include the ranking, link, title, and description of each search result
-   Ability to specify the number of pages and number of results per page
-   Option to use a proxy for scraping
-   Built-in random user agent feature to prevent bans

## Getting Started

1.  Clone the repository and navigate to the project directory

```
git clone https://github.com/yrs147/scraper.git 
cd google-search-scraper
```

2.  Build and run the project

```
go build ./google-search-scraper
```

3.  Input the search term, country code, and language code in the prompt
4.  Optionally specify the number of pages, number of results per page, and use a proxy
5.  The results will be printed in the terminal

## Built With

-   [Go](https://golang.org/) - The programming language used
-   [goquery](https://github.com/PuerkitoBio/goquery) - Package for parsing html and xml

