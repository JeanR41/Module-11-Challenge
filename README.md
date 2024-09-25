# Mars Weather Data Scraper
## Overview

This project involves scraping and analyzing Mars weather data from the Mars Temperature Data Site. Using Python libraries such as Splinter and BeautifulSoup, I automated the process of collecting data on Martian temperatures, atmospheric pressure, and other relevant metrics. The scraped data is stored in a Pandas DataFrame for analysis and visualization.

# Analysis
## Minimum Temperature
By calculating the average minimum temperature for each month, we found that Month 3 is the coldest month on Mars, with an average minimum temperature of -83.307292.
A bar chart was plotted to visually represent the average minimum temperatures across all months, highlighting the temperature fluctuations throughout the Martian year.
After Month 3, the second coldest month is Month 4, with an average minimum temperature of -82.74742, followed by Month 2 (-79.932584), and Month 5 (-79.308725).

## Atmospheric Pressure
By calculating the average atmospheric pressure for each month, we found that Month 9 has the highest atmospheric pressure on Mars, with an average pressure of 913.305970 Pa, and Month 6 has the lowest atmospheric pressure, at 745.054422 Pa.
A bar chart was plotted to visually represent the average atmospheric pressure across all months, highlighting the pressure fluctuations throughout the Martian year.

## Year Length
A Martian year is approximately 690 Earth days. This is visually estimated by plotting the daily minimum temperature over time. The temperature fluctuations create a visualization of how Mars cycles through lower and higher temperatures throughout a Martian year, and the space between two peaks or two troughs on the plot can provide markers for how many terrestrial days it takes for Mars to cycle through a full Martian year. This illustrates the relationship between the Martian and terrestrial calendars.

## Additional sources used during this challenge:
In Step 2 on the part_1_mars_news.ipynb code, I referenced Real Python while writing the recursion.
https://realpython.com/python-recursion/
