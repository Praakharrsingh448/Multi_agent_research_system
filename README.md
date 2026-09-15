# Multi-Agent Research System

A Python-based research assistant that searches the web and extracts readable content from public webpages. The project uses Tavily for web search and LangChain tools for agent integration.

## Features

- Web search using Tavily
- URL scraping with BeautifulSoup
- Environment-based API key configuration
- Request timeouts and response-size limits
- Protection against private and local network URLs
- Dependency vulnerability checks with `pip-audit`

## Requirements

- Python 3.10 or newer
- Tavily API key
- Gemini API key, if used by the agent implementation

## Installation

Clone the repository and open the project directory:

````powershell
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
Set-Location YOUR_REPOSITORY

