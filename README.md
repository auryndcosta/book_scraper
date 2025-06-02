#  Book Scraper - Books to Scrape

A Python script to scrape book data from [Books to Scrape](http://books.toscrape.com/) for analysis of pricing, ratings, availability, and trends.

## Features

- Scrapes all books (~1000) across paginated pages
- Extracts key information:
  - **Title**
  - **Price**
  - **Rating** (converted to number)
  - **Availability**
  - **Product URL**
- Saves data to `books_data.csv`
- Skips and logs missing data entries
- Handles HTTP errors gracefully

---

## Output

**books_data.csv**
