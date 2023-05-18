# Zhihu scraper

Scrape answers of question(s), and their comments

## Step
1. Make a list of all question urls (e.g., 'https://www.zhihu.com/question/417891051') in a .txt file named "Zhihu_all_questions_urls.txt", put in in the folder named 'zhihu'
2. Run zhihu_answers.ipynb
3. Run zhihu_comment.ipynb

## What you can get
### Answers
- About question: title, question url, total amount of answer of this question
- About answer: content, answer url, upvote count, time modified, *all* comment count
- About author: author url, number of followering, number of followers, gender, location

### Comments
- About answer: question title, question url, answer id, answer content
- About comment: comment id, created time, comment upvote, child comment count
- About author: author url, author gender (more info can be scrabed by using the get_author_info function in zhihu_answers.ipynb
