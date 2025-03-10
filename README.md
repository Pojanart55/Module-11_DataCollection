# Mission to Mars

## Overview

This assignment involves web scraping and data analysis of information related to Mars. It consists of two main parts:

1. **Scraping Mars News:** Extracting news titles and preview text from a Mars news website.
2. **Scraping and Analyzing Mars Weather Data:** Extracting weather data from a table on a Mars website and performing basic analysis.

## Deliverables

* **part_1_mars_news.ipynb:** Jupyter Notebook containing the code for scraping Mars news articles.
* **part_2_mars_weather.ipynb:** Jupyter Notebook containing the code for scraping and analyzing Mars weather data.
* **mars_weather_data.csv:** CSV file containing the extracted Mars weather data.

## Tools and Technologies Used

* **Python:** Programming language used for web scraping and data analysis.
* **Splinter:** Library for automating web browser interactions.
* **Beautiful Soup:** Library for parsing HTML and XML documents.
* **Pandas:** Library for data manipulation and analysis.
* **Matplotlib:** Library for creating visualizations.
* **Jupyter Notebook:** Interactive environment for running code and documenting analysis.

## Scraping and Analysis Steps

### Part 1: Mars News

1.  Use Splinter to automate a browser and visit the Mars news website.
2.  Use Beautiful Soup to parse the HTML content of the page.
3.  Extract the titles and preview text of the news articles.
4.  Store the extracted data in a list of dictionaries.
5.  Print the list of dictionaries to confirm success.

### Part 2: Mars Weather Data

1.  Use Splinter to automate a browser and visit the Mars Temperature Data Site.
2.  Use Beautiful Soup to parse the HTML content of the page.
3.  Extract the data from the HTML table into a list of lists.
4.  Create a Pandas DataFrame from the extracted data.
5.  Clean and analyze the data using Pandas functions to answer questions about the Mars weather.
6.  Export the DataFrame to a CSV file.

## Analysis Results

* **Number of Months on Mars:** There are 12 months on Mars.
* **Number of Martian Days (Sols) of Data:** There are 1867 sols (Martian days) worth of data.
* **Coldest and Warmest Months:** The coldest month is month 3 and the hottest month is month 8.
* **Months with Lowest and Highest Pressure:** The month with the lowest pressure is month 6 and the month with the highest pressure is month 9.
* **Estimated Terrestrial Days in a Martian Year:** Based on Minimum Temperature over Time graph, A Martian year is approximately twice the length of an Earth year.

## Visualizations

* **Average Minimum Temperature by Month:**
  
  ![image](https://github.com/user-attachments/assets/e63bf852-f7a2-4f36-b26b-6843981ae22e)

The average minimum numbers by month are all negative, which means they're below freezing.  The coldest months are around months 3 and 4, where the temperature drops to about -83 degrees Celsius.  The "warmest" month is month 8, but even then, it's still a very cold -68 degrees Celsius.  So, this data tells us that Mars is a consistently cold place, with some months being just a little bit less cold than others.
  
* **Average Pressure by Month:**
  
  ![image](https://github.com/user-attachments/assets/7144b4b2-991d-4313-9658-c5c9935a5b96)

The data highlights the dynamic nature of Mars's atmosphere and its seasonal fluctuations. Months 5 and 6 exhibit the lowest average pressures, falling below 750 units, indicating a period of relatively thin atmosphere.  Months 2 and 9 demonstrate the highest average pressures, exceeding 880 and 900 units respectively, signifying denser atmospheric conditions. The remaining months show intermediate pressure levels, fluctuating between these extremes. 

* **Daily Minimum Temperature over Time:**
  
  ![image](https://github.com/user-attachments/assets/bd7916d8-b77f-4c2a-b799-97f449474cb4)
  
The Minimum Temperature over Time graph shows the daily minimum temperature on Mars over several Earth years, from 2013 to 2018. The temperatures are consistently very cold, ranging from about -65°C to -85°C, highlighting the frigid Martian climate. We can observe a clear cyclical pattern, with peaks and valleys indicating seasonal changes. The peaks, where temperatures are relatively "warmer," occur roughly every two Earth years, suggesting that a Martian year is approximately twice the length of an Earth year. This pattern allows us to visually estimate the length of a Martian year by measuring the time between repeating temperature trends.

## Resources

* **Mars News Website:** (https://static.bc-edx.com/data/web/mars_news/index.html)
* **Google** and **Stackoverflow** website for coding research and debugging. 
