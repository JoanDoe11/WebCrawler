# WebCrawler
Implementation of a web crawler in Python.

A web crawler is a program for systematical browsing of web pages. It starts with a list of URLs to visit (seeds). As it visits these web pages, it identifies all the hyperlinks in the seeds and adds them to the list of pages to be visited (crawl frontier). This is continued to a certaiin depth.

# Python libraries

*lib: requests* - used for making HTTP requests in Python. It abstracts the complexities of making requests using a simple API.

*lib: re* - provides operations for regular expression matching.

*lib: urllib.parse* - standard interface for parsing URL strings.

*lib: datetime.time* - module that provides various time-related functions.

*lib: multiprocessing* -a package that supports spawning processes using an API, allows the programmer to fully leverage multiple processors on a given machine. It runs on both Unix and Windows.
