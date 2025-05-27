Google Search Keyword Scraper + GPT-4 Content Generator

This project automates the process of:
- Searching a keyword on Google using Selenium
- Using OpenAI GPT-4 to generate SEO-optimized content (title, intro, answers, conclusion)
- Storing the generated content into Excel workbooks for further use

Features

- Google search automation via Selenium
- GPT-4 prompt-driven title, introduction, FAQ, and conclusion generation
- Saves results to structured `.xlsx` files using `openpyxl`
- Multi-prompt orchestration for content-rich outputs

Dependencies

- Selenium
- OpenAI
- Pandas
- openpyxl

Install them using the `requirements.txt`.

Folder Structure

.
├── prompt/ # For storing question & answer sets
├── prompt2/ # For storing title & intro outputs
├── prompt3/ # For storing conclusion outputs
├── scrap.py # Main scraping and generation script
├── README.md
└── requirements.txt


Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/keyword-scraper-gpt.git
   cd keyword-scraper-gpt


