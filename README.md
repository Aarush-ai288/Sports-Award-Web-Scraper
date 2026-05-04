# Sports-Award-Web-Scraper
This program is designed to web scrape for season long NBA and NFL major awards.
# 🏀🏈 Sports Awards Scraper

A Python CLI tool that scrapes NBA and NFL award data from Wikipedia.

## 🚀 Features

* Extract NBA awards (MVP, ROY, DPOY, etc.)
* Extract NFL awards (MVP, Offensive & Defensive Rookie of the Year)
* Command-line interface for dynamic input
* Handles inconsistent webpage structures

## 🛠️ Tech Stack

* Python
* requests
* BeautifulSoup
* pandas
* argparse

## Dependencies
* pip install requests pandas beautifulsoup4 lxml

## Arguments
* This program uses command line arguments: --league (NBA/NFL) -- season (example formats: 2023-24 (for NBA, XXXX-XX), 2024 (for NFL (XXXX)

##  Usage

### NBA

```bash
python stats.py --league nba --season "2022–23 NBA season"
```

### NFL

```bash
python stats.py --league nfl --season "2023 NFL season"
```

##  Notes

* Data is scraped from Wikipedia
* Structure may change depending on the season page format

## Sources

* Wikipedia NBA & NFL season pages
* NBA MVP page
* AP NFL MVP page
