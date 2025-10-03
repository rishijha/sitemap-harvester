# Sitemap Crawler

A Python tool to crawl website sitemaps and extract metadata from URLs.

## Installation

```bash
pip install sitemap-crawler
```

## Usage

```bash
sitemap-crawler --url https://example.com --output results.csv --timeout 10
```

### Options

- `--url`: Base URL of the website (required)
- `--output`: Output CSV file (default: sitemap_metadata.csv)
- `--timeout`: Request timeout in seconds (default: 10)

## Features

- Automatically discovers sitemaps from common locations
- Parses robots.txt for sitemap URLs
- Handles sitemap index files recursively
- Extracts metadata including title, description, keywords, and Open Graph data
- Outputs results to CSV format

## Requirements

- Python 3.7+
- requests
- beautifulsoup4
