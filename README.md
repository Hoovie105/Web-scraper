# Web-Scraper
A Python-based web scraping agent that leverages Firecrawl tools and OpenAI's 
GPT models for advanced website crawling, data extraction, and automation.

Features:
Scrape websites and crawl pages using Firecrawl tools
Extract structured data from web pages
Powered by OpenAI GPT-4o-mini for intelligent automation
Easily extendable with additional tools
Requirements
Python 3.10+
OpenAI API key (OPENAI_API_KEY)
Firecrawl API key (FIRECRAWL_API_KEY)

Installation:

-Clone this repository:
git clone https://github.com/Hoovie105/Web-scraper.git
cd Web-scraper
2-Install dependencies:
pip install -r requirements.txt

Usage:

-Create a .env file in the project root with your API keys
OPENAI_API_KEY=your_openai_key
FIRECRAWL_API_KEY=your_firecrawl_key

-Run the main script
python main.py

Project Structure:
main.py — Main entry point for the web scraping agent
pyproject.toml — Project dependencies and metadata
.env — (Not included) Store your API keys here
License
MIT
