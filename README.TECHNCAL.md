# **Mars News and Weather Web Scraping and Analysis**

----

### **Installation:**

----

If the computer has Anaconda, Jupyter Notebook, and a recent version of Python, the IPython notebook already has the following dependencies installed: datetime, io, json, matplotlib, numpy, pandas, pathlib, os, pandas, requests, requests_html, scipy.

In addition to those modules, the IPython notebook needs the following to execute: holoviews, hvplot, geoviews, geopy, aspose-words, dataframe-image, selenium, beautiful soup, splinter, chromedriver.

Here are the requisite Terminal commands for the installation of these peripheral modules:

python3 -m pip install holoviews

python3 -m pip install hvplot

python3 -m pip install geoviews

python3 -m pip install geopy

python3 -m pip install aspose-words

python3 -m pip install dataframe-image

python3 -m pip install selenium

python3 -m pip install beautifulsoup4

python3 -m pip install splinter

https://chromedriver.chromium.org/getting-started

----

### **Usage:**

----

The IPython notebooks, MarsNewsPy.ipynb and MarsWeatherPy.ipynb, require the following Python scripts with them in the same folder:

PyConstants.py

PyFunctions.py

PyLogConstants.py

PyLogFunctions.py

PyLogSubRoutines.py

PySubroutines.py

If the folders, Resources, Logs, and Images are not present, an IPython notebook will create them.  The Resources folder holds the output files from the IPython Notebooks; the Logs folder contains debug and log files from testing the IPython Notebooks; and the Images folder has the PNG image files of IPython Notebooks' tables and plots.

To place the IPython notebook in Log Mode, Debug Mode, or Image Mode set the parameter for the appropriate subroutine in coding cell #2 to True. In Debug Mode, the program displays the debug information and writes it to a debug file in the Logs folder; the same is true in Log Mode for log information sent to a log file. If the program is in Log Mode but NOT Debug Mode, it displays no debug information, but writes that information to the log file. If the program is in Image Mode, it writes all DataFrames, hvplot maps, and matplotlib plots to PNG files in the Images Folder.

----

### **Resource Summary:**

----

#### Source code

MarsNewsPy.ipynb, MarsWeatherPy.ipynb

#### Input files

https://static.bc-edx.com/data/web/mars_news/index.html \
https://static.bc-edx.com/data/web/mars_facts/temperature.html

#### Output files

MarsNewsData.json, MarsWeatherData.csv

#### SQL script

n/a

#### Software

Jupyter Notebook, Matplotlib, Numpy, Pandas, Python 3.11.4, Scipy, Selenium

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)

----

### **GitHub Repository Branches:**

----

#### main branch 

|&rarr; [./MarsNewsPy.ipynb](./MarsNewsPy.ipynb)

|&rarr; [./MarsWeatherPy.ipynb](./MarsWeatherPy.ipynb)

|&rarr; [./PyConstants.py](./PyConstants.py)

|&rarr; [./PyFunctions.py](./PyFunctions.py)

|&rarr; [./PyLogConstants.py](./PyLogConstants.py)

|&rarr; [./PyLogFunctions.py](./PyLogFunctions.py)

|&rarr; [./PyLogSubRoutines.py](./PyLogSubRoutines.py)

|&rarr; [./PySubRoutines.py](./PySubRoutines.py)

|&rarr; [./README.TECHNICAL.md](./README.TECHNICAL.md)

|&rarr; [./README.md](./README.md)

|&rarr; [./Table-Of-Contents-MNAWATWS.md](./Table-Of-Contents-MNAWATWS.md)

|&rarr; [./Images/](./Images/)

  &emsp; |&rarr; [./Images/MarsWeatherPyFigure51AverageMinimumDailyTemperaturebyMonthonMars.png](./Images/MarsWeatherPyFigure51AverageMinimumDailyTemperaturebyMonthonMars.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyFigure52AverageDailyAtmosphericPressurebyMonthonMars.png](./Images/MarsWeatherPyFigure52AverageDailyAtmosphericPressurebyMonthonMars.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyFigure53SolarLongitudevsEarthTime.png](./Images/MarsWeatherPyFigure53SolarLongitudevsEarthTime.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyFigure54SolarLongitudevsEarthTimewithPeaks.png](./Images/MarsWeatherPyFigure54SolarLongitudevsEarthTimewithPeaks.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyFigure55MinimumDailyTemperaturevsEarthTime.png](./Images/MarsWeatherPyFigure55MinimumDailyTemperaturevsEarthTime.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyFigure56MinimumDailyTemperaturevsEarthTimewithLabeledPeaks.png](./Images/MarsWeatherPyFigure56MinimumDailyTemperaturevsEarthTimewithLabeledPeaks.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyTable31MarsWeatherData.png](./Images/MarsWeatherPyTable31MarsWeatherData.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyTable41MarsWeatherDataTypes.png](./Images/MarsWeatherPyTable41MarsWeatherDataTypes.png)

  &emsp; |&rarr; [./Images/MarsWeatherPyTable42UpdatedMarsWeatherDataTypes.png](./Images/MarsWeatherPyTable42UpdatedMarsWeatherDataTypes.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyTable51AverageLowTemperaturebyMonth.png](./Images/MarsWeatherPyTable51AverageLowTemperaturebyMonth.png)
  
  &emsp; |&rarr; [./Images/MarsWeatherPyTable52AverageDailyAtmosphericPressurebyMonth.png](./Images/MarsWeatherPyTable52AverageDailyAtmosphericPressurebyMonth.png)

  &emsp; |&rarr; [./Images/README.md](./Images/README.md)

|&rarr; [./Logs/](./Logs/)

  &emsp; |&rarr; [./Logs/20230922MarsNewsPyDebug.txt](./Logs/20230922MarsNewsPyDebug.txt)

  &emsp; |&rarr; [./Logs/20230922MarsNewsPyLog.txt](./Logs/20230922MarsNewsPyLog.txt)

  &emsp; |&rarr; [./Logs/20230922MarsWeatherPyDebug.txt](./Logs/20230922MarsWeatherPyDebug.txt)

  &emsp; |&rarr; [./Logs/20230922MarsWeatherPyLog.txt](./Logs/20230922MarsWeatherPyLog.txt)

  &emsp; |&rarr; [./Logs/README.md](./Logs/README.md)

|&rarr; [./Resources/](./Resources/)

  &emsp; |&rarr; [./Resources/MarsNewsData.json](./Resources/MarsNewsData.json)

  &emsp; |&rarr; [./Resources/MarsWeatherData.csv](./Resources/MarsWeatherData.csv)

  &emsp; |&rarr; [./Resources/README.md](./Resources/README.md)

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

N. James George © 2023. All Rights Reserved.
