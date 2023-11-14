# FakeVerseIndia

Each code for web extraction typically consists of two primary functions: **get_links** and **get_content**. 

**get_links**: We used the Chrome WebDriver to extract the links and then saved them as a CSV file. The method accepts a single parameter, which represents the page number. this function saves the article links in a CSV file which is later used for content extraction.

**get_content**: Within this function, the BeautifulSoup library is used to extract meta_features, textual_features, and media_features. The method receives a data frame containing the URLs to all articles from which the content has to be extracted. The retrieved data is ultimately stored as a CSV file.


Here is the drive link to our dataset:

https://drive.google.com/drive/folders/1fM77YELI7ncbrX0_nsjiu6UolsOZ-f7z?usp=sharing
