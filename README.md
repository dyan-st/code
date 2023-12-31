# Automation code (Python)
Code projects to improve your workflow &amp; automate repetitive tasks!

# SampleTitleScrape
Web scraper written with BeautifulSoup4, which does the following:
1. Extracts titles from website
2. Parses into pandas dataframe
3. Writes dataframe to Excel

# ScreenshotCode
Web scraper that retrieves screenshots of web pages, up to 4000px in depth! Allows you to scrape graphical webpages which don't support other forms of web scraping by tags, or webpages which change tags often! It does the following:
1. Retrieve URL
2. Opens ChromeDriver and scrolls down, making it ideal for infinite scrolling pages
3. Takes the screenshot
4. Renames the screenshot as the website title + datetime, for easy organization of screenshots

# FormatChecker
Need to check if Excel files have the same table format?
This code:
1. Loops through ALL Excel files in a folder, no matter the name.
2. Counts rows and columns
3. Creates Excel file with filename, row and columns!
Great for use prior to combining with PowerQuery!
