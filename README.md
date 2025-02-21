# AI Web Scraper

## Overview
AI Web Scraper is a web-based application built with Streamlit that allows users to scrape website content, extract meaningful text, and parse it using AI-powered processing. This tool is useful for web data extraction, analysis, and automated content summarization.

## Features
- Scrapes website content from a given URL.
- Extracts and cleans the main body content from the webpage.
- Splits large content into manageable chunks.
- Uses OpenAI's API to parse and analyze extracted text.
- Provides an intuitive web-based interface using Streamlit.

## Installation
### Prerequisites
Ensure you have Python installed (>= 3.8) and install the required dependencies.

```bash
pip install -r requirements.txt
```

### Clone the Repository
```bash
git clone <repository_url>
cd AI-Web-Scraper
```

## Usage
Run the Streamlit app using:
```bash
streamlit run trial.py
```

### Steps to Use
1. Enter the URL of the website you want to scrape.
2. Click on the **Scrape Website** button to extract content.
3. View the extracted content in an expandable section.
4. Provide a description of what you want to parse in the text area.
5. Click on the **Parse Content** button to process the text using AI.
6. The parsed results will be displayed on the screen.

## File Structure
```
AI-Web-Scraper/
│── trial.py             # Main Streamlit application
│── scrape.py            # Functions for web scraping and text extraction
│── parse.py             # AI-based text parsing functionality
│── requirements.txt     # List of dependencies
│── README.md            # Documentation
```

## Dependencies
The application requires the following Python libraries:
```bash
streamlit
openai
beautifulsoup4
requests
```

## Future Enhancements
- Implement authentication for secure scraping.
- Enable multi-page parsing.
- Improve text summarization using advanced AI models.

## License
This project is licensed under the MIT License.



