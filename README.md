# OOP-Social-Finder
This Python class effectively scrapes social media page links from a list of URLs, including Facebook, Instagram, X, and LinkedIn.
As someone primarily focused on functional programming, this attempts a transformation of a previously crafted script, now adapted to adhere to object-oriented programming principles.

## Libraries
    pandas
    bs4
    requests
    fake_useragent
    requests
    
## Use-Cases
* Market Research: Gather social media URLs of competitors or similar businesses to analyze their online presence, engagement, and content strategies.
* Lead Generation: Collect social media links from websites related to your target audience to generate leads or potential customers.
* Data Analysis: Use the scraped social media URLs as part of data analysis projects, such as sentiment analysis, network analysis, or demographic studies.
* SEO Analysis: Extract social media links from websites to analyze their impact on search engine optimization and online visibility.
* Competitor Analysis: Benchmark your social media presence against competitors by scraping their social media profiles for comparison.

## Limitations
This script incorporates ethical considerations by only scraping each domain once and implementing a 5-second sleep timer between requests to prevent overloading servers. It utilizes rotating fake user agents for added anonymity. However, it's important to note that while these measures provide some basic anonymity, they may not be sufficient for full anonymity. Various methods such as fake user agents, proxies, and headless browsers would be necessary for complete anonymity.

Additionally, it's essential to be mindful that each request carries your current IP address, and continuous scraping of the same sites may lead to timeouts or IP bans. For further legal considerations regarding web scraping, please refer to this [article](https://techcrunch.com/2022/04/18/web-scraping-legal-court/).

## Additional Comments
This script was originally created in a Jupyter Notebook; however, it can be converted to a .py file using this [method](https://nbconvert.readthedocs.io/en/stable/usage.html_). The Python environment also exists in Anaconda.

This serves as a simple example of the possibilities of data mining and enriching a database at no cost. Many functionalities can be added, such as error handling, using tuples instead of lists for multiple values to be processed through the class, and incorporating print statements to track the progress of the script. Feel free to customize this script to suit your specific use case.
