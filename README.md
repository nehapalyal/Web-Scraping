PROJECT 1 : 

📊 Yahoo Finance Stock Scraper
This project is a Python-based web scraper that uses Selenium to extract stock data from Yahoo Finance, focusing on the Most Active Stocks section.

🚀 Features
Automatically navigates to the "Most Active Stocks" page on Yahoo Finance

1. Scrapes data such as:

  Stock Name & Symbol ,
  Price (USD) ,
  Daily Change , 
  Volume (in millions) ,
  Market Cap (converted to billions) ,
  PE Ratio 

2. Cleans and saves the data into an Excel file

🛠️ Tech Stack
   1. Python
   2. Selenium WebDriver
   3. Pandas, NumPy
   4. Excel export using openpyxl

📂 Output : An Excel file named Reconstructed yahoo scraper.xlsx containing structured stock data.



PROJECT 2 :

# 🏙️ 99acres Real Estate Scraper

> A personal side project that tested my patience—and my Selenium skills! 😅

This project scrapes real estate property listings from [99acres.com](https://www.99acres.com) using Selenium and filters them based on specific, real-world criteria. After collecting the data, I cleaned and organized it into a structured Excel file using Python and Pandas.

---

## 📌 What I Scraped

The scraper targets listings that meet the following filters:

- 💰 **Price:** Below ₹5 Crore  
- 🏠 **Status:** Ready to move  
- ✅ **Verified:** Only verified properties  
- 🎥 **Media:** Listings with both videos and photos  
- 📄 **Pagination:** Handled multiple pages with 'Next' button clicks

---

## 🛠️ Tools & Technologies

- **Selenium** – for automated browser control and interaction  
- **Pandas** – for cleaning and organizing the data  
- **OpenPyXL / XlsxWriter** – for Excel output (optional)  
- **ChromeDriver** – to power Selenium with Chrome  
- **Time & Re module** – for waits and text cleanup

---

## 🧹 Data Cleaning

Once scraped, the raw data was cleaned to remove:

- Duplicates  
- Incomplete entries  
- Extra whitespace or symbols  
- Inconsistent formatting in price, area, etc.

The cleaned dataset is saved as an Excel file (`99acres_cleaned_data.xlsx`), ready for further analysis or visualization.

---

## 🚀 Highlights & Challenges

- Automating slider filters and status dropdowns took a fair bit of trial and error 🎯  
- Dealing with dynamic content and pagination meant building smart, repeatable navigation logic 🧠  
- Ensuring anti-bot measures didn’t block me (hello, headless Chrome and wait tricks! 👀)

---

## 📊 Sample Output

The final Excel file contains structured columns like:

- Property name 
- Price  
- Area (sq. ft)  
- Location  

---

## 🙌 Final Thoughts

This project was both a brain teaser and a patience workout—but totally worth it! Looking forward to exploring more automation, scraping, and data wrangling challenges.


✨ Author
  Neha Palyal
