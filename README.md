# Task 1: Search Engine
Create a vertical search engine comparable to Google Scholar, but specialized in retrieving just papers/books published by a member of Coventry University's Research Centre for health and life sciences (RCHL): 
https://pureportal.coventry.ac.uk/en/organisations/centre-for-health-and-life-sciences 

That is, at least one of the co-authors is a member of RCHL.

Your system crawls the relevant web pages and retrieves information about all available publications. For each publication, it extracts available data (such as authors, publication year, and title) and the links to both the publication page and the author's profile (also called "pureportal" profile) page.

Make sure you that your crawler is polite, i.e. it preserves the robots.txt rules and does not hit the servers unnecessarily or too fast.

Because of low rate of changes to this information, your crawler may be scheduled to look for new information, say, once per week, but it should ideally be able to do so automatically, as a scheduled task. Every time it runs, it should update the index with the new data. Make sure you apply the required pre-processing tasks to both the crawled data and the users' queries.

From the user's perspective, your system provides an interface similar to Google Scholar's main page, where the user may enter in queries/keywords concerning the resources they wish to locate. The results will then be shown by your system, arranged by relevancy, in a manner similar to Google Scholar. However, the search results are limited to RCHL members' publications. Unless you aim to earn a score of 70 or above, the user interface does not need to be web-based (like Google Scholar), and the usual Python interface in your IDE would do. However, for more usability, it would be preferable to be able to click on the printed links rather than copying and pasting them into a browser.
![image](https://github.com/sanjok1988/IR_simple_crawler_search_engine_in_python/assets/15711292/0819fcfa-acc8-4e21-b611-a3bfa38964b9)
