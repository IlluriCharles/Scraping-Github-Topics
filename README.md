# Scraping-Github-Topics
 
 Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It's a useful technique for creating datasets for research and learning. It is developed using python3.

### Required Libraries
- Requests
- BeautifulSoup
- Pandas
- OS module

### project outline:
- This code is going to scrape https://github.com/topics
- We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
- For each topic, we'll get the top repositories in the topic from the topic page
- For each repository, we'll grab the `repo name`, `username`, `stars` and `repo URL` 
- After the data is collected the collected data stored in `data folder` with title name .csv format

