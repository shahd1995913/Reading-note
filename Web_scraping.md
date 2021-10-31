# Web scraping

## Web scraping : is a task that has to be performed responsibly so that it does not have a detrimental effect on the sites being scraped.

##  Web Crawlers can retrieve data much quicker, in greater depth than humans, so bad scraping practices can have some impact on the performance of the site.

## While most websites may not have anti-scraping mechanisms, some sites use measures that can lead to web scraping getting blocked, because they do not believe in open data access.

## In Python Code
### start by importing the following libraries.
### import requests
### import urllib.request
### import time
### from bs4 import BeautifulSoup

## Techniques
## 1. Human copy-and-paste
- The simplest form of web scraping is manually copying and pasting data from a web page into a text file or spreadsheet.
-  Sometimes even the best web-scraping technology cannot replace a human's manual examination and copy-and-paste, and sometimes this may be the only workable solution when the websites for scraping explicitly set up barriers to prevent machine automation.

## 2. Text pattern matching
- A simple yet powerful approach to extract information from web pages can be based on the UNIX grep command or regular expression-matching facilities of programming languages (for instance Perl or Python).

## 3. HTTP programming
- Static and dynamic web pages can be retrieved by posting HTTP requests to the remote web server using socket programming.

## 4. HTML parsing
- Many websites have large collections of pages generated dynamically from an underlying structured source like a database. 
- Data of the same category are typically encoded into similar pages by a common script or template. 
- In data mining, a program that detects such templates in a particular information source, extracts its content and translates it into a relational form, is called a wrapper. 
- Wrapper generation algorithms assume that input pages of a wrapper induction system conform to a common template and that they can be easily identified in terms of a URL common scheme.
