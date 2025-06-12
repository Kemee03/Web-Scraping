🛒 Product Price Comparison Tool using Web Scraping
This is a Python-based desktop application that allows users to search and compare product prices across popular Indian e-commerce platforms: Amazon, Flipkart, and Snapdeal. It uses web scraping techniques via BeautifulSoup and requests to fetch live pricing data and presents the results in a clean, scrollable GUI built with Tkinter.

🔍 Features
Multi-platform scraping: Retrieves product details from Amazon, Flipkart, and Snapdeal.

Graphical User Interface (GUI): Built with Tkinter, making it beginner-friendly and easy to use.

Real-time price comparison: Sorts and displays results by price to help users find the best deal.

Result export: Automatically saves the search results into a Product_List.txt file.

Formatted output: Uses tabulate to present results in a clear, readable table format.

Error handling: Informs the user if no results are found or if the data couldn't be fetched.

🛠 Tech Stack
Language: Python

Libraries Used:

requests – to fetch webpage content

BeautifulSoup – for parsing HTML data

Tkinter – to build the GUI interface

tabulate – to format search results in a table

🖥️ How It Works
User enters a product name in the search bar.

The app sends requests to each of the three websites with appropriate headers to mimic a browser.

HTML content is parsed using BeautifulSoup to extract product titles and prices.

Results are compiled, sorted by price, displayed in the GUI, and saved to a text file.

📂 File Structure
Web_scrapping.txt – Main application code (rename to .py before running)

Product_List.txt – Output file generated with search results
