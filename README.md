## Job listings scraper
A Python project in which I write a script that would automatically scrape job data from a popular Vietnamese job listing website, filter out jobs that do not match predetermined criteria, send an email about latest job listings and is set to run at regular intervals. It is a part of our Python for Beginner Challenge held by the Mentor and Supporters of the Self-study Data Discord community, with support from Sir Alex Freberg (CEO of Analyst Builder).

**The requirements for this project are as follows:**  
Create a Python script that scrapes job listings from a popular job board website (e.g., Topdev, ITViec, etc.) and filters the listings based on specific criteria using regular expressions. (Make sure the website's terms of service allow web scraping for personal use.)

Focus on extracting key information such as:
- Job title
- Company name
- Job location
- Job description
- Date posted
- Job link

Use regular expressions to filter the job listings based on certain criteria. For example:
- Jobs that require specific programming languages (e.g., Python, JavaScript).
- Jobs that include certain keywords (e.g., "remote", "full-time").
- Exclude jobs that contain unwanted terms (e.g., "internship", "part-time").

Store the filtered job listings in a CSV file or display them in a readable format.

**Bonus points:**  
- Pagination: Handle pagination to scrape multiple pages of job listings. (+1)
- Scheduling: Set up your script to run periodically to scrape and update the job listings daily or weekly. (+3)
- Notification System: Send an email notification with the latest job listings that match your criteria. (+5)
