# IMDb Top 250 Movies Scraper

This repository contains a web scraping project built using Scrapy to extract data from IMDb's Top 250 Movies list. The scraper collects information such as movie rank, title, release year, and rating, making it a great hands-on example of web scraping for data enthusiasts and developers.

---

## Features
- Extracts detailed information from IMDb's Top 250 Movies list:
  - Rank
  - Title
  - Release Year
  - IMDb Rating
- Outputs data in structured formats such as CSV or JSON.
- Demonstrates efficient use of Scrapy for web scraping tasks.

---

## Prerequisites

Before running the scraper, ensure you have the following installed:

- Python 3.7 or higher
- Scrapy library

To install Scrapy, run:

```bash
pip install scrapy
```

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/imdb-top250-scraper.git
   ```

2. Navigate to the project directory:
   ```bash
   cd imdb-top250-scraper
   ```

3. Install the required dependencies (if applicable).

---

## Usage

1. Run the Scrapy spider:
   ```bash
   scrapy crawl imdb_top250
   ```

2. Export the scraped data to a file (e.g., JSON or CSV):
   ```bash
   scrapy crawl imdb_top250 -o output.json
   scrapy crawl imdb_top250 -o output.csv
   ```

3. Find the output file in the project directory.

---

## File Structure

- `imdb_top250_scraper/`: Main Scrapy project folder.
  - `spiders/`: Contains the spider for scraping IMDb.
  - `settings.py`: Scrapy settings configuration.
  - `items.py`: Defines the data structure for the scraped items.

---

## Example Output

| Rank | Title                   | Year | Rating |
|------|-------------------------|------|--------|
| 1    | The Shawshank Redemption | 1994 | 9.3    |
| 2    | The Godfather           | 1972 | 9.2    |

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to suggest improvements or report bugs.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- IMDb for providing the Top 250 Movies list.
- The Scrapy documentation and community for guidance on web scraping.

Happy Scraping!
