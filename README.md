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

## Business Flow

![WhatsApp Image 2025-05-31 at 12 08 55_68c3ecbb](https://github.com/user-attachments/assets/9fa81391-5418-4f8d-a81f-20b3351a07e7)


## Output

**books_data.csv**
