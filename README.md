![75b69fa433aa55d699c53f6bc251200](https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-through-Web-Scraping/assets/137228821/b5629543-7cbb-43e3-b99a-00503463d61d)
![15960018785f210e564d90f](https://github.com/njgeorge000158/Mars-News-and-Weather-Web-Scraping-and-Analysis/assets/137228821/054b1ec5-ffad-43b2-8844-96879c0d1e2a)

# Mars News and Weather Web Scraping and Analysis

----

This Challenge is a full web-scraping and data analysis project.  To complete this task, I have to identify HTML elements on a page, find their attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup: these types of information include HTML tables and recurring elements such as multiple news articles.  As with all such projects, its completion requires the collection, organization, and storage of data, and then the visual communication of any insights.

For the first part, I use automated browsing to visit the [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html).  After a visual inspection of the webpage to identify which elements to scrape, I create a Beautiful Soup object and use it to extract text elements.  From these elements, I retrieve the titles and preview text of the news articles before storing the information in a List of Python Dictionaries.  After displaying the results in the IPython Notebook, MarsNewsPy.ipynb, I write the information to a JSON file in the Resources folder, MarsNewsData.json.

The second part includes the analysis of weather data subsequent to web scraping.  As with Part 1, I use automated browsing to visit and inspect the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) before scraping the Mars Weather Data from an HTML table into a Pandas DataFrame.  From this DataFrame, I answer the following questions concerning weather on Mars:

* How many months exist on Mars?

    There are 12 months on Mars.

* How many Martian (and not Earth) days worth of data exist in the scraped dataset?

    There are 1,867 Martian days worth of data on this webpage.

* What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:

![MarsWeatherPyFigure51AverageLowTemperaturebyMonthonMars](https://github.com/njgeorge000158/Mars-News-and-Weather-Web-Scraping-and-Analysis/assets/137228821/a7fca727-1fda-4c57-bc71-67aacdfcd753)

   On average, the month with the coldest minimum temperature on Mars in Curiosity's location is number 3, and the month with the warmest is number 8.

* Which months have the lowest and the highest atmospheric pressure on Mars?

![MarsWeatherPyFigure52AverageDailyAtmosphericPressurebyMonth](https://github.com/njgeorge000158/Mars-News-and-Weather-Web-Scraping-and-Analysis/assets/137228821/30bde89f-65b7-440d-a17c-813905d0cc44)

   On average, the month with the lowest atmospheric pressure on Mars in Curiosity's location is number 6, and the month with the highest is number 9.

* About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

![MarsWeatherPyFigure54SolarLongitudevsTimewithPeaks](https://github.com/njgeorge000158/Mars-News-and-Weather-Web-Scraping-and-Analysis/assets/137228821/89b9458d-4629-4f21-a345-03c49e89fad6)

   According to peaks in solar longitude from the data set, there are 687 Earth days in a Martian year, which is the same as the 687 Earth days found through an Internet search.

![MarsWeatherPyFigure56MinimumDailyTemperaturevsEarthTimewithLabeledPeaks](https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-through-Web-Scraping/assets/137228821/370c0e96-9d9e-4946-b91c-a6fc25bef86d)

   According to peaks in minimum temperatures from the data set, the number of Earth days in a Martian
year range from 674 to 701 with an average of 687.5, which is about the same as the 687 Earth days
found through an Internet search.

Ultimately, this project demonstrates effective use of web scraping to collect and analyze data. In this case, the findings provide valuable insights into Martian temperature, atmospheric pressure, and years.  Upon completion of the analysis, I exported all my results to the Images folder and a CSV file in the Resources folder, MarsWeatherData.csv.  

----

## Copyright

N. James George © 2023. All Rights Reserved.
