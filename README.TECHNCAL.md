# **Mars News and Weather Web Scraping and Analysis**

----

### **Installation:**

----

If the computer has Anaconda, Jupyter Notebook, and a recent version of Python, the IPython notebook already has the following dependencies installed: datetime, io, json, matplotlib, numpy, pandas, pathlib, os, pandas, requests, requests_html, scipy.

In addition to those modules, the IPython notebook needs the following to execute: holoviews, hvplot, geoviews, geopy, aspose-words, dataframe-image, selenium, beautiful soup.

Here are the requisite Terminal commands for the installation of these peripheral modules:

pip3 install -U holoviews

pip3 install -U hvplot

pip3 install -U geoviews

pip3 install -U geopy

pip3 install -U aspose-words

pip3 install -U dataframe-image

pip3 install -U selenium

pip3 install -U beautifulsoup4

----

### **Usage:**

----

The IPython notebooks, mars_news.ipynb and mars_weather.ipynb, require the following Python scripts with them in the same folder:

logx.py

mars_news_constants.py

mathx.py

matplotlibx.py

pandasx.py

timex.py

If the folders, logs and images, are not present, an IPython notebook will create them.  The folder, resources, holds the input/output files from the IPython Notebooks; the folder, logs, contains log files from testing the IPython Notebooks; and the folder, images, has the PNG image files of IPython Notebooks' tables and plots.

To place the IPython notebook in Log Mode or Image Mode set the parameter for the appropriate subroutine in coding cell #2 to True. In Log Mode, the notebook writes information to the log file in the folder, logs. If the program is in Image Mode, it writes all DataFrames, hvplot maps, and matplotlib plots to PNG files in the Folder, images.

----

### **Resource Summary:**

----

#### Source code

mars_news.ipynb, mars_weather.ipynb, logx.py, mars_news_constants.py, mathx.py, matplotlibx.py, pandasx.py, timex.py


#### Input files

https://static.bc-edx.com/data/web/mars_news/index.html
https://static.bc-edx.com/data/web/mars_facts/temperature.html

#### Output files

mars_news.json, mars_weather.csv

#### SQL script

n/a

#### Software

Jupyter Notebook, Matplotlib, Numpy, Pandas, Python 3.11.5, Scipy, Selenium

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)

----

### **GitHub Repository Branches:**

----

#### main branch 

|&rarr; [./mars_news_constants.py](./mars_news_constants.py)

|&rarr; [./mars_news.ipynb](./mars_news.ipynb)

|&rarr; [./mars_weather.ipynb](./mars_weather.ipynb)

|&rarr; [./README.TECHNICAL.md](./README.TECHNICAL.md)

|&rarr; [./README.md](./README.md)

|&rarr; [./images/](./images/)

  &emsp; |&rarr; [./images/mars_weatherFigure43AverageMinimumDailyTemperatureByMonthonMars.png](./images/mars_weatherFigure43AverageMinimumDailyTemperatureByMonthonMars.png)
  
  &emsp; |&rarr; [./images/mars_weatherFigure44AverageDailyAtmosphericPressurebyMonthonMars.png](./images/mars_weatherFigure44AverageDailyAtmosphericPressurebyMonthonMars.png)
  
  &emsp; |&rarr; [./images/mars_weatherFigure451SolarLongitudevsEarthTime.png](./images/mars_weatherFigure451SolarLongitudevsEarthTime.png)
  
  &emsp; |&rarr; [./images/mars_weatherFigure452SolarLongitudevsEarthTimewithPeaks.png](./images/mars_weatherFigure452SolarLongitudevsEarthTimewithPeaks.png)
  
  &emsp; |&rarr; [./images/mars_weatherFigure453MinimumDailyTemperaturevsEarthTime.png](./images/mars_weatherFigure453MinimumDailyTemperaturevsEarthTime.png)
  
  &emsp; |&rarr; [./images/mars_weatherFigure454MinimumDailyTemperaturevsEarthTimewithLabeledPeaks.png](./images/mars_weatherFigure454MinimumDailyTemperaturevsEarthTimewithLabeledPeaks.png)
  
  &emsp; |&rarr; [./images/mars_weatherTable24MarsWeatherData.png](./images/mars_weatherTable24MarsWeatherData.png)
  
  &emsp; |&rarr; [./images/mars_weatherTable31MarsWeatherDataTypes.png](./images/mars_weatherTable31MarsWeatherDataTypes.png)

  &emsp; |&rarr; [./images/mars_weatherTable33UpdatedMarsWeatherDataTypes.png](./images/mars_weatherTable33UpdatedMarsWeatherDataTypes.png)
  
  &emsp; |&rarr; [./images/mars_weatherTable43AverageLowTemperaturebyMonth.png](./images/mars_weatherTable43AverageLowTemperaturebyMonth.png)
  
  &emsp; |&rarr; [./images/mars_weatherTable44AverageDailyAtmosphericPressurebyMonth.png](./images/mars_weatherTable44AverageDailyAtmosphericPressurebyMonth.png)

  &emsp; |&rarr; [./images/README.md](./images/README.md)

|&rarr; [./logs/](./logs/)

  &emsp; |&rarr; [./logs/20240427mars_news_log.txt](./logs/20240427mars_news_log.txt)

  &emsp; |&rarr; [./logs/20240427mars_weather_log.txt](./logs/20240427mars_weather_log.txt)

  &emsp; |&rarr; [./logs/README.md](./logs/README.md)

|&rarr; [./resources/](./resources/)

  &emsp; |&rarr; [./resources/mars_news.json](./resources/mars_news.json)

  &emsp; |&rarr; [./resources/mars_weather.csv](./resources/mars_weather.csv)

  &emsp; |&rarr; [./resources/README.md](./resources/README.md)

----

### **References:**

----

[Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/)

[Matplotlib Documentation](https://matplotlib.org/stable/index.html)

[Numpy Documentation](https://numpy.org/doc/1.26/)

[Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)

[Python Documentation](https://docs.python.org/3/contents.html)

[Scipy Documentation](https://docs.scipy.org/doc/scipy/)

[Selenium Documentation](https://selenium-python.readthedocs.io/index.html)

----

### **Authors and Acknowledgment:**

----

### Copyright

Nicholas J. George © 2023. All Rights Reserved.
