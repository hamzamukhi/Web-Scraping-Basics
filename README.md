# Web-Scraping-Basics
The incredible amount of data on the Internet is a rich resource for any field of research or personal interest. To effectively harvest that data, you’ll need to become skilled at web scraping. The Python libraries requests and Beautiful Soup are powerful tools for the job. If you like to learn with hands-on examples and you have a basic understanding of Python and HTML, then this tutorial is for you.

What is Web Scraping?
Web scraping is the process of gathering information from the Internet. Even copy-pasting the lyrics of your favorite song is a form of web scraping! However, the words “web scraping” usually refer to a process that involves automation. Some websites don’t like it when automatic scrapers gather their data, while others don’t mind.

If you’re scraping a page respectfully for educational purposes, then you’re unlikely to have any problems. Still, it’s a good idea to do some research on your own and make sure that you’re not violating any Terms of Service before you start a large-scale project.

BeautifulSoup:
BeautifulSoup is one popular library provided by Python to scrape data from the web. 

Steps for Scraping any website:
Scrape a website using Python, you need to perform these 3 basic steps:
1-Sending an HTTP GET request to the URL of the webpage that you want to scrape, which will respond with HTML content. We can do this by using the Request library of Python.
2-Fetching and parsing the data using Beautifulsoup and maintain the data in some data structure such as Dict or List.
3-Analyzing the HTML tags and their attributes, such as class, id, and other HTML tag attributes. Also, identifying your HTML tags where your content lives.
