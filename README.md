# Web Scraper

A Python-based web scraper designed to crawl websites and generate comprehensive reports about their internal structure and links.

## Features

- Crawls websites and discovers internal links
- Generates detailed reports about page structure
- Handles various HTTP status codes
- Provides link analysis and statistics

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/web-scraper.git
cd web-scraper
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the web scraper with a target URL:

```bash
python scraper.py https://example.com
```

The scraper will:
- Crawl the specified website
- Discover internal links
- Generate a report with link statistics
- Display results in the console

## Requirements

- Python 3.7+
- requests
- beautifulsoup4
- urllib3

## Project Structure

```
web-scraper/
├── scraper.py          # Main scraper script
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Ideas for Extending the Project

- Make the script run on a timer and deploy it to a server. Have it email you every so often with a report
- Add more robust error checking so that you can crawl larger sites without issues
- Count external links, as well as internal links, and add them to the report
- Save the report as a CSV spreadsheet rather than printing it to the console
- Use a graphics library to create an image that shows the links between the pages as a graph visualization
- Make requests concurrently to speed up the crawling process
- ~~Add a README.md file explaining to users how to clone your git repo and get started~~
