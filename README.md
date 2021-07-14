# Scraping Top Repositories for Topics at GitHub
## Introduction
This is my first web scraping project. I wanted to know about all the top repositories for each topic on GitHub. But it seemed like a lot of hassle to manually go through each topic page on GitHub and search for it's top repositories. Also to remember which repository blongs to which topic was a lot of work for me. So I tried to automate the whlole process using the mighty Python and web scraping to do the work for me.
## Outline
* First we scrape through https://github.com/topics
* Then we get a list of all topics on the first page. For each topic, we fetch topic title, topic description and topic url
* Later we get a list of all the repositories on each topic page. For each repository, we fetch repository name, owner name, stars and repository url
* We create a CSV file of all the topics info collected
* At last we create a CSV file of all repositories info collected for each topic like the following :-

Repository Name,Userame,Stars,URL

three.js,mrdoob,72500,https://github.com/mrdoob/three.js

libgdx,libgdx,18600,https://github.com/libgdx/libgdx
## Tools used
I used
1. Python as the programming language due to its wide range of libraries (modules).
2. requests module to download the webpages.
3. BeautifulSoup module to scrape through the HTML codes of webpages.
4. Pandas module to create dataframes of collected data
5. os module to create folder and change path of directory
6. shutil module to delete directory
7. IPython.display module to import and display images
8. time module to sleep process
## References
I generally don't remember all codes and neither do I try to. Before solving any problem, I first create a rough outline of what I want to do and how I will solve it. Then I look for the syntax online using Goolge. I really want to thank saome websites which helped me with the codes and syntax :-

* [Stack Overflow](https://stackoverflow.com)
* [Geeks For Geeks](https://www.geeksforgeeks.org)
* [MDN Web Docs](https://developer.mozilla.org/en-US)
* [W3Schools](https://www.w3schools.com)
* There are multiple videos on [YouTube](https://www.youtube.com) 
* Also if you are a beginner and want to learn python from it's roots, I suggest you check the free course [PY4E](https://www.py4e.com) by Chuck Severance.
