# Movie-Finder

**What is it?**

Our Python group project is a webscraper that collects various data items of the 1000 most popular movies on IMDb. After collecting the data, the program allows the user to run various analyses on the data to help the user select the next movie to watch. Eventually, movie recommendations based on the users preferences are visualized on a HTML website.


**How does it work?**

Our project works by using various tools: first, we use BeautifulSoup to scrape the IMDb website. Second, Numerical Python (Numpy) and Pandas are used to collect, clean and store the data in a pandas dataframe. This dataframe (called movies in the code) is the basis for the subsequent analyses. Eventually, we creates a HTML website with movie recommendations based on YOUR preferences.

When scraping the IMDb website, the program automatically makes pauses of random length, in order to not overload the server.


**How can you use it?**

Download the Github repository to your on your personal computer. To run the code (file: *imdb1000.ipynb*), the following steps need to be performed:

1.   Run the code in "Part 1: Building the dataframe" in order to create a dataframe with the movies (file: *movies.csv*). Please note that the first cell, the webscraper, will take a few minutes to execute, as the program scrapes 1000 movies on the IMDb website. 

2.   Run the code in "Part 2: Running analyses on the data". Select the section that corresponds to the analysis you would like to perform.

3.   Run the code in "Part 3: HTML website". It automatically creates a HTML website (file: *YFM.html*) with visualized movie recommendation based on your preferences.

Please note that each Part of the code can be run individually.


**Sources**

* We have built the webscraper based on guides outlined on medium, which we used as a starting point to expand upon. The guides can be found under the following links: [Link 1](https://medium.com/better-programming/the-only-step-by-step-guide-youll-need-to-build-a-web-scraper-with-python-e79066bd895a),  [Link 2](https://medium.com/better-programming/how-to-scrape-multiple-pages-of-a-website-using-a-python-web-scraper-4e2c641cff8)

* The HTML page was created using the website https://8b.com/.


**Authors**

* Katharina Donhauser (16-725-772)

* Rafael Grünenfelder (17-725-177)

* Carla Kaiser (16-611-576)

* Thomas Maurenbrecher (16-614-109)
