# 🌱 Reddit Bioplastics Scraping Project
This script scrapes Reddit comments from 2010 to 2024 to gather discussions around bioplastics. We use multiple keywords to filter relevant posts, ensuring focused results for analysis.

## 🔍 Project Overview
Scope: Collects Reddit comments from 2010 to 2024 about bioplastics.
Keywords: Filters posts based on selected keywords related to bioplastics.
Filtering: Checks each post title to ensure at least one keyword is present for relevancy.

## 📊 Output
After running the script, results are saved in an Excel file with these columns:

Post Title
Post Text
Comment
URL
Date

## ⚙️ Tools and Libraries
PRAW: Utilized to connect with the Reddit API for data scraping.

pandas: for data manipulation and Excel output.

datetime: for handling date formats.

logging: for error tracking and debugging.

time: for managing pauses in the script to respect API rate limits.

google.colab.files: to enable file download in Google Colab.

aiohttp, asyncio, and nest_asyncio: for handling asynchronous requests.

praw.models.MoreComments: to manage comment thread expansion.

Feel free to explore, suggest improvements, or reach out if you have questions! 😊
