# scrape_yellowpages
Web scraper for yellowpages.co.id to get company contact details. Written in Python and using Selenium library.

NOTE: To use the script you need to download [__Chrome Selenium driver__](https://sites.google.com/a/chromium.org/chromedriver/downloads) first. Make sure it’s in your PATH, e. g., place it in /usr/bin or /usr/local/bin.
You can also use another browser driver if you want.

In Row 21, change the text in double quote marks to the industry of companies that you want to scrap, e. g restaurant, retail shop, etc. 

Specify the directory you want the CSV to be saved in and the format of the CSV naming by changing the value of directory (Row 120).

Outputs contacts to CSV with the following information:
- Company name
- City
- Address
- Industry type
- Phone number
- E-mail (if any)
- Website (if any)
