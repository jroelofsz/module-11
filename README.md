# Module-11 Challenge

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

---
## Instructions

This project includes 2 deliverables. 

1. ```mars_news.ipynb```

2. ```mars_weather.ipynb```


### Dependencies

This project uses dependencies that are required to run this project. To install them, please reference the command line and conda install lines below.

#### Command Line
```shell
pip install pandas
pip install beautifulsoup4
pip install splinter[selenium]
pip install matplotlib
pip install chromedriver_autoinstaller
pip install lxml
pip install html5lib
```

#### Conda

```shell
conda install -c conda-forge pandas
conda install -c conda-forge beautifulsoup4
conda install -c conda-forge splinter
conda install -c conda-forge selenium
conda install -c conda-forge matplotlib
conda install -c conda-forge chromedriver_autoinstaller
conda install -c conda-forge lxml
conda install -c conda-forge html5lib
```

**Please note:** My notebooks executed in chrome without the chromedriver_autoinstaller. However, your's may not. If you run into issues without it, please install it. 

---
## Execution

To execute the files, please run then in a Jupyter Notebook instance or in your choice of IDE that supports the ```.ipynb``` file extenstion.

#### Command Line
```shell
pip install jupyter
```

#### Conda
```shell
conda install -c conda-forge jupyter
```

The first file is ```/Noteboooks/mars_news.ipynb```.

This notebook scrapes the URL ```https://static.bc-edx.com/data/web/mars_news/index.html```. It will return a list of dictionaries. Each dictionary will have the ```title``` and ```preview_text``` of each article on the site.

The second file is ```/Notebooks/mars_weather.ipynb```. This file will scrape data out of an HTML table, load it into a dataframe, perform data analysis and save the results to a csv file in the ```/Out``` folder.

---


## Resources

1. [Pandas Documentation](https://pandas.pydata.org/docs/)
2. [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
3. [Splinter Documentation](https://splinter.readthedocs.io/en/latest/)
4. [Selenium Documentation](https://www.selenium.dev/documentation/)
5. [MatPlotLib Documentation](https://matplotlib.org/stable/contents.html)
6. [chromedriver_autoinstaller Documentation](https://pypi.org/project/chromedriver-autoinstaller/)
7. [lxml Documentation](https://lxml.de/)
8. [html5lib Documentation](https://html5lib.readthedocs.io/en/latest/)
9. [Jupyter Documentation](https://jupyter.org/documentation)
