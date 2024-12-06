# CNN-Web-Scraper

CNN Article Scraper is a Python-based tool designed to automate the extraction of news articles from CNN. It retrieves key details such as the title, author, publication date, category, and content, and organizes the data into a structured JSON format.

## Features

- **Automated Article Scraping**: Fetches and processes articles directly from CNN.
- **Data Extraction Includes**:
  - Title
  - Author(s)
  - Publication or Update Date
  - Article Content
  - Category and Subcategory

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/thantthirimaung/CNN-Web-Scraper.git
cd CNN-Web-Scraper
```

### 2. Install Dependencies
Ensure Python 3.7 or later is installed on your system. Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## Usage

### 1. Run the Script
Run the script to scrape the articles and save the data:

```bash
python main.py
```

### 2. View the Output
The scraped data will be saved in a JSON file (e.g., `cnn_articles.json`) with the following structure:

```json
[
    {
        "url": "https://www.cnn.com/2023/07/01/politics/supreme-court-term-takeaways/index.html",
        "title": "Key Supreme Court takeaways",
        "content": "The Supreme Court ruled on...",
        "metadata": {
            "category": "Politics",
            "sub_category": "Supreme Court",
            "published_date": "July 1 2023 9:00 AM",
            "author": "John Doe",
            "language": "English"
        }
    }
]
```
