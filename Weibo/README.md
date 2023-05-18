## Weibo scraper

### Posts
To scrape posts, please create a .txt file "info.txt" as following:
{"keyword": "your keyword", "start_time": "yyyy-mm-dd-hh", "end_time": "yyyy-mm-dd-hh", "page":1}

please create a .txt file "cookie.txt", and save your cookie.

Note: it is suggested that the duration between start_time and end_time is less than 6 months


Run the script weibo_keywords.ipynb

While scraping:
1. check the time frequently, as Weibo may return posts of today sometimes
2. check and update cookie every three hours
3. note that weibo might change the place they save all data. If this happens, please modify the script correspondingly

### Comments
Please have a .csv file with posts of interest, make sure your have mid and uid

Run the script weibo_comments.ipynb
