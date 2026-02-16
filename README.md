📰 Web Scraper for News Headlines
A simple Python-based web scraper that extracts top news headlines from a public news website and saves them into a text file.
This project was developed as part of a Python Developer Internship Task.
🚀 Features
Fetches live HTML content using requests
Parses headlines using BeautifulSoup
Extracts top 10 news headlines
Removes duplicate/empty entries
Saves output to headlines.txt
Includes proper error handling
🛠 Technologies Used
Python 3
requests (for HTTP requests)
BeautifulSoup4 (for HTML parsing)
File Handling
Exception Handling
📂 Project Structure
Copy code

├── news_scraper.py   # Main Python script
├── headlines.txt     # Output file (generated after running)
└── README.md         # Project documentation
⚙️ Installation
Install required packages:
Bash
Copy code
pip install requests beautifulsoup4
▶️ How to Run
Bash
Copy code
python news_scraper.py
After execution, a file named headlines.txt will be created containing the scraped headlines.
📌 Key Concepts Demonstrated
HTTP GET requests
Use of User-Agent header
HTML parsing with BeautifulSoup
find_all() method
.get_text(strip=True) usage
Try–Except error handling
Writing data to a .txt file
⚠️ Note
This scraper is intended for educational purposes only. Always ensure compliance with a website’s terms of service and robots.txt before scraping.# Elevate-labs_Task-3
