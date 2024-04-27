![mars_weather](https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/2f41e2c4-b918-4afd-af94-d99d040feac6)
![mars_surface](https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/9138e8d1-a2f5-4766-9ac1-3798360c2568)

# Mars News and Weather Web Scraping and Analysis

----

This Challenge is a full web-scraping and data analysis project.  To complete this task, I have to identify HTML elements on a page, find their attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup: these types of information include HTML tables and recurring elements such as multiple news articles.  As with all such projects, its completion requires the collection, organization, and storage of data, and then the visual communication of any insights.

For the first part, I use automated browsing to visit the [Mars News Website](https://mars.nasa.gov/news/).  After a visual inspection of the webpage to identify which elements to scrape, I create a Beautiful Soup object and use it to extract text elements.  From these elements, I retrieve the titles and preview text of the news articles before storing the information in a List of Python Dictionaries.  After displaying the results in the IPython Notebook, mars_news.ipynb, I write the information to a JSON file in the Resources folder, mars_news.json.

The second part includes the analysis of weather data subsequent to web scraping.  As with Part 1, I use automated browsing to visit and inspect the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) before scraping the Mars Weather Data from an HTML table into a Pandas DataFrame.  From this DataFrame, I answer the following questions concerning weather on Mars:

* How many months exist on Mars?

    There are 12 months on Mars.

* How many Martian (and not Earth) days worth of data exist in the scraped dataset?

    There are 1,867 Martian days worth of data on this webpage.

* What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:

<img width="960" alt="Screenshot 2024-04-27 at 10 21 16 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/bfa60572-bfe9-42ad-9bf8-f3ee66de33ce">

   On average, the month with the coldest minimum temperature on Mars in Curiosity's location is number 3, and the month with the warmest is number 8.

* Which months have the lowest and the highest atmospheric pressure on Mars?

<img width="945" alt="Screenshot 2024-04-27 at 10 22 15 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/5cfa13a3-c79e-4653-99e0-1f8acb7aef36">

   On average, the month with the lowest atmospheric pressure on Mars in Curiosity's location is number 6, and the month with the highest is number 9.

* About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

<img width="873" alt="Screenshot 2024-04-27 at 10 23 00 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/5c7af303-e372-4a5b-91f5-1373519faca0">

   According to peaks in solar longitude from the data set, there are 687 Earth days in a Martian year, which is the same as the 687 Earth days found through an Internet search.

<img width="1089" alt="Screenshot 2024-04-27 at 10 34 55 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/e7f8d699-2dcf-48e4-b63e-c81fd82af636">

   According to peaks in minimum temperatures from the data set, the number of Earth days in a Martian
year range from 674 to 701 with an average of 687.5, which is about the same as the 687 Earth days
found through an Internet search.

Ultimately, this project demonstrates effective use of web scraping to collect and analyze data. In this case, the findings provide valuable insights into Martian temperature, atmospheric pressure, and years.  Upon completion of the analysis, I exported all my results to the folder, images, and a CSV file in the folder, resources, mars_weather.csv.  

----

## Copyright

Nicholas J. George © 2023. All Rights Reserved.
