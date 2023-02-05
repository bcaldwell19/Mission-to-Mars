> Robin is now ready to take on the full web-scraping and data analysis project for the mission to Mars. She’s learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful >Soup. She’s also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.


> You’ll help Robin scrape, organize, analyze, and visualize the data. As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.


Deliverable 1: Scrape titles and preview text from Mars news articles.


Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


**Language**: Python
**Topic**: Basic Web Scraping
**Library**: Splinter, Beautiful Soup, Pandas, Matplotlib
__________________________________________________


## Part 1: Scrape Titles and Preview Text from Mars News

The focus of this deliverable was an introduction to using splinter and beautiful soup libraries for web scraping.  In this example, article titles and descriptions were scraped from the NASA mars website.

## Part 2: Scrape and Analyze Mars Weather Data

### How many months exist on Mars?

There are 12 months in mars’ year according to the provided data set.

### How many Martian days' worth of data are there?

There was a total of 1867 martian days worth of data in the data set.

## The data was analyzed to answer the following questions, and a data visualization was created to support each answer:

### Which month, on average, has the lowest temperature? The highest?

Mars' third month on average has the lowest temperatures. The eighth month has the highest temperature.

Figure 1:
![High and Low Temps](/Mission-to-Mars/images/avg_tmp.png)

### Which month, on average, has the lowest atmospheric pressure? The highest?

Mars' sixth month on average has the lowest atmospheric pressure. The ninth month has the highest atmospheric pressure.

Figure 2:
![High and Low atmospheric pressure](/Mission-to-Mars/images/avg_atm_p.png)

### How many terrestrial days exist in a Martian year?

If we assume one trough at approximately 1100 and another at 450; you can assume that a martian year is about 650 terrestrial days long.

Figure 3:
![Mars Temperature](/Mission-to-Mars/images/min_tmp_all.png)
