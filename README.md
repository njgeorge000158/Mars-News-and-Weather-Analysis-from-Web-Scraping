![mars_weather](https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/2f41e2c4-b918-4afd-af94-d99d040feac6)
![mars_surface](https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/9138e8d1-a2f5-4766-9ac1-3798360c2568)

# **Martian Climate Analysis: Web Scraping NASA News and Weather Data from the Red Planet**

----

## **Project Overview**

This project combines automated web scraping with structured data analysis to extract, organize, and interpret two distinct categories of Martian data: current news from NASA's Mars News Website and historical weather observations from the Mars Temperature Data Site. The technical pipeline integrates Splinter for automated browser navigation, Beautiful Soup for HTML parsing, Pandas for data manipulation, and Matplotlib for visualization — culminating in a comprehensive portrait of Martian climate conditions as recorded by NASA's Curiosity rover. All results are exported to their respective output folders upon completion.

---

## **Part One: Mars News Scraping**

Using Splinter to navigate to the Mars News Website and Beautiful Soup to parse its HTML structure, I identified and extracted the titles and preview text of current NASA Mars news articles. Each article was stored as a Python dictionary containing its title and preview text, and the full collection was assembled into a Python list — displayed in the IPython notebook `mars_news.ipynb` and exported to `mars_news.json` in the `resources` folder for persistent storage and downstream use.

---

## **Part Two: Martian Weather Data Analysis**

The second component of the project focuses on quantitative climate analysis. After scraping the Mars Weather Data table from the Mars Temperature Data Site into a Pandas DataFrame, I analyzed the data to answer five key questions about conditions on the Martian surface at Curiosity's location.

### *How many months exist on Mars?*
Mars has 12 months, consistent with its orbital and calendrical structure as tracked by NASA mission data.

### *How many Martian days of data are in the dataset?*
The scraped dataset contains 1,867 Martian days — known as sols — of weather observations, providing a robust multi-year record of surface conditions at Curiosity's location.

## **Temperature: Coldest and Warmest Months**

<img width="960" alt="Screenshot 2024-04-27 at 10 21 16 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/bfa60572-bfe9-42ad-9bf8-f3ee66de33ce">

As shown in Figure 4.3, minimum daily temperatures on Mars are uniformly frigid — every month averages well below 0°F — but meaningful variation exists across the Martian year. Month 3 is the coldest, with an average minimum temperature approaching -83°F, closely followed by Month 4 at approximately -82°F. The warmest month is Month 8, where the average minimum temperature rises to approximately -68°F — a relative improvement of roughly 15°F, though still brutally cold by any earthly standard. The temperature profile follows a broadly U-shaped pattern when read from the coldest months outward, consistent with seasonal warming and cooling driven by Mars's elliptical orbit and axial tilt. Notably, the two coldest months — 3 and 4 — correspond to the Martian southern hemisphere's winter, when Mars is near its aphelion and receives less solar energy. The relative warmth of months 7 through 9 reflects the opposite orbital position.

## **Atmospheric Pressure: Lowest and Highest Months**

<img width="945" alt="Screenshot 2024-04-27 at 10 22 15 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/5cfa13a3-c79e-4653-99e0-1f8acb7aef36">

Figure 4.4 reveals that Martian atmospheric pressure — already extraordinarily thin compared to Earth's — varies measurably across the year. Month 6 records the lowest average daily atmospheric pressure at approximately -74 Pa on the chart's inverted scale, while Month 9 records the highest at approximately -68 Pa. The overall pressure profile closely mirrors the temperature profile in shape, with pressure generally lower during the colder months and higher during the relatively warmer ones. This relationship is physically consistent: on Mars, atmospheric pressure fluctuates seasonally as carbon dioxide — the dominant atmospheric component — freezes out at the polar ice caps during winter, reducing the total atmospheric mass, and sublimes back into the atmosphere during warmer periods, raising pressure. The pattern visible in Figure 4.4 is a direct expression of this planetary-scale carbon dioxide cycle.

## **Length of a Martian Year: Two Independent Methods**

Perhaps the most elegant finding of the analysis is the independent confirmation of the Martian year's length through two entirely different approaches, both derived from the scraped dataset.

<img width="873" alt="Screenshot 2024-04-27 at 10 23 00 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/5c7af303-e372-4a5b-91f5-1373519faca0">

Figure 4.5.2 plots solar longitude — the angular position of Mars in its orbit around the Sun — against Earth time. Solar longitude completes a full 360° cycle with each Martian year, and the chart's sawtooth pattern makes each cycle visually unmistakable. Three complete cycle peaks are identified and labeled: July 30, 2013; June 17, 2015; and May 4, 2017. The intervals between consecutive peaks — approximately 687 Earth days each — yield a dataset-derived Martian year length of exactly 687 Earth days, in perfect agreement with the established astronomical value confirmed through independent internet research.

<img width="1089" alt="Screenshot 2024-04-27 at 10 34 55 AM" src="https://github.com/njgeorge000158/Mars-News-and-Weather-Analysis-from-Web-Scraping/assets/137228821/e7f8d699-2dcf-48e4-b63e-c81fd82af636">

Figure 4.5.3 provides a second, independent confirmation through the minimum daily temperature record plotted against Earth time from 2013 through 2018. The temperature time series displays a clear and repeating wave pattern, with three labeled warm-season peaks: January 9, 2013; November 14, 2014; and October 15, 2016. The intervals between these peaks range from 674 to 701 Earth days, with an average of 687.5 days — again converging on the accepted value of 687 Earth days per Martian year. The slight variation around the average reflects the natural day-to-day noise in temperature measurements rather than any true variation in orbital period. The visual symmetry of the temperature wave is itself informative: the roughly equal durations of the warm and cold phases suggest that Martian seasons, while extreme in temperature, are comparably balanced in length — a consequence of Mars's relatively modest axial tilt of approximately 25 degrees.

The convergence of two independent analytical methods — one based on orbital geometry and one based on surface temperature cycles — on the same answer is a powerful validation of both the dataset's integrity and the analytical approach.

---

## **Summary of Martian Climate Findings**

| Metric | Finding |
|---|---|
| Martian months | 12 |
| Sols in dataset | 1,867 |
| Coldest month (avg. min. temp.) | Month 3 (~-83°F) |
| Warmest month (avg. min. temp.) | Month 8 (~-68°F) |
| Lowest atmospheric pressure | Month 6 |
| Highest atmospheric pressure | Month 9 |
| Martian year (solar longitude method) | 687 Earth days |
| Martian year (temperature cycle method) | 674–701 Earth days (avg. 687.5) |
| Established Martian year length | 687 Earth days ✓ |

---

## **Conclusions**

Mars is a world of extreme cold, razor-thin atmosphere, and surprisingly orderly seasonal cycles. Temperatures at Curiosity's location never rise above freezing — even in the warmest months — and plunge to nearly -90°F at their coldest. Atmospheric pressure follows the temperature cycle in lockstep, driven by the seasonal migration of carbon dioxide between the atmosphere and the polar ice caps. Yet beneath these harsh conditions lies a planetary system of remarkable regularity: two entirely independent methods of estimating the Martian year from scraped surface data converge on the same answer — 687 Earth days — matching the value established by over a century of astronomical observation.

This project demonstrates that meaningful and verifiable scientific insights can be extracted from publicly available web data through disciplined scraping, careful analysis, and rigorous cross-validation.

----

## Copyright

Nicholas J. George © 2023. All Rights Reserved.
